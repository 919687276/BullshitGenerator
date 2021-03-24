<template>
  <div id="app">
    <div class="title">爱思思</div>
    <el-carousel :interval="4000" type="card" height="50vh">
      <el-carousel-item v-for="item in 6" :key="item">
        <img class="medium" src="~/assets/img/1.JPG">
      </el-carousel-item>
    </el-carousel>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#app{
  width: 100vw;
  height: 100vh;
  background-color: rosybrown;
}
.title{
  width: 100%;
  height: 5vh;
  color: pink;
  font-size: .2rem;
  display: flex;
  justify-content: center;
  align-items: center;
}
.medium{
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: auto;  /*定宽*/
  height: 100%;
}
</style>