<template>
  <div class="question__container">
    <div class="section1">
    <p>Commonly asked questions</p>
    <p>Ship in-app chat messaging with all the features your users expect.</p>
    </div>
    <div class="questions">
      <div class="in">
        <div class="price">
          <p>How is MAU calculated?</p>
          <img v-if="!selectIsMAU" src="~assets/images/black-arrow.svg" alt="" @click="showMAU">
          <img v-if="selectIsMAU" src="~assets/images/upside-down arrow.svg" alt="" @click="showMAU">
        </div>
        <p v-if="selectIsMAU" class="in-content">Life may just be gucci who knows?</p>
      </div>
      <div class="in">
        <div class="price">
          <p>What is the difference between Starter, Pro, and Enterprise plans?</p>
          <img v-if="!selectIsPlan" src="~assets/images/black-arrow.svg" alt="" @click="showPlan">
          <img v-if="selectIsPlan" src="~assets/images/upside-down arrow.svg" alt="" @click="showPlan">
        </div>
        <p v-if="selectIsPlan" class="in-content">Life would be good</p>        
      </div>
      <div class="in">
        <div class="price">
          <p>What happens if I hit my MAU limit??</p>
          <img v-if="!selectIsIf" src="~assets/images/black-arrow.svg" alt="" @click="showIf">
          <img v-if="selectIsIf" src="~assets/images/upside-down arrow.svg" alt="" @click="showIf">
        </div>
        <p v-if="selectIsIf" class="in-content">Life is for the living</p>
      </div>
      <div class="in">
        <div class="price">
          <p>How do I purchase higher levels of support?</p>
          <img v-if="!selectIsSupport" src="~assets/images/black-arrow.svg" alt="" @click="showSupport">
          <img v-if="selectIsSupport" src="~assets/images/upside-down arrow.svg" alt="" @click="showSupport">
        </div>
        <p v-if="selectIsSupport" class="in-content">Life is calm</p>
      </div>
      <div class="in">
        <div class="price">
          <p>What other limits do I need to be aware of?</p>
          <img v-if="!selectIsLimit" src="~assets/images/black-arrow.svg" alt="" @click="showLimit">
          <img v-if="selectIsLimit" src="~assets/images/upside-down arrow.svg" alt="" @click="showLimit">
        </div>
        <p v-if="selectIsLimit" class="in-content">Life is gucci</p>
      </div>
      <div class="in">
        <div class="price">
          <p>Do the prices listed on the pricing page include tax?</p>
          <img v-if="!selectIsShow" src="~assets/images/black-arrow.svg" alt="" @click="showOption">
          <img v-if="selectIsShow" src="~assets/images/upside-down arrow.svg" alt="" @click="showOption">
        </div>
        <p v-if="selectIsShow" class="in-content">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
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
    name: "FaQ",
    data (){
      return{
        selectIsShow: false,
        selectIsLimit: false,
        selectIsSupport: false,
        selectIsIf: false,
        selectIsPlan: false,
        selectIsMAU: false,
      }
    },
    methods: {
      showOption () {
      this.selectIsShow = !this.selectIsShow
    },
    showLimit () {
      this.selectIsLimit = !this.selectIsLimit
    },
    showSupport () {
      this.selectIsSupport = !this.selectIsSupport
    },
    showIf () {
      this.selectIsIf = !this.selectIsIf
    },
    showPlan () {
      this.selectIsPlan = !this.selectIsPlan
    },
    showMAU () {
      this.selectIsMAU = !this.selectIsMAU
    }
    }
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