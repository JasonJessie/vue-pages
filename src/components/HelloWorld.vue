<template>
  <div class="hello">
    <h1>Vue fb messenger test!!</h1>
    <!-- Messenger 洽談外掛程式 Code -->
    <div id="fb-root"></div>

    <!-- Your 洽談外掛程式 code -->
    <div id="fb-customer-chat" class="fb-customerchat">
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
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
