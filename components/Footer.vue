<template>
  <div class="container">
    <div class="robin-container">
      <div class="image">
        <img src="~assets/images/robin-2.svg" alt="">
      </div>
      <div class="second-segment">
        <div class="developers">
          <p>DEVELOPERS</p>
          <p>Chat SDKs</p>
          <p>Developer API</p>
          <p>Documentation</p>
        </div>
          <div class="resources">
            <p>RESOURCES</p>
            <p>Product Demos</p>
            <p>Help Center</p>
            <p>System Status</p>
          </div>
          <div class="company">
            <p>COMPANY</p>
            <p>About</p>
            <p>Security & Privacy</p>
            <p>Blog</p>
          </div>
      </div>
    </div>
    <div class="fourth-section">
      <div class="copyright">
        <p>© 2021 Robin Inc.</p>
      </div>
      <div class="random">
        <p>Terms of Service</p>
        <p>Privacy Policy</p>
        <p>Cookie Settings</p>
        <p>Sub-Processors</p>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "FooterPage"
  }
</script>

<style scoped>
.container{
  width: 100%;
  background-color: #0C1F55;
}
.robin-container{
  padding:2.6rem 0 3.6rem 0;
  margin: 0 10.2rem 0 9rem;
  border-bottom: 1px solid #808080;
  display: flex;
}
.second-segment{
  display: flex;
  flex: .1;
}
.image{
  flex: 1;
}
.resources,.company,.developers{
  width: 7rem;
}
.resources p,.company p,.developers p{
  color: #FFFFFF;
  font-size: 12px;
  margin-bottom: 1.3rem;
  font-weight: 600;
}
.resources p:last-child,.company p:last-child,.developers p:last-child{
  margin-bottom: none;
}
.resources p:first-child,.company p:first-child,.developers p:first-child{
  color: #808080;
  margin-bottom: 2rem;
  font-size: 0.8rem;
  font-weight: 700;
}
.company{
  margin-left: 9.8rem;
}
.developers{
  margin-right: 8.3rem;
}
.fourth-section{
  padding:2rem 0 2.2rem 0;
  margin: 0 10.2rem 0 9rem;
  display: flex;
  flex: .1;
}
.fourth-section p{
  color: #808080;
}
.copyright{
  flex: 1;
}
.random{
  display: flex;
}
.random p{
  margin-left: 2.5rem;
}
.random p:first-child{
  margin-left: none;
}
</style>