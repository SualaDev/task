<template>
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
            <p>10,000 Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>100 Concurrent Included</p>
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
            <p>25,000 Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>100 Concurrent Included</p>
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
            <p>50,000 Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>100 Concurrent Included</p>
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
            <p>100,000+ Monthly Active Users</p>
          </div>
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>MAU Overage Rate</p>          
          </div>         
          <div class="in">
            <img src="~assets/images/check.svg" alt="">
            <p>100 Concurrent Included</p>
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
</template>

<script>
  export default {
    name: "PaY"
  }
</script>

<style scoped>
.paycard{
  display: flex;
   /* border: 1px solid black; */
   margin: 5rem auto;
   width: 80%;
   justify-content: space-between;
}

.childcard{
  border: 1px solid #4568D1;
  background-color: #F5F7FC;
  padding: 2.25rem 1.6rem 2.4rem 0.8rem;
  /* margin: .5rem; */
  border-radius: 1rem;
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
  border-bottom: 1px solid #BBC1D6;
}
.second{
  display: flex;
  flex-direction: column;
  padding-bottom: 3.3rem;
  border-bottom: 1px solid #BBC1D6;
}
.in{
  display: flex;
  padding-top: 1.1rem;
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
</style>