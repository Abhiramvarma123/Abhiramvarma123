FITNESS AND HEALTH
/* CSS Reset */
body, header, nav, main, footer, h1, div, img, ul, figure, figcaption, section, article, aside, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
}

/* Style Rules for body and images */
body {
	background-color: #000;
}

img, video {
	max-width: 100%;
	display: block; 
}

/* Style rule for box sizing applies to all elements */
* {
	box-sizing: border-box;
}

/* Begin Style rules for mobile viewport */

/* Style rule for header */
header {
	top: 0;
	background-color: #000;
	height: 190px;
}

header img {
	margin: 0 auto;
}

/* Style rule for hamburger menu */
.mobile-nav a {
	color: #fff;
	font-family: 'Francois One', sans-serif;
	text-align: center;
	font-size: 2em;
	text-decoration: none;
	padding: 3%;
	display: block;
}

.mobile-nav a.menu-icon {
	display: block;
	position: absolute;
	right: 0;
	top: 0;
}

/* Show mobile class, hide tablet-desktop class and menu-links id */
.mobile {
	display: block;
}

.tablet-desktop, #menu-links {
	display: none;
}

/* Style rules for main content */
main {
	background-color: #fff;
	padding: 2%;
	font-size: 1.15em;
	font-family: 'Roboto Slab', serif;
}

video {
	margin: 0 auto 4%;
}

.mobile h3 {
	text-shadow: 5px 5px 8px #ccc;
}

article {
	padding: 2%;
}

article h3 {
	text-align: center;
}

article img {
	margin: 0 auto;
}

article ul {
	margin-left: 10%;
}

article:nth-of-type(2) {
	background-color: rgba(204, 204, 204, 0.3);
}

.tel-link {
	background-color: #404040;
	padding: 2%;
	margin: 0 auto;
	width: 80%;
	text-align: center;
	border-radius: 5px;
}

.tel-link a {
	color: #fff;
	text-decoration: none;
	font-size: 1.5em;
	display: block;
}

.hours {
	margin-left: 10%;
}

.action {
	font-size: 1.35em;
	color: #666600;
	font-weight: bold;
	text-shadow: 5px 5px 8px #ccc;
}

.frame {
	position: relative;
	max-width: 450px;
	margin: 2% auto;
}

.pic-text {
	position: absolute;
	bottom: 0;
	background: rgba(0, 0, 0, 0.5);
	color: #fff;
	width: 100%;
	padding: 20px;
	text-align: center;
	font-family: Verdana, Arial, sans-serif;
	font-size: 1.5em;
	font-weight: bold;
}

#weights, #cardio, #training {
	margin: 0 2%;
}

.round {
	border-radius: 8px;
}

.external-link {
	color: #666600;
	font-weight: bold;
	text-decoration: none;
}

#contact {
	text-align: center;
}

#contact .contact-email-link {
	color: #666600;
	text-decoration: none;
}

.map {
	border: 2px solid #000;
	width: 95%;
	height: 50%;
}

#form {
	margin-top: 2%;
	background-color: #f2f2f2;
	padding: 2%;
}

#form h2 {
	text-align: center;
}

/* Style rules for form elements */
fieldset, input, select, textarea {
	margin-bottom: 2%;
}

fieldset legend {
	font-weight: bold;
	font-size: 1.25em;
}

label {
	display: block;
	padding-top: 3%;
}

form #submit {
	margin: 0 auto;
	border: none;
	display: block;
	padding: 2%;
	background-color: #b3b3b3;
	font-size: 1em;
	border-radius: 10px;
}

/* Style rules for footer content */
footer .copyright {
	font-size: 0.75em;
	text-align: center;
	color: #fff;
	padding: 2% 4%;
	float: left;
	width: 75%;
}

footer p a {
	color: #fff;
	text-decoration: none;
}

.social {
	float: right;
	width: 20%;
	padding: 2%;
}

.social img {
	display: inline-block;
	padding: 5%;
}

/* Media Query for Tablet Viewport */ 
@media screen and (min-width: 630px), print {
	
/* Tablet Viewport: Show tablet-desktop class,hide mobile class */
.tablet-desktop {
	display: block;
}

.mobile, .mobile-nav {
	display: none;
}

/* Tablet Viewport:  Stylerule for header */
header {
	padding-bottom: 2%;
}

/* Tablet Viewport: Style rules for nav area */
nav {
	padding: 1%;
	margin-bottom: 1%;
}

nav ul {
	list-style-type: none;
	text-align: center; 
}

nav li {
	font-size: 1.5em;
	font-family: 'Francois One', sans-serif;
	display: inline-block;
	border-right: 1px solid #fff;
}

nav li:last-child {
	border-right: none;
}

nav li a {
	padding: 0.1em 0.75em;
	display: block;
	color: #fff;
	text-decoration: none;
}

/* Tablet Viewport: Style rules for main content area */
main ul {
	margin: 0 0 4% 10%;
}
	
.grid {
	display: grid;
	grid-template-columns: auto auto auto;
	grid-gap: 20px;
}
	
.pic-text {
	font-size: 1em;
	padding: 10px;
}
	
aside {
	text-align: center;
	font-size: 1.25em;
	font-style: italic;
	font-weight: bold;
	padding: 2%;
	background-color: rgba(204, 204, 204, 0.5);
	box-shadow: 5px 5px 8px #000;
	text-shadow: 5px 5px 5px #b3b3b3;
	border-radius: 0 15px;
}
	
.grid-item4 {
	grid-column: 1 / span 3;
}

#exercises {
	border-top: 1px solid #000;
	border-bottom: 1px solid #000;
	background: linear-gradient(to right, #ccc, #fff);
	background-color: #f2f2f2;
	padding: 1% 2%;
}

#exercises dt {
font-weight: bold;
}

#exercises dd {
	padding: 0.5% 1% 2% 0;
}

.viewex {
	font-weight: bold;
	cursor: pointer;
}

#example {
	display: none;
}

.tel-num {
	font-size: 1.25em;
}

.map {
	width: 600px;
	height: 450px;
}

/*Tablet Viewport: Style Rules for Table */
table {
	border: 1px solid #000;
	border-collapse: collapse;
	margin: 0 auto;
	width: 100%;
}

caption {
	font-size: 1.5em;
	font-weight: bold;
	padding: 1%;
}

th, td {
	border: 1px solid #000;
	padding: 2%;
}

th {
	background-color: #000;
	color: #fff;
	font-size: 1.15em;
}

tr:nth-child(odd) {
	background-color: #ccc;
}

/* Tablet Viewport: Style rule for form element */
form {
	width: 70%;
	margin: 0 auto;
}

/* Tablet Viewport: Animation */
@-webkit-keyframes text-animation {
	0% { font-size: 1em; }
	50% { font-size: 2em; }
	100% { font-size: 1.35em; }
}

@keyframes text-animation {
	0% { font-size: 1em; }
	50% { font-size: 2em; }
	100% { font-size: 1.35em; }
}

figcaption {
	-webkit-animation-name: text-animation;
	animation-name: text-animation;
	-webkit-animation-delay: 3s;
	animation-delay: 3s;
	-webkit-animation-duration: 5s;
	animation-duration: 5s;
}

}
/* Media Query for Desktop Viewport */
@media screen and (min-width: 1015px), print {

/* Desktop Viewport: Style rule for header */
header {
	width: 25%;
	float: left;
	padding-bottom: 0;
}
	
/* Desktop Viewport: Style rules for nav area */
nav {
	float: right;
	width: 70%;
	margin: 4em 1em 0 0;
}
	
nav ul {
	text-align: right;
}
	
nav li {
	border: none;
}
	
nav li a {
	padding: 0.5em 1em;
}
	
nav li a:hover {
	color: #000;
	background-color: #fff;
	transform: scale(1.3);
}
	
/* Desktop Viewport: Style Rules for main content */
main {
	clear: left;
}
	
main h1 {
	font-size: 1.8em;
}
	
article h3 {
	font-size: 1.75em;
}
	
.pic-text {
	font-size: 1.5em;
	padding: 20px;
}
	
.frame {
	opacity: 0.9;
}
	
.frame:hover {
	opacity: 1;
	box-shadow: 8px 8px 10px #808080;
	transform: translateY(10px);
}
	
#weights, #cardio, #training {
	width: 29%;
	float: left;
	margin: 0 2%;
}
	
#exercises {
	clear: left;
}


.offer:hover {
	transform: scale(1.25);
	cursor: pointer;
}

/* Desktop Viewport: Style Rules for form elements */
form {
	width: auto;
}

.form-grid {
	display: grid;
	grid-template-columns: auto auto auto;
	grid-gap: 20px;
}

.btn {
	grid-column: 1 / span 3;
}

}

/* Media Query for Large Desktop Viewports */
@media screen and (min-width: 1921px) {
	
	#container {
		width: 1920px; 
		margin: 0 auto;
	}
	
}

table {
	width: 80%;
}

/* Media Query for Print */
@media print {
	
body {
	background-color: #fff;
	color: #000;
}

}
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins',sans-serif;
}
body{
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
  background: linear-gradient(135deg, #71b7e6, #9b59b6);
}
.container{
  max-width: 700px;
  width: 100%;
  background-color: #fff;
  padding: 25px 30px;
  border-radius: 5px;
  box-shadow: 0 5px 10px rgba(0,0,0,0.15);
}
.container .title{
  font-size: 25px;
  font-weight: 500;
  position: relative;
}
.container .title::before{
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  height: 3px;
  width: 30px;
  border-radius: 5px;
  background: linear-gradient(135deg, #71b7e6, #9b59b6);
}
.content form .user-details{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 20px 0 12px 0;
}
form .user-details .input-box{
  margin-bottom: 15px;
  width: calc(100% / 2 - 20px);
}
form .input-box span.details{
  display: block;
  font-weight: 500;
  margin-bottom: 5px;
}
.user-details .input-box input{
  height: 45px;
  width: 100%;
  outline: none;
  font-size: 16px;
  border-radius: 5px;
  padding-left: 15px;
  border: 1px solid #ccc;
  border-bottom-width: 2px;
  transition: all 0.3s ease;
}
.user-details .input-box input:focus,
.user-details .input-box input:valid{
  border-color: #9b59b6;
}
 form .gender-details .gender-title{
  font-size: 20px;
  font-weight: 500;
 }
 form .category{
   display: flex;
   width: 80%;
   margin: 14px 0 ;
   justify-content: space-between;
 }
 form .category label{
   display: flex;
   align-items: center;
   cursor: pointer;
 }
 form .category label .dot{
  height: 18px;
  width: 18px;
  border-radius: 50%;
  margin-right: 10px;
  background: #d9d9d9;
  border: 5px solid transparent;
  transition: all 0.3s ease;
}
 #dot-1:checked ~ .category label .one,
 #dot-2:checked ~ .category label .two,
 #dot-3:checked ~ .category label .three{
   background: #9b59b6;
   border-color: #d9d9d9;
 }
 form input[type="radio"]{
   display: none;
 }
 form .button{
   height: 45px;
   margin: 35px 0
 }
 form .button input{
   height: 100%;
   width: 100%;
   border-radius: 5px;
   border: none;
   color: #fff;
   font-size: 18px;
   font-weight: 500;
   letter-spacing: 1px;
   cursor: pointer;
   transition: all 0.3s ease;
   background: linear-gradient(135deg, #71b7e6, #9b59b6);
 }
 form .button input:hover{
  /* transform: scale(0.99); */
  background: linear-gradient(-135deg, #71b7e6, #9b59b6);
  }
 @media(max-width: 584px){
 .container{
  max-width: 100%;
}
form .user-details .input-box{
    margin-bottom: 15px;
    width: 100%;
  }
  form .category{
    width: 100%;
  }
  .content form .user-details{
    max-height: 300px;
    overflow-y: scroll;
  }
  .user-details::-webkit-scrollbar{
    width: 5px;
  }
  }
  @media(max-width: 459px){
  .container .content .category{
    flex-direction: column;
  }
}
//Global variables
var video = document.getElementById("example");
var videoSource = document.getElementById("vid-src");
var descriptionSource = document.getElementById("despsrc");

//Hamburger menu function
function hamburger() {
	var menu = document.getElementById("menu-links");
	var logo = document.getElementById("ffc-logo");
	if (menu.style.display === "block" && logo.style.display === "none") {
			menu.style.display = "none";
			logo.style.display = "block";
	} else {
		menu.style.display = "block";
		logo.style.display = "none";
	}
}

//Function to display the burpees example video
function burpees() {
	videoSource.src = "media/burpees.mp4";
	descriptionSource.src = "media/burpees-descriptions.vtt";
	video.style.display = "block";
	video.load();
}

//Function to display the plank example video
function plank() {
	videoSource.src = "media/plank.mp4";
	descriptionSource.src = "plank-descriptions.vtt";
	video.style.display = "block";
	video.load();
}

//Function to display the mountain climbers example video
function mountain() {
	videoSource.src = "media/mc.mp4";
	descriptionSource.src = "media/mountain-descriptions.vtt";
	video.style.display = "block";
	video.load();
}

//Function to display a promo code
function discount() {
	var promo = document.getElementById("special");
	promo.firstChild.nodeValue = "Promo Code: D25START";
	promo.style.color = "#ff0000";
	promo.style.fontSize = "2em";
}
WEBVTT

NOTE
Descriptions for the Forward Fitness Club, Mountain Climber Video
File Name: mountain-descriptions.vtt

1
00:00.000 --> 00:04.500
Woman has her hands on the floor, in a push up position, and then alternates bringing a knee up to her chest.
