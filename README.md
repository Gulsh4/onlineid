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
    <style>
        :root{
    --primary-color:#111;
    --secondary-color:#f2f2f2;
}
.light-theme{
    --primary-color:#d5d5d5;
    --secondary-color:#222;
}
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none;
}
.hero-header{
    min height: 100vh;
    background-color:var(--primary-color);
    font-family: poppins,sans-serif;
}
.container{
    width: 95%;
    margin: 0 auto;
}
.toggle{
    position: fixed;
    right: 4%;
    top:5%;
    color: #fff;
    height: 50px;
    width: 50px;
    line-height: 50px;
    background-color: #2b2a2a;
    border-radius: 50%;
    text-align: center;
}
.header-content{
    display: flex;
    justify-content: space-between;
    align-items: center;
    min-height: 100vh;
}
.header-content .profile{
    height: 550px;
    width: 650px;
    border-radius: 30px;
    overflow: hidden;
    box-shadow: 7px 5px 28px rbga(0,0,0,0.1);
}
.profile img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
.header-content .text-content {
    padding: 2rem 3.5rew;
    margin: 1.2rem;
    color: var(--secondary-color);
    width: 80%;
}
.header-content .text-content h1{
    font-size: 3.5rem;
    color: #ffb400;
    position: ; relative;
    line-height: 3.6rew;
    margin-bottom:1.5rem;
}
.header-content .text-content h1::before{
    content: "";
    background-color:#ffb400;
    position: absolute;
    top:25%;
    left:6%;
    height:5px;
    width:30px;
    border-radius:10px;
}
.header-content .text-content h1 span{
    color: var(--secondary-color) ;
}
.navigation .nav{
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    position: relative;
    padding: 0.8rem;
}
.navigation .nav a{
    position: relative;
    font-size: 18px;
    display: block;
    margin: 10px;
    transition: 0.5s;
    color:var(--secondary-color);
}
.navigation .nav a i{
    height: 50px;
    width: 50px;
    line-height: 50px;
    background-color: #2d2a2a;
    border-radius: 50%;
    text-align: center;
    color: #fff;
    transition: 0.5s;    
}
.navigation .nav .active{
    color: var(--secondary-color);
    background-color: #ffb400;
}
 .navigation .nav a:hover i{
    background-color: #ffb400;
    color: var(--secondary-color);
}
.header-content .button{
    position: relative;
    width: 240px;
    min-height: 45px;
    line-height: 45px;
    overflow: hidden;
    borde:1px solid #ffb400;
    border-radius: 35px;
    margin:2.5rem 0;
    color:var(--secondary-color);
    background-color: transparent;
}
.button .text{
    font-family: poppins;
    font-size: 18px;
}
.button .icon{
    position: absolute;
    right: 0;
    top: 0;
    height: 47px;
    width: 47px;
    border-radius: 35px;
    background-color: #ffb400;
    color: #fff;
    font-size: 19px;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: 0.5s; 
 }
 .button:hover .icon{
    width: 100%;
 }
 @media(max-width:1200px)
 {
    .header-content{
        flex-direction: column;
    }
    .header-content .profile{
        width: 320px;
        height: 320px;
        border-radius: 50%;
        margin-top: 2rem;
    }
    .header-content .profile img{
        width: 100%;
        height: 100%;
    }
    .text-content{
        width: 100%;
        text-align: center;
    }
    .text-content h1::before{
        display: none;
    }
    .navigation{
        background-color: #2d2a2a;
        position: fixed;
        bottom: 0;
        width: 100%;
    }
    .navigation .nav{
        width: 60%;
        flex-direction: row;
        padding: 0.3rew;
        margin: auto;
    }
 }
 @media(max-width:768px)
 {
    .header-content .profile{
        width: 280px;
        height: 280px;
        border-radius: 50%;
        margin-top: 2rew;
    }
    .header-content .profile img{
        width: 100%;
        height: 100%;
    }
    .header-content .text-content h1{
        font-size: 1.5rem;
        line-height: 1.7rem;
    }    
}
    </style>

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
