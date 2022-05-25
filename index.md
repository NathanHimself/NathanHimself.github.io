<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tea Cozy</title>
    <link rel="stylesheet" href="./resorces/css/style.css">
</head>
    <style>
        body {
    font-family: Helvetica;
    font-size: 22px;
    color: seashell;
    opacity: 0.9;
    background-color: black;
}

.navbar {
    height: 69px;
    width: 100%;
    display: flex;
    position: fixed;
    background-color: black;
}

.navbar a {
    color: black;
}

.navbar img {
    height: 69px;
}

.navbar ul {
    list-style: none;
    display: inline-flex;
    flex-wrap: wrap;
}

.navbar ul li {
    padding: 0px 25px;
}

.navbar ul li a {
    color: seashell;
}

.navbar ul li a:hover {
    color: red;
}

.navbar ul li a:active {
    font-size: 20px;
}

#objective-image {
    background-image: url(../img-locations-background.jpg);
    background-position: center;
    background-repeat: no-repeat;
    height: 700px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}


.banner-text {
    text-align: center;
}

.featured-text {
    text-align: center;
}

.image-container {
    margin-left: 0px;
    margin-right: 0px;
    display: flex;
    flex-flow: column wrap;
    justify-content: center;
}

.image-container img {
    width: 300px;
    height: 200px;
}

.image {
    text-align: center;
    padding-top: 30px;
}

#location-image {
    height: 500px;
    background-image: url(../img-mission-background.jpg);
    background-position: center;
    background-repeat: no-repeat;
    width: 100%;
}

#location-image h2 {
    text-align: center;
    padding-top: 50px;
}

.box {
    background-color: black;
    width: 300px;
    height: 200px;
    text-align: center;
    border: 1px solid #DDD;
    border-radius: 5px;
    padding: 10px;
    opacity: 1;
    margin: 40px;
}

.row {
    display: flex;
    align-items: center;
    text-align: justify;
    justify-content: center;
}

.footer-text {
    text-align: center;
    height: 200px;
}

.copyright p {
    float: left;
    font-size: 15px;
}
    </style>
<body>
    <header>
    <nav class="navbar">
        <img src="./resorces/logo.jpg" alt="tea logo">
        <ul>
            <li><a href="#objective">Our objective</a></li>
            <li><a href="#featured">Most popular</a></li>
            <li><a href="#location">Locations</a></li>
        </ul>
    </nav>
    </header>
    <main>
    <section id="objective">
        <div id="objective-image">
            <div class="banner-text">
            <h2>Our Objective</h2>
            <h4>Our objective is always to create the best teas, fast, delicius, and cheap</h4>
            </div>
        </div>
    </section>
    <section id="featured">
            <div class="featured-text">
                <h1>Featured Tea's</h1>
                <p>The most popular tea's this month</p>
            </div>
            <div class="image-container">
                <div class="image">
                    <img src="./resorces/img-berryblitz.jpg" alt="black berry tea">
                    <p>Black Berry</p>
                </div>
                <div class="image">
                    <img src="./resorces/img-spiced-rum.jpg" alt="box of tea">
                    <p>Spiced Rum</p>
                </div>
                <div class="image">
                    <img src="./resorces/img-myrtle-ave.jpg" alt="">
                    <p>Myrtle Ave</p>
                </div>
                <div class="image">
                    <img src="./resorces/img-bedford-bizarre.jpg" alt="">
                    <p>Bedford Bizarre</p>
                </div>
            </div>
    </section>
    <section id="location">
        <div id="location-image">
            <h2>Locations</h2>
            <div class="row">
            <div class="box">
                <h3>Orgiva</h3>
                <p>Calle Sierra Nevada</p>
                <p>18400, Granada</p>
            </div>
            <div class="box">
                <h3>Lanjaron</h3>
                <p>Calle San Marcos</p>
                <p>18600, Granada</p>
            </div>
            <div class="box">
                <h3>Motril</h3>
                <p>Calle Benito Gonzalez</p>
                <p>20800, Motril</p>
            </div>
            </div>
    </section>
    </main>
    <footer>
        <div class="footer-text">
            <h2>Tea Cozy</h2>
            <h5>contact@teacozy.com</h5>
            <p>643-737-183</p>
        </div>
        <div class="copyright">
            <p>© 2022 Tea Cozy</p>
        </div>
    </footer>
</body>
</html>
