<template>
<div class="item">
    <div class="thumb-container">
        <img :src="thumbProduct" :alt="seriesProduct">
    </div>
    <h2>{{seriesProduct}}</h2>
</div>
</template>

<script>
export default {
    name: "Product",
    props: ["thumbProduct","seriesProduct"]

}
</script>

<style lang="scss" scoped>
.item{
    height: 250px;
    display: flex;
    flex-direction: column;
    flex-basis: calc(100% / 6);
    align-items: center;
    .thumb-container{
        height: 180px;
        overflow: hidden;
        
    
        img{
            height: 250px; 
        }
    }
        h2{
            color: white;
            font-size: 1em;
            font-weight: 300;
            text-align: center;
        }
    
}
</style>