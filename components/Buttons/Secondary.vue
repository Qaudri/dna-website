<template>
  <button @click="$emit('clicked')" class="font-medium text-sm xl:text-base 2xl:text-lg text-secondary hover:text-neutral-700 ease-in-out duration-500 border-b border-transparent hover:border-primary select-none outline-none">
    <slot />
  </button>
</template>