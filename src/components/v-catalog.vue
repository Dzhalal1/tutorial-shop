<template>
    <div>
        <span>Catalog</span>
        <v-catalog-item></v-catalog-item>
    </div>
</template>

<script>
    import vCatalogItem from './v-catalog-item'

    export default {
        name: "v-catalog",
        components: {
            vCatalogItem,
        }
    }
</script>

<style scoped>

</style>