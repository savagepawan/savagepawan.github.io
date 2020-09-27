# savagepawan.github.io
{
color:white;
margin:0;
}
#header
{background-color:#1abc9c;
height:50px;
line-height:50px;
}
#header-title{
display:block;
float:left;
font-size:20px;
font-weight:bold;
}
#header-nav{
display:block;
float:right;
}
#header-nav li {
display:inline;
padding-left:20px;
margin-top:0;
}
#header a{
color:white;
text-decoration:none;
text-transform:uppercase;
letter-spacing:0.1em
}
#header a:hover
{color:yellow;
}
.container{
max-width:1000px;
margin:0 auto;
}
#footer
{background-color:#2f2f2f;
padding:50px 0;
}
.column{
min-width:300px;
display:inline-block;
vertical-align:top;
}
#footer h4{
color:white;
text-transform:uppercase;
letter-spacing:0.1em;
}
footer p{
color:blue;
}
a{color:yellow;
text-decoration:none;
}
a:hover{
color:blue;
} 
 29  1stprojectweb.html 
@@ -0,0 +1,29 @@
<html>
<head>
<title>My Blog</title>
<link rel="stylesheet" type="text/css" href="1stproject.css">
</head>
<div id="header">
<div class="container">
<a id="header-title" href="index.html">My Blog</a>
<ul id="header-nav">
<li><a href="about.html">About</a></li>
<li><a href="mailto:me@me.com">Contact</a></li>
</ul>
</div>
</div>
<div id="footer">
<div class="container">
<div class="column">
<h4>My links</h4>
<p>
<a href="#">Twitter</a><br>
<a href="#">Facebook</a>
</p>
</div>
<div class="column">
<h4>My Story</h4>
<p><font color="red">Hi there! I'm an aspiring web developer.</p>
</div>
</div>
</div>
 91  assignment1.css 
@@ -0,0 +1,91 @@
{
color:white;
margin:0;
}
#header
{background-color:#1abc9c;
height:80px;
line-height:50px;
}
#header-title{
display:block;
float:left;
font-size:20px;
font-weight:bold;
}
#header-nav{
display:block;
float:right;
}
#header-nav li {
display:inline;
padding-left:20px;
margin-top:0;
}
#header a{
color:white;
text-decoration:none;
text-transform:uppercase;
letter-spacing:0.1em
}
#header a:hover
{color:yellow;
}
.container{
max-width:1000px;
margin:0 auto;
}


#footer
{background-color:#2f2f2f;
padding:50px 0;
}
.column{
min-width:300px;
display:inline-block;
vertical-align:top;
}
#footer h4{
color:white;
text-transform:uppercase;
letter-spacing:0.1em;
}
footer p{
color:white;
}
a{color:#abc9c;
text-decoration:none;
}
a:hover{
color:#f6A623;
}
.post{max-width:800px;
margin:0 auto;
padding:60px 0;
}
.post-author img{
width:50px;
border-radius:50%;
vertical-align:middle;
}
post-author span{
margin-left:16px;
}
.post-date{
color:blue;
font-size:14px;
font-weight:bold;
text-tranfom:uppercase;
letter-spacing:0.1em;
}
h1,h2,h3,h4 {
color:red;
}
p{
line-height:1.5;
}body{
margin:0;
color:green;
font-family:'montserrat',sans-serif;
}
 46  assignment1.html 
@@ -0,0 +1,46 @@
<html>
<head>
<link rel="stylesheet" type="text/css" href="assignment1.css" >
</head>
<div id="header">
<div class="container">
<a id="header-title" href="assignment1.css">My Blog</a>
<ul id="header-nav">
<li><a href="about.html">About</a></li>
<li><a href="mailto:me@me.com">Contact</a></li>
</ul>
</div>
</div>
<div id="content">
<div class="container">
<div class="post">
<div class="post-author">
<img src="me.jpg">
<span>Me</span>
</div>
<p class="post-date">Today</p>
<h3 class="post-title">Becoming a web developer</h3>
<div Class="post-content">
<p>If somebody would have told me a week a go that would be able to make a <strong>website</strong>, I would not have believed them.</p>
<p>Just a few days later , I came across <a href="https://getmimo.com">Mimo </a>and started to work on a <em>real</em> blog.</p>
<h1>me tooo
</div>
</div>
</div>
</div>
<div id="footer">
<div class="container">
<div class="column">
<h4>My links</h4>
<p>
<a href="#">Twitter</a><br>
<a href="#">Facebook</a>
</p>
</div>
<div class="column">
<h4>My Story</h4>
<p><font color="red">Hi there! I'm an aspiring web developer.</p>
</div>
</div>
</div>
