<template>
    <div>
        <h1>Uh-Oh!</h1>
        <p>It looks like you're experiencing some network issues, please click the back button and try again</p>
        <router-link :to="{ name: 'event-list' }">Or go back to the home page</router-link>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>