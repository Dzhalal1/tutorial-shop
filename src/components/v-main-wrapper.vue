<template>
    <div class="v-main-wrapper"></div>
</template>

<script>
    export default {
        name: 'v-main-wrapper',
        components: {
        },
        prop:{},
        data() {
            return{
                title: 'Hello'
            }
        },
    }
</script>

<style scoped>
    .v-main-wrapper {
        @apply flex justify-center items-center max-w-4xl m-auto;
    }
</style>
