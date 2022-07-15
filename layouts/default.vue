<template>
    <NuxtLink to="/">home</NuxtLink>
    <NuxtLink to="/test">test</NuxtLink>
    <p @click="counter++">plus</p>
    <slot />
</template>
<script lang="ts" setup>
const counter = useState<number>('counter', () => 0)
</script>

<style scoped>
a,
p {
    margin: 10px;
}
</style>