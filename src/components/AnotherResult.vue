<template>
    <div>
        <p>Another Counter is : {{ doubleCounter }}</p>
        <p>Number of Clicks : {{ stringCounter }}</p>
    </div>
</template>

<script>
    import { mapGetters } from 'vuex';
    import * as types from '../store/types';

    export default {
        name: "AnotherResult",
        computed: {
            ...mapGetters({
                doubleCounter : types.DOUBLE_COUNTER,
                stringCounter : types.CLICK_COUNTER,
            }),

        },
    }
</script>

<style scoped>

</style>
