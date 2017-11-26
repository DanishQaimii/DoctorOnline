<!DOCTYPE html>

<html>
 <head>
	<title> Home </title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	
	<!-- css file attached here -->
	<link href="header.css" type="text/css" rel="stylesheet"/>
	<link href="footer.css" type="text/css" rel="stylesheet"/>
	<link href="Contentarea.css" type="text/css" rel="stylesheet"/>
	<link href="HomePageImageSlider.css" type="text/css" rel="stylesheet"/>
	
	<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Tangerine"> <!-- link for google fonts -- reference = 'https://fonts.google.com/' -->
	<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet"> <!-- link for google icons --- reference = 'http://google.github.io/material-design-icons/'-->

 </head>
 
 <div id="mainbox">
  <body>
  
										<!-- Main Search Bar -->
  
	<form>
		<input class="main-search" type="search" name="search" placeholder="search..." />
	</form>
  
  
										<!-- Top Menu-->
   <header>
   <menu class="top-menu">
	 <menuitem class="top-menu-items"><a class="top-menu-link" href="#"> About Us </a> <span>|<span> </menuitem>
	 <menuitem class="top-menu-items"><a class="top-menu-link" href="#"> Sitemap </a> <span>|<span> </menuitem>
	 <menuitem class="top-menu-items"><a class="top-menu-link" href="#"> Help </a> <span>|<span> </menuitem>
	 <menuitem class="top-menu-items"><a class="top-menu-link" href="#"> Register </a> <span>|<span> </menuitem>
	 <menuitem class="top-menu-items"><a class="top-menu-link" href="#"> Login </a> </menuitem>
	</menu>
	
										  <!-- Logo -->
										
	<h1 id="logo"> Doctor Online . pk </h1>
									
									
	
										<!-- Main Menu -->
	<div>
	<menu class="main-menu">
	 <menuitem  class="home-tab"><a class="main-menu-link" href="#"> Home </a> </menuitem>
	 <menuitem class="main-menu-items"><a class="main-menu-link" href="#"> Find Doctors </a> </menuitem>
	 <menuitem class="main-menu-items"><a class="main-menu-link" href="#"> Services </a> </menuitem>
	 <menuitem class="main-menu-items"><a class="main-menu-link" href="#"> Hospitals </a> </menuitem>
	 <menuitem class="main-menu-items"><a class="main-menu-link" href="#"> Contact Us </a> </menuitem>
	</menu>
	</div>
   </header>
   
   
   
											<!--  image slider -->
											
											
	<!-- <img class="image-slider" src="homepage-images/1.jpg"/> -->
	<div class="slideshow-container">
	
		<div class="mySlides fade">
			<div class="numbertext">1 / 3</div>
			<img src="homepage-images/1.jpg" style="width:100%">
			<div class="text">Caption Text</div>
		</div>

		<div class="mySlides fade">
			<div class="numbertext">2 / 3</div>
			<img src="homepage-images/2.jpg" style="width:100%">
			<div class="text">Caption Two</div>
		</div>

		<div class="mySlides fade">
			<div class="numbertext">3 / 3</div>
			<img src="homepage-images/3.jpg" style="width:100%">
			<div class="text">Caption Three</div>
		</div>

		<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
		<a class="next" onclick="plusSlides(1)">&#10095;</a>

	</div>
	
		<br>

	<div style="text-align:center">
		<span class="dot" onclick="currentSlide(1)"></span> 
		<span class="dot" onclick="currentSlide(2)"></span> 
		<span class="dot" onclick="currentSlide(3)"></span> 
	</div>

	
	
	
	
									<!-- Services slider under image slider-->
									
	<div class="services-slider">
	 <h4 class="services-slider-heading"> Our Services </h4>
	 <p class="services-slider-note"> Doctor Online is providing the best services to our customers from the best Doctos, surgeon, labs and hospital at your door step.</p>
	</div>
	
	
	
											<!--Search a doctor-->
											
	<div class="form-area">
	  <h2 class="appointment-heading"> Search a Doctor </h2>
		<form class="appointment-form" method= "post" >
		
		 <table class="appointment-form-table">
		 
		  <tr class="table-row-2">
		  
		    <td class="form-table-data-label">
			 <label for="hospital"> Hospital Name: </label>
			</td>
			<td class="form-table-data-field">
			 <select id="hospital" name="Hospital">
			  <option> Select an option </option>
			  <option> Agha Khan Hospital </option>
			  <option> Ziauddin Hospital </option>
			  <option> Liaqat National Hospital </option>
			  <option> Medicare Health Center </option>
			 </select>	
			</td>
			
			<td class="form-table-data-label">
			 <label for="department"> Department Name: </label>
			</td>
			<td class="form-table-data-field">
			 <select id="doctor" name="Doctor">
			  <option> Select an option </option>
			  <option> Caridiology </option>
			  <option> Nurology </option>
			  <option> Parenting </option>
			  <option> Dentist </option>
			 </select>	
			</td>
			 
			<td class="form-table-data-label">
			 <label for="doctor"> Doctor Name: </label>
			</td>
			<td class="form-table-data-field">
			 <select id="doctor" name="Doctor">
			  <option> Select an option </option>
			  <option> Dr. Arif Alivi </option>
			  <option> Dr. Mahira rizvi </option>
			  <option> Dr. Ali abidi </option>
			  <option> Dr. Kashif khan </option>
			 </select>	
			</td>
			
		  </tr>
		  
		   </table>
		 
		 <button class="appointment-button-and-doctor-search-button"> Search </button>
		</form>
	</div>
	
											<!-- Booking an Appointment -->
											
	<div class="form-area">
	  <h2 class="appointment-heading"> Book an Appointment </h2>
		<form class="appointment-form" method= "post">
		
		 <table class="appointment-form-table">
		 
		  <tr class="table-row-1">
		  
			<td class="form-table-data-label">
			 <label for="name"> Full Name:* </label>
			</td>
			<td class="form-table-data-field">
			 <input class="appointment-form-field" type="text" name="username" id="name" placeholder="Username" >
			</td>
			
			<td class="form-table-data-label">
			 <label for="number"> Phone:* </label>
			</td>
			<td class="form-table-data-field">
			 <input class="appointment-form-field" type="number" name="username" id="number" placeholder="00923401234567"  >
			</td>
			
			<td class="form-table-data-label"
			 <label for="rmail"> Email:* </label>
			</td>
			<td class="form-table-data-field">
			 <input class="appointment-form-field" type="email" name="username" id="email" placeholder="example@doctoronline.pk"  >
			</td>
			
		  </tr>
		  
		  <tr class="table-row-2">
		  
		    <td class="form-table-data-label">
			 <label for="hospital"> Hospital Name: </label>
			</td>
			<td class="form-table-data-field">
			 <select id="hospital" name="Hospital">
			  <option> Select an option </option>
			  <option> Agha Khan Hospital </option>
			  <option> Ziauddin Hospital </option>
			  <option> Liaqat National Hospital </option>
			  <option> Medicare Health Center </option>
			 </select>	
			</td>
			
			<td class="form-table-data-label">
			 <label for="department"> Department Name: </label>
			</td>
			<td class="form-table-data-field">
			 <select id="doctor" name="Doctor">
			  <option> Select an option </option>
			  <option> Caridiology </option>
			  <option> Nurology </option>
			  <option> Parenting </option>
			  <option> Dentist </option>
			 </select>	
			</td>
			 
			<td class="form-table-data-label">
			 <label for="doctor"> Doctor Name: </label>
			</td>
			<td class="form-table-data-field">
			 <select id="doctor" name="Doctor">
			  <option> Select an option </option>
			  <option> Dr. Arif Alivi </option>
			  <option> Dr. Mahira rizvi </option>
			  <option> Dr. Ali abidi </option>
			  <option> Dr. Kashif khan </option>
			 </select>	
			</td>
			
		  </tr>
			
		 </table>
		 
		 <button class="appointment-button-and-doctor-search-button"> Submit </button>
		</form>
	</div>
	
					<!-- Blank Area just for a while until get ready (removable) -->
	
	<div class="content-box">
		
	</div>
	
										
										<!-- Footer start from here-->
	
	<footer>
	 
	 <div class="footer-column">
	 
	 <div class="footer-column-cell">
	 <h2 class="footer_headings"> Useful links </h2>
	 <p class="footer-item"> Medical Blog <p>
	 <p class="footer-item"> Registered as a Doctors <p>
	 <p class="footer-item"> Enlist Hospitals <p>
	 <p class="footer-item"> Complaints <p>
	 <p class="footer-item"> Feedback <p>
	 
	 </div>
	 
	 <div class="footer-column-cell">
	 <h2 class="footer_headings"> Services </h2>
	 <p class="footer-item"> Hospital Booking <p>
	 <p class="footer-item"> Medicines <p>
	 <p class="footer-item"> Home Delivery <p>
	 <p class="footer-item"> lab Test <p>
	 </div>
	 
	 <div class="footer-column-cell">
	 <h2 class="footer_headings"> Contact Us </h2>
	 
	 <form id="footer-contact-form" method= "post">
	  <label class=" footer-contact-label"> Full Name: </label> <br/>
	  <input class="footer-contact-field" type="text" name="name" value="" placeholder="Name"/> <br/>
	  
	  <label class=" footer-contact-label"> Mobile: </label> <br/>
	  <input class="footer-contact-field" type="number" name="number" value="number"  placeholder="03001234567"/><br/>
	  
	  <label class=" footer-contact-label"> Email: </label> <br/>
	  <input class="footer-contact-field" type="Email" name="email" value="" placeholder="example@doctoronline.pk"/><br/>
	  
	  <label class=" footer-contact-label"> Message: </label> <br/>
	  <textarea id="footer-contact-message" type="comment" placeholder="Enter your message..." ></textarea>
	  
	  <!--<input value="Send" type="submit"/>-->
	  
	  <button id="Footer-contact-button"> Send </button>
	 </form>
	 
	 <!--<p class="footer-item"> Email: danishqaimii@gmail.com <p>
	 <p class="footer-item"> Call: 03408391950 <p>
	 <p class="footer-item"> Phone: 021-38391950 <p>-->
	 </div>
	 
	 
	 <div class="footer-column-cell">
	 <h2 class="follow"> Follow Us </h2>
	 <p class="footer-item"> Facebook <p>
	 <p class="footer-item"> Twitter <p>
	 <p class="footer-item"> Instagram <p>
	 <p class="footer-item"> Google+ <p>
	 </div>
	 
	 </div>
	 
	</footer>
 
 
													<!--js-->

													
	<script>
		//console.log ('Welcome To Doctor Online');
		
		//var welcome="Welcome to the Doctor Online";
		//welcome = "Hellow Visitor";
		//alert(welcome);

		
	var slideIndex = 0;
	showSlides();

	function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none"; 
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1} 
    slides[slideIndex-1].style.display = "block"; 
    setTimeout(showSlides, 10000); // Change image every 2 seconds
}

								/* this code is for fading but not working */
/*var slideIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > x.length) {slideIndex = 1}    
    x[slideIndex-1].style.display = "block";  
    setTimeout(carousel, 9000);  */
	</script>
	
	
  </body>
 </div>
 
 
</html>
