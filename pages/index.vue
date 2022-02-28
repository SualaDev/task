<template>
<div>
  <div class="nav__bar">
  <Navbar/>
  </div>
  <div class="headers">
  <p class="title">Simple & Transparent Pricing. No surprises.</p>
  <p class="sub__title">The only tool you will need to power conversations. </p>
  <div class="trial">
    <div class="action">Start Free Trial</div>
    <img src="~assets/images/arrow.svg" alt="">
  </div>
  </div>
  <PayCards/>
  <div class="trusted">
    <p>TRUSTED BY EXPERTS AT</p>
    <img src="~assets/images/trusted.svg" alt="">
  </div>
  <FAQ/>
<div class="chat">
<div class="left">
  <p>CHAT</p>
  <p>See the all-in-one chat system in action</p>
  <p>The only tool you will need to power conversations and interactions on your product.<span class="g">Go live within days.</span></p>
  <div class="demo">
  <div>Start Demo</div>
  <img src="~assets/images/arrow-2.svg" alt="">
  </div>
</div>
<div class="right">
  <img src="~assets/images/robin.svg" alt="">
</div>
</div>
<Bottom/>
</div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style scoped>
.title{
  /* border: 1px solid black; */
  text-align: center;
  font-weight: 700;
  font-size: 40px;
  max-width: 40%;
  margin: 5rem auto 0 auto;
}

.sub__title{
  /* text-align: center; */
  margin: 2rem auto;
}
.headers{
  display: flex;
  flex-direction: column;
  align-items: center;
}

.chat{
  display: flex;
  /* padding: 9rem; */
  width: 100%;
  margin-top: 5rem;
}

.left{
  flex: .9;
  /* border: 1px solid black; */
  margin-left: 8.5rem;
  margin-top: 3rem;
}

.right{
  flex: .1;
}
.trial{
  display: flex;
  justify-content: space-between;
  background-color: #4568D1;
  color: #fff;
  border-radius: 1.75rem;
  width: 9rem;
  padding: 1rem 1.5rem;
  cursor: pointer;
}
.left p:first-child{
  color: #808080;
  margin-bottom: 1.5rem;
}
.left p:nth-child(2){
  font-size: 35px;
  font-weight: 700;
  max-width: 20rem;
  margin-bottom: 2.5rem;
}
.left p:nth-child(3){
  max-width: 20rem;
  font-weight: 400;
  font-size: 1.3rem;
  color: rgba(0, 0, 0, 0.685);
  margin-bottom: 4rem;
}
.g{
  font-weight: 800;
}
.demo{
  border: 1px solid #000000;
  display: flex;
  justify-content: space-between;
  color: #333333;
  background-color: #fff;
  width: 8rem;
  border-radius: 1.75rem;
  padding: 1rem 1.3rem 1rem 2.3rem ;
  font-size: 1rem;
  font-weight: 700;
  cursor: pointer;
}
.trusted p{
  text-align: center;
  color: #808080;
  
}
.trusted img{
 margin: 0 13.8rem 4.9rem 13rem;
 width: 65%;
}
</style>