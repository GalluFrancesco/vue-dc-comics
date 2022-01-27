<template>
    <div class="social">
        <div class="main-container txt-style">
            <div class="sign-button">SIGN-UP NOW!</div>
            <div class="social-icon">
                <div>FOLLOW US</div>
                <div>
                    <img src="../assets/footer-facebook.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-twitter.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-youtube.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-pinterest.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style lang="scss" scoped>
@import '../style/variables.scss';

    .social{
        background-color: #303030;
        padding: 24px 0;

        .main-container{
            width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;

            .sign-button{
                color: white;
                border: $main-blue solid 1px;
                padding: 12px;
            }

            .social-icon{
                display: flex;
                align-items: center;
                color: $main-blue;
                font-weight: bold;
                
                > div{
                    padding-left: 12px;
                }
            }
        }

    }
   
</style>