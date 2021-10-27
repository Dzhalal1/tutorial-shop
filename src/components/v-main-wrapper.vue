<template>
    <div class="v-main-wrapper">{{title}}
        <v-catalog></v-catalog>
<!--        <v-cart></v-cart>-->
    </div>

</template>

<script>
    import vCatalog from './v-catalog'
    // import vCart from ' ./v-cart'

    export default {
        name: 'v-main-wrapper',
        components: {
            vCatalog,
            // vCart,
        },
        prop: {},
        data() {
            return {
                title: 'Hello'
            }
        },
    }
</script>

<style scoped>
    .v-main-wrapper {
        @apply flex flex flex-col justify-center items-center max-w-4xl m-auto;
    }
</style>
