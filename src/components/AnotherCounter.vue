<template>
    <div class="mt-2">
        <button class="btn btn-primary" @click="asyncIncrement({ by: 50, duration: 500})">Increment</button>
        <button class="btn btn-danger ml-3" @click="asyncDecrement({ by: 50, duration: 500})">Decrement</button>
    </div>
</template>

<script>
    import { mapActions } from 'vuex';

    export default {
        name: "AnotherCounter",
        methods: {
            ...mapActions([
                'asyncIncrement',
                'asyncDecrement'
            ]),
        }
    }
</script>

<style scoped>

</style>
