<template>
  <nav id="navbar">
    <router-link to="/" class="link" id="home">Home</router-link>
    <p id="line"> | </p>
    <router-link to="/about" class="link" id="about">About</router-link>
  </nav>

  <router-view />
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

#navbar {
  width: 100%;
  height: 40px;
  margin: auto;
  padding-top: 2px;
  display: flex;
  justify-content: center;
  background-image: linear-gradient(to right,  rgb(5, 52, 93), rgb(182, 13, 74));
  font-family: Lucida Console;
}

.link {
  margin: 0px 40px 0px 0px;
  margin: auto;
  display: flex;
  justify-content: center;
  text-decoration: none;
  color: white;
  font-size: 30px;
}

.link:hover {
  color: rgb(5, 52, 93);
}

#home:hover{
color: rgb(182, 13, 74);
}

#line{
  color: white;
}

#about:hover{
  color: rgb(5, 52, 93);
}
</style>
