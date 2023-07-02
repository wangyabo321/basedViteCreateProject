<template>
  <div class="hello">
    {{ msg }}
    <br />
    <el-button type="primary">主要按钮</el-button>
    <el-button type="success">成功按钮</el-button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'HelloWorld',
  props: {
    msg: String
  }
})
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '../assets/css/common.scss';
.hello {
  color: $color;
  font-size: 20px;
}
</style>
