<template>
  <div class="navigation">
    <button>Account</button>
    <button>Leaderboard</button>
  </div>
</template>

<script>
export default {
  name: "Navigation",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.navigation {
  position: fixed;
  bottom: 0;
  left: 0;
  display: flex;
}
button {
  width: 50%;
  color: #fff;
  background-color: #0095da;
  display: inline-block;
}
</style>