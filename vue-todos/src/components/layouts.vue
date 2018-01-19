<template>
<!-- 最外层的容器 -->
  <section class="container">
      <section class="menu">
          <!-- 左边的容器 -->
          <menus></menus>
      </section>
      <section class="content-container">
        <!-- 右边的容器 -->
        <todo></todo>
      </section>
  </section>
</template>
<script>
import menus from './menus';
import todo from './todo';
export default {
  components:{ //注册menus组件，让其可以在template调用
      menus,
      todo
  }
}
</script>
<style lang="less" scoped>
@import url(../common/style/layouts.less);
</style>


