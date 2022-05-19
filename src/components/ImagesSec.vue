<template>
    <section class="p-0">
        <div class="pictures d-flex">
            <div class="picture">
                <img src="../assets/imgs/Yogurt-Nan-800x527.jpg" alt="Yogurt Nan" class="w-100 pointer">
            </div>
            <div class="picture">
                <img src="../assets/imgs/Mixed-fruits-800x527.jpg" alt="Mixed Fruits" class="w-100 pointer">
            </div>
            <div class="picture">
                <img src="../assets/imgs/r-rachel-park-366508-unsplash-min-800x527.jpg" alt="Breakfast" class="w-100 pointer">
            </div>
            <div class="picture">
                <img src="../assets/imgs/r-michelle-tsang-500721-unsplash-min-800x527.jpg" alt="Ice cream" class="w-100 pointer">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "ImageSec"    
}
</script>

<style lang="scss">
    .picture{
        width: calc(100% / 4);
    }
</style>