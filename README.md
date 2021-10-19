<!DOCTYPE html>
<html>

<head>
	<title>My Web Design</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="mystyles.css">
<!--<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>-->
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300&display=swap" rel="stylesheet">
</head>

<body>
	<div id="menu-bar" class="menu">
        <div id="menu-logo">
            <div class="image"></div>
        </div>
        <div  id="menu-contact" class="menu-item">
            <a href="#contact-section">Contact Me</a>
        </div>
        <div class="menu-item">
            <a href="#about-section">About </a>
        </div>
        <div class="menu-item">
            <a href="#home-section">Home</a>
        </div>

    </div>
   
    <div class="section" id="home-section">
        <div id="home-title">
            <div class="normal-text">My</div>
            <div class="heading-text">Overdramatic brain.</div>
            <div class="normal-text">and an ever so feel too deeply heart </div>
        </div>
    </div>
    <div class="section" id="about-section">
        <div id="about-title" class="heading-text">About Me</div>
        <div id="about-sub-sections">
            <div id="about-1">
                <div class="about-sub-img"></div>
                <div class="about-sub-txt">
                  <pre class="heading-text">               Needs a Mature brain and a kind soul like your's.<br><br></pre>
                        
                        

             
                </div>
                
            </div>
            <div id="about-2">
                <div class="about-sub-img"></div>
                <div class="about-sub-txt">
                    <pre class="heading-text"> Will you continue to ever so 
    Love me however i'am?                       
                      </pre> 
                   

                </div> 
            </div>
        </div>
    </div>

    <div class="section" id="contact-section">
        <div id="contact-title" class="heading-text"><br> Contact Me </div>
        <div id="contact-sub-section" class="normal-text">
            <div id="contact-phone">
                <div class="image"></div>
                <p>6360607843</p>
            </div>
            <div id="contact-mail">
                <div class="image"></div>
                <p>bhoomi1299@gmail.com</p>
            </div>
            <div id="contact-location">
                <div class="image"></div>
                <p>123-1234 Web St.
                   Mankato Mississippi<br> umm okay
                but you can find me in your heart</p>
            </div>
        </div>
    
        <div id="footer">
            <div id="footer-logo">
                <div class="image"></div>
                <div id="footer-copyright" class="normal-text">Copyright 2021</div>
            </div>
            <div id="footer-links" class="normal-text">
                <p>Quick Links</p>
                <a href="#home-section">Home</a>
                <a href="#about-section">About</a>
                <a href="#contact-section">Contact Me</a>
            </div>
            
        </div>
    </div>
</body>

</html>






/* General ---------------------- */
body{
    font-size:100%;
    margin:0;
    background-image: linear-gradient(#FFFDFD,#DDD6F3);
    border-radius: 75px;

}

.normal-text {
    font-size:100%;
    padding: 2%;
    font-family:"Cormorant Garamond";
    color:#6A6464 important;
    left:50%;

}

.heading-text{
    font-size:200%;
    font-family:"Cormorant Garamond";
    color:black;
    font-weight:bold;
    padding:2%;
    left: 40%;

}

.section{
    width:100%;
    height:90%;
    padding-top:20%;
}

.image{
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
}



/* Menubar ---------------------- */
#menu-bar{
    width: 100%;
    background-color:#FFFDFD;
    position: fixed; /* sticky menu bar*/
    z-index: 5; /* so that menu bar is always in front of all the other item*/
    top: 0;
    right: 0;
    padding:1%;
}

#menu-bar .menu-item{
    display: inline;
    padding:0%;

}

#menu-bar .menu-item a{
    padding: 1%;
    text-decoration: none;
    float: right;
    color:black;
}

#menu-logo{
    display:inline;
    padding-left:2%;
}

#menu-logo .image{
    width:80px;
    height:40px;
    background-image: url(images/logo_small.png);
    display:inline-block;
    padding: 0.2%;
}


/* Home ---------------------- */
#home-section{
    background-size:1440px;
    padding-bottom:15%;
    height:345px;
    width:1270px;
    background-image: url(images/home_bg.png);
    background-repeat: no-repeat;
    background-position:bottom;
    background-position-x:0 ;
}

#home-title{
    width:39%;
    position:absolute;
    top:0;
    right:0;
    padding-top:10%;
    padding-left:10%;
    text-align:left;
}

/* About Us ---------------------- */
#about-title{
    text-align:center;
}


#about-sub-sections{
    height: 100%;
    padding:0px;
    position:relative;
}

.about-sub-img{
    width:50%;
    height:120%;
    display:inline-block;
}

.about-sub-txt{
    width:50%;
    height:fit-content;
    position:absolute;
    top:50%;
    display:inline-block;
}

#about-1{
    width:100%;
    height:40%;
    position: relative;
    top:0;
}

#about-1 .about-sub-img{
    background-image: url(images/about_img1.png);
    width:500px;
    height:450px;
}
#about-1 .about-sub-txt{
    text-align:center;
    font-family:"Cormorant Garamond";
    
}

#about-2{
    width:100%;
    height:40%;
    position: relative;
}

#about-2 .about-sub-img{
    background-image: url(images/about_img2.png);
    width:700px;
    height:442px;
    float:right;
}

#about-2 .about-sub-txt{
    padding-top:10%;
    text-align:left;
    padding-right: 10px;
    font-family:"Cormorant Garamond";
    
}

/* Contact Us ---------------------- */

#contact-title{
    text-align: center;
    padding-top:15%;
}

#contact-sub-section{
    width:70%;
    position: relative;
    left:35%;
    padding:5%;
}

#contact-sub-section p{
    position:absolute;
    top:2%;
    display:inline-block;
    padding:3%;
    margin: 0;
}

#contact-phone .image{
    background-image: url(images/icon_phone.png);
    width:50px;
    height:50px;
}

#contact-mail .image{
    background-image: url(images/icon_mail.png);
    width:50px;
    height:50px;
}

#contact-location .image{
    background-image: url(images/icon_location.png);
    width:50px;
    height:50px;
}

#contact-phone p{
    text-align: right;
   
}
#contact-mail p{
    text-align: right;
   
}
#contact-location p{
    text-align: right 1px;
  
}

#contact-phone,#contact-mail,#contact-location{
    position: relative;
}

#contact-sub-section .image{
    width:50px;
    height:50px;
    display:inline-block;
}


/* Footer ---------------------- */

#footer{
    background-color:#8576FE;
    position: relative;
    bottom:0;
    padding: 2% 20%;
}

#footer div{
    color:beige;
}

#footer-logo{
    display:inline-block;
}

#footer-logo .image{
    width:295px;
    height:80px;
    background-image: url(images/big_logo.png);
    display:inline-block;
}

#footer-copyright{
    text-align:center;
    
}

#footer-links{
    display:inline-block;
    padding-left:40%;
    padding-top: 2%;

}
#footer-links{
    text-decoration:none;
}

#footer-links a{
    display: block;
    text-decoration:none;
    color:beige;
    padding-left:20%;
}
![about_img1](https://user-images.githubusercontent.com/56340018/137975729-5812b27b-277a-4210-a68a-02b6cffecbe4.png)
![about_img2](https://user-images.githubusercontent.com/56340018/137975736-bb7f70df-d6c2-4c25-bdaa-56fb3cdc265d.png)
![big_logo](https://user-images.githubusercontent.com/56340018/137975738-85e7456b-9ef6-427e-8450-7d30875d98ba.png)
![home_bg](https://user-images.githubusercontent.com/56340018/137975739-2d67d40e-dbef-47e3-b60d-c5fa72596378.png)
![icon_location](https://user-images.githubusercontent.com/56340018/137975742-212fb17e-488d-4ea6-8749-217b03b9b15e.png)
![icon_mail](https://user-images.githubusercontent.com/56340018/137975743-4d767a9c-e061-4e14-8c3a-4ac54ef3bf71.png)
![icon_phone](https://user-images.githubusercontent.com/56340018/137975746-c7f68982-e6a1-4c12-b0bd-42898a0c5f89.png)
![logo_small](https://user-images.githubusercontent.com/56340018/137975751-a4f7197d-229b-4b5d-9f8f-e1c35918a515.png)
