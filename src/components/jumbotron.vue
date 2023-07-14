<script>
export default {
    name:"jumbotron",
    data(){

        return{

        }
    },
    methods: {

    },
}
</script>

<template>
    <div class="jumbotron">
    </div>
</template>


<!-- per ora tieni scoped nei components in modo tale che si riferiscano solo ad esso -->
<style lang="scss" scoped>

   .jumbotron{
        width: 100%;
        height: 450px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        background-repeat: no-repeat;
       
    }
</style>