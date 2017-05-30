<template>
    <header>
        <app-login></app-login>
    </header>
</template>

<script>
    import Login from '@/components/Login'
    export default {
        name: 'header',
        components: {
            'app-login': Login,
        }
    }
</script>
