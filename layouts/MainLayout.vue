<template>
  <div>
    <div class="nav__bar">
      <Navbar/>
    </div>
    <div class="nuxt">
      <Nuxt/>
    </div>
  </div>
</template>

<script>
  export default {
    name:"MainLayout",
    layout:"NavBar"
  }
</script>

<style scoped>
.nav__bar{
  z-index: 2;
}
.nuxt{
  z-index: 1;
}
</style>