<template>
  <div>
    <h2>About</h2>
    <p>{{msg}}</p>
    <input type="text" v-model= 'msg'/>
  </div>
</template>

<script>
export default {
  props: {
    msg: String,
  },
};
</script>

<style>
</style>