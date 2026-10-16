<script setup>
import { useRouter } from 'vue-router';

const router = useRouter()

const navigateTo = (routeName) => {
    router.push({name: routeName})
}

</script>

<template>
    <header>
        <div class="NavLogo">Kape ni Emman</div>
        <nav class="nav-links">
            <button @click="navigateTo('home')" class="nav-btn">Home</button>
            <button @click="navigateTo('about')" class="nav-btn">About</button>
            <button @click="navigateTo('partnership')" class="nav-btn">Partnership</button>
            <button @click="navigateTo('gallery')" class="nav-btn">Gallery</button>
            <button @click="navigateTo('menu')" class="nav-btn">Menu</button>
        </nav>
    </header>
</template>