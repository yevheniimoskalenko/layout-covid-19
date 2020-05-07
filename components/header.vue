<template>
  <div class="header">
    <div class="nav">
      <logo />
      <el-menu
        class="menu"
        :default-active="$route.path"
        mode="horizontal"
        @select="handleSelect"
      >
        <el-menu-item index="1">Overview</el-menu-item>
        <el-menu-item index="2">Contagion</el-menu-item>
        <el-menu-item index="3">Symptoms</el-menu-item>
        <el-menu-item index="4">Prevention</el-menu-item>
        <el-menu-item index="5">
          <el-button round>Contact</el-button>
        </el-menu-item>
      </el-menu>
    </div>
    <div class="container">
      <el-row type="flex" justify="space-between">
        <el-col :span="10">
          <div class="info">
            <h2>COVID-19 Alert</h2>
            <h1>Stay at Home quarantine To stop Corona virus</h1>
            <p>
              There is no specific medicine to prevent or treat coronavirus
              disease (COVID-19). People may need supportive care to .
            </p>
          </div>
        </el-col>
        <el-col :span="14">
          <img src="@/static/Illustration 01.svg" alt class="image" />
        </el-col>
      </el-row>
    </div>
  </div>
</template>
<script>
import logo from '@/components/Logo'
export default {
  components: { logo },
  methods: {
    handleSelect(key, keyPath) {}
  }
}
</script>
<style lang="scss" scoped>
.container {
  margin-top: 50px;
}
.el-menu {
  background: none;
}
.info {
  display: flex;
  flex-direction: column;
  justify-content: center;

  height: 600px;
  h2 {
    color: #fa5652;
    font-size: 32px;
  }
  h1 {
    font-size: 52px;
    font-weight: bold;
    line-height: 60px;
  }
}
.el-menu--horizontal > .el-menu-item:not(.is-disabled):hover,
.el-menu--horizontal > .el-menu-item {
  background: none;
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
}
.el-menu-item.is-active {
  color: #ff383d;
  border: none;
  background: none;
}
.el-menu--horizontal > .el-menu-item.is-active {
  background: none;
  color: #ff383d;
}
.el-button {
  background: none;
  color: #ff383d;
  border: 2px solid #ff383d;
}
.image {
  position: relative;
  right: 0;
  overflow: hidden;
  display: block;
}
.header {
  display: block;
}
</style>
