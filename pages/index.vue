<template>
  <section>
    <h1 class="text-h1 white--text text-center">NUXT PLAYGROUND</h1>
    <v-card
      color="purple darken-4"
      width="100%"
      height="300"
      class="d-flex align-center justify-space-around"
    >
      <v-btn color="blue darken-4" width="200"
        ><nuxt-link to="/posts">ALL POSTS</nuxt-link>
      </v-btn>
      <v-btn color="blue darken-4" width="200"
        ><nuxt-link to="/posts">YOUR POSTS</nuxt-link></v-btn
      >
      <v-btn color="blue darken-4" width="200"
        ><nuxt-link to="/about">ABOUT</nuxt-link></v-btn
      >
    </v-card>
  </section>
</template>
<style scoped>
.v-application a {
  color: white !important;
}
</style>
