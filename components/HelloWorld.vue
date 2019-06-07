<template>
  <div class="hello">
    <input v-model.number="numData" type="number" />
    
    <div class="block">{{numData}} </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  methods: {
    
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
body{
  display:flex;
  justify-content:center;
  align-items:center;
}
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
.block{
  margin-top:1rem;
  font-size:2rem;
  width:80vw;
  background-color:red;
}
</style>
