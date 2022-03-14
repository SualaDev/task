<template>
  <div class="container">
    <OtherNavbar/>
    <div class="comp-container">
      <div>
        <Sidebar/>
      </div>
      <div class="main-section">
        <div class="about">
          <p>Home / Frontend / Flutter</p>
          <p>About Flutter Chat SDK</p>
          <p class="through">Through our Chat SDK for Flutter, you can efficiently integrate real-time chat into your client app. On the client-side implementation, you can initialize, configure and build the chat with minimal effort. On the server-side, Sendbird ensures reliable infra-management services for your chat within the app. This and other pages in the Getting started provide the Chat SDK’s structure and installation steps, then goes through the preliminary steps of implementing the Chat SDK in your own project.</p>
        </div>
        <div class="note">
          <p><span class="n">Note:</span> Robin server supports Transport Layer Security (TLS) from versions 1.0 up to 1.3. For example, in the server regions where TLS 1.3 isn’t available, lower versions from 1.0 to 1.2 will be sequentially supported for secure data transmission.</p>
        </div>
        <div class="requirements">
          <p class="re">Requirements</p>
          <p>The minimum requirements for Chat SDK for Flutter are:</p>
        </div>
        <ul class="list-container">
          <li class="android">
            <p>Android studio</p>
            <p>4.4 or later</p>        
          </li>
          <li class="dart">
            <p>Dart 2.10.4</p>
            <p>or later</p>        
          </li>
          <li class="flutter">
            <div>
              <p>Flutter 1.22.0</p>
            </div>
            <p>or later</p>        
          </li>
        </ul>
        <div class="sample">
          <p class="sa">Try the sample app</p>
          <p>Our sample app has the core features of the Chat SDK. Download the app from our GitHub repository to get an idea of what you can build with the actual SDK and start building in your project.</p> 
          <button class="download">
            <p>Download Now</p>
            <img src="~assets/images/blue-arrow.svg" alt="">
          </button>        
        </div>
        <div class="server">
          <p class="se">Connect to Robin server</p>
          <p>Our sample app has the core features of the Chat SDK. Download the app from our GitHub repository to get an idea of what you can build with the actual SDK and start building in your project.</p>
          <img src="~assets/images/code-2.svg" alt="">
        </div>
        <div class="robin">
          <p><span class="n">Note:</span>Robin server supports Transport Layer Security (TLS) from versions 1.0 up to 1.3.</p>
        </div>
        <div class="sdk-container" >
          <div class="previous">
            <p class="p">Previous</p>
            <div class="ab">
              <img src="~assets/images/less-than.svg" alt="">
              <p>About Chat SDK</p>
            </div>
          </div>
          <div class="next">
            <p class="i">Next</p>
            <div class="c">
              <p>Installing Chat SDK</p>
              <img src="~assets/images/greater-than.svg" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <Robin/>
    </div>
    <div>
      <Bottom/>
    </div>
  </div>
</template>

<script>
import Sidebar from '../components/Sidebar.vue'
  export default {
  components: { Sidebar },
    name: "SDKS"
  }
</script>

<style scoped>
.comp-container{
  display: flex;
}
.main-section{
  margin: 4.4rem 7.3rem 0 4.8rem;
}
.about p:first-child{
  text-transform: uppercase;
  color: #808080e3;
  line-height: 1rem;
  margin-bottom: 2.5rem;
}
.about p:nth-child(2){
  font-size: 25px;
  font-weight: 700;
  margin-bottom: 1rem;
}
.about p:nth-child(3){
  min-width: 55.1rem;
  font-size: 19px;
  line-height: 2.6rem;
  margin-bottom: 3.3rem;
}
.through{
  opacity: .9;
}
.note {
  background-color: #ECF0FA;
  margin-bottom: 2.8rem;
  opacity: .8;
  /* border-bottom: 1px solid #808080e3; */
}
.note p{
  padding: 1.7rem 3.5rem 1.7rem 2.8rem;
  line-height: 2.1rem;
  font-size: 17px;
  font-weight: 400;
}
.requirements{
  padding-top: 2.8rem;
  border-top: 1px solid #808080e3;
}
.requirements p:first-child{
  font-weight: 700;
  font-size: 25px;
  margin-bottom: 1rem;
}
.requirements p:nth-child(2){
  font-size: 15px;
  font-weight: 400;
  line-height: 2.6rem;
  margin-bottom: 1rem;
}
.sample{
  padding-top: 3rem;
  border-top: 1px solid #808080e3;
}
.sample p:first-of-type{
  font-weight: 700;
  font-size: 25px;
  margin-bottom: 1rem;
}
.sample p:nth-child(2){
  opacity: .9;
  font-weight: 400;
  line-height: 2.3rem;
  margin-bottom: 2rem;
}
.dart,.flutter,.android{
  display: flex;
}
.android{
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  border-radius: 3px;
}
.android p:first-child{
  background-color: #ECF0FA;
  padding: 3px 12px 3px 7px;
  margin-right: 0.2rem;
}
.dart{
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  border-radius: 3px;
}
.dart p:first-child{
  background-color: #ECF0FA;
  padding: 3px 9px 3px 7px;
  margin-right: 0.2rem;
}
.flutter{
  margin-bottom: 3.1rem;
  display: flex;
  align-items: center;
  border-radius: 3px;
}
.flutter p:first-child{
  background-color: #ECF0FA;
  padding: 3px 8px 3px 7px;
  margin-right: 0.2rem;
}
.download{
  border-radius: 1.9rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #4568d18c;
  width: 15rem;
  padding: 1rem 1.5rem;
  border: none;
  margin-bottom: 3.6rem;
  cursor: pointer;
}
.download p{
  font-size: 15px !important;
  margin-bottom: 0 !important;
  color: #4568D1;
}
.server{
  padding-top: 3rem;
  border-top: 1px solid #808080e3;
}
.server p:first-child{
  font-size: 25px;
  font-weight: 700;
  margin-bottom: 1rem;
}
.server p:nth-child(2){
  opacity: .9;
  font-weight: 400;
  line-height: 2.3rem;
  margin-bottom: 2rem;
}
.server img{
  margin-bottom: 1.3rem;
}
.robin{
  background-color: #ECF0FA;
  width: 46.2rem;
  margin-bottom: 4rem;
  opacity: .7;
}
.robin p{
  padding: 1rem 4.5rem 1.1rem 2.2rem;
}
.n{
  font-weight: 700;
  opacity: .95;
}
.sdk-container{
  width: 46.2rem;
  border: 1px solid #E3E3E3;
  border-radius: 4rem;
  display: flex;
  margin-bottom: 8.5rem;
}

.previous{
  padding: 1.3rem 8.8rem 2.3rem 3.6rem;
  border-right: 1px solid #E3E3E3;
}
.p,.i{
  color: #EA8D51;
  line-height: 2.1rem;
}
.next{
  padding: 1.3rem 7.5rem 2.3rem 3.4rem;
}
.ab{
  width: 9.1rem;
  display: flex;
}
.c{
  width: 11rem;
  display: flex;
}
.c p{
  margin-right: 1rem;
}
.ab p{
  margin-left: .8rem;
}
</style>