<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>

*{
    margin: O;
    padding: 0;
    list-style: none;
    text-decoration: none;
}
body{
    background-image: url('./pngtree-d-rendering-of-love-sign-pendant-on-a-sleek-black-background-image_13520922.png') ;
    background-repeat: no-repeat;
    background-size: cover;
}
nav{
    height: 80px;
    background: #777562;
}

nav img{
    width: 75px;
    position: absolute;
    top: 11px;
    left: 5%;
    border-radius: 40px;
    size: 12px;
}

nav ul{
    float: right;
    margin-right: 25px;

}
 nav ul li{
    display: inline-block;    
    line-height: 80px;
    margin: 0 15px;
}
 nav ul li a{
    position: relative;
    color: white;
    font-size: 18px;
    padding: 5px 0;
    text-transform: uppercase;
 }
 nav ul li a::before{
    position: absolute;
    content: '';
    left: 0;
    bottom: 0;
    height: 3px;
    width: 100%;
    background: white;
    transform: scaleX(0);
    transform-origin: right;
    transition: transform .4s linear;

 }
 nav ul li a:hover:before{
    transform: scaleX(1);
    transform-origin: left;

 }
label #bt,
label #ca{
    color: white;
    font-size: 30px;
    float: right;
    line-height: 80px;
    margin-right: 40px;
    cursor: pointer;
    display: none;
}
#check{
    display: none;

}
@media (max-width:994px){
    label #bt{
        display: block;
    }
    ul{
        position: fixed;
        width: 100%;
        height: 100vh;
        background: #34495e;
        top: 80px;
        left: -100%;
        text-align: center;
        transition: all .5s;
    }
    nav ul li{
        display: block;
        margin: 50px 0;
        line-height: 30px;
    }
#check:checked ~ ul{
    left: 0;
}
#check:checked ~ label #bt{
   display: none;

}
#check:checked ~ label #ca{
    display: block;
    
 }
    
nav ul li a{
    font-size: 20px;
}
}
    </style>
</head>
<body>
    <nav>
      <input type="checkbox" id="check">
      <label for="check">
        <i class="fa fa-bars" id="bt"></i>
        <i class="fa fa-times" id="ca"></i>
      </label>
        <img src="./WhatsApp Image 2024-05-18 at 7.39.13 PM.jpeg" alt="">
        <ul>
            <li><a>Home</a></li>
            <li><a>About</a></li>
            <li><a>Services</a></li>
            <li><a>Contact</a></li>
            <li><a>Feedback</a></li>
        </ul> 
        
    </nav>
</body>
</html>
