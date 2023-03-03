<script setup>
import {ref} from 'vue'

const data=ref(
    {
      dog:{
        name:"dog",
        call:"汪汪"
      },
      msg:"text案例"
    }
    )
</script>

<template>
<div>
  <p>{{data.dog}}</p>
  <p>{{ data.msg}}</p>
</div>
</template>
