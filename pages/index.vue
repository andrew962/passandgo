<template>
  <v-layout column justify-center align-center>
    <back-ground-image />
    <about-us />
    <team />
  </v-layout>
</template>

<script>
import BackGroundImage from '~/components/BackgroundImage.vue'
import AboutUs from '~/components/AboutUs.vue'
import Team from '~/components/Team.vue'

export default {
  components: {
    BackGroundImage,
    AboutUs,
    Team
  }
}
</script>
