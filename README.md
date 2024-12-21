<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christopher and Danielle</title>
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
    <h1>Chris and Danni's first year riding together</h1>
    <p>Watch these videos!</p>

    <h2>Chris and Danni's riding page</h2>
    <ul>
        <li>Coming home from Barry Dyngles</li>
        <li>Experience the ride.</li>
    </ul>

    <!-- Video -->
    <video width="640" height="360" controls>
        <source src="https://raw.githubusercontent.com/Rmccune85/First-Web-Page/main/Chris%20n%20Danni.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <!-- Audio -->
    <audio controls>
        <source src="https://archive.org/download/Badboys_201702/Badboys.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</body>
</html>
