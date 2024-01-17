<script>
import AppTitle from './components/AppTitle.vue';

export default {
    data() {
        return { 
            count: 0 
        }
    },
    components:{
        AppTitle
    }
}
</script>

<template>
    <div>
        <AppTitle/>
        
        <h1>Prova</h1>

        <p>{{ count }}</p>

        <button @click="count++">
            Incrementa counter
        </button>

    </div>
</template>

<style scoped>
</style>
