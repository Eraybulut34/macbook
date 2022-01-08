<template>
  <div class="hello">
    <!-- ----- aşa -->
    <nav class="navbar-lower">
      <router-link to="/characters" class="route-item">
        Store
      </router-link>
      <router-link to="/comics" class="route-item"> Mac </router-link>

    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar-lower {
  display: flex;
  justify-content: center;
  height: 44px;
  background-color: rgb(51 51 51);
  color: rgb(214 214 214);
  width: 100%;
  margin: auto;
}
.route-item {
  margin: 0 18px;
  display: flex;
  align-items: center;
  color: #fff;
  height: 100%;
  box-sizing: border-box;
  border-bottom: 2px solid transparent;
  text-decoration: none;
  font-family: "SF Pro Text", "Myriad Set Pro", "SF Pro Icons", "Helvetica Neue",
    "Helvetica", "Arial", sans-serif;
  -webkit-font-smoothing: antialiased;
  font-size: 12px;
  line-height: 3.66667;
  font-weight: 400;
  opacity: 0.8;
  text-decoration: none;
  white-space: nowrap;
}
li {
  margin: 0 18px;
  display: flex;
  align-items: center;
  color: #fff;
  height: 100%;
  box-sizing: border-box;
  border-bottom: 2px solid transparent;
  text-decoration: none;
  font-family: "RobotoCondensed Bold", "Trebuchet MS", Helvetica, Arial,
    sans-serif;
  font-size: 12px;
}
ul {
  list-style-type: none;
}
</style>
