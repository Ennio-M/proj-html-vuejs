<template>
    <main>
        <jumbo-tron/>
        <foodie-journal/>
    </main>
</template>

<script>
import FoodieJournal from './FoodieJournal.vue';
import JumboTron from './JumboTron.vue';

export default {
    name: "AppVue",
    components: {
        JumboTron,
        FoodieJournal
    }
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    main{
        background-color: $bg-color;
    }
</style>