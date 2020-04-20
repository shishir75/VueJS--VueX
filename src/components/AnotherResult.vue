<template>
    <p>Counter is : {{ counter }}</p>
</template>

<script>
    export default {
        name: "AnotherResult",
        computed: {
            counter() {
                return this.$store.state.counter * 2;
            }
        }
    }
</script>

<style scoped>

</style>
