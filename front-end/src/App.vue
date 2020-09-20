<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css2?family=Lexend+Zetta&display=swap" rel="stylesheet">
    <div id="menu">
      <div id="logoContainer">
        <router-link to="/">NATWORTH</router-link>
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
  font-size: 170%;
}

#logoContainer a {
  color: var(--white);
  text-decoration: none;
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

/* Mobile Styles */
@media only screen and (max-width: 601px) {

  #logoContainer {
    width: 30%;
    text-align: left;
    font-size: 120%;
  }

  #nav {
    display: flex;
    justify-content: space-between;
    width: 70%;
  }

  #nav a {
    font-weight: bold;
    color: var(--white);
    text-decoration: none;
    padding: 0px 5px 6px 5px;
  }

  #menu {
    display: flex;
    flex-direction: row;
    padding: 2% 3% 3% 3%;
    justify-content: space-between;
    font-family: 'Lexend Zetta', sans-serif;
    font-size: 70%;
    margin-left: 5%;
    margin-right: 5%;
  }

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    background: var(--black);
    color: var(--white);
    padding-bottom: 50%;
    padding-top: 2%;
  }

}

/* V small phones */
@media only screen and (max-width: 451px) {

  #logoContainer {
    width: 60%;
    text-align: center;
    font-size: 170%;
    margin-bottom: 10%;
  }

  #menu {
    display: flex;
    flex-direction: column;
    padding: 2% 3% 3% 3%;
    justify-content: center;
    align-items: center;
    font-family: 'Lexend Zetta', sans-serif;
    font-size: 70%;
  }

  #nav a {
    font-weight: bold;
    color: var(--white);
    text-decoration: none;
    padding: 0px 5px 6px 5px;
    margin-left: 4%;
    margin-right: 4%;
  }

  #nav {
    display: flex;
    justify-content: center;
    width: 70%;
  }
}

</style>
