<template>
    <div>
        <h1> Hallo Welt </h1>
        <p> Die Welt ist groß. Guten Tag und Hallo sehr geehrter {{name}}</p>


    </div>
</template>

<script>
    export default{
        name: 'HalloWelt',
        props: {
            name: String,
        }
    }
</script>

<style scoped>

</style>
