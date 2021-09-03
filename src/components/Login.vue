<template>
  <div class="login">
    <p>Already Signed Up?</p>
    <input id="one" type="text" placeholder="Username" />
    <br />
    <input id="two" type="password" placeholder="password" />
    <br />
    <button type="submit">Log in</button>
    <br />
    <a href="">Forgot Password</a>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>

<style scoped>
.login {
  background: white;
  float: right;
  width: 350px;
  height: 290px;
  margin-top: 0px;
  margin-left: 20px;
  border-radius: 7px;
  border: 2px solid rgb(37, 37, 37);
  box-shadow: 5px 10px #1b1a1a;
}

.login p {
  margin-top: 20px;
  margin-left: 70px;
  font-size: 24px;
  font-weight: bolder;
  color: rgb(39, 12, 102);
  font-weight: bold;
}

#one {
  margin-top: 15px;
  margin-left: 20px;
  padding: 15px;
  width: 280px;
  border: transparent;
  background: rgb(221, 221, 221);
}

#two {
  margin-top: 15px;
  margin-left: 20px;
  padding: 15px;
  width: 280px;
  border: transparent;
  background: rgb(218, 218, 218);
}

button {
  margin-top: 30px;
  margin-left: 110px;
  padding: 8px;
  width: 150px;
  font-size: 19px;
  font-weight: bold;
  color: white;
  background: rgb(39, 12, 102);
  border-radius: 3px;
}

a {
  margin-top: 1px;
  margin-left: 135px;
  font-size: 15px;
}
</style>