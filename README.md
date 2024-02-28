<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Navigation Bar</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  .navbar {
    background-color: #333;
    overflow: hidden;
  }
  .navbar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
  }
  .navbar a:hover {
    background-color: #555;
  }
  .navbar .dropdown {
    float: left;
    overflow: hidden;
  }
  .navbar .dropdown .dropbtn {
    font-size: 16px;
    border: none;
    outline: none;
    color: white;
    padding: 14px 20px;
    background-color: inherit;
    margin: 0;
  }
  .navbar .dropdown-content {
    display: none;
    position: absolute;
    background-color: #333;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }
  .navbar .dropdown-content a {
    float: none;
    color: white;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
  }
  .navbar .dropdown-content a:hover {
    background-color: #555;
  }
  .navbar .dropdown:hover .dropdown-content {
    display: block;
  }
</style>
</head>
<body>

<div class="navbar">
  <a href="#home">Home</a>
  <div class="dropdown">
    <button class="dropbtn">Products 
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <a href="#">Product 1</a>
      <a href="#">Product 2</a>
    </div>
  </div> 
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</div>

</body>
</html>
