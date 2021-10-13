<template>
  <div id="layout">
    <!-- 头部 -->
    <Header />
    <!-- 侧边栏 -->
    <div style="display: flex">
      <Aside />
    <router-view />
    </div>
    <!-- 内容 -->
  </div>
  
</template>

<script>
import Header from '@/components/Header.vue';
import Aside from '@/components/Aside.vue';
export default {
  name: 'Layout',
  components: {
    Header,
    Aside,
  }
}
</script>

<style lang="less" scope>

</style>
