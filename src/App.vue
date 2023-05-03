<script>
    import AppTitle from "./components/AppTitle.vue"
    export default{
        name: "App",
        components: {
            AppTitle
        }
    }
</script>

<template>
    <div>
        <AppTitle/>
        <h3>Sottotitolo di prova</h3>
    </div>
</template>

<style scoped>
    h3
    {
        color: yellow;
        text-align: center;
    }
</style>