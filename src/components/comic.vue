<script>
export default {
    name:"comic",
    data(){

        return{

        }
    },
    props:{
        comicThumb: String,
        comicSeries: String,
        comicType: String,
        comicPrice: String,
    },
    methods: {

    },
}
</script>

<template>
    <div class="card">
        <img :src="comicThumb" :alt="comicSeries">
        
        <h2>
            {{ comicSeries }}
        </h2>
        <p>
            {{ comicType }}
        </p>
        <p>
            {{ comicPrice }}
        </p>

    </div>
</template>


<!-- per ora tieni scoped nei components in modo tale che si riferiscano solo ad esso -->
<style lang="scss" scoped>
    .card{
        margin: 20px 10px;  
        
        img{
            width:100%;
            height: 300px;
        }

        

        h2{
            font-size: 20px;
            max-width: 250px;
        }

    }
    .card:hover{
        outline: 3px solid #028ef9;
        border-radius: 8px;
    }

</style>