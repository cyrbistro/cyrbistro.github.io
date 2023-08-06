<html>
<head>
<title>Courtyard Bistro</title>
<link rel="icon" type="image/x-icon"  href="courtyard.ico">
<style>
h1{
color: black;
font-family: sans-serif;
font-size: 30;
background-color: white;
margin: 25px 150px 25px 150px;
border-radius: 25px;
padding: 25px;
border-style: groove;
border-color: black;
}
body{
display: inline;
color: black;
font-size: 26;
background-color: lightgray;
text-align: center;
font-family: sans-serif;
background-image: url('bst1.jpg');
background-repeat: no-repeat;
background-size: cover;
}
p{
background-color: white;
padding: 25px;
font-size: 32;
font-family: sans-serif;
border-radius: 20px;
margin-left: 10px;
margin-right: 10px;
}
#hoursninfo{
background-color: white;
border: 2px solid darkgray;
font-size: 16;
margin-left: 150px;
margin-right: 150px;
border-radius: 16px;
}
button{
background-color: darkgray;
border: none;
color: black;
text-align: center;
border-radius: 8px;
padding: 15px;
opacity: 1.0;
font-family: sans-serif;
font-size: 13;
}
.q{
padding: 15px;
margin-left: 15px;
margin-right: 15px;
border-radius: 8px
}
#timed{
border: 2px solid gray;
margin-left: 200px;
margin-right: 200px;
font-size: 18;
opacity: .8;
background-color: white;
}
#static {
position: fixed;
  bottom: 25px;
  left: 25px;
  width: 200px;
}
img{
height: 100%;
width: 100%;
}
#sbux{
margin-left: 35px;
padding: 15px;
border-radius: 8px;
margin-right: 100px;
margin-top: 8px;
}
#row2{
margin-left: 85px;
}
#bgstyle{
background-color: 282828;
border-radius: 45px;
opacity: 0.9;
position: fixed;
left: 325px;
width: 700px;
height: 850px;
}
pre{
font-family: sans-serif;
}
</style>
</head>

<body>
<div id="bgstyle">
<h1>Welcome to	   The Bistro!</h1>
<p id="hoursninfo">
Dinner Hours are

<i><b>5PM-10PM</b></i>  Nightly



Breakfast Hours are

<i><b>6AM-10AM</b></i>  Mon-Fri

&

<i><b>7AM-11AM</b></i>  Sat-Sun
</p></pre>

<button type="button" onclick="breakMenu()">Click Here to See our Breakfast Menu </button>

<button type="button" class="q" onclick="dinnerMenu()">Click Here to See our Dinner Menu </button><pre>
</pre>
<pre><button id="row2" onclick="drinksMenu()"> Click Here to See our Drink Menu </button> <button id="sbux" onclick="starbucksMenu()">Click for We Proudly Serve Starbucks&reg</button></pre>
<pre>
</pre><button onclick="window.location.href='https://www.marriott.com/en-us/hotels/psccy-courtyard-richland-columbia-point/overview/','_self';">Click Here to return to the main website.</button>
<div id="static"><img src="logo.png"></div>
</body>
</html>
