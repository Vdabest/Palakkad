# Palakkad
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore Palakkad</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Explore Palakkad</h1>
        <p>Discover the beauty and culture of Palakkad through this fun quiz game!</p>
    </header>
    <main>
        <div id="map">
            <img src="cartoon_map.png" alt="Cartoon Map of Palakkad" usemap="#palakkadmap">
            <map name="palakkadmap">
                <area shape="rect" coords="100,150,200,250" alt="Palakkad Fort" onclick="showInfo('fort')">
                <area shape="rect" coords="250,300,350,400" alt="Malampuzha Dam" onclick="showInfo('dam')">
                <!-- Add more areas for different locations -->
            </map>
        </div>
        <div id="info">
            <h2 id="location-title"></h2>
            <p id="location-info"></p>
            <div id="quiz"></div>
        </div>
    </main>
    <footer>
        <p>Explore and enjoy your journey through Palakkad!</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
