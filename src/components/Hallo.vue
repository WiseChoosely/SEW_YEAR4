<template>
  <div>
    <h1>Hallo</h1>
    <p><u>{{ name }}</u></p>
  </div>
</template>

<script>
export default {
    name: 'Hallo',
    props: {
        name: {
          type: String,
          default: "foobar",
        }
    },
}
</script>

<style scoped>

</style>