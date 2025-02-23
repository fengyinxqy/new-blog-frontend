<template>
  <button @click="log">{{ msg }}</button>
</template>
<script setup lang="ts">
// 变量
const msg = 'Hello!'

// 函数
function log() {
  console.log(msg)
}
</script>
