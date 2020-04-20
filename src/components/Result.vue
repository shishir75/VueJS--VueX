<template>
    <div>
        <p>Counter is : {{ counter }}</p>
    </div>

</template>

<script>
    export default {
        name: "Result",
        computed: {
            counter() {
                return this.$store.getters.doubleCounter;
            }
        }
    }
</script>

<style scoped>

</style>
