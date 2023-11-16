<script setup>
import { RouterLink, RouterView } from 'vue-router'
import FooterComponent from './components/FooterComponent.vue';
</script>

<template>
    <body>
        <RouterView />
    </body>

    <footer>
        <FooterComponent />
    </footer>
</template>
