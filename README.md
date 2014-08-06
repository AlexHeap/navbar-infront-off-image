navbar-infront-off-image
========================

very simple navigation bar with very little styling, centred with fixed position to allow next div to appear behind. 

-html-

<!DOCTYPE html>
<head>
      <meta http-equiv='Content-Type' content='text/html; charset=UTF-8'>
      <title>general html</title>
      <link href="stylesheets/screen.css" rel="stylesheet" type="text/css" />
</head>

<body>
	<div id="navbar">	
		<ul>
			<li><a href="home">Home</a></li>
	  		<li><a href="about us">About</a></li>
	  		<li><a href="contact">Contact</a></li>
	 		<li><a href="Store">Store</a></li>
		</ul>
	</div>

	<div class="main-slide-image">
	</div>
</body>

</html>


-CSS- code also available in sass(check above)

#navbar {
  width: 500px;
  margin: 0 auto;
  background-color: green;
  position: fixed;
  left: 0;
  right: 0; }
  #navbar ul {
    list-style-type: none;
    z-index: 1000;
    text-align: center; }
  #navbar li {
    display: inline-block; }
    #navbar li a {
      width: 60px;
      margin: 0em 0.5em 0em 0.5em; }

.main-slide-image {
  height: 100px;
  background-color: red; }
