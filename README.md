<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="INDEX_FOLLOW">
    <meta name="descriptions" content="Best Online food Delivery Service in India | Foody.com">
    <meta name="keywords" content="Online foods in India, heathy foods in India, best online foods in India">
    <title>Best Online Food Delivery Service in India | Swiato.com</title>
    <link href="https://fonts.googleapis.com/css2?family=Yanone+Kaffeesatz:wght@600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500;600&display=swap" rel="stylesheet">
    <style>
        /* Css reset */
*{
    margin: 0px;
    padding: 0px;
}

/* navigation bar */
.navbar{
    display: flex;
    align-items: center;
}
.navbar::before{
    content: "";
    background-color: black;
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.7;
}

/* navigation bar: Logo */
.logo img{
    border: 2px solid black;
    border-radius: 1000px;
    margin: 7px 49px;
    width: 54px;
    transition: transform 0.2s ease-in 0s;
}
.logo img:hover{
    transform: scale(1.3);
}

/* navigation bar: content */
.navbar{
    position: relative;
    /* position: absolute;
    width: 100%; */
}
.items{
    list-style: none;
}
.navbar ul{
    display: flex;
}
.items a{
    color: white;
    border-radius: 100px;
    text-decoration: none;
    font-family: 'Yanone Kaffeesatz', sans-serif;
    font-size: 1.2rem;
    font-weight: bolder;
    padding-right: 60px;
    padding: 3px 27px;
    display: block;
}
.items a:hover{
    background-color: white;
    color: black;
}


/* section */
.back{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: rgb(0, 0, 0);
    font-family: 'Pacifico', cursive;
    font-size: 1.3rem;
    height: 100%;
    /* position: absolute;
    top: 0px; */
    /* width: 100%; */
}
.back p{
    width: 100%;
}
.btn{
    border: 2px solid white;
    background-color: brown;
    font-size: 1rem;
    color: white;
    border-radius: 12px;
    text-align: center;
    width: 150px;
    opacity: 0.7;
    
}
.btn:hover{
    background-color: whitesmoke;
    color: black;
    border: 2px solid black;
    opacity: .9;
    font-weight: bold;
}
.back::before{
    content: "";
    background: url('./Back3.jpg') no-repeat center center/cover ;
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -10;
    opacity: .88;
    top: 0px;
    left: 0px;

}





    </style>
</head>
<body>
    <div class="container">
        <nav class="navbar">
            <div class="logo">
                <a href="project.html"><img src="logo.png" alt="FOODY.com"></a>
            </div>
            <ul>
                <li class="items"><a href="project.html">Home</a></li>
                <li class="items"><a href="#">Services</a></li>
                <li class="items"><a href="#">About Us</a></li>
                <li class="items"><a href="#">Contact Us</a></li>
            </ul>
        </nav>
        <section class="back">
            <h1>Welcome to Swiato</h1>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta, vitae ut amet dolore mollitia iste sed quis, sunt asperiores unde quas non incidunt ab delectus laborum! Harum placeat maiores dolorum, amet ducimus labore sit!</p>
            <button class="btn">Order Now</button>
        </section>
    </div>
</body>
</html>
