<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <header>
    <div class="header-name">
      <img src="/i_wash_here_logo.png" alt="The I Wash Here Logo" width="150" height="150">
      <h1 class="title is-1">I Wash Here</h1>
    </div>
  </header>
</template>

<style scoped>
  .header-name {
    display: flex;
    align-items: center;
    gap: 12px;
  }
</style>
