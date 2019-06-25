<template>
  <div class="app-wrapper">
    <div></div>
    <div class="sidebar-wrapper">
      <sidebar></sidebar>
    </div>
    <div class="main-wrapper">
      <navbar></navbar>
      <app-main></app-main>
    </div>
  </div>
</template>

<script>
import AppMain from './AppMain.vue'
import Navbar from './Navbar.vue'
import Sidebar from './Sidebar.vue'

export default {
  name: 'Layout',
  components: {
    AppMain,
    Navbar,
    Sidebar
  }
}
</script>

<style lang="scss" scoped>
.app-wrapper {
  .sidebar-wrapper {
    width: 180px;
    position: fixed;
    top: 0;
    bottom: 0;
    left: 0;
    z-index: 1001;
    overflow: hidden;
    transition: all 0.28s ease-out;
  }
  .main-wrapper {
    min-height: 100%;
    margin-left: 180px;
    transition: all 0.28s ease-out;
  }
}
</style>
