<template>
  <div class="container">
    <div class="nav__bar">
      <div class="logo__area">
        <img src="~assets/images/logo.svg" alt="">
      </div>
      <div class="main">
      <NuxtLink to="/">Pricing</NuxtLink>
      <NuxtLink to="/docs">Docs</NuxtLink>
      <NuxtLink to="/use">Use Cases</NuxtLink>
      <NuxtLink to="/sdk">SDKs</NuxtLink>
      <NuxtLink to="/e">Enterprise</NuxtLink>
      <NuxtLink to="/f">Try Demo</NuxtLink> 
      </div>
      <div class="action">
        <p>Sign In</p>
        <div class="start">Get started</div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "NavBar",
    layout: "MainLayout"
  }
</script>

<style scoped>
.container{
  box-shadow: 0px 10px 20px rgba(0, 104, 255, 0.09);
  /* position: fixed;
  width: 100%; */
  z-index: 1;
}
.nav__bar{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.5rem;
  margin: 0 auto;
  max-width: 1400px;
  height: 100%;
}
a{
  text-decoration: none;
  color: #808080;
  opacity: .7;
  line-height: 1rem;
}
.nuxt-link-exact-active{
  opacity: .2;
}

.action{
   /* border: 1px solid black; */
   display: flex;
   align-items: center;
   justify-content: space-between;
   cursor: pointer;
   min-width: 200px;
}
.action p:first-child{
  color: #476BD2;
  font-size: 14px;
}
.main{
  display: flex;
  flex-basis: 35%;
  justify-content: space-between;
  cursor: pointer;
  align-items: center;
  min-width: 450px;
}
.start{
  background-color: #476BD2;
  color: white;
  border-radius: 2rem;
  padding: 1rem;
}
@media only screen and (max-width: 1920px){
  .nav__bar{
    width: 75%;
  }
  .nav__bar .main{
    flex-basis: 20%;
  }
}
@media only screen and (max-width: 1450px){
  .nav__bar{
    width: 85%;
  }
  .nav__bar .main{
    flex-basis: 50%;
  }
}
@media only screen and (max-width: 1050px){
  .nav__bar{
    width: 90%;
  }
  .nav__bar .main{
    flex-basis: 50%;
  }
}
@media only screen and (max-width: 800px){
  .nav__bar{
    width: 90%;
  }
  .nav__bar .main{
    flex-basis: 35%;
  }
}
@media only screen and (max-width: 500px){
  .nav__bar{
    width: 95%;
  }
  .nav__bar .main{
    flex-basis: 35%;
  }
}
</style>