<template>
  <v-app dark>
    <v-app-bar
      app
      color="black"
      dark
    >
      <div class="d-flex align-center">
        <v-btn light fab>

        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          :src="require('./assets/NFTW-Square-Logo.svg')"
          transition="scale-transition"
          width="25%"
        />
        </v-btn>
        <h1 class="ml-3">New FronTier Works</h1>
      </div>


    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

<style>

h1, h2 {	font-family: Impact,Haettenschweiler,Franklin Gothic Bold,Charcoal,Helvetica Inserat,Bitstream Vera Sans Bold,Arial Black,sans serif; text-transform: uppercase;
}
.v-card__text, .v-card__title {
  word-break: normal !important;
}
</style>
