<template>
<div class="box">
  <el-dropdown placement="bottom" trigger="click">
    <span class="el-dropdown-link">
      <i class="el-icon-user"></i>
    </span>
    <el-dropdown-menu slot="dropdown">
      <el-dropdown-item>退出</el-dropdown-item>
    </el-dropdown-menu>
  </el-dropdown>
</div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="less" scoped>
  .box{
    width: 100%;
    height: 40px;
    display: flex;
    justify-content: right;
    align-items: center;
    .el-dropdown-link {
      cursor: pointer;
      color: #409EFF;
      .el-icon-user{
        margin: 0 8px 0 0;
        font-size: 26px;
      }
    }
  }
 
</style>