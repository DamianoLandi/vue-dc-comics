<template>
    <div class="main-container">
        <Movies/>
    </div>
</template>

<script>
import Movies from "./Movies.vue"

export default {
    name: "MainContent",
    components: {
        Movies,
    }
}
</script>

<style scoped lang="scss">
    .main-container{
        background-color: #1C1C1C;
        min-height: 150px;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
</style>