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
                <div>
                    <img src="../" alt="">
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
            font-weight: bolder;
            font-size: larger;
            font-size: 35px;
        }

        .container{
            width: 100%;
        }
    
    }

</style>