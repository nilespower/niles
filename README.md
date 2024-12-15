<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>стиль</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background: black;
            color: lime;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background: black;
            padding: 20px;
            border-bottom: 4px solid lime;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        header h1 {
            font-size: 3em;
            color: lime;
            text-shadow: 2px 2px black;
            margin: 0;
        }

        .rad-light {
            width: 50px;
            height: auto;
            position: absolute;
        }

        .rad-light-left {
            left: 20px;
            top: 20px;
        }

        .rad-light-right {
            right: 20px;
            top: 20px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: lime;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav ul li a:hover {
            text-shadow: 0px 0px 5px lime;
        }

        .pixel-art {
            margin: 20px auto;
            width: 100%;
            height: auto;
        }

        section {
            padding: 20px;
            line-height: 1.6;
            text-align: left;
            max-width: 800px;
            margin: 20px auto;
            background: rgba(0, 0, 0, 0.8);
            border: 2px solid lime;
            border-radius: 10px;
        }

        section img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 20px;
        }

        footer {
            background: black;
            color: lime;
            padding: 10px;
            font-size: 0.8em;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="images/torch.png" alt="Rad Light" class="rad-light rad-light-left">
        <h1>стиль</h1>
        <img src="images/torch.png" alt="Rad Light" class="rad-light rad-light-right">
        <nav>
            <ul>
                <li><a href="#nostalgia">Nostalgia</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="nostalgia">
        <h2>Embracing Imperfection</h2>
        <p>Life in the past was never about perfection—it was about authenticity. The cracks, the flaws, the realness of every moment shaped who we were. In today’s polished world, we’ve lost the beauty of imperfection. Let’s embrace the raw, unfiltered essence of life, just as it was meant to be.</p>
        <img src="images/retro-scene.png" alt="Retro Scene">
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Our social media is @Gobacktothegoodolddays</p>
        <video autoplay controls width="600">
            <source src="OldVHS.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

    <footer>
        <p>&copy; 2024 стиль | Designed with retro vibes</p>
    </footer>
</body>
</html>
