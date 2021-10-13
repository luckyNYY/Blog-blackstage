<template>
  <div class="container">
    <div class="left">博客后台管理</div>
    <div class="mian"></div>
    <div class="right">
      <el-dropdown>
  <span class="el-dropdown-link">
    用户名<i class="el-icon-arrow-down el-icon--right"></i>
  </span>
  <el-dropdown-menu slot="dropdown">
    <el-dropdown-item>个人信息</el-dropdown-item>
    <el-dropdown-item>退出登录</el-dropdown-item>
  </el-dropdown-menu>
</el-dropdown>
    </div>
  </div>
</template>

<script>
    export default {}
</script>

<style lang="less" scope>
  .container {
    height: 50px; 
    line-height: 50px; 
    border-bottom: 1px solid #ccc; 
    display: flex;
  }
  .left {
    width: 200px;
    padding-left: 30px;
    font-weight: bold;
    color: #409EFF;
  }
  .mian {
    flex: 1;
  }
  .right {
    width: 100px;
  }
  .el-dropdown-link {
    cursor: pointer;
    color: #409EFF;
  }
  .el-icon-arrow-down {
    font-size: 12px;
  }
</style>