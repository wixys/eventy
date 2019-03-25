<template>
    <div>
        <h1>{{ userName }}</h1>
    </div>
</template>

<script>
import { mapState } from 'vuex'

    export default {
        computed: mapState({
            userId: state => state.user.id,
            userName: state => state.user.name,
            userCategories: state => state.user.categories,
        })
    }
</script>

<style scoped>

</style>
