<template>
    <section class="subscribe d-flex justify-content-center align-items-center">
        <div class="subscribe_text text-center">
            <h1 class="my-3">Subscribe <span>&amp;</span> Receive A Free eBook</h1>
            <p class="lh-lg">Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse maximus lacus non nunc lacinia <br> lobortis.</p>
            <div class="input_field d-flex justify-content-center align-items-center my-4">
                <input type="text" placeholder="Insert your email... *" class="me-4 rounded-2">
                <a href="#" class="text-white text-uppercase py-3 px-4 learn">Subscribe</a>
            </div>
            <p class="smaller my-2">Cras porttitor pellentesquee sem eu pretium.</p>
        </div>
    </section>
</template>

<script>
export default {
    name: "SubscribeSec"    
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    
    .subscribe{
        height: 500px;
        background-image: url(../assets/imgs/subscribe-sec-bg.png);
        background-color: $white-font !important;
        background-position: center;
        background-size: cover;
    }
    h1{
        color: $main-font-color;
    }
    .subscribe_text{
        span{
            color: $page-theme;
        }
        input{
            height: 55px;
            width: 450px;
            &:hover{
                border-color: $page-theme;
            }
        }
    }
</style>