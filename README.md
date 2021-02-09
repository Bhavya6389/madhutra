# madhutra
madhutra website


//HTML Code//
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kotakparivaar.com</title>
    <link rel="stylesheet" href="css/index.css">
</head>
<body>
    <div class="navigation">
    <nav id="navbar">
        <div id="logo">
            <img  src="photos/logo/logo.png" alt="Kotakparivaar.com">
        </div>
        <div id="logotext">
            <p>KOTAK</p>
            <p>PARIVAAR</p>
        </div>

        <ul>
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#">About</a></li>
            <li class="item"><a href="#">Events</a></li>
            <li class="item"><a href="#">Photos</a></li>
        </ul>
    </nav>
</div>
</body>
</html>




//CSS//

*{
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
    box-sizing: border-box;
}

#navbar{
    display: flex;
    align-items: center;
}

/* Navigation bar:logo and img */
#logo{
    
    margin: 0px 5px;;
}
#logo img{
    height: 60px;
    margin: 3px 5px;
    
}

/* NAvigation logo text */
#logotext{
    font-size: 1.1rem;
    color: black;
    display: block;
    margin: 1px 1px ;
    padding: 1px 1px;
}

/* Navigation bar list styling */
#navbar{
    position: relative;
}

#navbar ul{
    display: flex;
}

#navbar::before{
    content: "";
    background-color: white;
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.7;
}

#navbar ul li{
    list-style: none;
    font-size: 1.1rem;
}

#navbar ul li a{

    color: black;
    text-decoration: none;
    display: block;
    margin: 10px 15px;
    padding: 10px 8px;
}

#navbar ul li a:hover{

    color: white;
    background-color: rgb(110, 108, 108);
    border-radius: 16px;
}


