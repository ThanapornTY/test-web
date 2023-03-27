<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="icon-con">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQb3P_QsFHgyFH5J3eH_dBE8cjlsvN8udJU57CPzhoUKK8iAxvHxuY5LZ5vtjV9639Wuvk&usqp=CAU" alt="">
    </div>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink> | 
        <RouterLink to="/about">About</RouterLink> | 
        <router-link to="/testTem">testTem</router-link>
        <router-link to="/singin"></router-link> | 
        <router-link to="/LogIn"><button>login</button></router-link>
      </nav>
    </div>
  </header>

  
<div class="con">
  <RouterView/>
</div>
  
</template>

<style scoped>

.wrapper{
  width: 100%;
  background-color: rgb(255, 255, 255);
  padding: 1rem;
  /*border-radius:  0px 0px 20px 20px;*/
  text-align: center;
  box-shadow: 5px 2px 2px 0px rgba(0, 0, 0, 0.25);
  position:relative;
  
}
.wrapper button{
  background-color: aquamarine;
  width: 70px;
  height: 30px;
  border-radius: 10px;
}
.wrapper button:hover{
  background-color: rgb(74, 90, 84);
  transition: 0.50s;
  color: aliceblue;
  width: 70px;
  height: 30px;
  border-radius: 10px;
}
.icon-con img{
  position:relative;
  height: 50px;
  border-radius: 50%;
  left: 50%;
  margin-top: 1rem;
}

.name-con h1{
  color: antiquewhite;
  padding: 1rem;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

</style>
