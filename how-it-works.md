---
layout: page
title: How Hazard Map Works
---

<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/1.jpg" style="width:100%">
    <div class="text">People are susceptible to getting infected. Infected people recover after some characteristic time.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/2.jpg" style="width:100%">
    <div class="text">The infection spreads within a city from person to person through physical proximity. Infected people get recovered after some characteristic time.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/3.jpg" style="width:100%">
    <div class="text">The infection also spreads from city to city because people travel using air, road, or rail as mode of transport. The blue and yellow coloured arrows denote the traffic between various cities. Initially there is only one infected case in city D.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/4.jpg" style="width:100%">
    <div class="text">After some time, there are infected cases in city A and C. People are also getting recovered in these cities.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/5.jpg" style="width:100%">
    <div class="text">Even though city D and city B are not connected, the infection reaches city B after some time.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/6.jpg" style="width:100%">
    <div class="text">Eventually, the infection reaches all cities. The first time since the outbreak when the active cases cross a threshold is used as a proxy for the risk associated with that city.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">7 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/7.jpg" style="width:100%">
    <div class="text">The Data for the three modes of transport - air, rail, and road was collected/estimated through various methods.</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">8 / 8</div>
    <img src="https://https://mansi-budamagunta.github.io.github.io/hazard_map/images/8.jpg" style="width:100%">
    <div class="text"> Bigger red circle implies higher risk, while smaller red circle implies lower risk. City A has more risk than city B in the above example.</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
  <span class="dot" onclick="currentSlide(8)"></span>
</div>

<head>
  <style>

* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 800px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: black;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: black;
  font-size: 25px;
  padding: 8px 12px;
  position: relative;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: black;
  font-size: 20px;
  padding: 8px 12px;
  position: relative;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 25px;
  width: 25px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1s;
  animation-name: fade;
  animation-duration: 1s;
}

@-webkit-keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

</style>
</head>

<script>
  var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}
</script>
