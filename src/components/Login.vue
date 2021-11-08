<template>
    <div>
        <md-card>
            <md-toolbar class="md-primary">
                <h3 class="md-title">{{title}}</h3>
            </md-toolbar>
        <md-card-content>
        <md-field>
            <label>{{placeholderEmail}}</label>
            <md-input></md-input>
        </md-field>

         <md-field>
            <label>{{placeholderPassword}}</label>
            <md-input></md-input>
        </md-field>
        </md-card-content>
        <md-card-actions>
            <div class= "md-layout md-alignment-left">
                <md-button class="md-raised md-primary">{{buttonText}}</md-button>
            </div>
        </md-card-actions>
        </md-card>
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
