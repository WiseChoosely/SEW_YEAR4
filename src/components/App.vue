<template>
<div>
  <login title="Anmelden bei Fakebook" placeholderEmail="Email" placeholderPassword="Passwort"></login>
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
