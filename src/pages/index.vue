<template>
    <div class="home">
      后台首页 <el-button class="" @click="addCount">{{count}}</el-button><el-button class="" @click="addCount2">{{form.count}}</el-button>
    </div>
</template>

<script setup>
import { reactive, ref } from 'vue';

  let count = ref(1);
  const form = reactive({
    count:0
  })
  const addCount = () => {
    count.value += 1;
  }
  const addCount2 = () => {
    form.count++;
  }
</script>


<style scoped>

</style>