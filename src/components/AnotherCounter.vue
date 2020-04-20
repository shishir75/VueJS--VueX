<template>
    <div class="mt-2">
        <button class="btn btn-primary" @click="increment">Increment</button>
        <button class="btn btn-danger ml-3" @click="decrement">Decrement</button>
    </div>
</template>

<script>
    import { mapMutations } from 'vuex';

    export default {
        name: "AnotherCounter",
        methods: {
            ...mapMutations([
                'increment',
                'decrement'
            ]),
        }
    }
</script>

<style scoped>

</style>
