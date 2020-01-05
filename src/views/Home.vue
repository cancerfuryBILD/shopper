<template>
  <div class="home">
    <Header />
    
  </div>
</template>

<script>
// @ is an alias to /src

import Header from "@/components/common/header.vue";

export default {
  name: "home",
  components: {
    Header
  }
};
</script>

<style>
.home {
  width: 72%;
  margin: 0 auto;
}
</style>