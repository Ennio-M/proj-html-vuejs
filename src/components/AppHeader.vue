<template>
    <section>
        <h2 v-for="item in data.navbar" :key="item.id">{{item.text}}</h2>
        <i v-for="(social, index) in data.socials" :key="index" :class="social"></i>
    </section>
</template>

<script>
export default {
    name: 'AppHeader',
    props: {
        data: Object
    }    
}
</script>

<style lang="scss">
    
</style>