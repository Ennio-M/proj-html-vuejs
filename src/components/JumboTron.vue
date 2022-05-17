<template>
    <section class="jumbo d-flex justify-content-center align-items-center">
        <div class="jumbo_text">
            <h1>
                Food Corner: Top Japanese <br>
                Restaurants for Sushi
            </h1>
            <p class="m-0">March 25, 2019</p>
            <div class="today text-uppercase">
                <h6 class="m-0 text-white">Today's pick</h6>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "JumboTron"    
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';

    .jumbo{
        height: 500px;
        background-image: url(../assets/imgs/single-post-img3-1200x790.jpg);
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        .jumbo_text{
            background-color: $white-font;
            color: $main-font-color;
            border-radius: 8px;
            padding: 40px 80px 30px;
            text-align: center;
            position: relative;
            p{
                font-size: .8em;
                color: $light-font-color;
            }
            .today{
                position: absolute;
                top: -8%;
                left: 50%;
                transform: translate(-50%, 0);
                background-color: $page-theme;
                padding: 4px 15px;
                border-radius: 8px;
                box-shadow: 0 5px 15px $light-font-color;
            }
        }
    }
</style>