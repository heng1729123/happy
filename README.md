<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            text-align: center;
            padding: 50px;
            color: #fff;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px #000;
        }
        button {
            font-size: 1.2em;
            padding: 10px 20px;
            color: #fff;
            background-color: #ff6f61;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            box-shadow: 2px 2px 5px #000;
        }
        button:hover {
            background-color: #ff4b3e;
        }
        .message {
            margin-top: 20px;
            font-size: 1.2em;
            display: none;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>🎉 Happy Birthday! 🎂</h1>
    <button onclick="showMessage()">Click Me!</button>
    <div class="message" id="birthdayMessage">
        🥳 Happy birthday to you wish you all the best in your life and your future! 🎁
    </div>

    <script>
        function showMessage() {
            const message = document.getElementById('birthdayMessage');
            message.style.display = 'block';
        }
    </script>
</body>
</html>
