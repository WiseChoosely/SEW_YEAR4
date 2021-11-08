<template>
  <div class="md-layout md-alignment-left">

    <zaehler-button buttonText="Ich zähle und bin bei:"/>
    <zaehler-button class="md-raised md-primary" buttonText="Ich zähle auch und bin bei:"/>

  </div>
</template>

<script>
// 1. Importiere benötigte Komponenten
import Hallo from './Hallo'
import ZaehlerButton from './ZaehlerButton.vue'

export default {
  name: 'App',

  components: {
    Hallo,
    ZaehlerButton,
  },

  methods: {
    answer() {
      return 42
    },
  },
}
</script>

<style scoped>
</style>