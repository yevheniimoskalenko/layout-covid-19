<template>
  <div class="footer">
    <el-row type="flex" align="middle">
      <el-col>
        <logo />
      </el-col>
      <el-col>
        <el-menu class="menu" :default-active="$route.path" mode="horizontal">
          <el-menu-item index="1">Overview</el-menu-item>
          <el-menu-item index="2">Contagion</el-menu-item>
          <el-menu-item index="3">Symptoms</el-menu-item>
          <el-menu-item index="4">Prevention</el-menu-item>
        </el-menu>
      </el-col>
      <el-col></el-col>
    </el-row>
    <div class="company">
      <span>2020 @ All rights reserved by pixelspark.co</span>
    </div>
  </div>
</template>
<script>
import logo from "@/components/Logo";
export default {
  components: { logo }
};
</script>
<style lang="scss" scoped>
.company {
  display: flex;
  justify-content: center;
  margin: 70px 0px 20px;

  font-size: 23px;
  line-height: 28px;
  color: #415e56;
}
.el-menu {
  background: none;
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
@media (max-width: 576px) {
  .company {
    span {
      font-size: 16px;
      line-height: 30px;
    }
  }
}
@media (min-width: 576px) {
  .company {
    span {
      font-size: 16px;
      line-height: 30px;
    }
  }
}

@media (min-width: 768px) {
}

@media (min-width: 992px) {
}

@media (min-width: 1200px) {
}
</style>
