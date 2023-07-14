<script>
export default {
    name:"mainHeader",
    data(){

        return{

        }
    },
    methods: {

    },
}
</script>

<template>
    <header>
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>
    </header>
</template>


<!-- per ora tieni scoped nei components in modo tale che si riferiscano solo ad esso -->
<style lang="scss" scoped>

    header{
        padding: 40px;
        text-align: center;
        background-color: white;
        display: flex;
        justify-content: space-around;
        align-items: center;

        ul > li {
            list-style: none;
            display: inline-block;
            margin-right: 20px;
            font-weight: bolder;
        }
    }

    img {
        height: 50px;
        width: 50px;
    }



</style>