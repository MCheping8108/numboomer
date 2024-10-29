<template>
  <div class="mb-4">
    <el-button>Default</el-button>
    <el-button type="primary">数字炸弹</el-button>
    <el-button type="success">数字炸弹</el-button>
    <el-button type="info">数字炸弹</el-button>
    <el-button type="warning">数字炸弹</el-button>
    <el-button type="danger">数字炸弹</el-button>
  </div>

  <div class="mb-4">
    <el-button plain>Plain</el-button>
    <el-button type="primary" plain>数字炸弹</el-button>
    <el-button type="success" plain>数字炸弹</el-button>
    <el-button type="info" plain>数字炸弹</el-button>
    <el-button type="warning" plain>数字炸弹</el-button>
    <el-button type="danger" plain>数字炸弹</el-button>
  </div>

  <div class="mb-4">
    <el-button round>Round</el-button>
    <el-button type="primary" round>数字炸弹</el-button>
    <el-button type="success" round>数字炸弹</el-button>
    <el-button type="info" round>数字炸弹</el-button>
    <el-button type="warning" round>数字炸弹</el-button>
    <el-button type="danger" round>数字炸弹</el-button>
  </div>

  <div>
    <el-button :icon="Search" circle />
    <el-button type="primary" :icon="Edit" circle />
    <el-button type="success" :icon="Check" circle />
    <el-button type="info" :icon="Message" circle />
    <el-button type="warning" :icon="Star" circle />
    <el-button type="danger" :icon="Delete" circle />
  </div>
</template>

<script lang="ts" setup>
import {
  Check,
  Delete,
  Edit,
  Message,
  Search,
  Star,
} from '@element-plus/icons-vue'
</script>
