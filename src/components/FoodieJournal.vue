<template>
    <section>
        <div class="container journal p-5">
            <div class="d-flex justify-content-around align-items-center pb-4">
                <div class="bar"></div>
                    <h3 class="text-uppercase text-center m-0">Foodie Journal</h3>
                    <div class="bar"></div>
            </div>
            <div class="row row-cols-3 gx-5">
                <div class="col">
                    <div class="card border-0">
                        <img src="../assets/imgs/single-post-img3-400x263.jpg" class="card-img-top pointer" alt="Sushi">
                        <div class="card-body text-center">
                            <h4 class="card-text active_title">Food Corner: Top Japanese <br> Restaurants for Sushi</h4>
                            <p class="card-text">By admin | March, 25th of November</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                        <img src="../assets/imgs/fi-roundup-400x263.jpg" class="card-img-top pointer" alt="Healthy Recipes">
                        <div class="card-body text-center">
                            <h4 class="card-text active_title">Roundup: My New Favourite <br> Recipes For Healthy Living</h4>
                            <p class="card-text">By admin | March, 25th of November</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                        <img src="../assets/imgs/fi-toasts-400x263.jpg" class="card-img-top pointer" alt="Toasts with tea">
                        <div class="card-body text-center">
                            <h4 class="card-text active_title">Why These Toasts with Tea are <br> My New Favourite</h4>
                            <p class="card-text">By admin | March, 25th of November</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'FoodieJournal'
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';

    .journal{
        background-color: $white-font;
        transform: translate(0, -15%);
        .bar{
            width: 490px;
            height: 1px;
            background-color: $light-font-color;
        }
        h3{
            font-size: 1.2em;
        }
        p{
            font-size: .8em;
        }
    }
</style>