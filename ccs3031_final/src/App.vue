<script setup lang="ts">
import AppFooter from './components/AppFooter.vue';
import AppNavBar from './components/AppNavBar.vue';

</script>

<template>
    <div class="app-wrapper">
 <AppNavBar/>
        <main class="main-content">
 <RouterView/>
 </main>

 <AppFooter />
 </div>
</template>