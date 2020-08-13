<template>
  <div id="example-1">
    <button v-on:click="up" class="btn btn-danger">{{lable}}</button>

    <p v-bind;style="{fontsize:fsize+'px'}">{{ counter }} times.</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      counter: 0,
      fsize: 50,
    };
  },
  props: {
    lable: String,
  },
  methods: {
    up: function () {
      counter += 1;
      fsize += 10;
    },
  },
};
</script>

<style>
</style>