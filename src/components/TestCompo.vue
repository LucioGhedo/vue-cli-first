<template>
  <div>
    <div>{{ personalMsg }}</div>
    <section>
      <div class="jumbotron">
        <h2>{{ msg }}</h2>
        <img src="https://picsum.photos/200/200" alt="lorem picsum">
        <div>jumbotron</div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'TestCompo',
  props: {
    msg: String,
    personalMsg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
.jumbotron {
  background-color: #42b983;
  color: white;
  padding: 50px;
  background-image: url('https://picsum.photos/1900/420');
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
