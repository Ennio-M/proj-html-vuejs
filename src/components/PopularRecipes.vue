<template>
    <section>
        <div class="container">
            <div class="row row-cols-1">
                <div class="col text-center my-4">
                    <h3 class="text-uppercase py-3">Popular recipes</h3>
                    <p>Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse <br> maximus lacus nunc lacina lobortis</p>
                </div>
            </div>
            <div class="row row-cols-2 gx-5">
                <div class="col">
                    <div class="card border-0">
                        <img src="../assets/imgs/Yogurt-Nan-400x263.jpg" class="card-img-top" alt="Yogurt Nan">
                        <div class="card-body p-5">
                            <h4 class="card-title m-0">Lunch Favourite with Salad, Naan And Beans</h4>
                            <p class="smaller">Bakery, Featured, Healthy, Latest Recipes, Staff Picks</p>
                            <hr class="my-4">
                            <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Modi molestiae vel asperiores placeat unde sed possimus? Deserunt nesciunt id minus repellat rerum accusamus quia eligendi vitae pariatur delectus. Explicabo voluptatibus quo vel in consequuntur dolorem soluta, repellendus placeat repellat rem eveniet, maxime accusantium deleniti est velit vero mollitia voluptate exercitationem voluptatem tempore, animi blanditiis veniam! Quasi quod repellat optio. Tempore magni et animi dolor necessitatibus dignissimos aperiam, atque minus suscipit?</p>
                            <a href="#" class="text-white text-uppercase py-2 px-4 learn">Learn more</a>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="row row-cols-2 g-4">
                        <div class="col">
                            <img src="../assets/imgs/Mixed-fruits-460x295.jpg" alt="Mixed fruits" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/r-rachel-park-366508-unsplash-min-460x295.jpg" alt="Breakfast" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/r-michelle-tsang-500721-unsplash-min-460x295.jpg" alt="Ice cream" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/quick-summer-drink-460x295.jpg" alt="Quick summer drink" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="Vegetables" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/perfect-cosmopolitan-460x295.jpg" alt="Cosmopolitan" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/fi2x-6-460x295.jpg" alt="Mixed breakfast" class="w-100">
                        </div>
                        <div class="col">
                            <img src="../assets/imgs/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="Brooke lark" class="w-100">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "PopularRecipes"
}
</script>

<style lang="scss">
@import '../styles/variables.scss';

    h3, h4{
        color: $main-font;
    }
    p{
        color: $secondary-font-color;
        font-size: .8em;
    }
    .smaller{
        font-size: .7em;
    }
    hr{
        color: $secondary-font-color;
    }
    .learn{
        font-size: .8em;
        background-color: $page-theme;
    }
</style>