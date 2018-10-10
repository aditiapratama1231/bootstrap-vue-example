<template>
<b-navbar toggleable="md" type="light" class="navbar-color">

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand href="#">Logo</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav class="ml-auto">
      <b-nav-item href="#">Attack</b-nav-item>
      <b-nav-item href="#">Defense</b-nav-item>
      <b-nav-item>Magic</b-nav-item>
    </b-navbar-nav>

  </b-collapse>
</b-navbar>

<!-- navbar-1.vue -->
</template>

<script>
export default {
    name: 'Navbar'
}
</script>


<style scoped>
    .navbar-color {
        background-color: white;
    }
</style>
