<script setup>
import {ref} from "vue";
const data=ref({
  src:'src',
  href:'href',
  srcdata1:'https://img0.baidu.com/it/u=525778574,3424229382&fm=253&fmt=auto&app=138&f=JPEG?w=450&h=338',
  hrefdata1:'www.baidu.com',
  message:'去百度搜索图片'
})
</script>
<template>
  <div>
    <a :href="data.hrefdata1">
      {{ data.message}}
      <img :src="data.srcdata1"/>
    </a>

  </div>

</template>




