<template>
  <div class="header">
    <div class="nav">
      <el-row>
        <el-col :span="3" :sm="4" :xl="12" :xs="3" :md="4" :lg="6" class="logo">
          <logo />
        </el-col>
        <el-col
          :span="21"
          :sm="20"
          :xl="12"
          :xs="21"
          :md="20"
          :lg="18"
          class="menu_arr"
        >
          <el-dropdown class="show">
            <span class="el-dropdown-link">
              <i class="el-icon-s-grid"></i>
            </span>
            <el-dropdown-menu slot="dropdown">
              <el-dropdown-item index="1">Overview</el-dropdown-item>
              <el-dropdown-item>Contagion</el-dropdown-item>
              <el-dropdown-item>Symptoms</el-dropdown-item>
              <el-dropdown-item>Prevention</el-dropdown-item>
              <el-dropdown-item>Contact</el-dropdown-item>
            </el-dropdown-menu>
          </el-dropdown>
          <el-menu
            :default-active="$route.path"
            class="hidden"
            mode="horizontal"
          >
            <el-menu-item index="1">Overview</el-menu-item>
            <el-menu-item index="2">Contagion</el-menu-item>
            <el-menu-item index="3">Symptoms</el-menu-item>
            <el-menu-item index="4">Prevention</el-menu-item>
            <el-menu-item index="5">
              <el-button round>Contact</el-button>
            </el-menu-item>
          </el-menu>
        </el-col>
      </el-row>
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
.el-row {
  display: flex;
  justify-content: center;
}
.hidden {
  display: none;
}
.show {
  display: flex;
}
.el-dropdown {
  font-size: 24px;
  display: flex;
  justify-content: center;
  align-items: flex-end;
}
.el-icon-s-grid {
  color: #e23238;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu_arr {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.logo {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.header {
  display: block;
  margin-top: 20px;
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
@media (max-width: 576px) {
  .el-menu-item {
    padding: 0 5px;
  }
  .hidden {
    display: none;
  }
  .show {
    display: block;
  }
}
@media (min-width: 576px) {
  .hidden {
    display: none;
  }
  .show {
    display: block;
  }
}

@media (min-width: 768px) {
  .show {
    display: block;
  }
  .hidden {
    display: none;
  }
}

@media (min-width: 992px) {
  .show {
    display: none;
  }
  .hidden {
    display: block;
  }
}

@media (min-width: 1200px) {
  .show {
    display: none;
  }
  .hidden {
    display: block;
  }
}
</style>
