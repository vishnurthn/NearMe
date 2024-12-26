# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Map</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }
        img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
        }
        h1 {
            text-align: center;
            color: #333;
        }
    </style>
</head>
<body>
    <!-- Image Map Generated by http://www.image-map.net/ -->

    <h1>Explore the Neighborhood</h1>
<img src="Screenshot 2024-10-14 073307.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Perumal Temple" title="Perumal Temple" href="kovil.html" coords="1053,690,852,773" shape="rect">
    <area target="" alt="Wireless Station" title="Wireless Station" href="wireless-station.html" coords="1443,641,1515,680" shape="rect">
    <area target="" alt="My Sweet Home" title="My Sweet Home" href="Home.html" coords="610,956,838,1034" shape="rect">
    <area target="" alt="Car Wash" title="Car Wash" href="car-wash.html" coords="1242,964,1127,920" shape="rect">
    <area target="" alt="Football Turf" title="Football Turf" href="turf.html" coords="898,1046,1016,1109" shape="rect">
</map>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perumal Temple</title>
    <style>
        body {
            background-color: #fff8e1;
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            text-align: center;
            color: #444;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            text-align: justify;
        }
        img {
            display: block;
            margin: 20px auto;
            border: 5px solid #ddd;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <h1>Perumal Temple</h1>
    <p>
        The Perumal Temple is a magnificent structure dedicated to Lord Vishnu, revered as Perumal in South Indian tradition. Known for its Dravidian-style architecture, the temple is adorned with intricately carved stone pillars and vibrant gopurams (tower gates). 
    </p>
    <p>
        It serves as a spiritual hub, hosting various festivals like Vaikunta Ekadasi and Brahmotsavam, which attract thousands of devotees. The serene ambiance, combined with the temple's historical significance, makes it a must-visit for both pilgrims and history enthusiasts. Legend has it that the temple's sanctum sanctorum radiates divine energy, believed to provide peace and prosperity to those who visit.
    </p>
    <img src="padavettamman-kovil-temple-kannathur-reddykuppam-reddikuppam-kanchipuram-tamil-nadu-south-india-image-best-248242469.webp" alt="Perumal Temple" width="500">
</body>
</html>

<!DOC<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Football Turf</title>
    <style>
        body {
            background-color: #e8f5e9;
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            text-align: center;
            color: #388e3c;
        }
        p {
            font-size: 18px;
            line-height: 1.8;
            text-align: justify;
            margin: 20px 0;
        }
        img {
            display: block;
            margin: 20px auto;
            border: 5px solid #ddd;
            border-radius: 10px;
            max-width: 90%;
        }
    </style>
</head>
<body>
    <h1>Football Turf</h1>
    <p>
        The Football Turf is a top-tier facility designed for sports enthusiasts. The field boasts a high-quality synthetic grass surface, providing a safe and professional-grade environment for players of all skill levels.
    </p>
    <p>
        Whether you're a seasoned athlete or just looking to have some fun, this turf is perfect for practice sessions, tournaments, and friendly matches. With floodlights and well-maintained facilities, it remains a popular destination for evening games and community events.
    </p>
    <img src="football-turf-grass-500x500.webp" alt="Football Turf">
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wireless Station</title>
    <style>
        body {
            background-color: #f9f9f9;
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        p {
            font-size: 18px;
            line-height: 1.8;
            text-align: justify;
            margin: 20px 0;
        }
        img {
            display: block;
            margin: 20px auto;
            border: 5px solid #ddd;
            border-radius: 10px;
            max-width: 90%;
        }
    </style>
</head>
<body>
    <h1>Wireless Station</h1>
    <p>
        The Wireless Station is a modern marvel that ensures seamless connectivity across the city. It is the nerve center for high-speed communication, enabling uninterrupted internet and telecommunication services. With cutting-edge technologies like 5G and IoT integration, this station plays a pivotal role in the region's digital infrastructure.
    </p>
    <p>
        It serves as a critical facility for industries, homes, and businesses, providing robust support for smart devices, streaming, and data transfer. The station also contributes to the city's vision of becoming a smart city, connecting people and technology more efficiently than ever before.
    </p>
    <img src="istockphoto-625121684-612x612.jpg" alt="Wireless Station">
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Home</title>
    <style>
        body {
            background-color: #e3f2fd;
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            text-align: center;
            color: #1976d2;
        }
        p {
            font-size: 18px;
            line-height: 1.8;
            text-align: justify;
            margin: 20px 0;
        }
        img {
            display: block;
            margin: 20px auto;
            border: 5px solid #ddd;
            border-radius: 10px;
            max-width: 90%;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Home</h1>
    <p>
        Located in the serene locality of Porur, Ambal Nagar, Chennai, my home is a warm and inviting place that has been my sanctuary for the past 17 years. Nestled in a quiet neighborhood, it offers a peaceful escape from the bustling city life while still being close to essential amenities.
    </p>
    <p>
        The house is surrounded by lush greenery, with a cozy garden that adds a touch of nature to our everyday lives. The interiors are thoughtfully designed, making it the perfect space for family gatherings, relaxation, and memorable moments.
    </p>
    <img src="beautiful-home-clip-art-charming-cozy-house-vector-illustration-isolated-white_1167562-14965.avif" alt="My Home">
</body>
</html>
```
## OUTPUT
![Screenshot 2024-12-26 102325](https://github.com/user-attachments/assets/77e3eb45-64a3-4ff0-bd46-41e38eb6bb52)
![Screenshot 2024-12-26 102347](https://github.com/user-attachments/assets/e8faee1c-ed4b-4de4-9665-8a52f7821195)
![Screenshot 2024-12-26 102559](https://github.com/user-attachments/assets/57c9bcbc-ef7f-473d-a6dd-c9ef0dd4912c)
![Screenshot 2024-12-26 102619](https://github.com/user-attachments/assets/d145e9bd-8036-4b2c-810c-e50ca6bea6a9)





## RESULT
The program for implementing image maps using HTML is executed successfully.
