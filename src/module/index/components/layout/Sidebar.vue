<template>
  <el-scrollbar class="app-sidebar-scroll">
    <el-menu
      active-text-color="#ffd04b"
      background-color="#545c64"
      class="menu-wrapper"
      text-color="#fff"
    >
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-menu-item>
        <i class="el-icon-setting"></i>
        <span>设置</span>
      </el-menu-item>
      <el-submenu>
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>导航</span>
        </template>
        <el-menu-item-group>
          <!-- <span>分组一</span> -->
          <el-menu-item>选项一</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
    </el-menu>
  </el-scrollbar>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.menu-wrapper {
  min-height: 100%;
}
</style>

<style lang="scss">
.app-sidebar-scroll {
  height: 100%;
  .el-scrollbar__wrap {
    overflow-x: hidden !important;
  }
}
</style>
