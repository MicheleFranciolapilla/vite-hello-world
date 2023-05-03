<script>
    import AppTitle from "./components/AppTitle.vue"
    import AppHero from "./components/AppHero.vue"
    export default{
        name: "App",
        components: {
            AppTitle,
            AppHero
        }
    }
</script>

<template>
    <div>
        <AppTitle/>
        <h3>Sottotitolo di prova</h3>
        <AppHero/>
    </div>
</template>

<style scoped>
    h3
    {
        color: yellow;
        text-align: center;
    }
</style>