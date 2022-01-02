<template>
  <v-row justify="center" align="center">
    <Background />
    <Snake style="position: absolute" />
  </v-row>
</template>
<script>
import Background from '~/components/Background/Background'
import Snake from '~/components/Snake/Snake'
export default {
  components: { Snake, Background }
}
</script>
