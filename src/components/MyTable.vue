<template>
  <div>
    <table class="table table-hover">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">商品名称</th>
      <th scope="col">价格</th>
      <th scope="col">标签</th>
      <th scope="col">操作</th>
    </tr>
  </thead>
  <tbody>
    <tr v-for="item in list" :key="item.id">
      <th scope="row">{{item.id}}</th>
      <td>{{item.name}}</td>
      <td>￥{{item.price}}</td>
      <td>
        <button type="button" class="btn-primary del">+Tag</button>
      </td>
      <td style="width:30px"><button type="button" class="btn-danger del">删除</button></td>
    </tr>
  </tbody>
</table>
<div>

</div>

  </div>
</template>

<script>
export default {
  name: 'VuedemoMyTable',

  data() {
    return {
      list:[{
        id:1,
        name:'鞋子',
        price:'298'
      },
      {
        id:2,
        name:'上衣',
        price:'88'
      },{
        id:3,
        name:'毛衣',
        price:'199'
      },{
        id:4,
        name:'女装',
        price:'288'
      },{
        id:5,
        name:'旗袍',
        price:'999'
      },
      ]
    };
  },

  mounted() {
    
  },

  methods: {
    
  },
};
</script>

<style lang="less" scoped>
.table{
  position: relative;
  top: 55px;

  .del{
    box-sizing: border-box;
    border: none;
    border-radius: 4px;
    width: 60px;
  }
}
</style>