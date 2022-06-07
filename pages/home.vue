<template>
</template>

<script>
export default {
  name: "Home",
  layout: 'Navigation',
  mounted() {
    layui.use(['dropdown', 'util', 'layer'], function(){
      var element = layui.element;
      var layer = layui.layer;

      //监听折叠
      element.on('collapse(test)', (data) => {
        layer.msg('展开状态：'+ data.show);
      });
    });
  },
}
</script>

<style scoped>

</style>
