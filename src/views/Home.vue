<template>
  <div class="home">
    <hero></hero>
  </div>
</template>

<script>
import Hero from "@/components/Hero.vue";
export default {
  name: 'Home',
  components: {
    Hero
  }
}
</script>

<style lang="scss" scoped>
@import "@/assets/styles/settings.scss";
</style>
