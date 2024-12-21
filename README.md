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

        /* Styling for audio and video */
        audio, video {
            display: block;       /* Makes the player block-level for spacing */
            margin-top: 20px;     /* Adds space above the player */
            width: 100%;          /* Makes it responsive */
            max-width: 400px;     /* Limits the width */
        }

        iframe {
            margin-top: 20px;     /* Adds space above the iframe */
            width: 100%;          /* Makes it responsive */
            max-width: 400px;     /* Limits the width */
            height: 166px;        /* Standard height for SoundCloud embeds */
            border: none;         /* Removes border */
        }
    </style>
</head>
<body>
    <h1>Chris and Danni's first year riding together</h1>
    <p>Watch these videos and listen to the music!</p>

    <h2>Chris and Danni's riding page</h2>
    <ul>
        <li>Coming home from Barry Dyngles</li>
        <li>Experience the ride.</li>
    </ul>

    <!-- Video -->
    <video width="640" height="360" controls>
        <source src="https://www.youtube.com/watch?v=FW3EW6HPZtg" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <!-- Audio from SoundCloud -->
    <iframe 
        src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/user9245331/dierks-bentley-ride-on&auto_play=true" 
        allow="autoplay">
    </iframe>
</body>
</html>
