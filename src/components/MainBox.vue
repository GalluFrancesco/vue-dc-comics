<template>
    <main>
        <div class="card-container">
            <div class="item" v-for="(comic,i) in comics" :key="i">
                <div class="card" >
                    <img :src="comic.thumb" alt="">
                    <p class="txt-style">{{comic.series}}</p>
                </div>
            </div>
        </div>
        <div class="load-button txt-style">LOAD MORE</div>
    </main>
</template>

<script>
export default {
    props:{
        comics:Array
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';

    main{
        width: 100%;
        background-color:black ;
        padding: 72px 0;
        .card-container{
            width: 1000px;
            display: flex;
            margin: 0 auto;
            flex-wrap: wrap;
            justify-content: space-between;
            .item{
                .card{
                    width: 150px;
                    height: 200px;
                    margin-bottom: 12px;
                    img{
                        width: 100%;
                        height: 150px;
                        object-fit: cover;
                        object-position:top;
                    }
                    p{
                        text-transform: uppercase;
                        color: white;
                    }
                }
            }
        }

        .load-button{
            margin: 0 auto;
            margin-top: 72px;
            text-align: center;
            width: 150px;
            padding: 12px 0px;
            color: white;
            font-weight: bold;
            background-color: $main-blue;
        }
    }
</style>