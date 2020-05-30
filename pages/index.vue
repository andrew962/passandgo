<template>
  <v-layout column justify-center align-center>
    <back-ground-image />
    <about-us />
  </v-layout>
</template>

<script>
import BackGroundImage from '~/components/BackgroundImage.vue'
import AboutUs from '~/components/AboutUs.vue'

export default {
  components: {
    BackGroundImage,
    AboutUs
  }
}
</script>
