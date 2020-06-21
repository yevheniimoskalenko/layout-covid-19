<template>
  <div class="header">
    <div class="nav">
      <logo />
      <el-menu class="menu" :default-active="$route.path" mode="horizontal">
        <el-menu-item index="1">Overview</el-menu-item>
        <el-menu-item index="2">Contagion</el-menu-item>
        <el-menu-item index="3">Symptoms</el-menu-item>
        <el-menu-item index="4">Prevention</el-menu-item>
        <el-menu-item index="5">
          <el-button round>Contact</el-button>
        </el-menu-item>
      </el-menu>
    </div>
  </div>
</template>
<script>
import logo from "@/components/Logo";
export default {
  components: {
    logo
  }
};
</script>
<style lang="scss" scoped>
.header {
  display: block;
}
.el-menu {
  background: none;
}
.el-menu--horizontal > .el-menu-item:not(.is-disabled):hover,
.el-menu--horizontal > .el-menu-item {
  background: none;
  border-bottom: none;
}
.el-menu--horizontal {
  border-right: none;
}
.el-menu.el-menu--horizontal {
  border: none;
}
.nav {
  display: flex;
  justify-content: space-between;
  border: none;
}

.el-menu-item.is-active {
  color: #ff383d;
  border: none;
  background: none;
}
.el-menu--horizontal > .el-menu-item.is-active {
  background: none;
  color: #ff383d;
  border: none;
}
.el-button {
  background: none;
  color: #ff383d;
  border: 2px solid #ff383d;
}
</style>
