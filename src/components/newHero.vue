<template>
  <div>
    <div class="jumbotron">
      <span>ciao sono un jumbotron</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'newHero'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.jumbotron {
  height: 300px;
  border: 1px solid black;
  width: 80%;
  margin: 0 auto;
  display: flex;
}

span {
  margin: auto;
}

</style>