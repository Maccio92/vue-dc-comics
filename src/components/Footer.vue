<template>
<div>
    <div class="upper-footer">
        <div class="container">
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
        <div class="container-low">
            <div class="left-col">
                <button>SIGN-UP NOW</button>
            </div>
            <div class="right-col">
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
    display: flex;
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
        width: 80%;
        height: 100%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .left-col{
            button{
                border: solid 2px #0282f9;
                padding: 10px;
                background-color: #303030;
                color: white;
            }
        }
        .right-col{
            display: flex;
            align-items: center;
            gap: 15px;
                h2{
                    color: #0282f9;
                    font-size: 1em;
                }   
        }
        img{
            height: 20%;
        }
    }
}
.container{
    display: flex;
    justify-content: start;
    .col{
        width: 15%;
        h3{
            color: white;
            font-size: 0.8em;
            margin: 8px 0;
        }
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