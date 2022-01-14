<template>
<div class="item flex">
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
    flex-direction: column;
    flex-basis: calc(100% / 6);
    .thumb-container{
        height: 180px;
        overflow: hidden;
        img{
            height: 250px; 
        }
    }    
}
</style>