<script setup lang="ts">
import PersonalInformation from "../components/PersonalInformation.vue";
</script>

<template>
  <el-container>
    <el-aside>
      <div class="header-context">
        <!-- 个人信息显示 -->
        <el-aside class="personal-information">
          <PersonalInformation />
        </el-aside>

        <!-- 分隔符 也不知道有啥用 暂时先放这 -->
        <el-divider class="divider" direction="vertical" content-position="center" />
      </div>
    </el-aside>
  </el-container>
</template>

<style>

.el-header {
  padding-left: 0;
  padding-right: 0;
  width: auto;
  height: auto;
}

.el-container {
  margin: 0;
}

body {
  background-color: #141414;
}

body {
  margin: 0;
}

.nav-tabs > .el-tabs__content {
  text-align: center;
  color: white;
}

.header-context {
  display: flex;
  width: 180px;
  border-bottom: 1px white solid;
  border-right: 1px white solid;
}

.divider {
  margin-top: 25px;
}

.personal-information {
  width: auto;
  height: auto;
}
</style>