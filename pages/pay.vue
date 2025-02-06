<template>
  <Navbar />
  <Container class="py-20">
    <div class="">
      <TypographyH2 class="text-center mb-6">Choose Your Package</TypographyH2>
      
      <div class="grid md:grid-cols-3 gap-4">
        <div v-for="price in prices" :key="price.id" 
             class="border border-secondary rounded-lg p-4 text-center">
          <h3 class="text-xl font-semibold">{{ price.name }}</h3>
          <p class="text-2xl font-bold my-4">${{ price.amount }}</p>
          <ButtonsPrimary disabled
            @click="handlePayment(price.id, price.amount)"
            :disabled="loading"
            class="w-full disabled:opacity-50"
          >
            {{ loading ? 'Processing...' : 'Book Now' }}
          </ButtonsPrimary>
        </div>
      </div>
    </div>
  </Container>
  <Footer />
</template>

<script setup>
import { ref } from 'vue'
import { loadStripe } from '@stripe/stripe-js'

const loading = ref(false)

const prices = ref([
  { id: 1, amount: 'TBD', name: 'DNA Test' },
  { id: 2, amount: 'Coming Soon', name: 'BBL Lab Testing' },
  { id: 3, amount: 'Coming Soon', name: 'Drug Testing' }
])

const stripePromise = loadStripe('your_publishable_key') // Replace with your key

const handlePayment = async (priceId, amount) => {
  loading.value = true
  
  // try {
  //   const stripe = await stripePromise
    
  //   // Create checkout session
  //   const response = await fetch('/api/create-checkout', {
  //     method: 'POST',
  //     headers: {
  //       'Content-Type': 'application/json',
  //     },
  //     body: JSON.stringify({
  //       name: prices.value.find(p => p.id === priceId).name,
  //       amount: amount
  //     }),
  //   })

  //   const { sessionId } = await response.json()

  //   // Redirect to checkout
  //   const result = await stripe.redirectToCheckout({
  //     sessionId,
  //   })

  //   if (result.error) {
  //     console.error(result.error)
  //   }
  // } catch (error) {
  //   console.error('Payment failed:', error)
  // } finally {
  //   loading.value = false
  // }
}
</script>