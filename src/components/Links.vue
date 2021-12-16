<template>
  <div class="Links">
    <h3>{{ msg }}</h3>
    <ul>
      <li>
        <a href="lnk1" target="_blank" rel="noopener">{{ lnkName1 }} </a>
      </li>
      <li>
        <a href="lnk2" target="_blank" rel="noopener">{{ lnkName2 }} </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Links",
  props: {
    lnk1: String,
    lnkName1: String,
    msg: String,
    lnk1: String,
    lnkName2: String,
  },
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
