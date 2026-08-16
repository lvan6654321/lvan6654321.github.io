<template>
  <p class="kinetic-text">
    <span
      v-for="(char, index) in characters"
      :key="index"
      class="char"
    >{{ char }}</span>
  </p>
</template>

<script setup>
import { computed } from 'vue'

const props = defineProps({
  text: {
    type: String,
    required: true
  }
})

// Split text into individual characters including spaces
const characters = computed(() => [...props.text])
</script>
