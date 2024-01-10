# This is the webpage for  a Hospital using Html and CSS

## Getting Started

### Html Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="new2.css" />
    <title>hospital</title>
  </head>
  <body>
    <header class="header">
      <nav class="menu">
        <ul>
          <li><a href="#">Home</a></li>
          <li>
            <a href="#">Specialities</a>
            <ul>
              <li><a href="image.jpg">ENT, Neck Surgery</a></li>
              <li><a href="img.jpg">Radio Diagnosis</a></li>
              <li><a href="image.jpg">Gynaecology</a></li>
              <li><a href="img.jpg">Physiotherapy</a></li>
              <li><a href="image.jpg">Ophthalmology</a></li>
              <li><a href="img.jpg">Dermatology</a></li>
            </ul>
          </li>
          <li><a href="#about">About us</a></li>
          <li><a href="img.jpg">Medical Package</a></li>
          <li>
            <a href="image.jpg">Services</a>
            <ul>
              <li><a href="img.jpg">At Home Service</a></li>
              <li><a href="image.jpg">Book HealthCheckup</a></li>
            </ul>
          </li>
          <li><a href="fb.jpeg">Health Library</a></li>
          <li><a href="Carrer.html">Career</a></li>
          <li><a href="cont.html">Make an appointment</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <div class="a1">
        <h1>Healthy-life hospital</h1>
        <p>Hope . Care . Love</p>
        <button>Learn More</button>
        <br><button><a href="reg.html"id="r">Register With Us</a></button>
      </div>
      <div class="a2">
        <div class="a3">
          <p class="a3-heading">2,600</p>
          <p class="a3-text">Beds</p>
        </div>
        <div class="a3">
          <p class="a3-heading">80</p>
          <p class="a3-text">Fully Networked Modular Operation Theatres</p>
        </div>
        <div class="a3">
          <p class="a3-heading">50</p>
          <p class="a3-text">Specialities</p>
        </div>
       
      </div>
      <div id="about"class="about">
        <div class="about-text">
          <h1>About Us</h1>
          <p>
            Hope. Care. Love. These are the words that form the cornerstone of
             our  medical institution—Healthy-life- Hospitals. Born out
            of Amm benevolence, our Hospitals value care as much as
            science. Here, patients are always viewed as people and will always
            be at the core of all decisions. We are an institution of healing
            where everyone is welcome, irrespective of race, gender, religion,
            or economic status. We are a healthcare centre that believes service
            to humanity comes above all else. 
          </p>
        </div>
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3dbkFOpaRY4l5VHTHGXh3jexVjTMOlMYFlQ&usqp=CAU"
          alt="me"
        />
      </div>
    </main>
    <footer class="footer">
      <div class="copy">Copyright &copy; 2022 Healthy-life Hosptial | All Rights
        Reserved</div>
      <div class="bottom-links">
        <div class="links">
          <span>More Info</span>
          <a href="#">Address</a>
          <a href="#">About</a>
          <a href="cont.html">Contact Us</a>
        </div>
        <div class="links">
          <span>Social Links</span>
          <div class="image">
            <img src="insta.jpeg" alt="follow on instagram">
            <img src="fb.jpeg" alt="follow on facebook">
            <img src="tele.jpeg" alt="join on telegram">
            <img src="whatsapp.jpeg" alt="whatsapp">
        
      </div>
  </body>
</html>
```
### CSS code 
```
*
{
  margin: 0%;
  padding: 0%;
}
body {
  margin: 0;
  box-sizing: border-box;
}
/* CSS for header */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #f5f5f5;
}

.header .logo {
  font-size: 25px;
  font-family: 'Sriracha', cursive;
  color: #000;
  text-decoration: none;
  margin-left: 30px;
}

.menu {
  margin-top: 40px;
  position: fixed;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #f5f5f5;
  margin-right: 20px;
}

.menu ul

{
    margin:10px;
padding: 0%;
list-style-type:none;
position: relative;
margin-left: 0%;

}
.menu ul li{
    padding: 0%;
    margin: 0%;
    background-color:rgb(0, 81, 128);
	/*border:2px solid white;*/
	width:164.8px;
	height:40px;
 
    text-align:center;
	line-height:40px;
	float:left;
}
.menu ul ul{
display: none;
position: absolute;
top: 100%;
padding-left:0%;
}
.menu ul ul li
{
    padding:0%;
    width:170px;
	height:50px;
float:none;
display: block;
}
.menu ul li:hover>ul
{
display: block;
}
.menu>ul::after
{
content: " ";
display: block;
clear: both;
}
.menu ul li:hover>a
{
    background-color: aliceblue;
color: rgb(6, 6, 6);
}
.menu ul li a
{
 color:azure;
text-align: center;
display: block;
width: 100%/*84%*/;
padding:0.07em 0.8em 0.6em 1.05em;
background-color:rgb(0, 81, 128);
}



.a1 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%/*97.9%*/;
  height: 565px;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.5) 100%), url("https://shardahospital.org/assests/images/slider-1.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.a1 h1 {
  font-family: sans-serif;
  font-size: 60px;
  color: #fff;
  font-weight: bold;
  text-transform: uppercase;
  margin: 0;
}

.a1 p {
  font-size: 20px;
  color: #d1d1d1;
  text-transform: uppercase;
  margin: 20px 0;
}

.a1 button {
  font-size: medium;
  background-color: #5edaf0;
  color: #000;
  padding: 9px 20px;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  cursor: pointer;
  box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4)
}
#r{
  text-decoration: none;
  color: black;
}
.a2 {
    /*width:86.1%*/
    background-color: rgb(88, 127, 150);
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 40px 80px;
}

.a2 .a3 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 40px;
}

.a2 .a3 i {
  width: fit-content;
  font-size: 50px;
  color: #fffbfb;
  border-radius: 50%;
  border: 2px solid #fffbfb;
  padding: 12px;
}

.a2 .a3 .a3-heading {
  font-size: 40px;
  color: #f1ebeb;
  text-transform: uppercase;
  margin: 10px 0;
}

.a2 .a3 .a3-text {
  font-size:larger;
  font-weight: bold;
  color: #fffbfb;
  margin: 10px 0;
}

.about{

  display: flex;
  justify-content: center;
  align-items: center;
  padding: 40px 80px;
  border-top: 2px solid #eeeeee;
}

.about img {
  width: 500px;
  max-width: 100%;
  height: 300px;
  border-radius: 10px;
}

.about-text h1 {
  font-size: 60px;
  color: #3f1f55;
  text-transform: uppercase;
  margin: 0;
}

.about-text p {
  font-size: 15px;
  color: #585858;
  margin: 10px 0;
}
.footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #302f49;
  padding: 40px 80px;
}

.footer .copy {
  color: #fff;
}

.bottom-links {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 40px 0;
}

.bottom-links .links {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 40px;
}

.bottom-links .links span {
  font-size: 20px;
  color: #fff;
  text-transform: uppercase;
  margin: 10px 0;
}

.bottom-links .links a {
  text-decoration: none;
  color: #a1a1a1;
  padding: 10px 20px;
}
.footer .image img{
  width:20px;
  height:20px;
  padding: 5px;
  float:right;}
```


