<template>
    <h1>{{ msg }}</h1>
</template>

<script>
    import adapters from '@/adapters'
    const service = adapters.service

    export default {
        name: 'hello',
        data() {
            return {
                msg: service.getMsg()
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1 {
        font-weight: normal;
    }
</style>
