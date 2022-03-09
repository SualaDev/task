<template>
  <div class="container">
    <div class="flutter">
      <img src="~assets/images/flutter.svg" alt="">
      <p>Flutter Chat SDK</p>
      <img src="~assets/images/mask.svg" alt="">
    </div>
    <div class="cards-container">
    <div>
      <p>Getting Started</p>
      <NuxtLink to = "/sdk" class="chat">
        <p>About Chat SDK</p>
        <img src="~assets/images/black-arrow.svg" alt="">
      </NuxtLink>
      <p>Installing Chat SDK</p>
      <p>Send First Message</p>
    </div>
    <div>
      <p>tutorials</p>
      <p>1:1 Messaging</p>
      <p>Group Messaging</p>
      <p>Multimedia Management</p>
    </div>
    <div>
      <p>Guides</p>
      <p>Authentication</p>
      <p>Application</p>
      <p>Users</p>
      <p>Event Holders</p>
      <p>Push Notifications</p>
      <p>Error Messages</p>
      <p>Logger</p>
      <p>Change Logs</p>
    </div>
   </div>
  </div>
</template>

<script>
  export default {
    name:"SideBar"
  }
</script>

<style scoped>
.container{
  /* width: 15%; */
  margin: 3.7rem 5.1rem 0 4.9rem;
}
.flutter{
  display: flex;
  justify-content: space-around;
  border: 1px solid #566BA0;
  align-items: center;
  margin-bottom: 3.3rem;
}
.cards-container p:first-child{
  text-transform: uppercase;
  color: #808080e3;
  font-weight: 700;
}
.cards-container p{
  font-size: 17px;
  font-weight: 700;
  line-height: 3.1rem;
}
a.nuxt-link-exact-active {
  color: blue;
  fill: blue;
}
.chat{
  display: flex;
  text-decoration: none;
  justify-content: space-between;
}
.chat p{
  font-size: 17px;
  font-weight: 700;
  color: #000 !important;
}
</style>