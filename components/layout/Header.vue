<template>
  <div
    class='navbar opacity-80 h-20 shadow-lg bg-black text-neutral-content'>
    <div class='navbar-start'></div>
    <div class='navbar-center'>
      <div class='grid grid-flow-col gap-4 '>
        <button class='btn btn-primary ' v-for='i in 3' :key='i'>
          <icon-hero-academic-cap />
          I'm a link
        </button>
        <button class='btn bg-green-700'>Welcome to espoleta</button>
        <button class='btn btn-primary' v-for='i in 3' :key='i'>
          <icon-hero-academic-cap />
          I'm a link
        </button>
      </div>
    </div>
    <div class='navbar-end'></div>
  </div>
</template>

<script lang='ts'>
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  // name: 'Header'
})
</script>

<style scoped>

</style>
