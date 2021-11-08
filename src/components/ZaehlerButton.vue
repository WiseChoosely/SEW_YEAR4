<template>
        <md-button class="md-raised" @click="count()">{{buttonText}} {{counter}}</md-button>
    
</template>

<script>
export default {
    name: 'ZaehlerButton',
     props: {
        buttonText: String,
    },
    methods: {
        count(){ this.counter++;}
    },

    data() {
        return {
            counter: 0,
        }
    }
}
</script>

<style scoped>

</style>