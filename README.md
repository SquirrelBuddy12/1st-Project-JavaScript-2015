# 1st-Project-JavaScript-2015
Pancake House 1st Project
<!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="content-type" content="text/html"; charset=utf-8" />
<link href="js_styles.css" rel="stylesheet" type="text/css" />
<title>Rebecca's Pancake House</title>
</head>
<header>
<h1>Rebecca's Pancake House</h1>
</header>
<nav>
<b><a href="index.html">Home</b></a> &nbsp;
<b><a href="menu.html">Menu</b></a> &nbsp;
<b><a href="prices.html">Prices</b></a> &nbsp;
<b><a href="onlineordering.html">Online Ordering</b></a> &nbsp;
<b><a href="reservations.html">Reservations</b></a> &nbsp;
</nav>

		
	 <script type="text/javascript">
		
	prompt("visit the site", "http://www.goodtoknow.co.uk/recipes/537316/24-things-you-never-thought-to-do-with-pancakes");

      </script>
      
<p><h1>SAVOR YOUR SWEET MOMENTS!</h1>
<p><h2>Our objective is to create a fun, delicious experience in pancake<br>
enjoyment!</h2>
<script>
}
function nameValidate() {
  if (document.GetElementById('name').value == ""); 
  {
  window.alert("Please enter your name.");
 return false;
  }
    }
  </script>
  </head>
<body>
 </head>
 <body>
<h3>Welcome to Rebecca's Pancake House, please enter your name and password</h3>
<form name="form1" method="post" "
enctype="application/x onsubmit="returnnameValidate"
/>
<p>name:<input type="text" id="name" size="16" />
<p>password:<input type="text" id="password" size="16" />
<input type="submit" value="Submit" />
</p>
</form>
 
    <script type="text/javascript">
    /* <![CDATA[ */
    /*]]> */
         function checkForNumber(fieldValue){
      var numberCheck = isNAN(fieldValue);
       if (numberCheck == true){
        window.alert("You must enter a
	numeric value!");
	 return false;
	 }
         else
	   return true;
	   }
	   
 function confirmSubmit() {
    var submitForm=window.confirm(
	"Are you sure you want to submit the form?");
   if (document.forms[0].name_personal.value == ""
       || document.forms[0].name_personal.value ==""
       || document.forms[0].city_personal.value==""
       || document.forms[0].state_personal.value==""
       || document.forms[0].zip_personal.value=="") {
    window.alert("You must enter your billing information.");
     return false;
   }
    else if (document.forms[0].name_billing.value==""
       || document.forms[0].adddress_billing.value ==""
       || document.forms[0].city_billing.value==""
       || document.forms[0].state_billing.value==""
       || document.forms[0].zip_billing.value=="") {
    window.alert("You must enter your address information.");
      return false;
       	 }
    else if (document.forms[0].area.value==""
       || document.forms[0].exchange.value ==""
       || document.forms[0].phone.value=="") {
     window.alert("You must enter your telephone number.");
	return false;
   }
	else if (document.forms[0].userName.value=="") {
	window.alert("yYou must enter a user name.");
	return false;
    }
    else if (document.forms[0].password.value==""
	|| document.forms[0].password_confirm.
	value=="") {
	window.alert("You must enter a password.");
	    return false;
		}
		return true;
function confirmReset() {
    var resetForm = window.confirm(
	"Are you sure you want to reset the form?");
    if (resetForm ==true)
     return true;
    return false;
	}
	
function nameValidate() {
  if (document.GetElementById('name').value == ""); 
  {
  window.alert("Please enter your name.");
 return false;
  }
    }
 }  
  function calcGroupReservation(groupSize) {
   var dailyMinimum = $50;
     if(groupSize >= 5 && groupSize <=25)
	   dailyMinimum = 50 /1.1;
	     else if (groupSize) > 25 && < 36)
         dailyMinimum = 50 /1.25;
		  var groupRate = groupSize * dailyRate;
		   document.forms[0].discount.value = groupRate.toFixed(2);
		     }
  </head>
  </script>
<body>
<img src="images/pancakeingredients.jpg" alt="Pancake Ingredients" width="300" Height="187" />
<br>
<img src="images/blueberryraspberrypancakes.jpg" alt="Blueberryraspberrypancakes" width="300" Height="187" />  
<main>
<img src="images/banner2.jpg" alt="Pancakes" width="462" Height="87" />   
<img src="images/banner1.jpg" alt="Pancakes" width="462" Height="87" /> 
		
<h2>Group Discount Reservations</h2>
<ul>
<li>Minimum Rate: $50</li>
<li>10-25 people: 10% Discount</li>
<li>20-30 people: 20% Discount</li>
</ul>
<p>How many people are in your group?
 <input type="text" size="10" value="0"
   onchange="calcGroupReservation(this.value)" /></p>
   <p>Your group rate is $<input type="text"
    name="discount" size="20" value="0"
     readonly="readonly"
	  class="total" /></p>
	  <form action= "FormProcessor.html" method="get"
				enctype="application/x-www-form-urlencoded">
				<p>How should we contact you? <input type = "radio"
				name="ContactHow" value = "call me" />Call me
				<input type="radio" name="ContactHow"
				value="email_me" /> Email me</p>
				<p><input type= "submit" />
				<p><input type= "reset"  />
				</form>
<p><h2>Thank you for visiting our website and we look forward to seeing you soon at Rebecca's Pancake House!</h2></p>				
<div>
6001 W. Parmer Rd.<br>
Austin, TX 78727<br>
888-555-5555
</div>
<p><small><i>Copyright 2015</i> &copy; Rebecca's Pancake House</small></p>
<a href="mailto:rebecca@leo.com">contact@rebeccaspancakehouse.com</a>
</body>
</script>
</main>
</html>


