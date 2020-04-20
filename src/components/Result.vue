<template>
    <p>Counter is : {{ counter }}</p>
</template>

<script>
    export default {
        name: "Result",
        computed: {
            counter() {
                return this.$store.state.counter;
            }
        }
    }
</script>

<style scoped>

</style>
