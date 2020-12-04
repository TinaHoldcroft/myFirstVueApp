<template>
    <LoginComponent message="Please login to view jobs"></LoginComponent>
</template>

<script>
import LoginComponent from './components/LoginComponent.vue'

export default {
    name: 'HomePage',
    components: {
        LoginComponent
    }
}
</script>