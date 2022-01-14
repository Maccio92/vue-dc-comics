<template>
<div class="product">
    <img class="thumb" :src="iconFeature" :alt="altFeature">
    <p class="caption">{{captionFeature}}</p>
</div>
</template>

<script>
export default {
    name: "Features",
    props: ["iconFeature", "captionFeature", "altFeature"]
}
</script>

<style lang="scss" scoped>

.product{
    display: flex;
    justify-content: center;
    width: calc(100% / 5);
    align-items: center;
    gap: 10px;
    z-index: 2;
    .thumb{
    width: 20%;
    }
    .caption{
    font-size: 0.8em;
    color: white;
    } 
}
</style>