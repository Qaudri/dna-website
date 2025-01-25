<template>
  <h1 :class="color==='primary' ? 'text-primary' : color==='white' ? 'text-white' : color === 'secondary' ? 'text-secondary' :'text-neutral-800'" class="text-4xl md:text-5xl xl:text-6xl uppercase font-bold"><slot/></h1>
</template>
<script>
  export default {
    props: {
      color: String
    }
  }
</script>