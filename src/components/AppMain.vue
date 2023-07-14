<script>
import jumbotron from '../components/jumbotron.vue';

export default {
    name:"AppMain",
    components:{
        jumbotron,
    },
    data(){

        return{
        
        }
    },
    methods: {

    },
}
</script>

<template>
    <main>
        <div class="container">

            <jumbotron />
            
            <div class="content">
                <div class="card" v-for="i in 12" :key="i">
                    <img src="https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg" alt="">
                    <h2>
                        Cazzoman returns
                    </h2>
                </div>
            </div>
        </div>
    </main>
</template>


<!-- per ora tieni scoped nei components in modo tale che si riferiscano solo ad esso -->
<style lang="scss" scoped>

    main{

        background-color: black;
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-around;
        

        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            margin: 0 auto;
            padding: 50px 400px;

            .card{
                margin: 20px 10px;
            }
        }

        .container{
            width: 100%;
        }
    
    }

</style>