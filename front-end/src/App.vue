<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css2?family=Lexend+Zetta&display=swap" rel="stylesheet">
    <div id="menu">
      <div id="logoContainer">
        Logo goes here
      </div>
      <div id="nav">
        <router-link to="/">HOME</router-link>
        <router-link to="/projects">PROJECTS</router-link>
        <router-link to="/contact">CONTACT</router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>

:root {
  --black: #080208;
  --plum: #261f3e;
  --lt-plum: #3b3356;
  --purple-highlt: #777aa9;
  --white: #eee;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: var(--black);
  color: var(--white);
  padding-bottom: 50%;
}

body {
  margin: 0px;
  background: var(--black);
}

#menu {
  display: flex;
  flex-direction: row;
  padding: 2% 3% 3% 3%;
  justify-content: space-between;
  font-family: 'Lexend Zetta', sans-serif;
  font-size: 70%;
}

#logoContainer {
  width: 60%;
  text-align: left;
}

#nav {
  display: flex;
  justify-content: space-between;
  width: 40%;
}

#nav a {
  font-weight: bold;
  color: var(--white);
  text-decoration: none;
  padding: 0px 5px 6px 5px;
  margin-left: 8%;
}

#nav a.router-link-exact-active {
  color: var(--purple-highlt);
  border-bottom: 3px solid;
}
</style>
