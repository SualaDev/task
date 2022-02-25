<template>
  <div class="question__container">
    <div class="section1">
    <p>Commonly asked questions</p>
    <p>Ship in-app chat messaging with all the features your users expect.</p>
    </div>
    <div class="questions">
      <div class="in">
        <p>How is MAU calculated?</p>
        <img src="~assets/images/black-arrow.svg" alt="">
      </div>
      <div class="in">
        <p>What is the difference between Starter, Pro, and Enterprise plans?</p>
        <img src="~assets/images/black-arrow.svg" alt="">        
      </div>
      <div class="in">
        <p>How do I purchase higher levels of support?</p>
        <img src="~assets/images/black-arrow.svg" alt="">
      </div>
      <div class="in">
        <p>What other limits do I need to be aware of?</p>
        <img src="~assets/images/black-arrow.svg" alt="">
      </div>
      <div class="in">
        <p>Is every feature automatically included in the enterprise plan?</p>
        <img src="~assets/images/black-arrow.svg" alt="">
      </div>
      <div class="in">
        <p>Do the prices listed on the pricing page include tax?</p>
        <img src="~assets/images/black-arrow.svg" alt="">
      </div>
    </div>
      <div class="section2">
      <p>Got additional questions? </p>
      <p>We would love to have a chat with you.</p>
      <div class="contact">
        <div>Contact Support</div>
        <img src="~assets/images/blue-arrow.svg" alt="">
      </div>      
      </div>
  </div>
</template>

<script>
  export default {
    name: "FaQ"
  }
</script>

<style scoped>
.question__container{
  background-color: #F5F7FC;
  width: 70%;
  margin: 0 auto;
  padding: 4rem;
  border-radius: 15px;
  
}
.section1{
display: flex;
  flex-direction: column;
  align-items: center;
}
.section1 p:first-child{
  font-size: 2.1rem;
  font-weight: 700;
  margin-bottom: 1.4rem;
}
.section1 p:nth-child(2){
  max-width: 20.6rem;
  font-size: 1.1rem;
  font-weight: 400;
  text-align: center;
  margin-bottom: 2.2rem;
}
.questions{
  display: flex;
  flex-direction: column;

}
.section2{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.in{
  display: flex;
  justify-content: space-between;
  padding: 1.7rem 2.4rem 2.2rem 3.1rem;
  background-color: #fff;
  margin-bottom: 1.3rem;
}
.in p{
  font-size: 20px;
  font-weight: 700;
}
.in img{
  cursor: pointer;
}
.section2 p:first-child{
  font-size: 17px;
  font-weight: 700;
  margin-bottom: 0.5rem;
}
.section2 p:nth-child(2){
  font-size: 16px;
  font-weight: 400;
  margin-bottom: 1.3rem;
}
.contact{
  display: flex;
  justify-content: space-between;
  padding: 0.9rem 1.6rem;
  background-color: #fff;
  color: #4568D1;
  border-radius: 1.9rem;
  cursor: pointer;
}
.contact img{
  margin-left: 1.4rem;
}
</style>