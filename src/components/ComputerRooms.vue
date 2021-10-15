<template>
  <div class="table">
    <div class="body" v-if="list.length !== 0 ">
      <div class="body-item" v-for="item in list" :key="item" @click="openComputerClass">
        <img class="body-item_img" alt="" src="../assets/PicsArt_10-14-02_51_49.png">
        <h3>{{ item.number }}</h3>
      </div>
    </div>
    <h2 v-else>Нет информации о классах</h2>
  </div>
</template>

<script>


export default {
  name: "ComputerRooms",
  data() {
    return {
      list: []
    }
  },
  methods: {
    openComputerClass() {

    }
  }
}
</script>

<style scoped>
.body {
  display: flex;
  flex-wrap: wrap;
  border: darkgrey 2px solid;
  border-radius: 10px;
  background-color: lightgray;
  padding-top: 20px;
  justify-content: center;
}

.body-item {
}

.body-item_img {
  display: flex;
  width: 70px;
  height: 70px;
  margin: 20px;

}
</style>