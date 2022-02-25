<template>
  <div class="container">
    <div class="parent">
      <div class="chat">
        <p>Ready to have a chat?</p>
        <p>We’d love to talk about your messaging strategy and help make your software more conversational.</p>
      </div>
      <div class="button">
        <div class="sales">
          <div class="btn">
          <div>Talk To Sales</div>
          <img src="~assets/images/white-arrow.svg" alt="">
          </div>
        </div>
        <div class="robin">
          <div class="btn">
          <div>Try Robin</div>
          <img src="~assets/images/white-arrow.svg" alt="">
          </div>
        </div>
      </div>
    </div>
    <div>
          <div>
              <img src="~assets/images/robin-2.svg" alt="">
            </div>
            <div>
              <p>RESOURCES</p>
              <p>Documentation</p>
              <p>Developer API</p>
              <p>Product Demos</p>
              <p>Help Center</p>
              <p>System Status</p>
            </div>
            <div>
              <p>Company</p>
              <p>About</p>
              <p>Security & Privacy</p>
              <p>Blog</p>
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
  padding:5.25rem 10.2rem 6.2rem 9rem;
  border-bottom: 1px solid #808080;
}
.container{
  width: 100%;
  background-color: #0C1F55;
}
.button{
  border: 1px solid black;
  display: flex;
  justify-content: space-between;
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
  color: #fff;
  font-size: 1.25rem;
}
.sales{
  position: relative;
  width: 207px;
  display: flex;
  justify-content: space-between;
  background-color: #4568D1;
  color: #fff;
  padding: 1rem 1.5rem 1rem 1.3rem;
  border-radius: 1.9rem;
  height: 50px;
}
.robin{
  position: relative;
  width: 207px;
  display: flex;
  justify-content: space-between;
  background-color: #0C1F55;
  color: #fff;
  padding: 1rem 1.5rem 1rem 1.3rem;
  border-radius: 1.9rem;
}
.btn{
  align-self: center;
  justify-self: center;
}
</style>