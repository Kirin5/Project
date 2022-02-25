<template>
  <div id="nav">
    <router-link to="/">消息</router-link> |
    <router-link to="/about">考试</router-link>|
    <router-link to="/Me">我</router-link>
  </div>
  <div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 580px;
  width: 360px;
  background-color: rgba(235, 235, 227, 0.938);
  display: flex;
  flex-direction: column-reverse;
}
#nav {
  padding: 30px;
  background-color: rgb(125, 136, 135);
  display: flex;
  justify-content: space-around;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
