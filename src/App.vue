<template>
  <NavBar />
  <div class="hello">
    <Image />
    <div class="hello1">
      <Signup />
      <Login />
    </div>
  </div>
</template>

<script>
import Login from "./components/Login.vue";
import Signup from "./components/Signup.vue";
import NavBar from "./components/NavBar.vue";
import Image from "./components/Image.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Signup,
    Login,
    Image,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
.hello {
  background-image: linear-gradient(
    rgba(12, 209, 101, 0.3),
    rgba(0, 0, 0, 0.5)
  );
  background-repeat: no-repeat;
  background-size: cover;
  background-position: fixed;
  width: 1160px;
  height: 450px;
  margin-left: 230px;
  margin-top: 100px;
  border-radius: 10px;
  box-shadow: 5px 10px 5px #525050;
}

.hello .hello1 {
  display: flex;
}
</style>
