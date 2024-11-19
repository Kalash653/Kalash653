
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Music Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>My Music</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#albums">Albums</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to My Music World</h2>
            <p>Discover new tunes and explore our latest music albums!</p>
        </div>
    </section>

    <section id="albums">
        <h2>Featured Albums</h2>
        <div class="albums-container">
            <div class="album">
                <img src="album1.jpg" alt="Album 1">
                <h3>Album Title 1</h3>
                <audio controls>
                    <source src="track1.mp3" type="audio/mp3">
                    Your browser does not support the audio element.
                </audio>
            </div>
            <div class="album">
                <img src="album2.jpg" alt="Album 2">
                <h3>Album Title 2</h3>
                <audio controls>
                    <source src="track2.mp3" type="audio/mp3">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Music Website. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
<!---
Kalash653/Kalash653 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
