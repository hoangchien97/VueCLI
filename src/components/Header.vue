<template>
    <header>
        <h1>{{title}}</h1>
    </header>
</template>

<script>
export default {
    name: 'header',
    props: {
        title: String
    },
    data(){
        return{
            // text: 'Header'
        }
    }
}
</script>

<style>

</style>