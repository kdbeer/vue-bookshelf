<template>
  <aside class="sidebar">
    <nav class="nav">
      <ul>
        <li class="sb-list active">
          <a class="sb-link" href="#">Welcome</a>
        </li>
        <li class="sb-list">
          <a class="sb-link" href="#">Who We Are</a>
        </li>
        <li class="sb-list">
          <a class="sb-link" href="#">What We Do</a>
        </li>
        <li class="sb-list">
          <a class="sb-link" href="#">Get In Touch</a>
        </li>
      </ul>
    </nav>
  </aside>
</template>

<script>
export default {
  name: "Sidebar",
  props: {
    msg: String
  }
};
</script>
