<script setup lang="ts">
import { UserFilled } from '@element-plus/icons-vue'
</script>

<template>
  <div class="user">
    <el-avatar :icon="UserFilled" shape="square" class="avatar"/>
    <div class="username">F1uffySn0w</div>
  </div>
</template>

<style scoped>
.user {
  display: flex;
  width: 150px;
  margin-top: 12px;
  margin-left: 7px;
  margin-bottom: 12px;
}

.username {
  margin-left: 10px;
  margin-top: 6px;
  font-size: 18px;
  color: white;
}
</style>