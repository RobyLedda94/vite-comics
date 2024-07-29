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
                            <ul class='d-flex list-unstyled align-items-center justify-content-center'>
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
        
    </main>
</template>

<style lang="scss" scoped>
    .jumbo-black{
        background-color: black;
    }

    .jumbo-blue{
        background-color: #387cec;
    }

    .content-main{
        padding: 40px 0;
        color: white;

        ul{
            li{
                padding: 0 19px;
                span{
                    margin-left: 5px;
                }
                img{
                    width: 60px;
                }
            }
        }
    }
</style>