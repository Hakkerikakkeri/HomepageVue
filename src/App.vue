<template>
<div id="nav">
  <router-link class="nav-link" to="/">Home</router-link>
  <router-link class="nav-link" to="/about">About</router-link>
</div>
  <router-view/>
</template>

<style>
#nav{
  font-family: 'DM Sans', sans-serif;
  color: white;
  float: right;
  margin-top: 15px;
  margin-right: 15px;
}

.nav-link{
  color: white;
  text-decoration: none;
  margin: 10px;
}

#nav a.router-link-exact-active {
  color: var(--accent);
}
</style>
