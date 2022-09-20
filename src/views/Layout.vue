<template>
    <div class="common-layout">
      <el-container>
        <el-aside width="200px">Aside</el-aside>
        <el-main class="main">Main</el-main>
      </el-container>
    </div>
</template>

<script>
export default {
  name: 'cesium-layout'
}
</script>

<style scoped lang='less'>
.main{
    height: 100%;
    width: 100%;
    border: 0;
    margin: 0;
    padding: 0;
}
</style>
