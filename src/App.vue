<script setup>
import { RouterView } from 'vue-router';
import MainNav from './components/Nav.vue';
</script>

<template>
    <header>
        <h1>Le titre de mon site</h1>
    </header>
    <main-nav />
    <RouterView />
    <footer>
        <p>&copy; Le pied de page</p>
    </footer>
</template>
