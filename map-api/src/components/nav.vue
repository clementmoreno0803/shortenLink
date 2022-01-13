<template>
  <nav>
    <img src="../assets/logo.svg" alt="" />
    <div id="links">
      <div id="menu">
        <ul>
          <li><a href="#">Features</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Ressources</a></li>
        </ul>
      </div>
      <div id="login">
        <ul>
          <li><a href="#">Login</a></li>
          <li><a href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<style>
nav {
  display: flex;
  align-items: center;
  height: 100px;
}
#links {
  width: 95%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  height: 250px;
  width: 500px;
}

ul {
  display: flex;
  margin: 0;
  align-items: center;
}
ul li {
  list-style: none;
  margin-left: 25px;
}

#login li:last-child a:last-child{
  background: var(--primary);
  list-style: none;
  padding: 10px 30px;
  border-radius: 25px;
  color:white;
}
a {
  font-family: "Poppins";
  font-size: 0.775em;
  color: rgb(191, 191, 191);
  text-decoration: none;
}
</style>
