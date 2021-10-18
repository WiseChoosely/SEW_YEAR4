<template>
    <div>
        <md-toolbar class="md-primary">
            <h3 class="md-title">{{title}}</h3>
        </md-toolbar>

        <md-field>
            <label>{{placeholderEmail}}</label>
            <md-input></md-input>
        </md-field>

         <md-field>
            <label>{{placeholderPassword}}</label>
            <md-input></md-input>
        </md-field>

     

    </div>
</template>

<script>

export default{
    name: 'Login',
    props: {
        title: String,
        placeholderEmail: String,
        placeholderPassword: String, 
        buttonText: String,
    }
}

</script>

<style scoped>

</style>
