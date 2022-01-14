<template>
<div class="product flex">
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
    justify-content: center;
    width: calc(100% / 5);
    gap: 10px;
    z-index: 2;
    .thumb{
    width: 20%;
    }
}
</style>