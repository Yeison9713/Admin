<template>
  <div class="content">
    <navbar_static />
    <section class="main">
      <header_stacti />
      <div style="margin: 25px;">
        <body_inicio />
      </div>
    </section>
  </div>
</template>

<script>
import navbar_static from "../components/Navbar.vue";
import header_stacti from "../components/Header.vue";
import body_inicio from "../components/Inicio.vue";
export default {
  name: "app",
  components: {
    navbar_static,
    header_stacti,
    body_inicio
  }
};
</script>