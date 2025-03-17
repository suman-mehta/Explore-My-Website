<DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You!</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
            text-align: center;
            padding: 50px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background: url('https://images.unsplash.com/photo-1497294815431-9365093b7331?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D') no-repeat center center fixed;
            background-size: cover;
            animation: fadeIn 1s ease-in;
        }
        /* ... बाकी CSS स्टाइलिंग ... */
    </style>
</head>
<body>
    <main>
        <div style="background-color: rgba(0, 0, 0, 0.5); padding: 20px; border-radius: 10px; max-width: 600px; margin: 0 auto;">
            <h1 style="color: #ffdd57; margin-bottom: 20px; animation: fadeInUp 1s ease-in-out forwards;">Explore My Website</h1>
            <p style="font-size: 1.2em; line-height: 1.6; margin-bottom: 20px; animation: fadeInUp 1s ease-in-out forwards;">Welcome Discover more about my work by visiting my main site.</p>
            <a href="https://suman-mehta.github.io/My-website-/" class="button" aria-label="Go Back Home" style="border: 2px solid white; padding: 10px 20px; font-weight: bold; text-decoration: none; color: white; display: inline-block; animation: pulse 2s infinite;">Explore My Portfolio</a>
        </div>
        <div class="gif-container" style="margin-top: 30px;">
            <img src="https://media4.giphy.com/media/JlknBlMbcebNMRTvMX/giphy.gif?cid=6c09b952e9k9bac8f04t3sqwgqhaksad5wgplvjlai56uw2y&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=s" alt="Thank You GIF" style="max-width: 100%; height: auto;">
        </div>
    </main>
    <style>
        @keyframes fadeInUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
    </style>
</body>
</html>
