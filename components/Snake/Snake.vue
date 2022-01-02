<template>
  <div><SnakePart v-for="i in 3" :key="i" /></div>
</template>

<script>
import SnakePart from '~/components/Snake/SnakePart'
export default {
  name: 'Snake',
  components: { SnakePart }
}
</script>
