<template>
  <div class="hello">
    {{arr}}
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        arr: [1, 2, 3, 4, 5],
        msg: '我是version组件的数据'
      }
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