<template>
  <div class="container">
    <div class="background">
      <OtherNavbar/>
    <div class="text">
      <p class="title">RobinChat Use Cases</p>
      <p class="we">Teams of all sizes trust the Robin Chat API for building in-app messaging without the headache of implementing complex features with the scalability </p>
    </div>
    <div class="padding-container">
      <div class="first-cards">
      <div class="social">
        <img src="~assets/images/chat.svg" alt="">
        <p class="title">Social Community</p>
        <p class="we">Keep users hooked on your platform by allowing them create realistic experiences through engaging live streams with our live chat features.</p>
        <div class="learn">
          <p>Learn More</p>
          <img src="~assets/images/use-arrow.svg" alt="">
        </div>
      </div>
      <div class="notification">
        <img src="~assets/images/megaphone.svg" alt="">
        <p class="title">Marketing & Sales</p>
        <p class="we">Create interaction between buyers and sellers in real-time to boost sales and customer services with Robin in-app chat features.</p>
        <div class="learn">
          <p>Learn More</p>
          <img src="~assets/images/use-arrow.svg" alt="">
        </div>
      </div>
      <div class="education">
        <img src="~assets/images/pagepen.svg" alt="">
        <p class="title">Education</p>
        <p class="we">Set up unlimited remote learning experiences. Create virtual class-rooms and connect teachers, trainers, students and parents.</p>
        <div class="learn">
          <p>Learn More</p>
          <img src="~assets/images/use-arrow.svg" alt="">
        </div>
      </div>
    </div>
    <div class="second-cards">
      <div class="gaming">
        <img src="~assets/images/xbox_controller.svg" alt="">
        <p class="title">Gaming</p>
        <p class="we">Integrate in-app messaging and create immersive gaming experiences for your gamers.</p>
        <div class="learn">
          <p>Learn More</p>
          <img src="~assets/images/use-arrow.svg" alt="">
        </div>
      </div>
      <div class="live">
        <img src="~assets/images/youtube.svg" alt="">
        <p class="title">Live Streaming</p>
        <p class="we">Enable chat for a more fan-tastic viewing experience that drives engagement and increases your app stickiness.</p>
        <div class="learn">
          <p>Learn More</p>
          <img src="~assets/images/use-arrow.svg" alt="">
        </div>
      </div>
      <div class="retail">
        <img src="~assets/images/shopping.svg" alt="">
        <p class="title">Retail & E-commerce</p>
        <p class="we">Keep users hooked on your platform by allowing them create realistic experiences through engaging live streams with our live chat features.</p>
        <div class="learn">
          <p>Learn More</p>
          <img src="~assets/images/use-arrow.svg" alt="">
        </div>
    </div>
    </div>
    </div>
    <button class="use">
      <p>Other Use Cases</p>
    </button>
    </div>
    <div>
      <Robin/>
    </div>
    <div>
      <Footer/>
    </div>
  </div>
</template>

<script>
  export default {
    name:"UseCase"
  }
</script>

<style scoped>
.background{
  background-image: url('~assets/images/ColourfulBG.svg');
  background-size: 100%;
}
.text{
  margin: 5rem auto 0 auto;
  text-align: center;
}
.text p:first-child{
  font-size: 40px;
  font-weight: bold;
  margin-bottom: 1.5rem;
}
.text p:nth-child(2){
  margin: 2rem auto;
  max-width: 33.9rem;
  opacity: .8;
  font-size: 17px;
  line-height: 2.1rem;
}
.padding-container{
  margin: 0 2rem;
}
.first-cards{
  display: flex;
  margin-bottom: 1rem;
}
.social,.notification,.education{
  padding: 1.9rem 4.7rem 3.6rem 3.5rem;
}
.gaming{
  padding: 2.6rem 4.7rem 3.6rem 3.5rem;
}
.retail{
  padding: 1.9rem 2.7rem 3.6rem 1.5rem;
}
.live{
  padding: 1.9rem 4.6rem 3.5rem 3.5rem;
}
.first-cards p:nth-child(2){
  margin: 1rem 0;
  font-size: 28px;
  font-weight: bold;
  font-weight: 700;
}
.first-cards p:nth-child(3){
  opacity: .8;
  font-size: 19px;
  font-weight: 400;
  min-width: 18.6rem;
  line-height: 1.8rem;
}
.notification,.gaming,.retail{
  box-shadow: 0px 15px 20px 10px rgba(69, 104, 209, 0.06);
  border-radius: 8px;
  opacity: 0.9;
}
.second-cards{
  display: flex;
}
.second-cards p:nth-child(2){
  margin: 1rem 0;
  font-size: 28px;
  font-weight: bold;
  font-weight: 700;
}
.second-cards p:nth-child(3){
  opacity: .8;
  font-size: 19px;
  font-weight: 400;
  line-height: 1.8rem;
  min-width: 18.6rem;
}
.learn{
  display: flex;
  margin: 2rem 0 !important;
  /* padding: 0 !important; */
}
.learn p{
  margin-right: .6rem;
}
.gaming img:nth-child(1){
  margin-top: 1.2rem;
}
.gaming p:nth-child(2){
  margin-top: 1.5rem;
}
.use{
  margin: 3.5rem 45% 5rem 45%;
  background-color: #4568D1;
  color: #FFFFFF;
  padding: 1rem;
  border-radius: 30.5px;
  border: none;
  cursor: pointer;
}
.sdk{
  background-color: #102a7944;
  margin: 4rem 1rem 1.3rem 1rem;
  border-radius: 25px;
  padding: 2.5rem 6rem 3rem 6rem;
}
.sdk p:nth-child(1){
  text-align: center;
  font-weight: 700;
  font-size: 28px;
}
.sdk p:nth-child(2){
  text-align: center;
  font-size: 15px;
  font-weight: 400;
}
.btn-container {
  display: flex;
  /* justify-content: space-between; */
  padding: 0.9rem 24.6rem;
  /* width: 25.8rem; */
}
</style>