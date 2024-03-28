<template>
  <el-button type="primary" size="default" @click="" :icon="Edit">Edit</el-button>
  <el-pagination
      :page-sizes="[100, 200, 300, 400]"
      layout="total, sizes, prev, pager, next, jumper"
      :total="400"
    />
    <Test></Test>
</template>

<script setup lang="ts">
import {Edit} from '@element-plus/icons-vue'
import Test from '@/components/Test.vue'
</script>

<style scoped></style>
