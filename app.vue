<template>
    <Navbar />
    <header class="py-20">
      <Container>
        <TypographyH1 color="white">
          Trustworthy <br> Paternity <br> Testing
        </TypographyH1>
        <TypographyP color="white">15 Years of Accurate, Convenient, and Private DNA Testing Services.</TypographyP>
        <ButtonsPrimary class="border border-white mt-4">Learn More</ButtonsPrimary>
      </Container>
    </header>

    <Container class="py-20">
      <TypographyH2 class="text-center">How It Works</TypographyH2>
      <TypographyP class="text-center">Simple, Hassle-Free Process in 3 Easy Steps</TypographyP>

      <ul class="grid gap-6 lg:grid-cols-3 mt-8">
        <li class="p-4 border border-secondary rounded-lg">
          <div class="bg-secondary w-10 aspect-square rounded-full grid place-content-center">
            <img src="/calendar.svg" class="w-6" alt="Calendar Icon"> 
          </div>
          <dl class="mt-2">
            <dt class="font-medium">Schedule Your Appointment</dt>
            <dd>Contact us to set a date and time that works for you.</dd>
          </dl>
        </li>
        <li class="p-4 border border-secondary rounded-lg">
          <div class="bg-secondary w-10 aspect-square rounded-full grid place-content-center">
            <img src="/card.svg" class="w-6" alt="Credit Card Icon"> 
          </div>
          <dl class="mt-2">
            <dt class="font-medium">Make Your Payment</dt>
            <dd>Secure your appointment by making a payment online or over the phone.</dd>
          </dl>
        </li>
        <li class="p-4 border border-secondary rounded-lg">
          <div class="bg-secondary w-10 aspect-square rounded-full grid place-content-center">
            <img src="/phone.svg" class="w-6" alt="Phone Icon"> 
          </div>
          <dl class="mt-2">
            <dt class="font-medium">Confirmation Call</dt>
            <dd>We'll call you to confirm the appointment and location details to ensure everything is set.</dd>
          </dl>
        </li>
      </ul>

      <TypographyP class="text-center mt-6 lg:w-2/3 mx-auto">With our professional, hassle-free service, you can trust us to handle your Paternity Testing and DNA testing needs with care and discretion.
      </TypographyP>

    </Container>

    <section class="py-20 bg-primary">
      <Container>
        <TypographyH2 class="text-center">What Happens After Your Appointment?</TypographyH2>
      <TypographyP class="text-center lg:w-2/3 mx-auto">Once your appointment is complete, we make the next steps as simple and convenient as possible. Here's what you can expect:</TypographyP>

      <ul class="grid gap-6 lg:grid-cols-3 mt-8">
        <li class="p-4 border border-secondary rounded-lg">
            <img src="/clipboard.svg" class="w-10" alt="Clipboard Icon"> 
          <dl class="mt-2">
            <dt class="font-semibold text-secondary">Receive Your Instruction Card & Contact Information</dt>
            <dd> After your appointment, we provide you with an instruction card and a contact number for any follow-up questions or support you might need.</dd>
          </dl>
        </li>
        <li class="p-4 border border-secondary rounded-lg">
            <img src="/beaker.svg" class="w-10" alt="Beaker Icon"> 
          <dl class="mt-2">
            <dt class="font-semibold text-secondary">Samples Sent to the World's Largest DNA Collection Network</dt>
            <dd>Your samples, whether collected via a simple cheek (buccal) swab or, in some cases, a blood draw, are sent out to the largest DNA sample collection network in the world for testing and analysis.</dd>
          </dl>
        </li>
        <li class="p-4 border border-secondary rounded-lg">
            <img src="/location.svg" class="w-10" alt="Location Icon"> 
          <dl class="mt-2">
            <dt class="font-semibold text-secondary">Convenient Collection Locations</dt>
            <dd>We prioritize your convenience, ensuring that the sample-collection appointments are located near your home or office, making it easy to fit into your schedule.</dd>
          </dl>
        </li>
      </ul>

      <TypographyP class="text-center mt-6 lg:w-2/3 mx-auto">Whether it's for paternity testing, genetic analysis, or another service, we’re committed to providing a seamless experience every step of the way.
      </TypographyP>
      </Container>


    </section>

    <Container class="grid lg:grid-cols-2 gap-8 py-20 items-center">
      <div>
        <TypographyH2>Why Choose Us?</TypographyH2>
        <TypographyP>Easy, Easy, Easy!</TypographyP>

        <ul class="grid gap-6 mt-8">
          <li class="">
            <TypographyH3 color="secondary">01</TypographyH3>
            <dl class="mt-1">
              <dt class="font-medium">Easy Appointments</dt>
              <dd>Scheduling is a breeze with convenient locations near your home or office. No hassle, no stress—just a simple appointment that works with your busy life.</dd>
            </dl>
          </li>
          <li class="">
            <TypographyH3 color="secondary">02</TypographyH3>
            <dl class="mt-1">
              <dt class="font-medium">Easy Sample Collection</dt>
              <dd>Forget complicated procedures. We use easy, non-invasive methods like cheek swabs, so you're in and out in no time. In rare cases, a blood draw may be needed, but that's still a quick and simple process.</dd>
            </dl>
          </li>
          <li class="">
            <TypographyH3 color="secondary">03</TypographyH3>
            <dl class="mt-1">
              <dt class="font-medium">Easy Results</dt>
              <dd>   Your samples are sent to the world's largest DNA testing network for accurate, fast results. We keep you informed every step of the way, making it easy to understand your next steps.</dd>
            </dl>
          </li>
        </ul>
      </div>
      <img src="/02.png" alt="Microscope image" class="hidden lg:block">
    </Container>

    <Container class="grid lg:grid-cols-2 lg:grid-col-reverse gap-8 py-20 items-center">
      <img src="/03.jpg" alt="">

      <div>
        <TypographyH2>Why Take a DNA Test?
        </TypographyH2>
        <TypographyP>The Benefits of DNA Testing</TypographyP>

        <ul class="grid gap-2 mt-4">
          <li class="">
            ✅ Establish Paternity
          </li>
          <li class="">
            ✅ Confirm Sibling Relationships
          </li>
          <li class="">
            ✅ Resolve Inheritance or Benefit Claims
          </li>
          <li class="">
            ✅ Discover Your Biological Parent
          </li>
        </ul>
      </div>
    </Container>

    <Footer />
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

body {
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
header {
  background: url('/header.jpg');
  background-size: cover;
  background-position: center;
}
</style>