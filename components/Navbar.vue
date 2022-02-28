<template>
  <div class="container">
    <ul class="nav__bar">
      <div class="logo__area">
        <img src="~assets/images/logo.svg" alt="">
      </div>
      <div class="main">
      <li>Pricing</li>
      <li>Docs</li>
      <li>Use Cases</li>
      <li>SDKs</li>
      <li>Enterprise</li>
      <li>Try Demo</li> 
      </div>
      <div class="action">
        <li>Sign In</li>
        <div class="start">Get started</div>
      </div>
    </ul>
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
  /* width: 100%; */
  padding: 1.5rem;
  z-index: 2;
}

ul {
  list-style-type: none;
  display: flex;
  justify-content: space-evenly;
}

  .logo__area{
    /* border: 1px solid black; */
    flex: .2;
  }

.action{
   /* border: 1px solid black; */
   display: flex;
   align-items: center;
   flex: .2;
   justify-content: space-evenly;
   cursor: pointer;
}

.main{
  display: flex;
  flex: .6;
  justify-content: space-around;
  cursor: pointer;
}
li{
  font-size: 14px;
  color: #000000;
}
.start{
  background-color: #476BD2;
  color: white;
  border-radius: 2rem;
  padding: 1rem;
}
.action li{
  color: #476BD2;
}
</style>