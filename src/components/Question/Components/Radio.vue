<template>
  <el-radio-group v-model="radio">
    <el-radio style="margin-left: 2px" v-for="(answerhh,index) in answer" v-bind:key="answerhh" :label=index border  size="mini" >
      <h8  >{{answerhh}}</h8>
    </el-radio>
  </el-radio-group>
</template>

<script>
export default {
  props: ['answer'],
  data () {
    return {
      radio: -1
    };
  }
}
</script>