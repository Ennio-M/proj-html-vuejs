<template>
    <section>
        <div class="container journal p-5">
            <h3 class="text-uppercase text-center">Foodie Journal</h3>
            <div class="row row-cols-3">
                <div class="col">
                    <div class="card border-0">
                    <img src="../assets/imgs/single-post-img3-200x132.jpg" class="card-img-top" alt="...">
                    <div class="card-body text-center">
                        <h4 class="card-text">Food Corner: Top Japanese <br> Restaurants for Sushi</h4>
                        <p class="card-text">By admin | March, 25th of November</p>
                    </div>
                </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                    <img src="../assets/imgs/fi-roundup-200x132.jpg" class="card-img-top" alt="...">
                    <div class="card-body text-center">
                        <h4 class="card-text">Roundup: My New Favourite <br> Recipes For Healthy Living</h4>
                        <p class="card-text">By admin | March, 25th of November</p>
                    </div>
                </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                    <img src="../assets/imgs/fi-toasts-200x132.jpg" class="card-img-top" alt="...">
                    <div class="card-body text-center">
                        <h4 class="card-text">Why These Toasts with Tea are <br> My New Favourite</h4>
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
    name: 'FoodieJournal',
        
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';

    .journal{
        background-color: $white-font;
        transform: translate(0, -10%);
        h3{
            font-size: 1.2em;
            padding-bottom: 15px;
        }
        h3, h4{
            color: $main-font-color;
        }
        p{
            color: $secondary-font-color;
            font-size: .8em;
        }
    }
</style>