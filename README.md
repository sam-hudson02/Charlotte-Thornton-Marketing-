<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Charlotte Thornton Marketing</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Cormorant:wght@400;700&display=swap">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
            padding: 0;
            max-width: 1200px; /* Increased maximum width */
            margin: auto; /* Center the page */
        }

        header {
            background-color: #9bbcde;
            color: #fff;
            padding: 30px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            position: relative;
            margin-bottom: 50px;
            border-radius: 10px;
        }

        header h1 {
            font-size: 42px;
            margin: 40px 0 30px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            font-family: 'Cormorant', serif;
            position: relative;
        }

        header h1::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 0;
            width: 100%;
            height: 2px;
            background-color: #fff;
            z-index: -1;
        }

        header img {
            width: 400px;
            height: auto;
            margin-top: 20px;
        }

        nav {
    background-color: #fff;
    padding: 10px 0;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
}

        nav a {
            color: #9bbcde;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
            transition: color 0.3s;
            font-family: 'Roboto', sans-serif;
        }

        nav a:hover {
            color: #7a9ebc;
        }

        main {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-top: 80px;
        }

        section {
            margin-bottom: 30px;
            text-align: center;
            border: 2px solid #9bbcde;
            border-radius: 10px;
            padding: 20px;
        }

        h2 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #9bbcde;
            font-family: 'Cormorant', serif;
        }

        p {
            font-size: 16px;
            margin-bottom: 20px;
            color: #555;
            font-family: 'Roboto', sans-serif;
        }

        img {
            width: 100%;
            max-width: 600px;
            height: auto;
            margin: 20px auto;
            display: block;
        }

        .social-links {
            margin-top: 20px;
        }

        .social-links a {
            color: #9bbcde;
            text-decoration: none;
            margin: 0 10px;
            font-size: 18px;
            transition: color 0.3s;
            font-family: 'Roboto', sans-serif;
        }

        .social-links a:hover {
            color: #7a9ebc;
        }

        footer {
            background-color: #343a40;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: relative;
            width: 100%;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }

        footer p {
            font-size: 14px;
            color: #ccc;
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
<body>

<nav>
    <a href="#portfolio">Portfolio</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<header>
    <h1>Charlotte Thornton Marketing</h1>
    <img src="/Users/charlottethornton/Downloads/5f254cd8-077a-4324-81e9-1c3345e17881.jpg" alt="Image">
</header>

<main>
    <section id="about">
        <h2>About</h2>
        <p>I'm thrilled to introduce myself as a Marketing Assistant with a fresh perspective and a recent Marketing degree from the University of Southampton. Graduating in July 2023, I've had the pleasure of meeting and learning from many incredible business owners throughout my academic journey. These encounters ignited my passion for collaborating with entrepreneurs, aiding them in enhancing their digital marketing presence using a variety of innovative tools and strategies.</p>
        <p>I am currently a Marketing Assistant, and in this role I've been fortunate to lead the charge in developing and executing data-driven SEO strategies, resulting in remarkable traffic boosts month after month. Additionally, my contributions to our social media marketing strategy have led to impressive returns on investment, thanks to engaging content and targeted advertisements. I've also played a pivotal role in shaping strategic decisions by delivering insightful competitor analyses and user experience assessments.</p>
        <p>During my time at the University of Southampton, I didn't just earn a degree; I gained hands-on experience collaborating with industry leaders like the CEO of Digiwell and working with environmental organizations like tEC. These experiences not only honed my marketing skills but also taught me valuable lessons in organization and time management.</p>
        <p>After University, I had the honor of working with Tom Spleth, an artist in North Carolina, as well as Sophie Waters, an incredible up-and-coming singer, both of whom I am currently working with to build their marketing presence.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <p>Tom Spleth Art</p>
        <img src="/Users/charlottethornton/Downloads/copywrite protected.jpg" alt="Tom Spleth Art">
        <br>
        <br>
        <hr>
        <p></p>
        <p>Sophie May Music</p>
        <img src="/Users/charlottethornton/Downloads/Screenshot 2024-04-01 at 01.42.22.png" alt="Sophie May Singing">
        <br>
        <br>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <div class="social-links">
            <a href="mailto:charlottethornton2@gmail.com" target="_blank">Email</a>
            <a href="https://www.instagram.com/char.thornton_/" target="_blank">Instagram</a>
            <a href="https://www.linkedin.com/in/charlotte-e-thornton/" target="_blank">LinkedIn</a>
        </div>
    </section>
</main>

<footer>
    <p>&copy; 2024 Charlotte Thornton Digital Marketing. All rights reserved.</p>
</footer>

</body>
</html>
