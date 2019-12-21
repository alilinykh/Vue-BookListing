<template>
  <div>
    <li>{{book.title}}:{{book.author}}</li>
  </div>
</template>

<script>
export default {
  name: "BookItem",
  props: ["book"],
  data() {}
};
</script>

<style scoped>
    li {
        display: block;
        margin: 0 10px;
    }
</style>