<template>
  <div>
   <h1>
       看我
   </h1>
   <button  @click="btn">点我</button>
   <ul>
 
</ul>
  </div>
</template>

<script>
import { Toast } from 'mint-ui';

export default {
  name: "login",
  methods: {
    btn() {
      Toast({
        message: "提示",
        position: "bottom",
        duration: 2000
      });
    }
  }
};

</script>

<style>
</style>
