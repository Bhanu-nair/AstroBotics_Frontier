# AstroBotics_Frontier
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astrobotics Frontier</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            text-align: center;
            max-width: 1000px;
            padding: 30px;
            background-color: #111;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.2);
        }
        h1 {
            font-size: 60px;
            margin-bottom: 15px;
            background: linear-gradient(to right, #f7e600, #00f);
            -webkit-background-clip: text;
            color: transparent;
        }
        h2 {
            font-size: 22px;
            color: #f7e600; /* Subtle yellow color */
            margin-bottom: 20px;
        }
        .description {
            font-size: 18px;
            color: #ccc;
            line-height: 1.7;
            margin-bottom: 30px;
        }
        .planet-list {
            list-style-type: none;
            padding: 0;
        }
        .planet-list li {
            font-size: 28px;
            margin: 15px 0;
        }
        .planet-list a {
            color: #00f;
            text-decoration: none;
            transition: color 0.3s, transform 0.3s, font-size 0.3s;
        }
        .planet-list a:hover {
            color: #f7e600;
            font-size: 34px;
            transform: scale(1.2);
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.6);
            cursor: pointer;
        }
        .planet-list a:active {
            color: #ff0;
        }
        footer {
            margin-top: 30px;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Astrobotics Frontier</h1>
        <h2>Exploring the mysteries of our planetary neighbors</h2>
        
        <p class="description">
            NASA’s robotic explorers are venturing where humans have never gone before. From the arid surface of Mars to the icy oceans of Europa, these machines are unlocking secrets of the universe. 
            These incredible robotic missions combine cutting-edge technology with scientific curiosity, enabling us to explore distant worlds while pushing the boundaries of human achievement.
        </p>
        
        <p class="description">
            The journey is just beginning, and the universe awaits discovery. Join us as we expand our reach to other planets, unveiling mysteries, exploring atmospheres, 
            and preparing the path for humanity's future in space. The robots of today are the pioneers of tomorrow's interplanetary civilization!
        </p>

        <ul class="planet-list">
            <li><a href="mercury.html">Mercury</a></li>
            <li><a href="venus.html">Venus</a></li>
            <li><a href="earth.html">Earth</a></li>
            <li><a href="mars.html">Mars</a></li>
            <li><a href="jupiter.html">Jupiter</a></li>
            <li><a href="saturn.html">Saturn</a></li>
            <li><a href="uranus.html">Uranus</a></li>
            <li><a href="neptune.html">Neptune</a></li>
        </ul>

        <footer>
            © 2024 AstroBotics Frontier - Reaching Beyond Our Solar System
        </footer>
    </div>

</body>
</html>
