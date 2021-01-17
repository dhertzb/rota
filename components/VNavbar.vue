<template>
  <b-navbar toggleable="lg" class="my-3 mt-4">
    <b-container fluid="xl">
      <b-navbar-brand href="/">
        <img src="~/assets/brand/rota.svg" class="navbar__logo" alt="LogoRota">
      </b-navbar-brand>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav align="right" class="ml-auto">
          <b-nav-item class="navbar__item" href="/carreiras">Carreiras</b-nav-item>
          <b-nav-item class="navbar__item" href="/sobre">Sobre</b-nav-item>
          <b-nav-item class="navbar__item" href="/login">Login</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-container>
  </b-navbar>
</template>
<script>
export default {
  
}
</script>
<style scoped>
.navbar__logo{
  width: 150px;
}
.navbar__item{
  color: black;
  font-weight: bold;
}
</style>