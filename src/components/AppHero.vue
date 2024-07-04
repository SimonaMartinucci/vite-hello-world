<script>
    export default {
        name: "AppHero",
    }
</script>

<template>
    <div class="jumbo">
        <div class="jumbo_title">JUMBO</div>
    </div>
</template>

<style scoped>
   .jumbo {
    width: 100%;
    height: 400px;
    display: block;
    background-image: url(../assets/jumbo.png);
    background-size: cover;
   }

   .jumbo_title {
    text-align: center;
    font-size: 70px;
    padding-top: 120px;
    font-weight: 900;
    color: white;
   }
</style>