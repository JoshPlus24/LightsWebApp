<template>
  <div class="hello">
    <h1>Sainsbury's Lights</h1>
    <input type="text" name="guess" placeholder="What time will the lights turn on?" id>
    <button>Lights On</button>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  padding: 0 20px;
}
h1 {
  font-size: 10vw;
  margin: 0 0 40px;
}
input {
  padding: 3px 5px;
  margin-bottom: 30px;
  width: 100%;
  border-radius: 5px;
}
button {
  width: 100%;
  box-shadow: unset;
  background-color: #0095da;
  border: unset;
  color: #fff;
  font-size: 5vw;
  border-radius: 5px;
}
</style>
