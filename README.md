/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 20px;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
}

nav ul {
    list-style-type: none;
    margin-top: 20px;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
}

section {
    padding: 40px 0;
}

section h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    text-align: center;
}

.container .team,
.container .player {
    text-align: center;
    margin-bottom: 40px;
}

.container .team img,
.container .player img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 20px;
}

.container .team h3,
.container .player h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.container .team p,
.container .player p {
    font-size: 1.1rem;
}

.container .gallery-image {
    width: 33.33%;
    float: left;
    padding: 5px;
}

.container .gallery-image img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    transition: transform 0.3s ease-in-out;
}

.container .gallery-image img:hover {
    transform: scale(1.05);
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

footer p {
    font-size: 1.1rem;
}
