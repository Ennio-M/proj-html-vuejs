<template>
    <section>
        <div class="container">
            <div class="row row-cols-1">
                <div class="col text-center my-4">
                    <h3 class="text-uppercase py-3">Culinary Collection</h3>
                    <p>Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse <br> maximus lacus non nunc lacinia lobortis.</p>
                </div>
            </div>
            <div class="row row-cols-4 g-5">
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/drinks-recipes.png" alt="Drinks">
                        <h6 class="text-uppercase">Drinks</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/soups-recipes.png" alt="Soups">
                        <h6 class="text-uppercase">Soups</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/baking-recipes.png" alt="Bakery">
                        <h6 class="text-uppercase">Bakery</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/dinner-recipes.png" alt="Dinner">
                        <h6 class="text-uppercase">Dinner</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/healthy-recipes.png" alt="Healthy">
                        <h6 class="text-uppercase">Healthy</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/staff-picks.png" alt="Staff picks">
                        <h6 class="text-uppercase">Staff picks</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/premium-recipes.png" alt="Appetizers">
                        <h6 class="text-uppercase">Appetizers</h6>
                    </div>
                </div>
                <div class="col">
                    <div class="box">
                        <img src="../assets/imgs/quick-easy-recipes.png" alt="Quick and easy">
                        <h6 class="text-uppercase">Quick &amp; easy</h6>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "CulinaryCollection"    
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';

    section{
        padding-top: 2em;
    }
    p{
        font-size: .8em;
    }
    .box{
        background-color: $white-font;
        text-align: center;
        padding: 1em 0;
        cursor: pointer;
        box-shadow: 0 0px 20px $shadows;
        &:hover img{
            transform: scale(1.08);
        }
        img{
            width: 50%;
            transition: all .4s ease-in-out;
        }
        h6{
            font-weight: 600;
        }
    }
</style>