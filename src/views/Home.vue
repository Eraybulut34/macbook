<template>
  <div class="home">
<Navbar/>
<img src="@/assets/images/header.jpg" alt="">
<All/>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import All from "@/components/All.vue";

export default {
  name: "Home",
  components: {
    All,
    Navbar
  },
};
</script>

<style scoped>
.home{
  align-items: center;
  justify-content: center;
  
}
</style>
