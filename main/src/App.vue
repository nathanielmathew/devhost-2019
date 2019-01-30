<template>
  <div id="App">
    <NavBar />
    <div id="contents">
      <Event />
    </div>
  </div>
</template>
<style>
#App{
  font-family: sans-serif;
  background: #130e25;
  color: white;
  padding: 0px 0px 40px 0px;
}
#contents{
  margin: 5px 10%;
  background: #0906146b;
  padding: 30px;
  border-radius: 30px;
}
</style>
<script>
import NavBar from "./components/navbar";
import Events from "./views/Events";
export default{
  components:{
    'Event':Events,
    'NavBar':NavBar
  }
}
</script>
