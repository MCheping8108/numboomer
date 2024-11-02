<template>
  <el-tabs v-model="activeName" class="demo-tabs">
    <el-tab-pane label="User" name="first">
      <el-input v-model="input" style="width: 240px" placeholder="数字炸弹，你准备好了吗" />
      <el-button type="primary" @click="handleClick">炸弹</el-button><br>
      在tab中的config配置
    </el-tab-pane>
    <el-tab-pane label="Config" name="second">
      <p>目标数字</p><el-input v-model="target" style="width: 240px" placeholder="数字炸弹，你准备好了吗" />
    </el-tab-pane>
    <el-tab-pane label="update log" name="third">
      <h1>更新日志</h1><br>
      <h2>2024-11-2</h2>
      <p>基础布局，写出基本逻辑</p>
      <h2>2024-10-29</h2>
      <p>新建文件夹</p>
    </el-tab-pane>
    <el-tab-pane label="Task" name="fourth">Task</el-tab-pane>
  </el-tabs>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
import {
  Check,
  Delete,
  Edit,
  Message,
  Search,
  Star,
  TabsPaneContext 
} from '@element-plus/icons-vue'

const input = ref('')
const target = ref('')

const handleClick = () => {
  if (input.value === target.value) {
    // console.log('炸弹成功')
    alert('炸弹成功')
  }
}
  
</script>
