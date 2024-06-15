<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Landing Page</title>
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Header Styles */
header {
    background-color: #333;
    color: #fff;
    padding: 10px;
}
nav ul {
    list-style: none;
}
nav ul li {
    display: inline;
    margin-right: 20px;
}

/* Hero Section Styles */
.hero {
    /* background-image: url('download.jpg'); */
    /* background-image: url("https://paruluniversity.ac.in/app/images/slider/background_image/424961Home%20Page.jpeg");
    background-size: cover; */
    background-image: url(galgotias.jpg);
    background-size: cover;
    text-align: center;
    color: #fff;
    padding: 100px 0;
}
.hero h1 {
    font-size: 36px;
}
.cta-button {
    background-color: #ff5722;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
}

/* Features Section Styles */
.features {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.feature {
    flex: 1;
    padding: 20px;
    text-align: center;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
    </style>
</head>
<body>
  
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                
                <li><a href="#">About Us</a></li>
                <!-- <li><a href="#">S -->
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to parul university website</h1>
        <h2>Finding more information about university </h2>
        <a href="https://paruluniversity.ac.in/" class="cta-button">Get Started</a>
    </section>

    <section class="features">
        <div class="feature">
            <h2>About Placements</h2>
            <p>75% students placed to here</p>
            <a href="#" class="cta-button">click now</a>
        </div>
        <div class="feature">
            <h2>Admission</h2>
            <p>Admissoin based information</p>
            <a href="#" class="cta-button">Click now </a>
        </div>
        <div class="feature">
           <h2> Cources </h2>
           <p>University provides many cources</p>
           <a href="#" class="cta-button">Click now</a>
        </div>
    </section>

    <footer>
        <p> copyright  2023 parul university information
            Designed by me
        </p>
    </footer>
    <script> src="script.js" </script>
</body>
</html>

