# MOCKUP_COMENDADOR
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>THE DRIFT SPORTS</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background: gray;
    color: #333;
}


.top-bar {
    background:gray;
    color: #fff;
    padding: 8px 40px;
    font-size: 14px;
    display: flex;
    justify-content: space-between;
}


header {
    background  : gray;
    padding: 18px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 26px;
    font-weight: bold;
    color: #fff;
}

.nav a {
    color: #fff;
    margin-left: 28px;
    text-decoration: none;
    font-size: 16px;
}

.nav a:hover {
    text-decoration: underline;
}


.hero {
    background: url("") 
    center/cover no-repeat;
    padding: 90px 40px;
}

.hero-content {
    max-width: 1200px;
    margin: auto;
    display: flex;
    align-items: center;
    gap: 50px;
}

.hero-text {
    flex: 1;
    color: #fff;
}

.hero-text h1 {
    font-size: 42px;
    margin-bottom: 20px;
}

.hero-text h1 span {
    color: #ffc107;
}

.hero-text p {
    line-height: 1.7;
    margin-bottom: 30px;
}

.hero-buttons a {
    padding: 12px 22px;
    background: #2c3236;
    color: #fff;
    text-decoration: none;
    margin-right: 10px;
    border-radius: 4px;
    font-size: 15px;
}

.hero-buttons a:last-child {
    background: transparent;
    border: 1px solid #fff;
}

.hero-img {
    flex: 1;
}

.hero-img img {
    width: 80%;
    border-radius: 5%;
}


.services {
    margin-top: -60px;
    padding: 0 40px;
}

.service-boxes {
    max-width: 1200px;
    margin: auto;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
}

.service {
    background: #124f77;
    color: #fff;
    padding: 30px;
    border-radius: 6px;
}

.service h3 {
    margin-bottom: 12px;
    color: #ffc107;
}


.about {
    max-width: 1200px;
    margin: 100px auto;
    display: flex;
    gap: 50px;
    padding: 0 40px;
}

.about-text {
    flex: 1;
}

.about-text h2 {
    font-size: 32px;
    margin-bottom: 20px;
}

.about-text p {
    line-height: 1.8;
}

.about-img {
    flex: 1;
}

.about-img img {
    width: 100%;
    border-radius: 8px;
}
</style>
</head>

<body>


<div class="top-bar">
    <div style = "background-color: dimgrey;">📞 +63 009 430 4320</div>

    <div style="color: #124f77;">✉️ k.comojetnop@gmail.com</div>
</div>


<header>
    <div class="logo">THE DRIFT SPORTS</div>
    <nav class="nav">
        <a href="#">Home</a>
        <a href="#">Services</a>
        <a href="#">Portfolio</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>


<section class="hero">
    <div class="hero-content">
        <div class="hero-text">
            <h1>THE <span>EXPERT</span> DRIFT EXPERIENCE</h1>
            <p>
                Welcome to THE DRIFT SPORTS. We bring adrenaline, precision,
                and professional motorsport training for all skill levels.
            </p>
            <div class="hero-buttons">
                <a href="#">GET STARTED</a>
                <a href="#">LEARN MORE</a>
            </div>
        </div>

        <div class="hero-img">
            <img src="kkkk.jpg.jfif" alt="Drift">
        </div>
    </div>
</section>


<section class="services">
    <div class="service-boxes">
        <div class="service">
            <h3>We Innovate</h3>
            <p>Modern drifting techniques and advanced car control.</p>
        </div>
        <div class="service">
            <h3>Performance</h3>
            <p>Track-focused training with real motorsport experience.</p>
        </div>
        <div class="service">
            <h3>Full Service</h3>
            <p>Events, coaching, vehicle prep, and safety training.</p>
        </div>
    </div>
</section>


<section class="about">
    <div class="about-text">
        <h2></h2>
        <p>
            We provide top-tier drifting solutions, professional coaching,
            and high-energy events for enthusiasts and professionals alike.
        </p>
    </div>
    <div class="about-img">
        <img src="kkkk.jpg.jfif" alt="About Drift">
    </div>
</section>

</body>
</html>
