<template>
    <div>
        <p v-if="greeting"></p>
    </div>
</template>

<script>
    export default {
        name: "",
        data() {
            return {
                greeting: 'hello world'
            }
        },
    }
</script>

<style scoped>

</style>
