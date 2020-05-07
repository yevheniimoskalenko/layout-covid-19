<template>
  <el-container>
    <el-header>
      <el-row type="flex" justify="center">
        <el-col :span="20">
          <app-nav />
        </el-col>
      </el-row>
    </el-header>
    <el-main>
      <el-row type="flex" justify="center">
        <el-col :span="20">
          <nuxt />
        </el-col>
      </el-row>
    </el-main>
    <el-row type="flex" justify="center">
      <el-col :span="20">
        <el-footer>Footer</el-footer>
      </el-col>
    </el-row>
  </el-container>
</template>
<script>
import appNav from "@/components/nav";
export default {
  components: { appNav }
};
</script>
<style></style>
