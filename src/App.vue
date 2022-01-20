<template>

  <div id="app">
    <div id="nav">
      <header>
        <ul>
          <li class="logo">PIM CODE</li>
          <li><router-link to="/port">Portfolio</router-link></li>
          <li><router-link to="/about">About Me </router-link></li>
          <li><router-link to="/">Home </router-link></li>
        </ul>
      </header>

        <!-- <li><router-link to="/">Home </router-link></li>
        <li><router-link to="/about">About Me </router-link> </li> -->

    </div>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&display=swap');

*{
  background-color: rgb(154, 148, 131);
}
#app{
  font-family: 'Playfair Display', serif;
}
li {
  display: inline;
  float: right;
}
.logo{
  margin-top: 11px;
  margin-left: 12px;
  display: inline;
  float: left;
  color:#F6E6CB;
}
/* a {
  display: block;
  padding: 10px;
  margin: 0;
  background-color: rgb(154, 148, 131);
} */
ul {
  list-style-type: none;
  margin-right: 30px;
  padding: 0;
  overflow: hidden;
}

li a {
   display: block; 
  color: rgb(229, 220, 195);
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
} 


/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: rgb(170, 164, 146);
}
/* header li router-link{
  transform: all 0.3s ease 0s;
} */
</style>
