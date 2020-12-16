<template>

    <header class="header">
      <div class="header-logo"><img src="/printasite-logo.png" alt=""></div>

        <ul class="header-menu">
          <div class="dropdown">
            <a class="dropbtn">Разработка сайтов</a>
            <div class="dropdown-content">
              <a href="#">Интернет магазин</a>
              <a href="#">Корпоративный сайт</a>
              <a href="#">Landing page</a>
              <a href="#">Сайт визитка</a>
              <a href="#">Дизайн сайта</a>
            </div>
          </div>
            <li><nuxt-link to="./portfolio">Портфолио</nuxt-link></li>
            <li><nuxt-link to="./contacts">Контакты</nuxt-link></li>
        </ul>
  
      <div class="callback">
        <a href="">Обратный звонок</a>
      </div>
    </header>
</template>

<style>

.header a{
  text-decoration: none;
  color: #fff;
  outline: none;
  -webkit-transition: color 0.2s ease-in-out;
  -moz-transition: color 0.2s ease-in-out;
  -ms-transition: color 0.2s ease-in-out;
  -o-transition: color 0.2s ease-in-out;
  transition: color 0.2s ease-in-out;
  margin: 0;
  padding: 0;
  font-family: "Roboto slab", sans-serif;
  font-size: 16px;
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
  outline: 0;
  overflow-x: hidden;
  overflow-y: auto;
}
.callback{

  display: block;
  float: left;
  height: 48px;
  margin-top: 6px;
  padding: 10px 25px;
  cursor: pointer;
  border: 2px solid #fff;
  margin-right: 20px;

}
.header-menu{
  display: flex;
  justify-content: space-between;
  font-family: "Roboto slab", sans-serif;
  padding: 18px 20px;
  min-width: 400px;
  list-style:none
}

.header-logo img{
  width: 87%;
  margin-left: 20px;
}
.header{
  display: flex;
  justify-content: space-between;
  background-color: rgba(0, 0, 0, 0.6);
  visibility: visible;
  opacity: 1;
  position: relative;
  box-sizing: border-box;
  color: #fff;
  max-height: 60px;

}
.dropdown{
  min-height: 43px;

}


/* Dropdown Button */

/* The container <div> - needed to position the dropdown content */


/* Dropdown Content (Hidden by Default) */
.dropdown-content {
    display: none;
    position: absolute;
    background-color: rgba(17, 17, 17, 0.5);
    margin-top: 18px;
    width: 400px;
    text-align: center;
}

/* Links inside the dropdown */
.dropdown-content a {
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    padding: 10px 20px;
    font-size: 18px;
    color: #ffffff;
}


/* Change color of dropdown links on hover */
.dropdown-content a:hover {font-size: 17px;}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {font-size: 17px;}
</style>

