<template>
    <footer>
        <div class="main-container">
           <div class="box-lists">
                <div class="txt-style">
                    <h4>DC COMICS</h4>
                    <ul>
                        <li>1</li>
                        <li>2</li>
                        <li>3</li>
                        <li>4</li>
                        <li>5</li>
                        <li>6</li>
                        <li>7</li>
                    </ul>
                    <h4>SHOP</h4>
                    <ul>
                        <li>1</li>
                        <li>2</li>
                    </ul>
                </div>
                <div class="txt-style">
                    <h4>DC</h4>
                    <ul>
                        <li>1</li>
                        <li>2</li>
                        <li>3</li>
                        <li>4</li>
                        <li>5</li>
                        <li>6</li>
                        <li>7</li>
                        <li>8</li>
                        <li>9</li>
                        <li>10</li>
                        <li>11</li>
                    </ul>
                </div>
                <div class="txt-style">
                    <h4>SITES</h4>
                    <ul>
                        <li>1</li>
                        <li>2</li>
                        <li>3</li>
                        <li>4</li>
                        <li>5</li>
                    </ul>
                </div>
           </div>
           <div class="box-logo-bg"></div>
        </div>
    </footer>
</template>

<script>

</script>

<style lang="scss" scoped>

    footer{
        background: url('../assets/footer-bg.jpg');
        background-size: cover;

        .main-container{
            margin: 0 auto;
            width: 1000px;
            height: 250px;
            display: flex;
            justify-content: space-between;

            .box-lists{
                display: flex;            
                > div{
                    padding: 36px 12px;
                    h4{
                        color: white;
                    }

                    ul{
                        color:grey;
                        font-size: 10px;
                    }
                }
            }

            .box-logo-bg{
                width: 400px;
                background: url('../assets/dc-logo-bg.png') no-repeat center;
                background-size:cover;
            }
        }
    }
</style>