<template>
  <div class="navbar">
    <div class="topnav">
      <a href="#"><img src="../assets/Todo.png" width="15"></a>	
      <a href="#"><img src="../assets/chat.png" width="15"></a>	
    	<a href="#"><img id="c" src="../assets/mail.png" width="15"></a>	
      <a href="#"><img id="d" src="../assets/calendar.png" width="15"></a>
      <a href="#"><img src="../assets/star.png" width="15">	</a>

        <div class="topnav-right">
          <a href="#"><p>English</p></a>
          <a><img src="../assets/bell.png" width="15"></a>
          <a><img src="../assets/search2.png" width="15"></a>
          <a href="#"><p>John Doe Available</p></a>
          <a href="#"><img src="../assets/Oval3.png" width="35"></a>
        </div>
    </div>

  <div class="card">
            <div class="carde">
							<span >Card Actions</span> &nbsp;
							<span ><img src="../assets/bar.png" id="bar" height="28px"></span> &nbsp;
							<span ><img src="../assets/home.png" width="15px" height="15px" ></span>&nbsp;
							<span > <a href="#">&raquo; </a></span>&nbsp;
							<span ><img src="../assets/eCommerce.png"></span>&nbsp;
							<span > <a href="#">&raquo; </a></span>&nbsp;
							<span class="elect">Electronics</span>
            </div>
							<div><img src="../assets/settings.png" id="setting" width="25"></div>
    </div>
    <br />
    <div class="default">
      <span class="left">
  		  <p>7,618 results found in 5ms</p>
    	</span>
  	  <span class="right">
        <div class="dropdown">
          <button class="dropbtn">Default <span class="caret"></span></button>
          <div class="dropdown-menu">
              <a href="#">HTML</a>
              <a href="#">CSS</a>
          </div> 
        </div>
        <a href="#"><img src="../assets/Grid3.png" height="40"/></a> <a href="#"><img src="../assets/list.png" height="40"/></a>
  	  </span>
    </div>
    <div class="search">
      <input type="text" placeholder="Search here">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>
<style scoped>
.left {
  float: left;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 20px;
  color: #2C2C2C;
  margin-top: 40px;
  margin-left: -152px;
}
.right {
  float: right;
  margin-top: 30px;
}
.elect {
  font-size: 11px;
  line-height: 17px;
  color: #2C2C2C;
}
.default {
  margin-top: 5px;
  width: 700px;
  float: right;
  margin-right: -25px;
}
.search input[type=text] {
  width: 830px;
  float: right;
  padding: 8px;
  background: #FFFFFF;
  box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216); 
  border-radius: 8px;
  margin-right: 5px;
  margin-top: 1px;
  font-family: Montserrat;
  font-weight: 200;
  font-size: 14px;
  line-height: 27px;
   outline: none;
   background-image: url("../assets/base.png");
   background-repeat: no-repeat;
   background-position: right center;
   
}
.dropdown {
  position: relative;
  display: inline-block;
  top: -15px;
}
.dropbtn {
  width: 110px;
  height: 30px;
  background-color: #FFFFFF;
  border: 1px solid transparent;
  cursor: pointer;
  font-size: 12px;
  padding: 5px 18px;
  box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
  border-radius: 8px;
}

.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  min-width: 160px;
  padding: 8px 0;
  background: white;
  box-shadow: 0 1px 8px 2px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown-menu a {
  color: #444;
  padding: 10px 16px;
  text-decoration: none;
  display: block;
}

.dropdown:hover .dropdown-menu {
  display: block;
}

.dropdown-menu a:hover {
  background-color: #e9e9e9;
}

.caret {
  display: inline-block;
  float: right;
  margin-left: 15px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
  margin-top: 5px;
  margin-right: 0px;
}

.topnav {
  overflow: hidden;
  height: 50px;
  width: 1130px;
  background: #FFFFFF;
  box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
  border-radius: 8px;
  margin-top: 19px;
}

.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 16px 2px;
  margin-left: 10px;
  text-decoration: none;
  font-size: 10px;
}
.topnav p {
  font-size: 10px;
  width: 45px;
  padding-bottom: 18px;
  color: black;
}
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
.topnav-right {
  float: right;
  width: 230px;
  height: 30px;
  text-align: justify;
  padding: -10px 2px;
  line-height: 10px;
}
.card {
  padding: 0px 2px;
  margin-left: 10px;
}
.card a {
  text-decoration: none;
font-size: 14px;
}
.carde {
  float: left;
  margin-top: 12px;
  margin-left: -12px;
}
#setting{
  position: relative;
	border-radius: 50%;
	background: #7E72F2;
  display: block;
  float: right;
  margin-top: 15px;
}
#bar {
  border: 1px #979797;
}
</style>
