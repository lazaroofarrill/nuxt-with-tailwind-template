<template>
  <div
    class='navbar opacity-80 h-20 shadow-lg bg-black text-neutral-content'>
    <div class='navbar-start'></div>
    <div class='navbar-center'>
      <div class='grid grid-flow-col gap-4 '>
        <button class='btn btn-ghost ' v-for='i in 3' :key='i'>
          <icon-hero-academic-cap />
          I'm a link
        </button>
        <div class='dropdown'>
          <div tabindex='0' class='btn btn-ghost'>Español
            <icon-hero-academic-cap />
          </div>
          <ul tabindex='0' class='p-2 shadow menu text-black dropdown-content bg-base-100 rounded-box w-52'>
            <li v-for='i in 3' :key='i'>
              <a href=''>Item {{ i }}</a>
            </li>
          </ul>
        </div>
        <button class='btn btn-ghost'>Welcome to espoleta</button>
        <button class='btn btn-ghost' v-for='i in 3' :key='i'>
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
