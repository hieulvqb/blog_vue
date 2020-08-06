<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Contact page</h2>
    <router-link to="/contact">Contact</router-link>
    <router-link to="/news">News</router-link>
  </div>
</template>

<script>
export default {
  // name: 'hello',
  data () {
    return {
      msg: 'Welcome contact'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}
</style>
