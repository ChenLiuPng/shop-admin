<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
  <div>
    <!-- <el-row class="mb-4">
      <el-button>Default</el-button>
      <el-button type="primary">Primary</el-button>
      <el-button type="success">Success</el-button>
      <el-button type="info">Info</el-button>
      <el-button type="warning">Warning</el-button>
      <el-button type="danger">Danger</el-button>
    </el-row> -->
    <button class="btn">按钮</button>
  </div>
</template>

<style scoped>
  .btn {
    @apply bg-purple-500 text-indigo-50 px-4 py-1 rounded-full transition-all duration-500 hover:(bg-purple-900) focus:(ring-2 ring-purple-900);
  }
</style>
