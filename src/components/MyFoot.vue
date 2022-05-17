<template>
  <div class="box2">
    <ul class="nav nav-pills nav-fill">
  <li class="nav-item">
    <a class="nav-link " href="#"  @click="comname = 'MygoodsList'">商品列表</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#" @click="comname = 'MygoodSearch'">商品搜索</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">我的信息</a>
  </li>
</ul>
  </div>
</template>

<script>
export default {
  name: 'VuedemoMyFoot',

  data() {
    return {
      comname:'MygoodsList'
    };
  },

  mounted() {
    
  },

  methods: {
    
  },
};
</script>

<style lang="less" scoped>

.box2{
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 50px;
}
</style>