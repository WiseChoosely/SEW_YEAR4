<template>
  <div>
    <md-radio v-model="radio" value="value1" disabled="false">1</md-radio>
    <md-radio v-model="radio" value="value2">2</md-radio>
    <md-radio v-model="radio" value="value3">3</md-radio>
    <md-radio v-model="radio" value="value4">4</md-radio>
    <md-radio v-model="radio" value="vlaue5">5</md-radio>
  </div>
</template>

<script>

export default{
    name: 'ReihungRadio',
    props: {
        name: String,
       
    }
}

</script>

<style scoped>

</style>