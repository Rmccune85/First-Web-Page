# First-Web-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First HTML Page</title>
    <style>
        /* Styling for images */
        img {
            width: 100%;          /* Makes the image responsive */
            max-width: 400px;     /* Limits the maximum width to 400px */
            height: auto;         /* Maintains aspect ratio */
            border-radius: 10px;  /* Optional: Adds rounded corners */
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5); /* Optional: Adds shadow */
        }

        /* Styling for audio */
        audio {
            display: block;       /* Makes the audio player block-level for spacing */
            margin-top: 20px;     /* Adds space above the audio player */
            width: 100%;          /* Makes it responsive */
            max-width: 400px;     /* Limits the width to match the image */
        }
    </style>
</head>
<body>
    <h1>Welcome to HTML5</h1>
    <p>This is my first web page!</p>

    <h2>About Me</h2>
    <ul>
        <li>I am new at learning HTML5.</li>
        <li>I am exploring web development.</li>
    </ul>

    <!-- Local Image -->
    <img src="20200830_211509256_iOS.jpg" alt="Twins">

  	<!-- Local Audio -->
    <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</body>
</html>
