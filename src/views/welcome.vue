<template>
  <div class="welcome">
      个人中心管理页
    <el-container>
      <el-aside width="200px" >侧边导航</el-aside>
      <el-container>
        <el-header style="background:bisque">头部</el-header>
        <el-main style="background:cadetblue">内容</el-main>
      </el-container>
    </el-container>

  </div>
</template>
<script>
export default {
    name: 'Container',
 
}
</script>
<style lang="less" scoped>
.welcome{
    .el-aside{
        background: crimson;
    }
}
</style>