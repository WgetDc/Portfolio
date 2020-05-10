<template>
  <main>
    <px-header/>
    <px-body/>
  </main>
</template>

<script>
import PxHeader from "@/components/PxHeader";
import PxBody from "@/components/PxBody";

export default {
  name: "App",
  components: {
    PxHeader,
    PxBody 
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

*{
  background: #0d1219;
  font-family: 'Ubuntu', sans-serif;
}
</style>
