<template>
  <el-input></el-input>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import { Input } from "element-ui";

@Component({
  components: {
    Input
  }
})
export default class HelloWorld extends Vue {}
</script>
