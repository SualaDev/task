<template>
  <div class="container">
    <div class="background">
      <OtherNavbar/>
    <div class="docs-container">
      <div class="robin">
        <p class="title">RobinChat Docs</p>
        <p class="we">Teams of all sizes trust the Robin Chat API for building in-app messaging without the headache of implementing complex features with the scalability </p>
      </div>
      <div>
        <img src="~assets/images/code.svg" alt="">
      </div>
    </div>
    </div>
    <div class="second-part">
      <p class="d">Documentation</p>
      <div class="frontend-api">
        <div class="frontend">
          <p>Frontend</p>
          <img src="~assets/images/flureact.svg" alt="">
        </div>
        <div class="api">
          <p class="a">API</p>
          <div class="api-container">
            <p class="p">API Documentation</p>
            <div class="read">
              <p>Read Now</p>
              <img src="~assets/images/black-arrow.svg" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <Footer/>
    </div>
  </div>
</template>

<script>
  export default {
    name:"DocsPage"
  }
</script>

<style scoped>
.background{
  background-image: url("~/assets/images/docs-background.svg");
  background-size: 100%;
}
.docs-container{
  margin: 6.5rem 6.6rem 3.9rem 6.6rem;
  display: flex;
  justify-content: space-between;
}
.robin{
  margin-top: 3rem;
}
.robin p:first-child{
  font-size: 45px;
  font-weight: 400;
  margin-bottom: 1.6rem;
}
.robin :nth-child(2){
  font-size: 15px;
  font-weight: 400;
  max-width: 22rem;
  opacity: .8;
  line-height: 25px;
}
.second-part{
  margin: 3.9rem 24.1rem 7.1rem 6.8rem;
}
.d{
  font-size: 30px;
  font-weight: 700;
  margin-bottom: 3.1rem;
}
.frontend-api{
  display: flex;
}
.frontend p{
  color: #808080;
  text-transform: uppercase;
  font-size: 13px;
  margin-bottom: 1.75rem;
  font-weight: bold;
  opacity: .3;
}
.api{
  margin-left: 5.4rem;
}
.a{
  text-transform: uppercase;
  font-size: 13px;
  color: #808080;
  font-weight: bold;
  margin-bottom: 2.3rem;
  opacity: .3;
}
.api-container{
  border: 1px solid #EBEBEB;
  box-shadow: 0px 5px 9px 2px rgba(69, 104, 209, 0.06);
  border-radius: 0.5rem;
  padding: 1.8rem 5.4rem 1.9rem 1.8rem;
  width: 50%;
}
.p{
  margin-bottom: 2.4rem;
  font-size: 18px;
  font-weight: 600;
  width: 15rem;
}
.read{
  display: flex;
}
.read p{
  margin-right: .8rem;
  font-size: 15px;
  font-weight: 700;
}
</style>