<template>
    <section class="masthead" role="img" aria-label="Image Description">
  <h1>
    Nuxt food app
  </h1>
    <button>
      See restaurants >
    </button>
</section>
</template>
<script>
export default {
}
</script>
<style lang="scss" scoped>
.masthead {
    padding: 40px;
    width: 100%;
    height: 80vh; /* if you don't want it to take up the full screen, reduce this number */
    overflow: hidden;
    background-size: cover !important;
    background: radial-gradient(ellipse at center, rgba(0,0,0,0) 0%, rgba(0,0,0,0) 37%, rgba(0,0,0,0.65) 100%), url(~assets/headerimg.jpg) no-repeat center center scroll;
}

h1 {
  font-style: normal;
  font-weight: bold;
  color: #eee;
  font-size: 8vmin;
  letter-spacing: 0.03em;
  line-height: 1;
  text-shadow: 1px 2px 4px rgba(0, 0, 0, 0.8);
  margin-bottom: 40px;
}

</style>
