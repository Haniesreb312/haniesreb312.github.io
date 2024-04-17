<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hani's Football Passion</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <img src="header-image.jpg" alt="Football Stadium">
        <h1>Hani's Football Passion</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#teams">Teams</a></li>
                <li><a href="#players">Players</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Hani's Football Passion</h2>
            <img src="about-image.jpg" alt="Football Field">
            <p>Welcome to Hani's Football Passion, your ultimate destination for all things football! From thrilling match highlights to exclusive player interviews, we cover it all. Stay tuned for the latest updates and insights from the world of football.</p>
        </div>
    </section>

    <section id="teams">
        <div class="container">
            <h2>Featured Teams</h2>
            <div class="team">
                <img src="manchester-united.png" alt="Manchester United">
                <h3>Manchester United</h3>
                <p>Get the latest news, match reviews, and player analysis of Manchester United.</p>
            </div>
            <div class="team">
                <img src="barcelona.png" alt="FC Barcelona">
                <h3>FC Barcelona</h3>
                <p>Experience the magic of FC Barcelona with in-depth coverage and expert commentary.</p>
            </div>
        </div>
    </section>

    <section id="players">
        <div class="container">
            <h2>Star Players</h2>
            <div class="player">
                <img src="marcus-rashford.jpg" alt="Marcus Rashford">
                <h3>Marcus Rashford</h3>
                <p>Discover the talent and passion of Marcus Rashford and his impact on the football world.</p>
            </div>
            <div class="player">
                <img src="lamine-yamal.jpg" alt="Lamine Yamal">
                <h3>Lamine Yamal</h3>
                <p>Explore the skills and achievements of Lamine Yamal, a rising star in the football scene.</p>
            </div>
        </div>
    </section>

    <section id="gallery">
        <div class="container">
            <h2>In the Spotlight</h2>
            <div class="gallery-image">
                <img src="gallery-image1.jpg" alt="Gallery Image 1">
            </div>
            <div class="gallery-image">
                <img src="gallery-image2.jpg" alt="Gallery Image 2">
            </div>
            <div class="gallery-image">
                <img src="gallery-image3.jpg" alt="Gallery Image 3">
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <p>Have questions, feedback, or suggestions? We'd love to hear from you! Reach out to us using the form below.</p>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" cols="50" required></textarea><br>
                <input type="submit" value="Submit">
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Hani's Football Passion - All rights reserved.</p>
    </footer>

</body>

</html>
