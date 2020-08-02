<template>
   <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">KeeOwn</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Link</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  nav {
    margin-bottom: 1em;
  }
</style>
