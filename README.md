<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-Ua-copatible" cotent="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <!-----Font Awesome icon css-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
</head>
<body>
    <div class="hero-header">
        <div class="container">
            <div class="toggle">
                <i class="fa fa-sun"></i>
            </div>

            <div class="header-content">
                <div class="profile">
                    <img src="images/photo.jpg" alt="">
                </div>
                <div class="text-content">
                    <h1>I'm Gulshan Nandeshwar <br> <span>Web Developer</span></h1>
                    <p>
                        He is youngest Businessman and Motivational Speaker, CEO of Filmzella website, 
                        which can run world wide I am working with new NMC company
                        Hexaware technology Serviceing notice praiod text good boss I hope you like mo post and all.
                    </p>
                    <button class="button">
                        <span class="text" >Download CV</span>
                        <a href="https://drive.google.com/file/d/1Gobpxq7j9t1WoVlDZF9gZIqQXIQkM7nj/view">
                        <span class="icon fa fa-arrow-right"></span>
                    </button> 
                </div>
                <div class="navigation">
                    <div class="nav">
                        <a href="#">
                            <i class="fa fa-home active"></i>
                        </a>
                        <a href="#">
                            <i class="fa fa-user"></i>
                        </a>
                        <a href="#">
                            <i class="fa fa-cog"></i>
                        </a>
                        <a href="https://wa.me/+917083418278">
                            <i class="fa fa-comment"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!--- javascript for dard and light theme toggle button-->
    <script>
        let btn=document.querySelector(".toggle");
        let icon=document.querySelector(".toggle i");
        let body=document.querySelector(".hero-header");

    btn.onclick=function(){
        body.classList.toggle("light-theme");
        if(body.classList.contains("light-theme"))
        {
            icon.classList.add("fa-moon");
            icon.classList.aremove("fa-sun");
        }
        else{
            icon.classList.add("fa-sun");
            icon.classList.remove("fa-moon");
        }
    }
    </script>
</body>
</html>
