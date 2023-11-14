<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Azure Fabrics</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>Azure Fabrics</h1>
        <p>Effortless Style, Endless Versatility</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#videos">Videos</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to Clothing Brand - your go-to source for the latest fashion trends. Our YouTube channel is dedicated to showcasing the best in clothing and style.</p>
    </section>
    <section id="videos">
        <h2>Latest Videos</h2>
        <!-- You can embed YouTube videos here -->
        <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have questions or suggestions? Reach out to us:</p>
        <form action="mailto:your@email.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required
