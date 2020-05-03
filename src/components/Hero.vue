<template>
  <section class="fullscreen">
      <div class="hero-body">
          <div class="conatiner">
              <h1 class="title font-weight-500 primary">
                <b>Therapy</b> with Stella
              </h1>
              <h2 class="subtitle body-font primary">
                  helping you heal
              </h2>
          </div>
          <div class="image-container">
              <img class="profile-image" src="@/assets/images/kind-therapist.png" alt="photo of stella looking empathetic">
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: "Hero"
}
</script>

<style scoped lang="scss">
@import "@/assets/styles/settings.scss";
.fullscreen {
    height: calc(100vh - 60px);
}

.body-font {
    font-family: $font-body;
    font-style: italic;
}

.font-weight-500 {
    font-weight: 500;
}

.background {
    background-color: $background;
}

.primary {
    color: darken($primary-color, 5%);
}

.secondary {
    color: $secondary-color;
}

.image-container {
    width: 100%;
    display: flex;
    align-items: center;
    margin-top: 2rem;
    justify-content: center;
}

.profile-image {
    border-radius: 50%;
    max-width: 70%;
-webkit-box-shadow: 11px 13px 25px -12px $secondary-color;
-moz-box-shadow: 11px 13px 25px -12px $secondary-color;
box-shadow: 11px 13px 25px -12px $secondary-color;
}

</style>