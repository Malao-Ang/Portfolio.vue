<template>

  <div id="app">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <div id="nav">
      <header>
        <ul>
          <li class="logo">PIM CODE</li>
          <li>
            <div class="nav">
              <button class="dropdown-button">Portfolio 
                <i class="fa fa-caret-down"></i>
                </button>
                <div class="dw-content">
                  <a href="/port">Portfolio Menu </a>
                  <a href="/port#cernificate">Certificates</a>
                  <a href="/port#Photos" >Photos</a>
                  <a href="/port" >Project</a>
              </div>
            </div>
          </li>
          <li><router-link to="/about">About Me </router-link></li>
          <li><router-link to="/">Home </router-link></li>
        </ul>
      </header>
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
.nav{
  float: left;
  overflow: hidden;
}
.nav a{
  float: left;
  overflow: hidden;
}


.nav .dropdown-button {
  text-decoration: none;
  border:none;
  outline: none;
  color: #F6E6CB;
  font-family: 'Playfair Display', serif;
  font-size:16px;
  padding: 14px 16px;
}
.nav:hover .dropdown-button {
  background-color: rgb(170, 164, 146);
}
.dw-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.nav:hover .dw-content {
  display: block;
}
.dw-content a {
  float: none;
  color: #F6E6CB;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
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