<template>
  <div style="height: 64px; width: 64px">
    <img :src="spotify" alt="" ondragstart="return false;" @dblclick="handleClick" />
  </div>
</template>

<script setup lang="ts">
  import spotify from '@renderer/assets/images/spotify-64.png';
  const handleClick = () => {
    console.log('dblclick');
  };
</script>

<style scoped></style>
