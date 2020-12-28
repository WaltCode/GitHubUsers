<template>
  <div id="app">
    <div id="contaier">
      <Input/>
    </div>
  </div>
  
</template>
<script>
import Input from "./components/input.vue"
export default {
  name: "app",
  components:{
    Input
  }
}
</script>

<style scope>
body{
  background: #e8f7f0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
#container
{
  width: 50%;
  transform: translate(-50%, -80%);
  position: absolute;
  left: 50%;
  top: 20%;
  
}
</style>>
