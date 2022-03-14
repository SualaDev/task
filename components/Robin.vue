<template>
  <div class="container">
    <div class="robin-container">
      <div class="robin">
        <p class="title">Start using Robin Chat SDKs</p>
        <p class="we">No matter what you're building, we can power it</p>
      </div>
      <div class="btn-container">
        <button class="sales">
          <p>Talk To Sales</p>
          <img src="~assets/images/white-arrow.svg" alt="">
        </button>
        <button class="try">
          <p>Try Robin</p>
          <img src="~assets/images/blue-arrow.svg" alt="">
        </button>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name:"RobinPage"
  }
</script>

<style scoped>
 .container{
   margin: 0 1rem 2.4rem 1rem;
 }
 .title{
   color: #071439;
 }
 .robin-container{
   padding: 4.5rem 31% 5rem 36%;
   border-radius: 1.5rem;
   background-color: #4568d13b;
 }
 .robin p:first-child{
   font-weight: 700;
   font-size: 28px;
   margin-bottom: 1rem;
 }
 .robin p:nth-child(2){
   font-size: 400;
   font-size: 15px;
   opacity: .9;
   margin-bottom: 2.6rem;
 }
 .btn-container{
   width: 25.8rem;
   display: flex;
 }
 .sales{
   margin-right: 1rem;
   width: 9.8rem;
   background-color: #4568D1;
   display: flex;
   justify-content: space-between;
   align-items: center;
   border: none;
   border-radius: 1.9rem;
   padding: 1rem 1.5rem 1rem 1.4rem;
   color: white;
 }
 .try{
   width: 9.8rem;
   background-color: #4568d13b;
   display: flex;
   justify-content: space-between;
   align-items: center;
   border: none;
   border-radius: 1.9rem;
   padding: 1rem 1.5rem 1rem 1.4rem;
   color: #4568D1;
 }
</style>