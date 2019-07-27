<head>
<style>
body {background-color: white;}
p    {color: black;}
 
 .main-content :first-child {
    margin-top: 0;
}
.main-content h1, .main-content h2, .main-content h3, .main-content h4, .main-content h5, .main-content h6 {
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
    color: #b78f52;
    text-decoration: none;
    background-color: #b78f52;
    border-color: rgba(255,255,255,1);
    box-shadow: 0 0 white;
    }
    .main-content .btn{
    position: absolute!important;
    right: 10px!important;
    top: 10px!important;
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

/* Add padding BETWEEN each column (if you want) */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
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
.site-footer-credit{
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

// Number of slides
$slide-count: 5;

// Tab colours (must be same as number of slides)
$c-slides: #2E112D #540032 #820333 #C9283E #F0433A;

// Slide backgrounds (must be same as number of slides)
$b-slides: url('https://placehold.it/2000x2500/2E112D/fff?text=1') url('https://placehold.it/2000x2500/540032/fff?text=2') url('https://placehold.it/2000x2500/820333/fff?text=3') 
url('https://placehold.it/2000x2500/C9283E/fff?text=4') 
url('https://placehold.it/2000x2500/F0433A/fff?text=5');

// Total duration of slide animation
$animation-duration: 1s;

// Dimensions of the slides
$slide-width: 50%;
$slide-height: 100%;

// Slide content overflow (auto or hidden)
$slide-overflow: auto;

// Slide content colours
$c-black: #000;
$c-grey: #AAA;
$c-light-grey: #DDD;

// Other colours
$c-background: #101010;
$c-text: $c-light-grey;
$c-label-text: $c-grey;

/****************************************/

html, body {
  margin: 0;
  background-color: $c-background;
  font-family: sans-serif;
}

.slideshow {
  width: 100%;
  height: 100%;
  border: 0px;
  padding: 0px;
  margin: 0 auto;
  background-color: $c-black;
  overflow: hidden;
}

input {
  display: none;
  
  &:checked + .slide {
    transform: translateX(0px);
    transition: transform #{$animation-duration / 2} ease-in-out;
    
    .slide__content {
      width: 100%;
      display: block;
    }
  }
}

@mixin slide-popout {
  position: absolute;
  margin: auto;
  top: 0px;
  right: 0px;
  bottom: 0px;
  left: 0px;
  width: 100%;
  height: 100px;
}

.slide {
  transform: translateX(#{-$slide-width * 2});
  position: absolute;
  width: $slide-width;
  height: $slide-height;
  background-size: $slide-width $slide-height;
  transition: transform #{$animation-duration / 2} ease-in-out;
  
  &__content {
    box-sizing: border-box;
    height: calc(100% - 60px);
    overflow: $slide-overflow;
    padding: 50px;
    color: $c-text;
    position: absolute;
    left: 100%;
    display: none;
    animation-name: fade-in;
    animation-duration: $animation-duration;
    animation-iteration-count: 1;
    opacity: 1;
  }
  
 $i: 1;
 @each $slide in $b-slides {
    &:nth-child(#{$i * 3}) {
      background: $slide;
      background-repeat: no-repeat;
      background-size: 100%;
      background-position: center;
      
   &:after {
    @include slide-popout;
      }
    }
    $i: $i + 1;
  }
}

label {
  box-sizing: border-box;
  color: $c-label-text;
  font-weight: bold;
  display: block;
  width: calc((50% / #{$slide-count}) - 2%);
  margin: 5px 1%;
  height: 50px;
  line-height: 50px;
  border-bottom: solid 4px $c-grey;
  text-align: center;
  position: absolute;
  bottom: 5px;
  text-transform: uppercase;
  
  &:hover {
    cursor: pointer;
    color: #FFF;
    border-bottom: solid 4px #FFF;
  }
  
  $i: 0;
  @each $slide in $c-slides {
    &:nth-child(#{($i * 3) + 1}) {
      left: calc(50% + (#{$i} * (50% / #{$slide-count})));
      border-bottom-color: $slide;
    }
    $i: $i + 1;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
  }
  50% {
    transform: translateY(-50px);
    opacity: 0;
  }
  100% {
    transform: translateY(0px);
    opacity: 1;
  }
}

.site-footer{
display: none;
}
</style>
</head>

<a href="https://github.com/ijjouake/ijjou" class="btn">View Portfolio</a>
<body><p>My name is Ijjou, I'm a business analyst with a background in statistics and management..</p>
<p> Getting insights out of data to build a business strategy is something that I really like. 
I am a big open source believer, therefore I prefer to use R and python for my daily work.
</p>
<p> On my website you can find some examples of my projects, most of them are interactive visualization.
</p>
<!--
<div class="cleaning" layout="column" layout-align="start center">
                <h2>Data Cleaning</h2>
                <img src="http://drive.google.com/uc?export=view&id=1SExsoJln2fgGrjugcwTJTOOeQpdeIz4A" style="width:100px;height:100px;">
            </div> -->
   <!--         
 <div class=".modeling" layout="column" layout-align="start center">
                <h2>Data Modeling</h2>
                <img src="http://drive.google.com/uc?export=view&id=1RLkY98wrRUykiIeNLuz1MV5wdPBU3Wxc" style="width:100px;height:100px;"> </div> -->
            
   <!--         
 <div class=".visualisation " layout="column" layout-align="start center">
                <h2>Data Visualisation</h2>
               <img src="http://drive.google.com/uc?export=view&id=1IH1BDCmzySD4PirStzy_BKsoCGlulny6" style="width:100px;height:100px;">
            </div>
 <svg class="svg--source" width="0" height="0" aria-hidden="true"> -->
 
   <!-- MAIN (Center website) -->
<div class="main">
<hr>

<h2>Last Projects</h2>
<p>A few pieces of my last projects.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1IH1BDCmzySD4PirStzy_BKsoCGlulny6" alt="Mountains" style="width:100%">
      <h3>Data Cleaning</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1SExsoJln2fgGrjugcwTJTOOeQpdeIz4A" alt="Lights" style="width:100%">
      <h3>Data Visualisation</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1RLkY98wrRUykiIeNLuz1MV5wdPBU3Wxc" alt="Nature" style="width:100%">
      <h3>Data Modeling</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="http://drive.google.com/uc?export=view&id=1SExsoJln2fgGrjugcwTJTOOeQpdeIz4A" alt="Mountains" style="width:100%">
      <h3>Machine Learning</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
</div>

<div class="content">
  <img src="http://drive.google.com/uc?export=view&id=1n3ynaOV5sjt9dBy8wlfOsyAKpQGJyZWY" alt="Ijjou" style="width:210px;height:210x">
  <h3>My name is Ijjou, ....</h3>
  <p>Lorem ipsum..</p>
</div>
    
    <!--slide gallery-->
    
    <fieldset class="slideshow">

  <!-- Slide 1 -->
  <label class="slide-button" for="slideCheckbox1">Intro</label>
  <input type="radio" id="slideCheckbox1" name="slide" checked></input>
  <div class="slide">
    <div class="slide__content">
      <h1>Slideshow Concept (No JS)</h1>
      <p>A pure CSS and HTML slideshow concept.</p>
      <p>To add or remove slides:</p>
      <ul>
        <li>Add a new slide template in the HTML</li>
        <li>Update the <code>$slide-count</code> SCSS variable</li>
        <li>Tab colours: Update the <code>$c-slides</code> SCSS variable</li>
        <li>Slide popout images: Update the <code>$b-slides</code> SCSS variable</li>
      </ul>
      <p>Use the tabs below to change slide.</p>
      <p>Et voila.</p>
    </div>  
  </div>

  <!-- Slide 2 -->
  <label class="slide-button" for="slideCheckbox2">More</label>
  <input type="radio" id="slideCheckbox2" name="slide"></input>
  <div class="slide">
    <div class="slide__content">
      <h1>More</h1>
      <p>More here</p>
    </div> 
  </div>

  <!-- Slide 3 -->
  <label class="slide-button" for="slideCheckbox3">Yet More</label>
  <input type="radio" id="slideCheckbox3" name="slide"></input>
  <div class="slide">
    <div class="slide__content">
      <h1>Yet More</h1>
      <p>Yet more here</p>
    </div>  
  </div>

  <!-- Slide 4 -->
  <label class="slide-button" for="slideCheckbox4">Zzz</label>
  <input type="radio" id="slideCheckbox4" name="slide"></input>
  <div class="slide">
    <div class="slide__content">
      <h1>Zzz</h1>
      <p>Yada yada</p>
    </div>   
  </div>

  <!-- Slide 5 -->
  <label class="slide-button" for="slideCheckbox5">The End</label>
  <input type="radio" id="slideCheckbox5" name="slide"></input>
  <div class="slide">
    <div class="slide__content">
      <h1>The end</h1>
      <p>It's over</p>
    </div>  
  </div>

  <!-- Add more slides here! -->

</fieldset>


        <!-- Footer-->
        
  <div class="footer-inner-new">          
 <div class="sqs-layout sqs-grid-12 columns-12" data-layout-label="Footer Content" data-type="block-field" data-updated-on="1483893114203" id="footerBlocks"><div class="row sqs-row"><div class="col sqs-col-12 span-12"><div class="sqs-block html-block sqs-block-html" data-block-type="2" id="block-713fe491a2c303b33937"><div class="sqs-block-content"><p class="text-align-center">© 2019 Ijjou Akentour. All rights reserved.</p></div></div></div></div></div>
        
<!-- END MAIN -->
</div>         
  
