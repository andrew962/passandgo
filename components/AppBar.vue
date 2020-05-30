<template>
  <v-app-bar elevate-on-scroll color="#fff" fixed app>
    <nuxt-link to="/">
      <v-img style="max-width:45% !important" src="/pass-and-go-logo.svg"></v-img>
    </nuxt-link>
    <v-spacer />
    <v-btn class="mr-3 ml-3 d-none d-md-flex" :ripple="false" v-on:click="btnInit" text large>Inicio</v-btn>
    <v-btn
      class="mr-3 ml-3 d-none d-md-flex"
      :ripple="false"
      v-on:click="btnOur"
      text
      large
    >Nosotros</v-btn>
    <v-btn class="mr-3 ml-3 d-none d-md-flex" :ripple="false" v-on:click="btnTeam" text large>Team</v-btn>
    <v-btn
      class="mr-3 ml-3 d-none d-md-flex"
      :ripple="false"
      v-on:click="btnServices"
      text
      large
    >Servicios</v-btn>
    <v-btn
      class="mr-3 ml-3 d-none d-md-flex"
      v-on:click="btnContactUs"
      rounded
      color="#46DDB0"
      small
      style="color: #fff;"
    >Contáctenos</v-btn>
  </v-app-bar>
</template>

<script>
import VueScrollTo from 'vue-scrollto'
export default {
  methods: {
    btnInit: () => {
      VueScrollTo.scrollTo('#passandgo', 500)
    },
    btnOur: () => {
      VueScrollTo.scrollTo('#our', 500)
    },
    btnTeam: () => {
      VueScrollTo.scrollTo('#team', 500)
    },
    btnServices: () => {
      VueScrollTo.scrollTo('#services', 500)
    },
    btnContactUs: () => {
      VueScrollTo.scrollTo('#contactus', 500)
    }
  }
}
</script>

<style>
</style>