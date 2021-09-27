<html lang="en">
<head>
<title>My Page</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.banner {
position: absolute;
top: 10px;
left: 10px;
color: #00FFC1;
font-weight: 700;
}
.nav {
position: absolute;
top: 25px;
right: 10px;
}
a {
color: #000000;
text-decoration: none;
font-size: 14px;
}
.content {
position: absolute;
top: 60px;
left: 15px;
}
button {
position: absolute;
top: 160px;
left: 1px;
background: #9C9C9C;
width: 0 auto;
height: 30px;
border: none;
outline: none;
}
.about-us-container {
display: table;
opacity: 0;
y-index: -1;
transition-duration: 3s;
position: fixed;
top: 70px;
left: 0;
width: 100%;
height: auto;
background: #000000;
}
.about-us-content {
text-align: center;
color: #ffffff;
}
.about-us-container:target {
opacity: 1;
y-index: 1;
}
.back {
color: #1500FF;
}
</style>
</head>
<body>

<div class="banner">beau</div>

<div class="nav">
<a href="#">How it Works</a>
&nbsp;
<a href="#about-us">About Us</a>
&nbsp;
<a href="#">Start Free Trial</a>
</div>

<div class="content">
<h3>No-Code Client <br>
Worksflows</h3>
<p>Build, visualize, automate worksflows, <br>
and design a path to guide clients <br>
throught your processes, step by step.</p>
<button>Start Free Trial</button>
</div>

<div class="about-us-container"id="about-us">
<div class="about-us-content">
<p>
Credits by: <br>
-GOOGLE LCC-
<br>
-BEAU-
<br><br>
Designed by: <br>
-Jin Kazama-
<br><br>
Copyrights © 2021 - All rights reserved
<br><br>
<a href="#"class="back"><b>[BACK]</b></a>
</p>
</div>
</div>

</body>
</html>
