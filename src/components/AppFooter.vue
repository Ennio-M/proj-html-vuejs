<template>
    <footer>
        <div class="footer_top py-5">
            <div class="container">
                <div class="row row-cols-4">
                    <div class="col px-4 myborder">
                        <img src="../assets/imgs/avada-food-logo-mob-2x.png" alt=" Avada Food logo" class="mb-3">
                        <div class="icons my-3">
                            <i v-for="(social, index) in data.socials" :key="index" :class="social" class="mx-2"></i>
                        </div>
                    </div>
                    <div class="col px-4 myborder">
                        <ul class="p-0">
                            <li v-for="item in data.navbar" :key="item.id">
                                <a href="#" :class="item.active ? 'active' : ''" v-if="item.text != null && item.text != 'Home'" class="lh-lg">{{item.text}}</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col px-4 myborder">
                        <h5>Contact</h5>
                        <ul class="p-0">
                            <li class="d-flex" v-for="(contact, index) in data.contacts" :key="index">
                                <i :class="contact.icon"></i>
                                <p class="ms-3">{{contact.text}}</p>
                            </li>
                        </ul>
                    </div>
                    <div class="col px-4">
                        <h5>Get our app</h5>
                        <img src="../assets/imgs/download-android-200x66.png" alt="Download Android" class="mb-2">
                        <img src="../assets/imgs/download-app-store-200x66.png" alt="Download iOS">
                    </div>
                </div>
            </div>
        </div>
        <div class="footer_bottom text-center">
            <p class="m-0">&copy; Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
        </div>
    </footer>
</template>

<script>
export default {
    name: "AppFooter",
    props: {
        data: Object
    } 
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';

    .footer_top{
        background-color: $white-font;
        a{
            color: $main-font-color;
            &:hover{
                color: $page-theme;
            }
        }
        i{
            color: $light-font-color;
        }
        h5{
            text-transform: uppercase;
            color: $page-theme;
            margin-bottom: 1.5em;
        }
        img{
            cursor: pointer;
        }
        .myborder{
            border-right: 1px dashed $light-font-color;
        }
    }
    .footer_bottom{
        background-color: $darker-bg-color;
        height: 40px;
        line-height: 40px;
        p{
            font-size: .6em;
        }
    }
</style>