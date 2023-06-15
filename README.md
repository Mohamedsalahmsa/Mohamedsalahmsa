<!DOCTYPE html>
<html>

<head>
    <title>Rakesh Guttedar</title>
  <style>
  /* @import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@200;300;400;500;600;700&family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap'); */

@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;600;700&display=swap');
/* reset default margin and padding */
* {
    margin: 0;
    padding: 0;
    /* font-family: 'Poppins', sans-serif; */
    font-family: 'Oswald', sans-serif;
}

/* Srcollbar Custimization */
body::-webkit-scrollbar {
    width: 0.4em;
}

body::-webkit-scrollbar-track {
    /* background: #f1f1f1; */
}

body::-webkit-scrollbar-thumb {
    background: #a7a7a7;
    border-radius: 30px;
}

/* Home Section */
.container {
    background-color: #E0EBE7;
    width: 100%;
    height: 100vh;
    overflow: hidden;
}

/* header styles */
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-right: 168px;
    margin-top: 42px;
}

header img {
    height: 70px;
    margin-left: 168px;
}

header nav ul {
    display: flex;
    list-style-type: none;
}

header nav li {
    margin-right: 73px;
}

header nav li a {
    color: #3F9C87;
    text-decoration: none;
    font-weight: 500;
    font-size: 18px;
}

header nav li a:hover {
    color: #000000;
}

/* main styles */


.img-container .mount {
    width: 70%;
    position: absolute;
    top: 18%;
    left: 18%;
}

.img-container .cloud-1 {
    width: 16%;
    position: absolute;
    top: 37%;
    left: 10%;
}

.img-container .cloud-2 {
    width: 16%;
    position: absolute;
    top: 28%;
    right: 10%;
}

/* Home Section end*/

/* Name container */
.name {

    position: absolute;
    top: 25%;
    right: 40%;
    text-align: center;
    color: #3F9C87;
}

.name h1 {
    font-size: 100px;
    font-family: happy Birthday;
    font-weight: 200;
}


.name p {
    font-size: 20px;

    font-weight: 600;
}

/* Name container end */

/* Info Container  */

.info {
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
    background-color: #FFF;
}


.info-content {
    margin: 40px;
}

.info-content img {

    width: 190px;
}

.info-content h1 {
    color: #3F9C87;
    margin: 15px;
}

.info-content p {
    color: #5C6462;
    max-width: 50ch;
    font-size: 22px;
}

/* Info Container  end*/

/* about cection */

.about {
    width: 100%;
    height: 100vh;
    text-align: center;
    overflow: hidden;
}

.about h1 {
    font-size: 50px;
    color: #3F9C87;
}

.about-info{
    width: 50%;
    margin: 100px auto 100px auto;
    text-align: left;
    line-height: 2;
}

.about-img-1{
    width: 190px;
    float: left;
    margin-right: 30px;
}

.about-img-2{
    width: 190px;
    float: right;
}

.about .about-info h3 {
    font-size: 30px;
    font-weight: 600;
    color: #3F9C87;
    margin-bottom: 30px;
}

.about-info p {
    color: #5C6462;
    max-width: 80ch;
}


/* about cection end */


/* contact Section */

.contact {
    width: 100%;
    height: 100vh;
    display: block;
    text-align: center;
}

.contact .contact-info{
    padding: 30px;
    color: #3F9C87;
}
.contact-info h1  {
    font-size: 50px;
    color: #3F9C87;
    margin: 40px;
}

.contact-info h3  {
    font-size: 30px;
    font-weight: 400;
    color: #3F9C87;
    margin: 40px;
}


.contact-info p  {
    font-size: 20px;
    margin: 40px;
    color: #5C6462;
}

.contact-info button{
    font-size: 20px;
    text-align: center;
    background-color: #3F9C87;
    color: #fff;
    outline: none;
    border: none;
    padding: 12px 23px;
    margin-bottom: 97px;
    cursor: pointer;
    transition: all .3s ease-in-out;
}

.contact-info button:hover{
    color: #000000;
    background-color: #3f9c86a4;
}

.contact-info button i{
    font-size: 25px;
    margin-right: 10px;
   
}


/* contact Section end */


/* footer Section */

.footer {
    background-color: #C5DED8;
    
    padding: 50px 0 20px;
}

.footer a{
    color: #3F9C87;
    text-decoration: none;
    margin: 10px 40px;
}

.footer p{
    margin-top: 30px;
    color: #000000a5;
}

    a:hover{
    color: #000000;
}
/* footer Section end */
  </style>
    <link rel="stylesheet" href="https://cdn.lineicons.com/4.0/lineicons.css" />

 <link rel="shortcut icon" type="image/x-icon" href="/images/favicon.icogaayq">
</head>

<body>
    <!-- Header Section -->
    <div class="container" id="home">
        <header>
            <img src="images/logo.png" alt="My Logo">
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>
        <div class="img-container">
            <img src="images/mounten.png" alt="" class="mount">
            <img src="images/cloud-1.png" class="cloud-1">
            <img src="images/cloud-1.png" class="cloud-2">
        </div>
        <div class="name" >
            <h1>I'm Raki</h1>
            <p>a web designer</p>
        </div>

    </div>
    <!-- Header Section End hear-->
    <!-- Info Section -->
    <div class="info">

        <div class="info-content">
            <img src="images/info-img.png" alt="">
            <h1>Hi.</h1>
            <p>I'm a web designer / developer based in India,
                Karnataka. I have a passion for web design and love to
                create for web and mobile devices.</p>
        </div>
    </div>
    <!-- Info Section End Hear-->

    <!-- About Section -->
    <div class="about" id="about">
        <div class="about-content">
            <h1>What I can do.</h1>
            <div class="about-info">
                <img src="images/info-img.png" alt="" class="about-img-1">
                <h3>Design what you want.</h3>
                <p>I like to keep it simple. My goals are to focus on
                    typography, content and conveying the message
                    that you want to send.</p>
            </div>
            <div class="about-info">
                <img src="images/info-img.png" alt="" class="about-img-2">
                <h3>Develop what you need.</h3>
                <p>I'm a developer, so I Know how to create your
                    website to run across devices using the latest
                    technologies available.</p>
            </div>
        </div>

    </div>
    <!-- About Section End Her-->

    <!-- Contact Section -->

    <div class="contact" id="contact">
       <div class="contact-info">
        <h1>I can help.</h1>
        <h3>I'm currently available for freelance work.</h3>
        <p>If you have a project that you want to get starred. think you need my help
           <br> with somethings or just fancy saying hey, then get in touch.</p>
        <button><i class="lni lni-whatsapp"></i>Message Me</button>
       </div>
        <!-- Footer Section --> 

        <div class="footer">
         
                <a href="#">FaceBook</a>
                <a href="#">Instagram</a>
                <a href="#">Github</a>
                <a href="#">hire me </a>
            
            <p>@ 2023 Coding Karunadu. All rights reserved.</p>
        </div>
        <!-- Footer Section End--> 
    </div>

   <!-- Contact Section --> 

</body>

</html>
