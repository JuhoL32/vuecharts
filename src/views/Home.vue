<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <CommitChart></CommitChart>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import CommitChart from '@/components/CommitChart.vue';
export default {
  name: "Home",
  components: {
    HelloWorld
  }
  
};
</script>
