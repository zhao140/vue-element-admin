<template>
  <el-container style="height: 100vh;">
    <el-aside width="250px"><Aside/></el-aside>
    <el-container>
      <el-header><Header/></el-header>
      <el-main><router-view></router-view></el-main>
    </el-container>
  </el-container>
</template>

<script>
import Header from '@/components/layout/Header.vue'
import Aside from '@/components/layout/Aside.vue'
export default {
  name: 'app',
  components:{
    Header,
    Aside
  }
}
</script>

<style scoped>
.el-header{
  padding: 0;
  height: 40px !important;
  background-color: rgba(201, 201, 201,0.3);
}
.el-main{
  padding: 0;
}
</style>