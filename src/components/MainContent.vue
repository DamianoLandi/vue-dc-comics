<template>
    <div>
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
    div{
        background-color: #1C1C1C;
        height: 150px;
        display: flex;
        justify-content: flex-start;
        align-items: center;
    }
</style>