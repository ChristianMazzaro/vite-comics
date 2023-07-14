<script>
export default {
    name:"AppMain",
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
        <div class="content"> -- > content goes here &LT;-- </div>
        <div></div>
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
        padding: 50px;

        .content {
            font-weight: bolder;
            font-size: larger;
            font-size: 35px;
        }
    
    }

</style>