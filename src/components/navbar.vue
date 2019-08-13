<template>
  <div class="tab-bar">
    <van-tabbar v-model="active">
      <van-tabbar-item name="home" icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item name="energy" icon="search">能耗</van-tabbar-item>
      <van-tabbar-item name="facility" icon="friends-o">设备</van-tabbar-item>
      <van-tabbar-item name="environment" icon="setting-o">环境</van-tabbar-item>
      <van-tabbar-item name="order" icon="setting-o">工单</van-tabbar-item>
      <van-tabbar-item name="polling" icon="setting-o">巡检</van-tabbar-item>
    </van-tabbar>
  </div>
</template>


<script>
import Vue from "vue";
import Button from "vant/lib/button";
import "vant/lib/button/style";
import { Tabbar, TabbarItem } from "vant";
Vue.use(Tabbar).use(TabbarItem);
export default {
  // props: {
  //   courrentTabBar: {
  //     type: String
  //   }
  // },
  // name: "home",
  components: {
    // HelloWorld
    // navbar
  },
  data() {
    return {
      active: 'home'
    }
  },
  methods: {
   
  },
  mounted() {

  }
};
</script>

<style lang="less" scoped>

</style>
