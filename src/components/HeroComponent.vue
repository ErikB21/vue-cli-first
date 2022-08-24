<template>
  <div>
    <div class="jumbotron">
        <div class="logo">
            <img alt="Vue logo" src="@/assets/logo.png"/>
            <MyTitle/>
        </div>
    </div>
  </div>
</template>

<script>
import MyTitle from "./MyTitle.vue";
export default {
    name: "HeroComponent",
    components: { MyTitle }
}
</script>

<style scoped>
    .jumbotron{
        width: 100%;
        height: 100vh;
        background-image: url('@/assets/space.jpg');
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background-size: cover;
    }
</style>