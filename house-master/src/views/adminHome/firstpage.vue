<template>
  <div>
    <div id="main" style="width: 1000px; height: 800px"></div>
    <!-- 这里可以添加一些默认显示的内容，或者直接留空 -->
  </div>
</template>

<script>
import * as echarts from "echarts";

export default {
  data() {
    return {
      
      loading: false,
      error: ''
    };
  },
  created() {
  
  },
  methods: {
    // 若不需要请求数据的方法，也可以将其删除
    cityCountEstate() {
      this.loading = true;
      this.error = '';
      
    }
  }
};
</script>

<style>
</style>