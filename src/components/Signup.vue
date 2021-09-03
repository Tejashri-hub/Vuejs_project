<template>
  <div class="yes">
    <p id="paratwo">
      Sign up for free access<br />to a community of Knowledge!
    </p>
    <form id="form" action="#" method="post">
      <input
        id="three"
        type="text"
        name="name"
        placeholder="Enter your full name"
      />
      <br />

      <input
        id="four"
        type="text"
        name="username"
        placeholder="Create a Username for Yourself"
      />
      <br />

      <input
        id="five"
        type="password"
        name="password"
        placeholder="Set a password"
      />
      <input id="fiveone" type="password" placeholder="confirm password" />
      <br />

      <input
        id="six"
        type="email"
        name="email"
        placeholder="Enter valid email address"
      />
      <br />
      <input id="seven" type="checkbox" />
      <label>
        <a href="#"> I agree with terms and conditions</a>
      </label>
      <br />
      <button id="in">Sign Up!</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "Signup",
};
</script>

<style scoped>
.yes {
  width: 700px;
  height: 350px;
  margin-left: 40px;
}

#paratwo {
  color: orangered;
  font-size: 24px;
  font-weight: bold;
}

#three {
  margin-top: 20px;
  padding: 8px;
  width: 680px;
  border-radius: 3px;
  border: transparent;
  background: rgb(218, 218, 218);
}

#four {
  margin-top: 10px;
  padding: 8px;
  width: 680px;
  border-radius: 3px;
  border: transparent;
  background: rgb(218, 218, 218);
}
#five {
  margin-top: 10px;
  padding: 8px;
  width: 329px;
  border-radius: 3px;
  border: transparent;
  background: rgb(218, 218, 218);
}
#fiveone {
  margin-top: 10px;
  padding: 8px;
  width: 325px;
  border-radius: 3px;
  border: transparent;
  background: rgb(218, 218, 218);
  margin-left: 10px;
}
#six {
  margin-top: 10px;
  padding: 8px;
  width: 680px;
  border-radius: 3px;
  border: transparent;
  background: rgb(218, 218, 218);
}

#seven {
  margin-top: 20px;
}

#in {
  margin-top: 30px;
  margin-left: 0;
  padding: 8px;
  width: 150px;
  font-size: 19px;
  font-weight: bold;
  color: white;
  background: rgb(39, 12, 102);
  border-radius: 3px;
}
</style>