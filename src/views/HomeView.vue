<template>
  <div>
    <tabar-header></tabar-header>
    <mygoods-list></mygoods-list>
    <my-good-search></my-good-search>
    <my-foot></my-foot>
  </div>
</template>

<script>
import MygoodsList from '@/components/MygoodsList.vue';
import MyFoot from '@/components/MyFoot.vue';
import TabarHeader from '@/components/TabarHeader.vue';
import MyGoodSearch from '@/components/MyGoodSearch.vue';
export default {
  components: { MygoodsList, MyFoot, TabarHeader, MyGoodSearch },
  name: 'VuedemoHomeView',

  data() {
    return {
      
    };
  },

  mounted() {
    
  },

  methods: {
    
  },
};
</script>

<style lang="less" scoped>

</style>