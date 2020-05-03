<template>
  <div class="nav">
    <router-link class="link" to="/">Home</router-link>
    <router-link class="link" to="Services">Service</router-link>
    <router-link class="link" to="Contact">Contact</router-link>
  </div>
</template>

<script>
export default {
  name: 'Nav',
}
</script>

<style scoped lang="scss">
@import "@/assets/styles/settings.scss";
.nav {
  position: fixed;
width: -webkit-fill-available;
    bottom: 0;
    max-width: 100vw;
    height: 60px;
  display: flex;
  justify-content: space-evenly;
  background-color: ($secondary-color);
  padding: 1rem;
  align-items: center;
}

.link {
  color: white;
}

.link:hover {
  color: $font-color;
}

@media(min-width: 781px) {

}

</style>
