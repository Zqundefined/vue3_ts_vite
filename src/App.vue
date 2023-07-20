<template>
    <div class="box">
        <h1>我是APP</h1>
    </div>
</template>

<script setup lang="ts">
const str = 'fjdklsajlk'
</script>

<style scoped lang="scss">
.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
}
.logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
}
.box {
    background: #543;
    h1 {
      color: #fff;
    }
}
</style>
