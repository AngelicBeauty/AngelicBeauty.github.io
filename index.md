
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
  margin:0;
  background-image: linear-gradient(to right, rgba(33, 178, 139, 0.5), rgba(49, 185, 191, 0));
  font-family: 'Josefin Sans', sans-serif;
  font-weight: bold;
}

.navbar {
  overflow: hidden;
  background-color: none;
  position: fixed;
  top: 0;
  width: 100%;
  background-image: url("Logo.jpg");
}

.navbar a {
  float: right;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  font-family: 'Josefin Sans', sans-serif;
}

.navbar a:hover {
  background: #ddd;
  color: black;
}

.main {
  padding: 26px;
  margin-top: 30px;
  height: 1500px; /* Used in this example to enable scrolling */
}

.titleMain {
  font-family: 'Josefin Sans', sans-serif;
  font-size: 50px;
  text-align: center;
}

.title {
  font-family: 'Josefin Sans', sans-serif;
  font-size: 40px;
}

.subtitleMain {
  font-family: 'Josefin Sans', sans-serif;
  font-size: 20px;
  text-align: center;
}

.subtitle {
  font-family: 'Josefin Sans', sans-serif;
  font-size: 25px;
}

.button {
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  background-color: #8a8888;
  font-family: 'Josefin Sans', sans-serif;
  width: 100px;
}

.buttonMenu {
  border: none;
  color: white;
  padding: 10px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  vertical-align: right;
  font-size: 16px;
  margin: 10px 0;
  cursor: pointer;
  background-color: #8a8888;
  font-family: 'Josefin Sans', sans-serif;
  width: 80px;
}

.button1 {
  position: fixed;
  top: 200px;
  left: 50px;
}

.button2 {
  position: fixed;
  top: 200px;
  left: 100px;
}

.logo {
  border-radius: 8px;
  width: 610px;
  height: 300px;
  float: right;
}

html {
  scroll-behavior: smooth;
}

.profilePic {
  border-radius: 50%;
  width: 150px;
  height: 150px;
}

.aboutUsText {
  font-family: 'Josefin Sans', sans-serif;
  font-size: 17px;
}

.aboutUsClose {
  font-family: 'Josefin Sanss', sans-serif;
  font-size: 21;
  font-weight: bold;
}

.Map {
  vertical-align: middle;
}

.mapText {
  font-size: 20px;
  font-weight: bold;
  display: inline-block;
}

.menuText {
  display: inline-block;
  vertical-align: middle;
  margin: 10px 0;
}

.contactText {
  display: inline-block;
  margin: 10px 0;
  font-size: 19px;
}

.contactTitle {
  font-size: 20px;
  display: inline-block;
  margin: 10px 0;
  font-weight: bold;
}

.fa-facebook {
  color: black;
  display: inline-block;
}

.fa-instagram {
  color: black;
  display: inline-block;
}

.fa {
  padding: 8px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}
#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (Image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption {
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform:scale(0)}
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}

</style>
</head>
<body>

<div class="navbar">
  <a href="#AboutUs">About Us</a>
  <a href="#Menu">Menu</a>
</div>

<div class="main">
  <h1 class="titleMain">ANGELIC BEAUTY</h1>
  <h2 class="subtitleMain"> Heavenly treatments with a personal touch</h2>

  <br>
  <br>
  <br>
  <br>
  <br id="AboutUs">

  <h3 class="title">ABOUT US</h3>
  <img class="profilePic" src="ProfilePicture.jpg" alt="Profile Picture"> 
  <h4 class="subtitle">Hello,</h4>
  <p class="aboutUsText">I'm Louise, owner of Angelic Beauty. A lot of my clients say I'm the best kept secret and I want to change that. 
    <br>
    I pride myself on making people feel at ease. It can be daunting coming into a new salon for the first time but 
    <br>
    once you've experienced my treatments, I'm sure I will not only become your Beauty Therapist of choice but also 
    <br>
    your friend.
    <br>
    <p class="aboutUsClose">Hope to meet you soon
      <br>
      Louise x
    </p>


    <br>
    <br>

    <p class="mapText">Find Us</p> &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<p class="contactTitle">Contact Us</p>
    <br>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2292.698648664158!2d-1.3754983842670006!3d54.92576006293772!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487e6669f43ca9ab%3A0x588964aa5a2136f4!2s35%20Mere%20Knolls%20Rd%2C%20Roker%2C%20Sunderland%20SR6%209LG!5e0!3m2!1sen!2suk!4v1626106107593!5m2!1sen!2suk" width="300" height="300" style="border:0;" allowfullscreen="" loading="lazy" class="Map"></iframe> &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<p class="contactText">Follow and Contact Us on Social Media or call at 07759 530 348</p> 
    <a href="https://www.instagram.com/angelicbeauty2020/" class="fa fa-instagram"></a>
    <a href="https://www.facebook.com/angelicbeauty2020/" class="fa fa-facebook"></a> 
    <p>Opening Hours
      <br>
      <br>
      Sunday - Tuesday: &nbsp&nbsp Closed
      <br>
      <br>
      Wednesday: &nbsp 09:15 - 15:00
      <br>
      <br>
      Thursday:   &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp09:15 - 15:00
      <br>
      <br>
      Friday:     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp09:15 - 19:00
      <br>
      <br>
      Saturday:     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp09:00 - 16:00
    </p>
    

    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <h5 class="title" id="Menu">Menu</h5>
    <p class="menuText">Check out our available services below and click the button to book your appointment now</p>
    <br>
    <br>
    <a href="https://bookings.gettimely.com/angelicbeauty2/book?uri=https%3A%2F%2Fbook.gettimely.com%2FBooking%2FService%3Fobg%3D771bdca0-4184-4c34-ae28-8360085293da" class="buttonMenu">Book Now</a>
    <br>
    <br>
    <img id="myImg" src="PriceList.jpg" alt="Price Lists" style="width:100%;max-width:300px">

    <div id="myModal" class="modal">

    <span class="close">&times;</span>
    
    <img class="modal-content" id="img01">

    <div id="caption"></div>
    


</div>

<script>
  var modal = document.getElementById("myModal");
  var img = document.getElementById("myImg");
  var modalImg = document.getElementById("img01");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  var span = document.getElementsByClassName("close")[0];
  span.onclick = function() { 
    modal.style.display = "none";
  }
</script>

</body>
</html>
