<script>
export default {
    name:"MainFooter",
    data(){

        return{

        }
    },
    methods: {

    },
}
</script>

<template>

    <footer>
    
        <div class="user_utilities">

            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DIGITAL COMICS</p>
            </div>
        

        </div>
        <div class="footer_links">

            <div class="links_container">
                <div>
                    <h2>
                        DC COMICS
                    </h2>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>Tv</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h2>
                        SHOP
                    </h2>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="middle_footer_links">
                    <h2>
                        DC
                    </h2>
                    <ul>
                        <li>Terms of Use</li>
                        <li>Privacy Policy(New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div>
                    <h2>
                        SITES
                    </h2>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>  

            <div class="dc_logo_bg">
            </div>
        </div>
        <div class="socials_links">
            <div>
                <button>
                SIGN-UP NOW!
                </button>
            </div>
            <div class="socials">
                <h2>
                FOLLOW US
                </h2>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
  </footer>
</template>


<!-- per ora tieni scoped nei components in modo tale che si riferiscano solo ad esso -->
<style lang="scss" scoped>

footer{
    .user_utilities {
        display: flex;
        align-items: center;
        justify-content: space-around;
        color: white;
        background-color: #028ef9;
        padding: 50px 300px;

        div{
        display: flex;
        align-items: center;
        }

        img{
        margin: 0 10px;
        height: 80px;
        width: 60px;
        }
    }
  
    .footer_links{
        background-image: url(../assets/img/footer-bg.jpg);
        display: flex;
        justify-content: space-around;
        align-items: center;
        color: white;

        ul>li{
            list-style: none;
            color: grey;
        }

        .dc_logo_bg{
            background-image: url(../assets/img/dc-logo-bg.png);
            background-size: 550px;
            background-position: center;
            height:448px;
            width: calc(100% - 60%);
            background-repeat:no-repeat;
        }

        h2{
            margin: 25px 0;
        }

        .links_container{
            display: flex;
            justify-content: space-between;

            .middle_footer_links{
                margin: 0 50px;
            }
        }
    } 
  
    .socials_links{
        background-color: rgb(64, 63, 63);
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 50px 100px;
        .socials{
            display: flex;
            align-items: center;
  
            h2{
                color: #028ef9;
                font-size: 18px;
            }

            img{
                margin: 0 10px;
            }
        }   

        button{
            color: white;
            background-color: rgb(64, 63, 63);
            border: 3px solid  #028ef9;
            padding: 15px;
        }
    }
}

</style>