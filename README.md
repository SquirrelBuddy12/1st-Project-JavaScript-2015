# 1st-Project-JavaScript-2015
Pancake House 1st Project
<!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link href="js_styles.css" rel="stylesheet" type="text/css" />
<title>Rebecca's Pancake House</title>
</head>
<body>
<header>
<h1>Rebecca's Pancake House</h1>
</header>
<nav>
<b><a href="index.html">Home</a></b> &nbsp;
<b><a href="rebeccaleoemail.html">Contact Us</a></b> &nbsp;
<b><a href="menu.html">Menu</a></b> &nbsp;
<b><a href="prices.html">Prices</a></b> &nbsp;
<b><a href="onlineordering.html">Online Ordering</a></b> &nbsp;
<b><a href="reservations.html">Reservations</a></b> &nbsp;
</nav>
   	<script type="text/javascript">
	/* <![CDATA[ */
    /*]]> */
		
	
	window.defaultStatus = "Welcome to Rebecca's Pancake House!";
		var pancakeWindow;
	 function show(linkTarget) {
	    pancakeWindow=window.open(linkTarget,"pancakeInfo","toolbar=no,menubar=no,location=no,
		  scrollbars=no,resizable=no,width=300,height=385");
		  pancakeWindow.focus();
		  }
	 var curImage="banner1";
	   function bannerAd() {
	     if (curImage == "banner2" ){
		   document.images[1].src = "images/banner1.jpg";
		     curImage = "banner1";
	}
	 else {
	   document.images[1].src = "images/banner2.jpg";
	     curImage = "banner2";
		 }
	}
	  function showPancake(linkTarget) {
	    var propertyWidth=462;
		  var propertyHeight=87;
		    var winLeft = (screen.width-propertyWidth)/2;
			 var win/Top = (screen.height-propertyHeight)/2;
			    var winOptions = "toolbar=no,"menubar=no,
				 location=no,scrollbars=no,resizable=no";
				    winOptions += ",width=" + propertyWidth;
					winOptions += ",height=" + propertyHeight;
					winOptions += ",left=" + winLeft;
					winOptions += ",top=" + winTop;
					  pancakeWindow = window.open(linkTarget,
					     "pancakeInfo", winOptions);
						  pancakeWindow.focus();
	</script>					  
			 
	
	                                                               
<img src="images/banner1.jpg" width="462" height="87" alt="BannerAd"><img src="images/banner2.jpg" width="462" height="87" alt="BannerAd">
<img src="images/banner1.jpg" width="462" height="87" alt="BannerAd"
onclick="this.src='images/banner2.jpg';" />"

			                 
                <a href="BananaPancake.html"
				   onmouseover="document.messageForm.pancakeLink.value
				     ='Click for more info on the Banana Pancake'"
				      onmouseout="document.messageForm.pancakeLink.value=''"
					   onclick="showPancake('BananaPancake.html');return false">
                    <img src="images/BananaPancake300.jpg" width="300" height="200" class="NoBorder" /></a>
					</head>
					
					<a href="CherryPancake.html"
				   onmouseover="document.messageForm.pancakeLink.value
				     ='Click for more info on the Cherry Pancake'"
				      onmouseout="document.messageForm.pancakeLink.value=''"
					   onclick="showPancake('CherryPancake.html');return false">
                    <img src="images/CherryPancake300.jpg" width="300" height="200" class="NoBorder" /></a>
                   
        
                                        <!--[Add form here]-->
										<form action="" name="messageForm"
										 <p><input type="text" name="PancakeLink" size="40"
										       style="color:Blue;font-weight:bold;
											     border-style:none; border-color; inherit;
												  border-width:medium;background-color: Transparent /></p>
                                                     </form>
											 
													 
                                              										

<p><h1>SAVOR YOUR SWEET MOMENTS!</h1></p>
<p><h2>Our objective is to create a fun, delicious experience in pancake<br>
enjoyment!</h2></p>
<p>We offer delicious fresh pancakes, toppings and syrup.<br>
You can order online and/or or eat in house!</p>
<ul>  
	<li>5 kinds of Pancakes</li>
	<li>5 toppings</li>
	<li>5 kinds of Syrup</li>
</ul>
<p>Rebecca's Pancake House was founded in 2015 by Rebecca Leo who has 30 years of cooking experience.  Her love of sweets
has lead her to this unique culinary experience for customers who increasingly want to make their own customized
pancakes.  Our recipes demand the highest standard of ingredients starting from our butter, which is grade AA,
our cream is at least 36% milk fat and our eggs are also AA quality. All our fruit is organic and local whenever possible.</p>
<p>Our signature items include the Blueberry Pancake which uses organic Maine blueberries, is baked to perfection and has a
delicious blueberry glaze on top.</p>
<p>Another signature Pancake is the Chocolate Chip which uses chocolate from Switzerland at a minimum of 25% milk fat and
served with whipped butter.</p>
<p>It is our mission to give you the friendliest service and highest standards of pancakes. We serve breakfast all day.
Thank you for visiting our website and we look forward to seeing you soon at Rebecca's Pancake House!</p>
<div>
6001 W. Parmer Rd.<br>
Austin, TX 78727<br>
888-555-5555
</div>
<div>
<p><small><i>Copyright 2015</i> &copy; Rebecca's Pancake House</small></p>
<a href="mailto:rebecca@leo.com">contact@rebeccaspancakehouse.com</a>
</div>
<br>
</body>
</main>
</html>


