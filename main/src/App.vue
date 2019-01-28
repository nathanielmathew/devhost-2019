<template>
  <div id="App">
    <ul id="Navbar">
      <div id="NavElements"><div id="NavLeft">devhost<p id="nineteen">:19</p></div>
        <div id="NavRight">
          <li><a href="Home.asp">Home</a></li>
          <li><a href="Event.asp">Event</a></li>
          <li><a href="Support.asp">Support</a></li>
          <li><a href="About.asp">About us</a></li>
        </div>
      </div>
    </ul>
  </div>
</template>

<style>
#App{
  font-family: sans-serif;
}

ul {
  width: 100%;
  list-style-type: none;
  margin: 0 ;
  padding: 10px ;
  background: #130e25;
  display: inline-block;
  border-radius: 10px 10px;
}

#NavElements{
  width: 95%;
  color: white;
  font-family: sans-serif;
  padding: 15px 25px;
}
#NavLeft{
  font-size: 39px;
}

#NavRight{
  font-size: 30px;
}
#nineteen{
  color: #50fd51;
}
li{
  float: right;
  padding: 0px 0px 0px;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 5px 20px;
  text-decoration: none;
}
li a:hover:not(.active) {
  color: #50fd51;
}
#NavLeft, #NavRight,#nineteen
{
    display:inline;
}
</style>
