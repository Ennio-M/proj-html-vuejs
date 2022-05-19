<template>
    <section>
        <div class="container py-5">
            <div class="row row-cols-2">
                <div class="col">
                    <h3 class="text-uppercase py-3">Farm to table</h3>
                    <p>Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse <br> maximus lacus non nunc lacinia lobortis.</p>
                </div>
                <div class="col">
                    <div class="text-end my-4">
                        <a href="#" class="text-white text-uppercase py-3 px-4 read_button">
                        Read our blog &nbsp;
                        <i class="fa-solid fa-book-open-reader"></i>
                    </a>
                    </div>
                </div>
            </div>
            <div class="row py-4 g-5">
                <div class="col-8">
                    <div class="row">
                        <div class="col-12 my-4">
                             <div class="card border-0">
                                <img src="../assets/imgs/single-post-img3-800x527.jpg" class="card-img-top pointer" alt="Yogurt Nan">
                                <div class="card-body p-5">
                                    <h4 class="card-title m-0 active_title">Food Corner: Top Japaneese Restaurants for Sushi</h4>
                                    <p>By admin | March, 25th of November</p>
                                    <hr class="my-4">
                                    <p class="card-text lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti placeat consequuntur aliquam similique id culpa perspiciatis architecto accusantium consectetur! Sequi aliquid hic enim deleniti aperiam qui. Nobis repudiandae saepe commodi, labore animi distinctio odio?</p>
                                    <div class="float-start">
                                        <a href="#" class="read_more pointer">Read More &gt;</a>
                                    </div>
                                    <div class="float-end read_more">
                                        <i class="fa-regular fa-comments"></i>
                                        <span>&nbsp; 0</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="card border-0 my-3">
                                <img src="../assets/imgs/fi-roundup-400x263.jpg" class="card-img-top pointer" alt="Healthy recipes">
                                <div class="card-body text-center">
                                    <h4 class="card-text px-3 active_title">Roundup: My New Favourite Recipes For Healthy Living</h4>
                                    <p class="card-text">By admin | March, 25th of November</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="card border-0 my-3">
                                <img src="../assets/imgs/fi-korean-food-400x263.jpg" class="card-img-top pointer" alt="Korean food">
                                <div class="card-body text-center">
                                    <h4 class="card-text px-3 active_title">Meal Prep: Korean Bibimbap with Kimchi</h4>
                                    <p class="card-text">By admin | March, 25th of November</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="card border-0 my-3">
                                <img src="../assets/imgs/fi-toasts-400x263.jpg" class="card-img-top pointer" alt="Toasts with tea">
                                <div class="card-body text-center">
                                    <h4 class="card-text px-3 active_title">Why These Toasts with Tea are My New Favourite</h4>
                                    <p class="card-text">By admin | March, 25th of November</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="card border-0 my-3">
                                <img src="../assets/imgs/fi-street-food-400x263.jpg" class="card-img-top pointer" alt="Bangkok street food">
                                <div class="card-body text-center">
                                    <h4 class="card-text px-3 active_title">Exploring Street Food in Bangkok</h4>
                                    <p class="card-text">By admin | March, 25th of November</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="card border-0 my-3">
                                <img src="../assets/imgs/fi-organic-breakfast-400x263.jpg" class="card-img-top pointer" alt="Organic recipes">
                                <div class="card-body text-center">
                                    <h4 class="card-text px-3 active_title">Organic Choices For Healthier Living</h4>
                                    <p class="card-text">By admin | March, 25th of November</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="card border-0 my-3">
                                <img src="../assets/imgs/fi-water-side-rest-400x263.jpg" class="card-img-top pointer" alt="Waterside restaurants">
                                <div class="card-body text-center">
                                    <h4 class="card-text px-3 active_title">5 Waterside Restaurants for Special Events</h4>
                                    <p class="card-text">By admin | March, 25th of November</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="more_posts text-center py-2 my-3 pointer">
                                <a href="#" class="text-uppercase smaller">Load more posts</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="row">
                        <div class="col-12 my-4">
                            <div class="ad">
                                <div class="ad_text text-center">
                                    <h4 class="text-uppercase lh-base">View our latest recipes</h4>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div>
                                <a href="#" class="singapore">
                                    <img src="../assets/imgs/singapore-featured-image-400x263.jpg" alt="Singapore">
                                    <h4 class="p-2">City Guide: Singapore</h4>
                                </a>
                                <div class="view_all text-uppercase text-center py-2 pointer">
                                    <i class="fa-solid fa-earth-americas"></i>
                                    <span>&nbsp; View all city guides</span>
                                </div>
                            </div>
                            <hr class="my-5">
                        </div>
                        <div class="col-12">
                            <div class="input-group">
                                <span class="input-group-text">
                                    <i class="fa-solid fa-magnifying-glass"></i>
                                </span>
                                <input type="text" class="form-control" placeholder="Search...">
                            </div>
                            <div class="follow">
                                <h6>Follow Us</h6>
                                <div v-for="(social, index) in data.socials" :key="index" class="text-center rounded-3 my-2 pointer">
                                    <i :class="social"></i>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 my-5">
                            <div class="row popular">
                                <div class="col-6 text-center pointer">
                                    <h5>Popular</h5>
                                </div>
                                <div class="col-6 text-center pointer">
                                    <h5>Recent</h5>
                                </div>
                                <div class="col-12">
                                    <ul class="my-5">
                                        <li class="d-flex align-items-center my-4">
                                            <div class="post_img pointer">
                                                <img src="../assets/imgs/single-post-img3-66x66.jpg" alt="Japanese restaurants" class="rounded-circle">
                                            </div>
                                            <div class="post_content">
                                                <h6 class="pointer">Food Corner: Top Japanese Restaurants for Sushi</h6>
                                                <p>March 25th, 2019</p>
                                            </div>
                                        </li>
                                        <li class="d-flex align-items-center my-4">
                                            <div class="post_img pointer">
                                                <img src="../assets/imgs/singapore-featured-image-66x66.jpg" alt="Singapore" class="rounded-circle">
                                            </div>
                                            <div class="post_content">
                                                <h6 class="pointer">City Guide: Singapore</h6>
                                                <p>February 27th, 2019</p>
                                            </div>
                                        </li>
                                        <li class="d-flex align-items-center my-4">
                                            <div class="post_img pointer">
                                                <img src="../assets/imgs/slide1-bg-66x66.jpg" alt="Nutritional tips" class="rounded-circle">
                                            </div>
                                            <div class="post_content">
                                                <h6 class="pointer">6 Nutritional Tips to Help Burn Body Fat</h6>
                                                <p>February 28th, 2019</p>
                                            </div>
                                        </li>
                                    </ul>
                                </div>
                                <div class="col-12">
                                    <div class="tweet_area p-5 rounded-1 pointer">
                                        <div class="d-flex justify-content-between align-items-center pb-3">
                                            <div class="from">
                                                <h5 class="d-inline-block">Tweets</h5>
                                                <p class="d-inline-block">&nbsp;by <span class="highlight">&commat;Theme_Fusion</span></p>
                                            </div>
                                            <i class="fa-solid fa-circle-info"></i>
                                        </div>
                                        <div class="tweet d-flex">
                                            <div class="logo">
                                                <img src="../assets/imgs/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="">
                                            </div>
                                            <div class="tweet_content px-2 w-100">
                                                <div class="tweet_head d-flex justify-content-between">
                                                    <div>
                                                        <h5 class="m-0 fw-bold">Theme Fusion</h5>
                                                        <p class="m-0 smaller">&commat; Theme Fusion</p>
                                                    </div>
                                                    <i class="fa-brands fa-twitter"></i>
                                                </div>
                                                <div class="tweet_text pt-3">
                                                    <p>
                                                        Do you need sublime WordPress hosting for your next website? Take advantage of exclusive partner offers that we have secured just for you, &amp; launch your site in seconds with <span class="highlight">&num;avada</span> on WP Engine hosting &amp; get 30&percnt; Off this Black Friday
                                                        <a href="#" class="highlight">bit.ly/3kjLLE2</a>
                                                        <span class="highlight">&nbsp;&num;BlackFriday2020</span>
                                                    </p>
                                                    <img src="../assets/imgs/avada-tweet.jpg" alt="Tweet picture" class="w-100 rounded-1 pt-2">
                                                </div>
                                                <div class="tweet_icons pt-1">
                                                    <div class="float-start">
                                                        <i class="fa-regular fa-heart smaller me-4"></i>
                                                        <i class="fa-solid fa-arrow-right-from-bracket smaller"></i>
                                                    </div>
                                                    <p class="float-end smaller">21h</p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "BlogPosts",
    props:{
        data: Object
    } 
}
</script>

<style lang="scss">
    @import '../styles/variables.scss';
    .read_button{
        font-size: .8em;
        background-color: $page-theme;
    }
    .read_more{
        font-size: .7em;
        color: $secondary-font-color;
        &:hover{
            color: $page-theme;
        }
    }
    .more_posts{
        background-color: $darker-bg-color;
        &:hover{
            background-color: $main-font-color;
        }
        & a{
            color: $main-font-color;
        }
        &:hover a{
            color: $white-font;
        }
    }
    .ad{
        background-image: url(../assets/imgs/ad-bg.jpg);
        height: 500px;
        background-position: center;
        background-size: cover;
        position: relative;
        cursor: pointer;
        .ad_text{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
    }
    .singapore{
        position: relative;
        h4{
            position: absolute;
            top: 150%;
            color: $white-font;
            background-color: $main-font-color;
        }
    }
    .view_all{
        color: $white-font;
        background-color: $page-theme;
        &:hover{
            color: $white-font;
        }
    }
    .input-group{
        border: 1px solid $light-font-color;
        border-radius: 5px;
        height: 45px;
        margin-bottom: 2em;
        &>*{
            background-color: $white-font !important;
            color: $light-font-color !important;
            border: none !important;
        }
    }
    .follow{
        h6{
            color: $page-theme;
        }
        i{
            color: $main-font-color;
        }
        div{
            width: 32px;
            height: 30px;
            background-color: $darker-bg-color;
            margin-right: .8em;
            border: 1px solid $light-font-color;
            display: inline-block;
        }
    }
    .popular{
        &>div:first-child{
            border-right: 1px solid $main-font-color;
        }
        .pop_rec{
            height: 40px;
        }
    }
    .post_img{
    }
    .post_content{
        padding-left: 10px;
        &>*{
            margin: 0;
        }
        h6:hover{
            color: $page-theme;
        }
    }
    .tweet_area{
        background-color: $white-font;
        &:hover{
            background-color: $twitter_hover;
        }
        &:hover .fa-twitter{
            color: $twitter_blue;
        }
        i{
            color: $light-font-color;
        }
        .from{
            &>*{
                margin: 0;
            }
        }
    }
    .highlight{
        color: $highlight_text;
    }
</style>