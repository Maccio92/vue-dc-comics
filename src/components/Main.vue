<template>
<div>
    <div class="main-container">
        <div class="container">
            <h1>Content Goes Here</h1>
        </div>
    </div>
    <div class="second-container">
        <div class="container">
            <div class="product">
                <img class="thumb" src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p class="caption">DIGITAL COMICS</p>
            </div>
            <div class="product">
                <img class="thumb" src="../assets/img/buy-comics-merchandise.png" alt="">
                <p class="caption">DC MERCHANDISE</p>
            </div>
            <div class="product">
                <img class="thumb" src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p class="caption">SUBSCRIPTIONS</p>
            </div>
            <div class="product">
                <img class="thumb" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p class="caption">DC SHOP LOCATOR</p>
            </div>
            <div class="product">
                <img class="thumb" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p class="caption">DC POWER VISA</p>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style lang="scss" scoped>
.main-container{
    width: 100%;
    height: 100px;
    background-color: #1c1c1c;
}
h1{
    color: white;
    font-size: 1em;
}
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}
.second-container{
    width: 100%;
    height: 150px;
    background-color: #0282f9;
}
.product{
    display: flex;
    justify-content: center;
    width: calc(100% / 5);
    align-items: center;
    gap: 10px;
    .thumb{
    width: 20%;
    }
    .caption{
        font-size: 0.8em;
        color: white;
    }   
}

</style>