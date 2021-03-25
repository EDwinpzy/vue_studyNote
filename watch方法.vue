<template>
<div>
    <div>常规监听，立即监听，深度监听</div>
    <div src = "https://blog.csdn.net/zx1294644276/article/details/112302839?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522161666199216780264085969%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=161666199216780264085969&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-112302839.first_rank_v2_pc_rank_v29_10&utm_term=vue%E4%B8%ADwatch">参考连接</div>
</div>
</template>

<script>
export default {
  data() {
    return {
      value: "",
    };
  },
  watch: {
    value: "changeValue",
  },
  methods: {
    changeValue() {
      console.log("当value值发生变化时执行这个方法");
    },
  },
};
</script>