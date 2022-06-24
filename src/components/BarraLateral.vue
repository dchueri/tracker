<template>
    <header>
        <h1>
            Tracker
        </h1>
    </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: 'BarraLateral'
})
</script>

<style scoped>
    header {
        background: #0d3b66;
        width: 100%;
        height: 100vh;
        padding: 1rem;
    }
    h1 {
        color: white;
        font-weight: 500;
        font-size: 3rem;
        text-align: center;
    }
    @media only screen and (max-width: 768px) {
        header{
            padding: 2.5rem;
            height:auto;
        }
    }
</style>