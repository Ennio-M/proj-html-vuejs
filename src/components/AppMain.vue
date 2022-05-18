<template>
    <main>
        <jumbo-tron/>
        <foodie-journal/>
        <popular-recipes/>
    </main>
</template>

<script>
import FoodieJournal from './FoodieJournal.vue';
import JumboTron from './JumboTron.vue';
import PopularRecipes from './PopularRecipes.vue';

export default {
    name: "AppVue",
    components: {
        JumboTron,
        FoodieJournal,
        PopularRecipes
    }
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    main{
        background-color: $bg-color;
    }
</style>