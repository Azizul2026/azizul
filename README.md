<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Page</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; background-color: #f4f4f4; padding: 20px; }
        .container { background: white; padding: 20px; border-radius: 10px; box-shadow: 0px 0px 10px gray; display: inline-block; }
        img { border-radius: 50%; width: 150px; height: 150px; margin-bottom: 10px; }
        a { display: block; margin: 5px; color: blue; text-decoration: none; font-size: 18px; }
        .fun-btn { margin-top: 10px; padding: 10px 15px; font-size: 16px; background: blue; color: white; border: none; border-radius: 5px; cursor: pointer; }
    </style>
</head>
<body>

    <div class="container">
        <img src="C:\Users\KIIT\Desktop\azizull.jpg" alt="Your Photo">
        <h1>Md Azizul Haque Khan</h1>
        <p>Welcome to my page! Connect with me below.</p>
        
        <!-- Links -->
        <a href="https://www.facebook.com/share/1CNnhRnjZu/ " target="_blank">Facebook</a>
        <a href="https://www.instagram.com/.azizul._" target="_blank">Instagram</a>
        <a href="https://github.com/Azizul2026" target="_blank">GitHub</a>

        <!-- Quote Button -->
        <button class="fun-btn" onclick="showQuote()">Click for Quote</button>
        <p id="quote"></p>
    </div>

    <script>
        function showQuote() {
            const quotes = [
                "Keep pushing forward!",
                "Life is an adventure!",
                "You are stronger than you think!",
                "Dream big and never give up!"
            ];
            document.getElementById("quote").innerText = quotes[Math.floor(Math.random() * quotes.length)];
        }
    </script>

</body>
</html>
