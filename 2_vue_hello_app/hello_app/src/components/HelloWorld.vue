<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <p>
      {{ message }}
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    title:String,
    message: String,
  },
};
</script>

<style>
div{
  margin:0px;
  padding:0px;
  text-align: left;
}
h1{
  font-size: 72pt;
}
p{
  color: #666;
  font-size: 16pt;
}
</style>
