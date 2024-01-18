
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        .image-container {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
            margin-top:150px; /* Added margin to the top */
			margin-right: 25.0%; /* Adjusted margin to bring images closer */
            margin-left: 25.0%; /* Adjusted margin to bring images closer */
        }

        .image-container a {
            width: 30%;
            margin-right: 15.0%; /* Adjusted margin to bring images closer */
            margin-left: 15.0%; /* Adjusted margin to bring images closer */
            text-decoration: none;
            display: block;
        }

        .image-container img {
            width: 100%;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<div class="image-container">
    <a href="#link1"><img src="trader photo/proper.png" alt="Proper"></a>
    <a href="#link2"><img src="trader photo/therapist.png" alt="Therapist"></a>
    <a href="#link3"><img src="trader photo/fence.png" alt="Fence"></a>
</div>

<div class="image-container">
    <a href="#link4"><img src="trader photo/Skier.png" alt="Skier"></a>
    <a href="#link5"><img src="trader photo/ragman.png" alt="Ragman"></a>
    <a href="#link6"><img src="trader photo/mechanic.png" alt="Mechanic"></a>
</div>

<div class="image-container">
    <a href="#link7"><img src="trader photo/jeager.png" alt="Jaeger"></a>
    <a href="#link8"><img src="image8.jpg" alt="Hideout"></a>
    <a href="#link9"><img src="trader photo/Ammo.jpg" alt="Ammo Guide"></a>
</div>

<div class="image-container">
    <a href="#link10"><img src="image10.jpg" alt="Quest Items"></a>
    <a href="#link11"><img src="image11.jpg" alt="Maps"></a>
    <a href="#link12"><img src="image12.jpg" alt="Coming Soon!"></a>
</div>



</body>
</html>
