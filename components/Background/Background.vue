<template>
  <v-row class="mx-4 red">
    <background-brick v-for="i in 12" :key="i" />
  </v-row>
</template>

<script>
import BackgroundBrick from '~/components/Background/BackgroundBrick'
export default {
  name: 'Background',
  components: { BackgroundBrick }
}
</script>

<style scoped>

</style>
