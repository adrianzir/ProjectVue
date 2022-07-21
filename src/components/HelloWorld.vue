<template>
  <div class="hello d-flex flex-column ">

    <h1 class="text-white">{{ msg }}</h1>
   <p class="text-danger">test 1</p>
   <ol class="text-white d-flex flex-column bg-success w-50 container">
   <li>1. placed more components</li>
   <li>2. style the app</li>
   <li>3. give it functions</li>
   </ol>
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
