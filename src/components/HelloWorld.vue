<template>
  <div class="hello">
    <h1>Vue fb messenger test!! 1.6 from component</h1>
    <Messenger />
  </div>
</template>

<script>
// import { test } from '../plugins/test';
// import VueFbCustomerChat from 'vue-fb-customer-chat'
// import Vue from 'vue'
import Messenger from './Messenger.vue'

export default {
  name: 'HelloWorld',
  components: {
    Messenger
  },
  props: {
    msg: String
  },
  methods: {
    runTest() {
      console.log('test X')
    }
  },
  // mounted() {
  //   /* eslint-disable */
  //   var chatbox = document.getElementById('fb-customer-chat');
  //   chatbox.setAttribute("page_id", "276309370870035");
  //   chatbox.setAttribute("attribution", "biz_inbox");
  //   window.fbAsyncInit = function() {
  //     FB.init({
  //       xfbml            : true,
  //       version          : 'v12.0'
  //     });
  //   };

  //   (function(d, s, id) {
  //     var js, fjs = d.getElementsByTagName(s)[0];
  //     if (d.getElementById(id)) return;
  //     js = d.createElement(s); js.id = id;
  //     js.src = 'https://connect.facebook.net/zh_TW/sdk/xfbml.customerchat.js';
  //     fjs.parentNode.insertBefore(js, fjs);
  //   }(document, 'script', 'facebook-jssdk'));
  //   /* eslint-disable */
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
