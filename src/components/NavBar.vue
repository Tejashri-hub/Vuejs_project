<template>
  <div class="nav">
    <div class="logo">
      <img
        src="https://inprospecttechnologies.in/img/logo_tag.4fa451af.png"
        alt="logo"
      />
    </div>
    <input type="text" id="search" placeholder="Search...." />
    <div class="home">
      <a href="#"><i id="home" style="color: white" class="fas fa-home"></i></a>
    </div>
    <button>Log in</button>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  props: ["img"],
};
</script>

<style scoped>
.nav {
  display: flex;
  background: rgb(52, 50, 80);
  height: 60px;
}

.nav .logo img {
  margin-left: 150px;
  height: 50px;
  width: 170px;
  margin-top: 5px;
}

.nav input {
  margin-left: 200px;
  height: 20px;
  margin-top: 17px;
  width: 380px;
}

.nav a #home {
  margin-left: 60px;
  margin-top: 23px;
}

.nav button {
  margin-left: 400px;
  height: 35px;
  margin-top: 14px;
  width: 80px;
  background: rgb(235, 94, 43);
  border-radius: 4px;
  font-weight: bold;
  color: white;
}
</style>