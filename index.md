<head>
<style>
p    {color: black;}
 
/* Style the header with a grey background and some padding */
.header {
  overflow: hidden;
  background-color: #f1f1f1;
  padding: 20px 10px;
  position: absolute;
  top: 10px;
  right: 10px;
}

/* Style the header links */
.header a {
  float: left;
  color: black;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

/* Style the logo link (notice that we set the same value of line-height and font-size to prevent the header to increase when the font gets bigger */
.header a.logo {
  font-size: 25px;
  font-weight: bold;
}

/* Change the background color on mouse-over */
.header a:hover {
  background-color: #ddd;
  color: black;
}

/* Style the active/current link*/
.header a.active {
  background-color: dodgerblue;
  color: white;
}

/* Float the link section to the right */
.header-right {
  float: right;
}

/* Add media queries for responsiveness - when the screen is 500px wide or less, stack the links on top of each other */ 
@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  .header-right {
    float: none;
  }
}
 
 .main-content :first-child {
    margin-top: 0;
}
.main-content {
    max-width: none!important;
}
section.main-content {
    max-width: none!important;
}
@media screen and (min-width: 100em){
.main-content {
    max-width: none!important;
}
section.main-content {
    max-width: none!important;
}
}

.main-content h1, .main-content h2, .main-content h3, .main-content h4, .main-content h5, .main-content h6 {
    max-width: 100rem;
    margin-top: 2rem;
    margin-bottom: 1rem;
    font-weight: normal;
    color:  #b78f52;
}
 .project-name {
    font-size: 4rem;
    font-family: "adobe-garamond-pro";
    line-height: 1em;
    text-transform: none;
    letter-spacing: 1px;
    font-weight: 400;
    font-style: italic;
    color: #fff;
    margin: 20px auto;
    opacity:0;
}
.project-tagline{
    font-family: "proxima-nova","Helvetica Neue",Helvetica,Arial,sans-serif;
    opacity: 1;
    color: #b78f52;
    letter-spacing: 0px;
    text-transform: none;
    font-size: 57px;
    line-height: 1em;
    text-transform: uppercase;
    letter-spacing: 4px;
    font-weight: 700;
    font-style: normal;
}
.page-header {
 color: #fff;
 text-align: center;
  width: 100%;
  height: 550px;
  background: url('http://drive.google.com/uc?export=view&id=1WXr2aWCUGwLcZC_X5Rl6f_PCsvmH9Sx0');
  background-size: cover;
  filter:opacity(1);
}
.btn:hover {
    display:none;
    color: white;
    text-decoration: none;
    background-color: #b78f52;
    border-color: rgba(255,255,255,1);
    box-shadow: 0 0 white;
    }
    .btn{
    display:none;
    color: none;
    text-decoration: none;
    background-color: none;
    border-color: none;
    box-shadow: none;
   }
    
.main-content .btn {
    position: absolute!important;
    right: 10px!important;
    top: 10px!important;
    background-color: #b78f52;
     text-transform: uppercase;
     }
     
   h2 {
   display: block;
   text-align: center;
   font-size: 1.5em;
   margin-block-start: 0.83em;
   margin-block-end: 0.83em;
   margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
 
}

* {
  box-sizing: border-box;
}

body {
  background-color: #fff;
  padding: 0px;
  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

* {box-sizing:border-box}


/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
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
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* Add padding BETWEEN each column (if you want) */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
}

.column2 {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

.site-footer-credits{
display:none;
}

.site-footer-owner{
display:none;
}
.footer-inner-new{
max-width: 1020px;
}   

.footer-inner, .pre-footer-inner {
    max-width: 1020px;
    display: none;

.site-footer{
display: none;
}
}
.vl{
  border-left: 6px solid green;
  width: 500px;
}

</style>
</head>
<div id="particles-js"></div>
<script src="particles.js"></script>

<div class="header">
  <a href="#default" class="logo">CompanyLogo</a>
  <div class="header-right">
    <a class="active" href="#home">Home</a>
    <a href="#contact">Contact</a>
    <a href="#about">About</a>
  </div>
 
 
</div>
<a href="https://github.com/ijjouake/ijjou" class="btn">View Portfolio</a>
<body>

<h2>At the heart of every great business decision is data.</h2>
<h3> It’s not what is interesting to the analyst, but what is impactful to the business </h3>

<!-- Portfolio Gallery Grid -->
   <div class="column">
    <div class="main-content">
      <img src="http://drive.google.com/uc?export=view&id=1MOdTjhRf70jbkXtBeerWUvEkmR2QFXlD" alt="Lights" style="width:100%">
      <h3>Data Visualisation</h3>
      <p>"Painting pictures with numbers is what makes the statistics unique and powerful."</p>
    </div>
  </div>
  <div class="column">
    <div class="main-content">
      <img src="http://drive.google.com/uc?export=view&id=1lsefpvecebCCws9TH7sLKiNHxExN2h0w" alt="Nature" style="width:100%">
      <h3>Data Modeling</h3>
      <p>Without the Data Model, data can completely fail to provide business value.</p>
    </div>
  </div>
  <div class="column">
    <div class="main-content">
      <img src="http://drive.google.com/uc?export=view&id=1VG0AZArApiSrvp8mNxhLf_bnoLTlk56B" alt="Mountains" style="width:75%">
      <h3>Machine Learning</h3>
      <p>Systems can learn from data, identify patterns and make decisions with minimal human intervention.</p>
    </div>
  </div>
<hr>

<div class="vl"></div>

<!-- <h2>There is no point to analytics unless it has a strategic payoff.</h2> -->
<h2>Because data trumps opinion.</h2>
<h3> My last projects</h3>

<div class="column2">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1MOdTjhRf70jbkXtBeerWUvEkmR2QFXlD" alt="Lights" style="width:100%">
      <h3>Data Visualisation</h3>
      <p>"Painting pictures with numbers is what makes the statistics unique and powerful."</p>
    </div>
  </div>
  <div class="column2">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1lsefpvecebCCws9TH7sLKiNHxExN2h0w" alt="Nature" style="width:100%">
      <h3>Data Modeling</h3>
      <p>Without the Data Model, data can completely fail to provide business value.</p>
    </div>
  </div>
  <div class="column2">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1VG0AZArApiSrvp8mNxhLf_bnoLTlk56B" alt="Mountains" style="width:75%">
      <h3>Machine Learning</h3>
      <p>Systems can learn from data, identify patterns and make decisions with minimal human intervention.</p>
    </div>
  </div>
  <div class="column2">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1VG0AZArApiSrvp8mNxhLf_bnoLTlk56B" alt="Mountains" style="width:75%">
      <h3>Machine Learning</h3>
      <p>Systems can learn from data, identify patterns and make decisions with minimal human intervention.</p>
    </div>
  </div>

<div class="content">
  <img src="http://drive.google.com/uc?export=view&id=1n3ynaOV5sjt9dBy8wlfOsyAKpQGJyZWY" alt="Ijjou" style="width:210px;height:210x">
 <h3>My name is Ijjou</h3>
 <p>I'm a business analyst with a background in statistics and management..
Getting insights out of data to build a business strategy is something that I really like. 
I am a big open source believer, therefore I prefer to use R and Python for my daily work.</p>
  
</div>
          <!-- Footer-->
        
  <footer class="site-footer">          
 <div class="sqs-layout sqs-grid-12 columns-12" data-layout-label="Footer Content" data-type="block-field" data-updated-on="1483893114203" id="footerBlocks"><div class="row sqs-row"><div class="col sqs-col-12 span-12"><div class="sqs-block html-block sqs-block-html" data-block-type="2" id="block-713fe491a2c303b33937"><div class="sqs-block-content"><p class="text-align-center">© 2019 Ijjou Akentour. All rights reserved.</p></div></div></div></div></div>
 
</div>         
</body>
/* particlesJS.load(@dom-id, @path-json, @callback (optional)); */
particlesJS.load('particles-js', 'assets/particles.json', function() {
  console.log('callback - particles.js config loaded');
});

{
  "particles": {
    "number": {
      "value": 80,
      "density": {
        "enable": true,
        "value_area": 800
      }
    },
    "color": {
      "value": "#ffffff"
    },
    "shape": {
      "type": "circle",
      "stroke": {
        "width": 0,
        "color": "#000000"
      },
      "polygon": {
        "nb_sides": 5
      },
      "image": {
        "src": "img/github.svg",
        "width": 100,
        "height": 100
      }
    },
    "opacity": {
      "value": 0.5,
      "random": false,
      "anim": {
        "enable": false,
        "speed": 1,
        "opacity_min": 0.1,
        "sync": false
      }
    },
    "size": {
      "value": 10,
      "random": true,
      "anim": {
        "enable": false,
        "speed": 80,
        "size_min": 0.1,
        "sync": false
      }
    },
    "line_linked": {
      "enable": true,
      "distance": 300,
      "color": "#ffffff",
      "opacity": 0.4,
      "width": 2
    },
    "move": {
      "enable": true,
      "speed": 12,
      "direction": "none",
      "random": false,
      "straight": false,
      "out_mode": "out",
      "bounce": false,
      "attract": {
        "enable": false,
        "rotateX": 600,
        "rotateY": 1200
      }
    }
  },
  "interactivity": {
    "detect_on": "canvas",
    "events": {
      "onhover": {
        "enable": false,
        "mode": "repulse"
      },
      "onclick": {
        "enable": true,
        "mode": "push"
      },
      "resize": true
    },
    "modes": {
      "grab": {
        "distance": 800,
        "line_linked": {
          "opacity": 1
        }
      },
      "bubble": {
        "distance": 800,
        "size": 80,
        "duration": 2,
        "opacity": 0.8,
        "speed": 3
      },
      "repulse": {
        "distance": 400,
        "duration": 0.4
      },
      "push": {
        "particles_nb": 4
      },
      "remove": {
        "particles_nb": 2
      }
    }
  },
  "retina_detect": true
}

