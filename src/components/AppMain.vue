<template>
    <main>
        <jumbo-tron/>
        <foodie-journal/>
        <popular-recipes/>
        <culinary-collection/>
        <blog-posts :data="data"/>
        <subscribe-sec/>
        <images-sec/>
        <app-fixed/>
    </main>
</template>

<script>
import AppFixed from './AppFixed.vue';
import BlogPosts from './BlogPosts.vue';
import CulinaryCollection from './CulinaryCollection.vue';
import FoodieJournal from './FoodieJournal.vue';
import ImagesSec from './ImagesSec.vue';
import JumboTron from './JumboTron.vue';
import PopularRecipes from './PopularRecipes.vue';
import SubscribeSec from './SubscribeSec.vue';

export default {
    name: "AppVue",
    components: {
        JumboTron,
        FoodieJournal,
        PopularRecipes,
        CulinaryCollection,
        BlogPosts,
        SubscribeSec,
        ImagesSec,
        AppFixed
    },
    props: {
        data: Object
    }
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    main{
        background-color: $bg-color;
    }
</style>