<template>
  <div class="paycard-container">
    <div class="paycard">
    <!-- <div class="paycard"> -->
      <div class="childcard">
        <div class="first">
          <p>Starter</p>
          <p>$69<span class="m">/mo</span></p>
        </div>
        <div class="second">
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Core Chat Features </p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 10,000</span> Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 100</span> Concurrent Included</p>
          </div>          
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Limited Message Storage</p>
          </div>     
        </div>
        <div class="started">
          <p>Get Started</p>
          <img src="~assets/images/blue-arrow.svg" alt="">
        </div>
      </div>
      <div class="childcard">
        <div class="first">
          <p>Growth</p>
          <p>$389<span class="m">/mo</span></p>
        </div>
        <div class="second">
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Core Chat Features </p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 25,000</span> Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 100</span> Concurrent Included</p>
          </div>          
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Limited Message Storage</p>
          </div>     
        </div>
        <div class="started">
          <p>Get Started</p>
          <img src="~assets/images/blue-arrow.svg" alt="">
        </div>       
      </div>
      <div class="childcard">
        <div class="first">
          <p>Pro</p>
          <p>$799<span class="m">/mo</span></p>
        </div>
        <div class="second">
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Core Chat Features </p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 50,000</span> Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 100</span> Concurrent Included</p>
          </div>          
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Limited Message Storage</p>
          </div>     
        </div>
        <div class="started">
          <p>Get Started</p>
          <img src="~assets/images/blue-arrow.svg" alt="">
        </div>       
      </div>
      <div class="childcard">
        <div class="first">
          <p>Enterprise</p>
          <p>Customized</p>
        </div>
        <div class="second">
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Core Chat Features </p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 100,000+</span> Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p><span class="a"> 100</span> Concurrent Included</p>
          </div>          
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>Limited Message Storage</p>
          </div>     
        </div>
        <div class="started">
          <p>Get Started</p>
          <img src="~assets/images/blue-arrow.svg" alt="">
        </div>
      </div>
  </div>
  </div>
</template>

<script>
  export default {
    name: "PaY"
  }
</script>

<style scoped>
.paycard-container{
  padding: 50px;
}
.paycard{
  display: flex;
  /* margin: 91px 55px 132px 91px; */
  /* min-width: 1294px; */
  width: 100%;
  justify-content: center;
  /* flex-wrap: wrap; */
}

.childcard{
  border: 1px solid #4568D1;
  background-color: #F5F7FC;
  padding: 20px;
  flex-basis: 23%;
  /* margin-top: 1rem; */
  /* flex-basis: 18%; */
  border-radius: 1rem;
  margin: 1%;
  /* min-width: 310px; */
}
.first p:first-child{
  font-size: 1.1rem;
  font-weight: 700;
  color: #EA8D51;
  margin-bottom: 0.5rem;
}
.first p:nth-child(2){
  font-size: 1.9rem;
  font-weight: 700;
}
.first{
  padding-bottom: 1rem;
  border-bottom: 1px solid rgb(128,128,128,.1)
}
.second{
  display: flex;
  flex-direction: column;
  padding-bottom: 3.3rem;
  border-bottom: 1px solid rgb(128,128,128,.1)
}
.in{
  display: flex;
  padding-top: 1.1rem;
  opacity: .8;
  /* padding-bottom: 1.5rem; */
}
.in p{
  margin-left: 0.7rem;
  color: #485476;
  /* margin-bottom: 1.9rem; */
}
.started{
  display: flex;
  color: #4568D1;
  padding-top: 1.7rem;
}
.started p{
  margin-right: 0.4rem;
}
.m{
  font-weight: 400;
}
.started{
  cursor: pointer;
}
@media only screen and (max-width: 1300px){
  .paycard{
    flex-wrap: wrap;
    justify-content: flex-start;
}
}
/* @media only screen and (max-width: 1920px){
  .paycard{
    width: 75%;
  }
}
@media only screen and (max-width: 1450px){
  .paycard{
    width: 85%;
  }
}
}
@media only screen and (max-width: 800px){
  .paycard{
    width: 90%;
  }
}
@media only screen and (max-width: 500px){
  .paycard{
    width: 95%;
  }
} */
</style>