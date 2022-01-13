<template>
<div class="container">
    <img src="../assets/img/dc-logo.png" alt="">
    <ul>
        <li><a href="#"></a>CHARACTERS</li>
        <li><a href="#"></a>COMICS</li>
        <li><a href="#"></a>MOVIES</li>
        <li><a href="#"></a>TV</li>
        <li><a href="#"></a>GAMES</li>
        <li><a href="#"></a>COLLECTIBLES</li>
        <li><a href="#"></a>VIDEOS</li>
        <li><a href="#"></a>FANS</li>
        <li><a href="#"></a>NEWS</li>
        <li><a href="#"></a>SHOP</li>
<a href=""></a>

    </ul>
</div>
</template>

<script>
export default {
    name: 'Header',
}
</script>
    name: 'Header',
<style lang="scss" scoped>
div{
    // background-color: aqua;
    height: 100px;
    display: flex;
    justify-content: space-between;
    
    height: 100px;
}
img{
    padding: 20px;
}
ul{
    display: flex;
    list-style-type: none;
    align-items: center;
    height: 100%;
    li{
        
        padding: 10px;
        font-size: 0.8em;
        font-weight: 700;
        height: 100%;
        &:hover,
        &:active {
            border-bottom: solid 3px #0282f9;
            cursor: pointer;
    }
        a{
        text-decoration: none;
        display: block;
        padding-top: 30px;
    }
    }
    
}
</style>