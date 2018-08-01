<template>
  <div class="goodbye">
    <h1>{{ msg }}</h1>
    <img src="../assets/logo.png" alt="Vue.js PWA">
  </div>
</template>

<script>
export default {
  name: 'goodbye',
  data () {
    return {
      msg: 'Eat My Shorts'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
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
    color: #35495E;
  }
</style>
