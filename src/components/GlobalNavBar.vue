<template>
  <nav>
    <ul>
      <li>
        <router-link class="rl" to="/"
          ><i class="fab fa-apple"></i
        ></router-link>
      </li>
      <li><router-link class="rl" to="/ImageSubmit">Mac</router-link></li>
      <li><router-link class="rl" to="/Price">iPad</router-link></li>
      <li><router-link class="rl" to="/MakeArticle">iPhone</router-link></li>
      <li><router-link class="rl" to="/MultiImg">Watch</router-link></li>
      <li><router-link class="rl" to="/Test">TV</router-link></li>
      <li><router-link class="rl" to="/Test">Music</router-link></li>
      <li><router-link class="rl" to="/Test">Service</router-link></li>
      <li>
        <router-link class="rl" to="/Learn"
          ><i class="fal fa-search"></i
        ></router-link>
      </li>
      <li>
        <router-link class="rl" to="/Learn"
          ><i class="fas fa-user-circle"></i
        ></router-link>
      </li>
    </ul>
  </nav>
  <router-view />
</template>

<style scoped>
nav {
  width: 100%;
  height: 45px;
  background: rgb(44, 44, 44);
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  z-index: 100;
}
nav ul {
  list-style: none;
  display: flex;
}
nav ul li {
  margin: 0 40px;
}
.rl {
  font-size: 13px;
  font-weight: 500;
  color: #cfcfcf;
  transition: 600ms;
}
.rl i {
  font-size: 14px;
  font-weight: 500;
  color: #cfcfcf;
  transition: 600ms;
}
.rl:hover {
  color: #ffffff;
}
.rl i:hover {
  color: #ffffff;
}
</style>
