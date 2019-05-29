<template>
  <div class="news-main">
    <h2 class="title">{{title}}</h2>
  </div>
</template>
<script>
export default {
  name: "News",
  data() {
    return {
      title: "新闻页面"
    };
  }
};
</script>
<style lang="scss" scoped>
// 使用scss预处理器
// scoped  局部  这里的样式 只会在当前的组件生效
$color:blue;
.news-main {
  .title {
    color:$color;
  }
}
</style>
