<template>
    <div class="card">
        <div class="img-container">
            <img :src="img">
        </div>
        <h5>{{title}}</h5>
    </div>
</template>

<script>
export default {
    name: "BaseCard",
    props:{
        img:String,
        title:String
    }
}
</script>

<style lang="scss" scoped>

    .card{
        width: 15%;
        height: 100%;

        h5{
            margin-top: 10px;
            font-size: 10px;
        }
    }
    
    .img-container{
        width: 100%;
        height: 150px;
        overflow: hidden;
        img{
            width: 100%;
            height: auto;
        }
    }
</style>