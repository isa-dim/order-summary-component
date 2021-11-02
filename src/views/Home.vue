<template>
  <div class="home">
    <HelloWorld msg="Hey dudes!" />
  </div>
</template>

<style scoped media="screen">
  .home{
    background-color:	#f5f7ff;
  }
</style>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
