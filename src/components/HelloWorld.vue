<template>
  <div>
    <IndexTop/>
    <IndexContent/>
  </div>
</template>

<script>
import IndexTop from './HelloWorld/IndexTop.vue'
import IndexContent from './HelloWorld/IndexContent'
export default {
  name: "HelloWorld",
  components: {
    'IndexTop': IndexTop,
    'IndexContent': IndexContent
  }
};
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
