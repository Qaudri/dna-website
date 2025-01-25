<template>
  <h2 :class="color==='primary' ? 'text-primary' : color==='white' ? 'text-white' : color === 'secondary' ? 'text-secondary' :'text-neutral-800'" class="text-3xl md:text-4xl font-semibold"><slot/></h2>
</template>
<script>
  export default {
    props: {
      color: String
    }
  }
</script>