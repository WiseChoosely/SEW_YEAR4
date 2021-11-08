<template>
<div class="md-layout md-alignment-top-center">
  <login class="md-layout-item md-size-50 " title="Anmelden bei Fakebook" placeholderEmail="Email" placeholderPassword="Passwort" buttonText="Anmelden"></login>
</div>
</template>

<script>
import Login from './Login.vue'

export default {
    name: 'App',

    components: {
      Login
    }
}

</script>

<style scoped>
</style>
