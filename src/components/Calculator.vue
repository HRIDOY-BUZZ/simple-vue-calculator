<template>
    Hello World
</template>

<style scoped>

</style>

<script setup>
import { ref } from 'vue'

defineProps({
    msg: String,
})

const count = ref(0)
</script>