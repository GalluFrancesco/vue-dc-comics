<template>
    <div class="market-box txt-style">
        <div class="card-buy-box">
            <div class="box-img">
                <img src="../assets/buy-comics-digital-comics.png" alt="">
            </div>
            <div class="box-txt">DIGITAL COMICS</div>
        </div>
        <div class="card-buy-box">
            <div class="box-img">
                <img src="../assets/buy-comics-merchandise.png" alt="">
            </div>
            <div class="box-txt">DC MERCHANDISE</div>
        </div>
        <div class="card-buy-box">
            <div class="box-img">
                <img src="../assets/buy-comics-subscriptions.png" alt="">
            </div>
            <div class="box-txt">SUBSCRIPTION</div>
        </div>
        <div class="card-buy-box">
            <div class="box-img">
                <img src="../assets/buy-comics-shop-locator.png" alt="">
            </div>
            <div class="box-txt">COMIC SHOP LOCATOR</div>
        </div>
        <div class="card-buy-box">
            <div class="box-img">
                <img src="../assets/buy-dc-power-visa.svg" alt="">
            </div>
            <div class="box-txt">DC POWER VISA</div>
        </div>
    </div>
</template>

<script>

</script>

<style lang="scss" scoped>
@import '../style/variables.scss';

    .market-box{
        width: 100%;
        height: 150px;
        background-color:$main-blue;
        display: flex;
        justify-content: center;
        align-items: center;

        .card-buy-box{
            display: flex;

            .box-img{
                height:50px;

                img{
                    height: 100%;
                }
            }

            .box-txt{
                font-size: 12px;
                color: white;
                margin: 0 18px;
                line-height: 50px;
            }
        }
    }


</style>