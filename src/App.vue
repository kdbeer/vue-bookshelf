<template>
  <div>
    <Header />
    <div class="wrapper">
      <!-- Sidebar -->
      <nav id="sidebar">
        <Sidebar />
      </nav>

      <!-- Page Content -->
      <div id="content">
        <!-- We'll fill this with dummy content -->
      </div>
    </div>
  </div>
</template>
<script>
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";

import Header from "./components/header.components";
import Sidebar from "./components/sidebar.component";

export default {
  name: "app",
  components: {
    Header,
    Sidebar
  }
};
</script>

<style lang="scss">
@import url("./styles/style.scss");
</style>
