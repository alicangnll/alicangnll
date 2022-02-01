<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Josefin Sans', sans-serif;
  font-weight: 500;
  line-height: 1.1;
}
.container {
max-width: 100%;   
background: #fff;
margin: 0px auto 0px;
border-radius: 3px;  
padding: 0;
margin-top: 50px;
}
@media only screen and (min-width: 1200px) {
.container {
    width: 1170px;
}
}
@media only screen and (max-width: 1200px) {
.container {
width: 1170px;
}
}
.data {
text-align: center;
padding: 45px;
}
.img {
top: 50%;
left: 50%;
padding: 15px;
border-radius: 140px;
width: 250px;
height: 250px;
}
h1 {
color: black;
margin-bottom: 15px;
font-size: 36px;
}
hr {
color: black;
}
.tamad {
font-size: 15px;
text-transform: uppercase;
margin-bottom: 5px;
color: black;
}
small {
color: black;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
  padding-left: 5%;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #315472;
  color: white;
}
.socia {
padding: 15px;
text-align: center;
}
.socia-but {
padding: 15px;
}
.fa {
color: black;
}
.fa:hover {
color: #315472;
}
</style>
<script>
var i = 0;
var txt = 'Web Developer & Cyber Security Expert';
var speed = 50;

function typeWriter() {
  if (i < txt.length) {
    document.getElementById("desc").innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, speed);
  }
}
$(document).ready(function() {
setTimeout(typeWriter(), 4000);
});
</script>
