<script setup lang="ts">
import PersonalInformation from "../components/PersonalInformation.vue";
import {
  House,
  Notification,
  Operation,
} from '@element-plus/icons-vue'
</script>

<template>
  <el-container>
    <el-aside class="sidebar">
      <el-row>
        <!-- 个人信息显示 -->
        <el-col>
          <el-aside class="personal-information">
            <PersonalInformation />
          </el-aside>
        </el-col>

        <!-- 菜单栏 -->
        <el-col class="features">
          <el-button type="primary" :icon="House" class="menu-buttom">Home</el-button>
          <el-button type="primary" :icon="Operation" class="menu-buttom">Setting</el-button>
          <el-button type="primary" :icon="Notification" class="menu-buttom">About</el-button>
        </el-col>
      </el-row>
    </el-aside>
  </el-container>
</template>

<style>
body {
  background-color: #141414;
  margin: 0;
}

.el-header {
  padding-left: 0;
  padding-right: 0;
  width: auto;
  height: auto;
}

.el-container {
  margin: 0;
}

.el-button {
  margin: 0;
}

.features {
  display: flex;
  flex-direction: column;
  margin-top: 8px;
  padding-left: 3px;
  width: auto;
  gap: 4px;

}

.sidebar {
  width: 170px;
  height: 1000px;
  background-color: #404040;
}

.nav-tabs > .el-tabs__content {
  text-align: center;
  color: white;
}

.personal-information {
  width: 170px;
  height: auto;
  border-bottom: 1px white solid;
  border-right: 1px white solid;
  border-radius: 4px;

  background-color: #2b2b2b;
}
</style>