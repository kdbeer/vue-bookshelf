<template>
  <div>
    <Header />
    <div class="wrapper">
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

export default {
  name: "app",
  components: {
    Header
  }
};
</script>

<style lang="scss">
@import url("./styles/style.scss");
</style>
