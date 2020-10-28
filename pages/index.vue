<template>
  <section id="main">
    <v-row justify="center" class="mx-auto" style="margin-top: 10vh">
      <v-col cols="12">
        <v-img
          src="/images/logo.png"
          alt="logo"
          max-width="720"
          class="mx-auto"
        />
      </v-col>
    </v-row>
    <v-row justify="center" class="mx-auto">
      <div class="text-center text-lg-h2 text-md-h2 text-sm-h2 text-h4">
        Coming soon...
      </div>
    </v-row>
    <v-row justify="center" class="mx-auto">
      <div class="text-center text-lg-h2 text-md-h2 text-sm-h2 text-h4">
        info e prenotazioni
        <a id="info" href="mailto:info@pinktattooshop.it"
          >info@pinktattooshop.it</a
        >
      </div>
    </v-row>
  </section>
</template>

<script>
export default {
  name: 'WorkInProgress',
  layout: 'work',
}
</script>

<style lang="scss">
@import '../assets/index.scss';
@font-face {
  font-family: 'Inky';
  src: url('~assets/fonts/Inky.ttf') format('truetype');
}

html {
  font-family: 'Inky', sans-serif !important;
}

.v-application {
  font-family: 'Inky', sans-serif !important;
}

.text-lg-h4 {
  font-family: 'Inky', sans-serif !important;
}
</style>
