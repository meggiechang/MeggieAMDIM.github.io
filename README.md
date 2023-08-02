<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

body, html {
  height: 100%;
  line-height: 1.8;
}

* {
    box-sizing: border-box;
  }
  body {
      background-image: url("../images/metalthing.jpg");
      background-size: cover;
      background-position: 0% 25%;
      background-color: #2F2F39;
      background-attachment: fixed;
      cursor: crosshair;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url(/w3images/mac.jpg);
  min-height: 100%;
}
background-image: url("../images/metalthing.jpg");
.w3-bar .w3-button {
  padding: 16px;
}
</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">NATIONAL INSTITUTE OF STANDARDS AND TECHNOLOGY</a>
    <!-- left-sided navbar links -->
    <div class="w3-left w3-hide-small">
      <a href="#home" class="w3-bar-item w3-button"><i class="fa fa-home"></i> HOME</a>
      <a href="#research" class="w3-bar-item w3-button"><i class="fa fa-search"></i> RESEARCH</a>
      <a href="#publications" class="w3-bar-item w3-button"><i class="fa fa-book"></i> PUBLICATIONS</a>
      <a href="#work with us" class="w3-bar-item w3-button"><i class="fa fa-handshake-o"></i> WORK WITH US</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-users"></i> TEAM</a>
      <a href="#news" class="w3-bar-item w3-button"><i class="fa fa-newspaper-o"></i> NEWS</a>
      <a href="#blog" class="w3-bar-item w3-button"><i class="fa fa-pencil"></i> BLOG</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close X</a>
  <a href="#home" onclick="w3_close()" class="w3-bar-item w3-button">HOME</a>
  <a href="#research" onclick="w3_close()" class="w3-bar-item w3-button">RESEARCH</a>
  <a href="#publications" onclick="w3_close()" class="w3-bar-item w3-button">PUBLICATIONS</a>
  <a href="#work with us" onclick="w3_close()" class="w3-bar-item w3-button">WORK WITH US</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#news" onclick="w3_close()" class="w3-bar-item w3-button">NEWS</a>  
  <a href="#blog" onclick="w3_close()" class="w3-bar-item w3-button">BLOG</a>
</nav>

<a href="https://meggiechang.github.io/#publications">
  Publications </a>
  
<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">
      Data Integration and Management for Additive Manufacturing</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Start something that matters</span><br>
    <span class="w3-large">Advancing our understanding of data processes.</span>
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">OVERVIEW</h3>
  <p class="w3-center w3-large">AM data is essential for establishing part traceability, understanding AM processes and making decisions during the product development lifecycle. The curation, integration, fusion, sharing and analysis of this data are considerable challenges because AM embodies all the 4 V's characteristics of Big Data - volume, velocity, variety, and veracity.</p>
  </div>
  <div class="w3-container w3-light-grey" style="padding:128px 16px">
    
  <h3 class="w3-center">OUR FOCUS</h3>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-plug w3-margin-bottom w3-jumbo w3-center"></i>
      <p>1) Development of a common information model for AM lifecycle data management.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-globe w3-margin-bottom w3-jumbo"></i>
      <p>2) Development of the best guidelines for AM data generation, collection, validation and storage.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-line-chart w3-margin-bottom w3-jumbo"></i>
      <p>3) Development of data structure and format to represent predictive models for AM applications.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-object-group w3-margin-bottom w3-jumbo"></i>
      <p>4) Development of AM data federation and information fusion methods for integrating diverse datasets.</p>
    </div>
  </div>




<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">14+</span>
    <br>Partners
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">55+</span>
    <br>Projects Done
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">89+</span>
    <br>Happy Clients
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">150+</span>
    <br>Meetings
  </div>
</div>



<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
</script>

</body>
</html>
