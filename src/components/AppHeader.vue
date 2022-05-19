<template>
    <header>
        <div class="container">
            <div class="pt-2 top-bar">
                <div class="float-start">
                    <span>Download App</span>
                    <span class="ios mx-2">iOS</span>
                    <span class="mx-3">Advertise with us</span>
                </div>
                <div class="float-end">
                    <i v-for="(social, index) in data.socials" :key="index" :class="social" class="mx-2"></i>
                </div>
            </div>
            <div class="text-center my-3">
                <img src="../assets/imgs/avada-food-logo.png" alt="Logo Avada Food">
            </div>
            <nav>
                <ul class="d-flex justify-content-center pb-3 m-0">
                    <li v-for="item in data.navbar" :key="item.id">
                        <a href="#" :class="item.active ? 'active' : ''" v-if="item.text != null">{{item.text}}</a>
                        <a href="" v-else><i :class="item.class"></i></a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
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
    @import '../styles/variables.scss';
    header{
        background-color: $darker-bg-color;
    }
    .top-bar{
        font-size: .7em;
        color: $light-font-color;
        height: 30px;
        .ios{
            padding: 1px 6px;
            background-color: $page-theme;
            color: $white-font;
            border-radius: 5px;
            text-decoration: none !important;
        }
        span, i{
            cursor: pointer;
        }
        span:hover{
            text-decoration: underline;
        }
    }
    nav{
        margin-top: 20px;
        li{
            margin: 0 30px 0;
        }
        a, i{
            color: $main-font-color !important;
            font-size: .8em;
            padding-bottom: 10px;
        }
        .active, a:active, i:active{
            border-bottom: 2px solid $page-theme;
            color: $page-theme !important;
        }
    }
</style>