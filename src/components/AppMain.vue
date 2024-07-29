<script>
export default {
    
}
</script>

<template lang="">
    <main>
        <div class='jumbo-black'>
            <div class='container'>
                <div class='row'>
                    <div class='col-12'>
                        <div class='content-main'>
                            <h4>Content goes here</h4>
                        </div>
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
                                <li class='d-flex'>
                                    <img src='../assets/img/buy-dc-power-visa.svg' />
                                    <span class='mt-1'>DC POWER VISA</span>
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
    .jumbo-black{
        background-color: black;
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
                span{
                    margin-left: 10px;
                    font-size: 12px;
                }
                img{
                    width: 50px;
                }
            }
        }
    }
    .immagine-sfondo{
        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
    }

    .content-main-bottom{
        ul{
            li{
                font-size: 12px;
                color: lightgrey;
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
            top: -70px
        }
    }
</style>