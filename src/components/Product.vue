<template>
<div class="item">
    <img :src="thumbProduct" :alt="seriesProduct">
    <h2>{{seriesProduct}}</h2>
</div>
</template>

<script>
export default {
    name: "Product",
    props: ["thumbProduct", "priceProduct", "seriesProduct", "typeProduct"]

}
</script>

<style lang="scss" scoped>

</style>