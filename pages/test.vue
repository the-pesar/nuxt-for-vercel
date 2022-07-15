<template>

    <h1>test {{ counter }}</h1>

</template>

<script lang="ts" setup>
const counter = useState<number>('counter')
</script>
