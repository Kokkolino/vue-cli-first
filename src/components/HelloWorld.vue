<template>
  <div class="hello">
    <h1>Questa é</h1>
    <p>La mia prima app con Vue CLI!</p>
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
<style scoped lang="scss">
.hello {
  padding: 30px;
  background-color: lightgray;
  width: max-content;
  margin: auto;
}

h1{
  font-size: 70px;
}

p{
  font-size: 30px;
}

</style>
