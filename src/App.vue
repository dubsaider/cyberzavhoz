<template>
  <div id="hello">
    <img alt="Vue logo" src="./assets/PicsArt_10-13-04_00_52.png">
    <HelloWorld msg="Well cum to Your Ass"/>
    <ComputerRooms/>
  </div>
</template>

<script>

import HelloWorld from "@/components/HelloWorld";
import ComputerRooms from "@/components/ComputerRooms";

export default {
  name: 'App',
  components: {
    ComputerRooms,
    HelloWorld
  }
}
</script>

<style>
#hello {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
