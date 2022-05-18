<template>
    <main>
        <jumbo-tron/>
        <foodie-journal/>
        <popular-recipes/>
        <culinary-collection/>
    </main>
</template>

<script>
import CulinaryCollection from './CulinaryCollection.vue';
import FoodieJournal from './FoodieJournal.vue';
import JumboTron from './JumboTron.vue';
import PopularRecipes from './PopularRecipes.vue';

export default {
    name: "AppVue",
    components: {
        JumboTron,
        FoodieJournal,
        PopularRecipes,
        CulinaryCollection
    }
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    main{
        background-color: $bg-color;
    }
</style>