<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Flower Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
			background-color: #8E8E8E;
        }
        header {
            background-color:#000000 ;
            color: white;
            padding: black;
            text-align: center;
        }
        nav a {
  			background-color: #000000;
			margin: 0 10px;
            color: white;
            text-align: center;
            padding: 0;
        }
        section {
            padding: 2em;
            margin: 2em 0;
			text-align: center;
        }
        footer {
            background-color: #000000;
            color: white;
            text-align: center;
            padding: black;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .gallery img {
            width: 200px;
            height: auto;
            margin: 10px;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
        <a href="#videos">Videos</a>
    </nav>

    <section id="home">
        <h1>Welcome to Our Flower Shop</h1>
        <p>Discover the beauty of our fresh flowers and unique arrangements.</p>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <img src="https://th.bing.com/th/id/OIP.rWuKeKmsrxUHndtvmUfOUQHaE8?w=291&h=194&c=7&r=0&o=5&dpr=1.5&pid=1.7">
        <img src="https://th.bing.com/th/id/OIP.o9KOY0Owz9mkVjedZLpWWAHaHT?w=196&h=194&c=7&r=0&o=5&dpr=1.5&pid=1.7">
		<img src="https://th.bing.com/th/id/OIP.VASJZbFzgAQya1UZP3iISwHaFh?w=265&h=197&c=7&r=0&o=5&dpr=1.5&pid=1.7">
		<img src="https://th.bing.com/th/id/OIP.F8iyMmrKIsuryD11Xt3KiwHaE7?w=297&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7">
		<img src="https://th.bing.com/th/id/OIP.bzi58T7afDabwM6N06h9IAHaHa?w=178&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7">
		<img src="https://th.bing.com/th/id/OIP.71DXKtLuwzhlaRxN8uo3vgHaJQ?w=134&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7">
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="/submit_form" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <section id="videos">
        <h2>Videos</h2>
		<iframe width="560" height="315" src="https://www.youtube.com/embed/OFK7DsCkyVM?si=LqehkUEm8jXHg4Es" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </section>

    <footer>
        <p>&copy; 2024 Flower Shop</p>
    </footer>
</body>
</html>
