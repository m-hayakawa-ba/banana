<template>
    <div>
        <h1>About Page</h1>
        <NavBar />
        <Original />
    </div>
</template>


<script>
import NavBar from '@/components/NavBar.vue';
import Original from '@/components/Original.vue';

export default {
    GetComponents: {
        NavBar,
        Original,
    }
}
</script>

