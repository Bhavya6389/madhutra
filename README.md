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
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
</head>

<body>
    <div class="navigation">
        <nav id="navbar">
            <div id="logo">
                <img src="photos/logo/logo.png" alt="Kotakparivaar.com">
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
        <section id="home">
            <h1 class="hfirst">MADHUTRA</h1>
            <h1 class="hfirst">KOTAK</h1>
            <h1 class="hfirst">PARIVAAR</h1>

        </section>

        <section id="about">
            <h1 class="hsecond">About us</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, nobis et quidem ducimus velit excepturi tenetur! Expedita aspernatur unde repellendus quisquam ut ipsa, molestias incidunt reiciendis veniam veritatis, fugit doloribus doloremque aliquam animi natus consectetur numquam eaque? Expedita, neque cumque Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique aliquid quasi ad corrupti voluptates nobis autem doloribus iusto a! Explicabo ea expedita, consequatur debitis consectetur aperiam ipsa exercitationem nisi numquam.
            </p>
        </section><hr>
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
    display:flex;
    
    align-items: center;
}

/* Navigation bar:logo and img */
#logo{
    width: 10%;
    margin: 0px 5px;;
}
#logo img{
    height: 75px;
    margin-left: 30px;
    
}

/* NAvigation logo text */
#logotext{
    
    font-size: 1.1rem;
    color: black;
    display: block;
    margin: 1px 1px ;
    padding: 1px 1px;
    font-size: 1.5rem;
    font-weight: 550;
}

/* Navigation bar list styling */

#navbar{
    background-color: brown;
    position: relative;
    
    
}

#navbar ul{
    width: 80%;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    
}

#navbar::before{
    content: "";
    background-color:brown;
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.3;
}

#navbar ul li{
    list-style: none;
    font-size: 1.4rem;
    font-weight: 550;
}

#navbar ul li a{

    color: black;
    text-decoration: none;
    display: block;
    margin: 10px 15px;
    padding: 10px 8px;
}

#navbar ul li a:hover{

    color: black;
    background-color:white;
    border-radius: 16px;
}

/* HOME SECTION */

#home{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 680px;
    background: image();
    font-size: 2.5rem;
   
}

#home::before{
    content: "";
    background: url('../photos/home.jpg')no-repeat center center/cover;
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.9;
}

/* HOME SECTION HEADING */

#home h1{
    position: relative;
    color: black;
    text-align: center;
    
}

/* UTILITY CLASSES */
.hfirst{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 15px;
}

/* ABOUT SECTION */
#about{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: brown
}

#about h1{
    position: relative;
    color: black;
    padding-bottom: 40px;
    padding-top: 20px;
    font-size: 4rem;
}

#about p{
    color:black;
    padding: 30px 250px;
    text-align: center;
}
    
