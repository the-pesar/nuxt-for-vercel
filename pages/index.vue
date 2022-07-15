<template>

    <h1>home {{ counter }}</h1>

</template>

<script lang="ts" setup>
const counter = useState<number>('counter')
</script>
