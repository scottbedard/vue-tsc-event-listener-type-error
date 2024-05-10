<script setup lang="ts">
function onEnter() {
  console.log('enter')
}

function onKeydown() {
  console.log('keydown')
}
</script>

<template>
  <input
    @keydown="onKeydown"
    @keydown.enter="onEnter" />
</template>
