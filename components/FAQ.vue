<template>
  <div class="question__container">
    <div class="section1">
    <p class="common">Commonly asked questions</p>
    <p class="ship">Ship in-app chat messaging with all the features your users expect.</p>
    </div>
    <div class="questions">
      <div v-for="faq in faqs" :key="faq.title" class="in">
        <div class="price">
          <p> {{ faq.content }}</p>
          <img v-if="!faq.visible" src="~assets/images/downward-up.svg" alt="" @click="toogleElementVisibility(faq)">
          <img v-if="faq.visible" src="~assets/images/upside-down arrow.svg" alt="" @click="toogleElementVisibility(faq)">
        </div>
        <p v-if="faq.visible" class="in-content">{{ faq.details }}</p>
      </div>
    </div>
      <div class="section2">
      <p class="got">Got additional questions? </p>
      <p class="we">We would love to have a chat with you.</p>
      <div class="contact">
        <div>Contact Support</div>
        <img src="~assets/images/blue-arrow.svg" alt="">
      </div>      
      </div>
  </div>
</template>

<script>
  export default {
    name: "FaQ",
    data (){
      return{
        visible: false,
        faqs: [
          {title:"1", content:"How is MAU calculated?", visible: false, details: "Life may just be gucci who knows?"},
          {title:"2", content:"What is the difference between Starter, Pro, and Enterprise plans?", visible: false, details: "Life would be good"},
          {title:"3", content:"What happens if I hit my MAU limit?", visible: false, details: "Life is for the living"},
          {title:"4", content:"How do I purchase higher levels of support?", visible: false, details: "Life is calm"},
          {title:"5", content:"What other limits do I need to be aware of?", visible: false, details: "Life is gucci"},
          {title:"6", content:"Do the prices listed on the pricing page include tax?", visible: false, details: "Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts."}
        ]
      }
    },
    methods: {
    toogleElementVisibility(faq) {  
      faq.visible = !faq.visible
    }
    }
  }
</script>

<style scoped>
.question__container{
  background-color: #F5F7FC;
  margin: 0 6.7rem 2.8rem 5.8rem;
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
.ship{
  opacity: .9;
}
.in{
  padding: 1.7rem 2.4rem 2.2rem 3.1rem;
  background-color: #fff;
  margin-bottom: 1.3rem;
}
.price{
  display: flex;
  justify-content: space-between;
}
.in p{
  font-size: 20px;
  font-weight: 700;
}
.in img{
  cursor: pointer;
}
.in-content{
  margin-top: 1.8rem;
  opacity: .8;
  font-size: 19px;
  font-weight: 400;
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