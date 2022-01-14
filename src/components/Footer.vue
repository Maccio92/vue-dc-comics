<template>
<div>
    <div class="upper-footer flex">
        <div class="container flex">
            <div class="col">
                <h3>DC COMICS</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <h3>SHOP</h3>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div class="col">
                <h3>DC</h3>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy Policy</li>
                    <li>Ad Choice</li>
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
            <div class="col">
                <h3>SITES</h3>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
            <img class="thumb-bg" src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
    <div class="lower-footer">
        <div class="container container-low flex">
            <div class="left-col">
                <button>SIGN-UP NOW</button>
            </div>
            <div class="right-col flex">
                <h2>FOLLOW US</h2>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>

        </div>
    </div>

</div>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style lang="scss">
.upper-footer{
    width: 100%;
    height: 300px;
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    align-items: center;
    position: relative;
    z-index: 1;
    .thumb-bg{
        width: 400px;
        position: absolute;
        top: -50px;
        right: 150px;
        z-index: 0;
    }
}
.lower-footer{
    width: 100%;
    height: 100px;
    background-color: #303030;
    position: relative;
    z-index: 1;
    .container-low{
        height: 100%;
        justify-content: space-between;
        .left-col{
            button{
                border: solid 2px #0282f9;
                padding: 10px;
                background-color: #303030;
                color: white;
            }
        }
        .right-col{
            gap: 15px;     
        }
        img{
            height: 20%;
        }
    }
}
.container{
    justify-content: start;
    .col{
        width: 15%;
        ul{
            list-style: none;
            li{
                color: grey;
                font-size: 0.6em;
                font-weight: 300;
                margin: 5px 0;
            }
        }
    }
}
</style>