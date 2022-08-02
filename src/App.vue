<template>
<nav id="navbar">
  <router-link to="/" class="link">Home</router-link>
  <p class="link"> | </p>
  <router-link to="/about" class="link">About</router-link>
</nav>
  <router-view/>
</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
}

#navbar{
  width: 220px;
  height: 40px;
  margin: auto;
  display: flex;
  justify-content: center;
  border: 1px solid rgb(5, 52, 93);
  border-radius: 3px;
}

.link{
  margin: 0px 40px 0px 0px;
    margin: auto;
  display: flex;
  justify-content: center;
  text-decoration: none;
color: rgb(182, 13, 74);
}

.link:hover{
color: rgb(5, 52, 93);
font-size: 25px;
}
</style>
