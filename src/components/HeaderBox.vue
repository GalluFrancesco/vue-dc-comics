<template>
    <header>
        <div class="logo">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTABLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<script>

</script>

<style lang="scss" scoped>
@import '../style/variables.scss';

    header{
        display: flex;
        height: 130px;
        align-items: center;
        justify-content: space-between;
        width: 1000px;
        margin: 0 auto;
        
        .logo{
            text-align: center;
        }
        
        ul{
            display: flex;

            li{
                margin: 0 12px;
                font-size: 12px;
                font-weight: bold;
                line-height: 130px;

                &:hover{
                    color: $main-blue;
                    border-bottom: $main-blue solid 4px;
                }
            }
        }
    }

</style>