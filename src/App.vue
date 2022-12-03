<script setup>
import { ref } from 'vue'

const inputText = ref(null)

</script>

<template>
<div>
    <h2>
      Enter name:
    </h2>
    <input type="text" v-model="inputText" maxlength="10"/>
    <p>
      Entered name: {{ inputText }}
    </p>
</div>
</template>

<style scoped>
</style>