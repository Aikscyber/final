<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!-- <h2>Essential Links</h2> -->
    
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
      msg: 'This is the Contact Component'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
  color: #7942b9;
}
</style>