<script>
    export default{
        name: 'AppHero'
    }
</script>

<template>
    <div class="hero-wrapper">
        <img src="../assets/img/app-hero.webp" alt="Hero image">
    </div>
</template>

<style>
    .hero-wrapper{
        border: 1px solid black;
        height: 620px;
        width: 1400px;
        margin: 0 auto;
    }
    img{
        width: 100%;
        object-fit: cover;
        max-height: 100%;
    }
</style>