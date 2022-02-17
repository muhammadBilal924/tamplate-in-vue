
<template>
    <div>
   <h1>Tamplate in vue js</h1>
    <h3>{{name}}</h3>
    <h3>{{email}}</h3>
    <button v-on:click="updateText">Click me</button>
    </div>
</templateApp>

<script>
    export default {
        name:'TamplateApp',
        data()
        {
            return{
                name:'M.Bilal',
                
            }
        },
        methods:{
            updateText()
           {
            this.name="M.Sufyan"
            }
        }
        
    }
</script>

<style lang="scss" scoped>

</style>