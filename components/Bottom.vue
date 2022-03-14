<template>
  <div class="container">
    <div class="parent">
      <div class="chat">
        <p class="ready">Ready to have a chat?</p>
        <p class="we">We’d love to talk about your messaging strategy and help make your software more conversational.</p>
      </div>
      <div class="button">
        <div class="sales">
          <button class="btn">
          <div>Talk To Sales</div>
          <img src="~assets/images/white-arrow.svg" alt="">
          </button >
        </div>
        <div class="robin">
          <button class="btn-2">
          <div>Try Robin</div>
          <img src="~assets/images/white-arrow.svg" alt="">
          </button>
        </div>
      </div>
    </div>
    <div class="robin-container">
      <div class="image">
        <img src="~assets/images/robin-2.svg" alt="">
      </div>
      <div class="second-segment">
          <div class="resources">
            <p>RESOURCES</p>
            <p>Documentation</p>
            <p>Developer API</p>
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
    name:"BottomPart"
  }
</script>

<style scoped>
.parent{
  display: flex;
  justify-content: space-between;
  padding:5.25rem 0 6.2rem 0;
  margin: 0 10.2rem 0 9rem;
  border-bottom: 1px solid #808080;
}
.container{
  width: 100%;
  background-color: #0C1F55;
}
.button{
  /* border: 1px solid black; */
  display: flex;
  justify-content: flex-end;
  align-items: center;
  flex: .5;
}
.chat{
  flex: .5;
}
.chat p:first-child{
  color: #fff;
  font-weight: 700;
  font-size: 2.7rem;
  margin-bottom: 1.9rem;
}
.chat p:nth-child(2){
  max-width: 32.8rem;
  font-weight: 400;
  color: #808080;
  font-size: 1.25rem;
}
.we{
  opacity: .8;
}
.btn{
  width: 207px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #4568D1;
  color: #fff;
  padding: 1rem 1.5rem 1rem 1.3rem;
  border-radius: 1.9rem;
  height: 50px;
  border: none;
  cursor: pointer;
}
/* .robin{
  width: 207px;
  display: flex;
  justify-content: space-between;
  background-color: #0C1F55;
  color: #fff;
  padding: 1rem 1.5rem 1rem 1.3rem;
  border-radius: 1.9rem;
} */
.btn-2{
  width: 207px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #0C1F55;
  color: #fff;
  padding: 1rem 1.5rem 1rem 1.3rem;
  border-radius: 1.9rem;
  border: none;
  margin-left: 1rem;
  border: 1px solid #4568D1;
  cursor: pointer;
}
/* .btn{
  align-self: center;
  justify-self: center;
} */
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
.resources,.company{
  width: 7rem;
}
.resources p,.company p{
  color: #FFFFFF;
  font-size: 12px;
  margin-bottom: 1.3rem;
  font-weight: 600;
}
.resources p:last-child,.company p:last-child{
  margin-bottom: none;
}
.resources p:first-child,.company p:first-child{
  color: #808080;
  margin-bottom: 2rem;
  font-size: 0.8rem;
  font-weight: 700;
}
.company{
  margin-left: 5rem;
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