<template>
  <div>
    <div class="content">
      <app-menu/>
      <nuxt />
    </div>
    <app-footer/>
  </div>
</template>
<script>
  import AppMenu from '@/components/AppMenu.vue'
import AppFooter from '@/components/AppFooter.vue'
  export default {
    components: {
      AppMenu,
      AppFooter
    }
  }
</script>
<style>
html {
  font-family: "Mulish", -apple-system, Roboto, Arial, sans-serif;
  font-size: 16px;
  font-weight: 300;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

h1,
h2,
h3,
h3,
h4 {
  font-family: "Poppins", -apple-system, Roboto, Arial, sans-serif;
  font-weight: 600;
}
</style>