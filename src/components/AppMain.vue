<script>
import datacards from '../data/cards'
export default {
    data() {
        return {
           datacards
        }
    },
}
</script>

<template lang="">
    <main>
        <div class='jumbotron'>
            <button class='current btn btn-primary'>CURRENT SERIES</button>
        </div>
        <div class='jumbo-black py-5'>
            <div class='container'>
                <div class='row'>
                    <div class='cards-container col-12 col-md-2' v-for="card, index in datacards" :key="index">
                        <img :src='card.thumb' :alt='card.series'>
                        <p> {{card.series}} </p>                                  
                    </div>
                    <div class='col-12 d-flex justify-content-center'>
                        <button class='btn btn-primary'>LOAD MORE</button>
                    </div>
                </div>
            </div>
        </div>
        <div class='jumbo-blue'>
            <div class='container'>
                <div class='row'>
                    <div class='col-12'>
                        <div class='content-main'>
                            <ul class='d-flex list-unstyled align-items-center justify-content-center flex-nowrap'>
                                <li>
                                    <img src='../assets/img/buy-comics-digital-comics.png' />
                                    <span>DIGITAL COMICS</span>                                   
                                </li>
                                <li>
                                    <img src='../assets/img/buy-comics-merchandise.png' />
                                    <span>DC MERCHANDISE</span>                                    
                                </li>
                                <li>
                                    <img src='../assets/img/buy-comics-subscriptions.png' />
                                    <span>SUBSCRIPTION</span>                                   
                                </li>
                                <li>
                                    <img src='../assets/img/buy-comics-shop-locator.png' />
                                    <span>COMIC SHOP LOCATOR</span>                                   
                                </li>
                                <li class='d-flex align-items-center'>
                                    <img src='../assets/img/buy-dc-power-visa.svg' />
                                    <span class='mb-1'>DC POWER VISA</span>
                                </li>
                            </ul>                  
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class='immagine-sfondo'>
            <div class='container'>
                <div class='row'>
                    <div class='col-12'>
                        <div class='content-main-bottom d-flex justify-content-between'>
                            <div class='left d-flex py-4'>
                                <ul class='list-unstyled'>
                                    <li>
                                        <p>DC COMICS</p>
                                    </li>
                                    <li>
                                        Characters
                                    </li>
                                    <li>
                                        Comics
                                    </li>
                                    <li>
                                        Movies
                                    </li>
                                    <li>
                                        TV
                                    </li>
                                    <li>
                                        Games
                                    </li>
                                    <li>
                                        Videos
                                    </li>
                                    <li>
                                        News
                                    </li>
                                    <li>
                                        <p class='mt-3'>DC COMICS</p>
                                    </li>
                                    <li>
                                        Shop DC
                                    </li>
                                    <li>
                                        Shop DC Collectibles
                                    </li>
                                </ul>
                                <ul class='list-unstyled mx-4'>
                                    <li>
                                        <p>DC</p>
                                    </li>
                                    <li>
                                        Terms Of Use
                                    </li>
                                    <li>
                                        Privacy policy (New)
                                    </li>
                                    <li>
                                        Ad Choices
                                    </li>
                                    <li>
                                        Advertising
                                    </li>
                                    <li>
                                        Jobs
                                    </li>
                                    <li>
                                        Subscription
                                    </li>
                                    <li>
                                        Talent Workshops
                                    </li>
                                    <li>
                                        CPSC Certificates
                                    </li>
                                    <li>
                                        Ratings
                                    </li>
                                    <li>
                                        Shop Help
                                    </li>
                                    <li>
                                        Contact Us
                                    </li>
                                </ul>
                                <ul class='list-unstyled'>
                                    <li>
                                        <p>SITES</p>
                                    </li>
                                    <li>
                                        DC
                                    </li>
                                    <li>
                                        MAD Magazine
                                    </li>
                                    <li>
                                        DC Kids
                                    </li>
                                    <li>
                                        DC Universe
                                    </li>
                                    <li>
                                        DC Power Visa
                                    </li>
                                </ul>
                            </div>
                            <div class='right'>
                                <img class='logo-grande' src='../assets/img/dc-logo-bg.png' />
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
    </main>
</template>

<style lang="scss" scoped>
    .jumbotron{
        background-image: url('../assets/img/jumbotron.jpg');
        background-size: cover;
        height: 400px;
        position: relative;
        .current{
            position: absolute;
            bottom: -18px;
            left: 258px;
            font-weight: bold;
        }
    }
    .jumbo-black{
        background-color: black;
        .cards-container{
            margin-bottom: 20px;
            p{
                color: white;
                padding-top: 10px;
            }
            img{
                width: 100%;
                max-height: 225px;
                object-fit: cover;
            }
        }
    }

    .jumbo-blue{
        background-color: #387cec;
        position: relative;
        z-index: 1;
    }

    .content-main{
        padding: 40px 0;
        color: white;

        ul{
            li{
                padding: 0 19px;
                margin: 0 10px;
                img{
                    width: 50px;
 
                }
                span{
                    margin-left: 10px;
                    font-size: 12px;
                }
            }
        }
    }
    .immagine-sfondo{
        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
    }

    .content-main-bottom{
        height: 357px;
        ul{
            li{
                font-size: 12px;
                color: rgb(131, 131, 131);
                p{
                    color: white;
                    font-weight: bold;
                }
            }
        }
    }
    .right{
        .logo-grande{
            width: 460px;
            position: relative;
            top: -46px
        }
    }
</style>