<template>
    <div>
        <a href="#" class="up_button rounded-circle text-center">
            <i class="fa-solid fa-chevron-up"></i>
        </a>
        <div class="right_buttons">
            <a href="#">
                <div class="r_button">
                    <i class="fa-solid fa-folder-closed"></i> <br>
                    Prebuilts
                </div>
            </a>
            <a href="#">
                <div class="r_button mt-2">
                    <i class="fa-solid fa-cart-arrow-down"></i> <br>
                    Buy Now
                </div>
            </a>
        </div>
    </div>
</template>

<script>
export default {
    name: "AppFixed"    
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    .up_button{
        height: 50px;
        width: 50px;
        background-color: $main-font-color;
        line-height: 50px;
        position: fixed;
        bottom: 5%;
        left: 3%;
        i{
            color: $white-font;
        }
    }
    .right_buttons{
        position: fixed;
        top: 28%;
        right: 2%;
        .r_button{
            text-align: center;
            background-color: $white-font;
            color: $fixed-blue;
            font-size: .8em;
            border-radius: 8px;
            padding: 6px 5px;
            box-shadow: 0 0px 25px $secondary-font-color;
        }
        
    }
</style>