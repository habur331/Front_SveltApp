<script lang="ts">
    import HeaderComponent from "./HeaderComponent.svelte";
    import AboutComponent from "./AboutComponent.svelte";
    import FunnyFactComponent from "./FunnyFactComponent.svelte";
    import LinksComponent from "./LinksComponent.svelte";
</script>


<HeaderComponent/>

<main>
    <AboutComponent/>
    <FunnyFactComponent/>
    <LinksComponent/>
</main>


<style>
    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }

    main {
        margin: 0;
    }
</style>