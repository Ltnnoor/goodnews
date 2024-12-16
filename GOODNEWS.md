<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Good News</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f8ff;
        }
        h1, p {
            margin-bottom: 20px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 18px;
            color: white;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #0056b3;
        }
        #good-news {
            display: none; /* Initially hidden */
            color: #2d2d2d;
            font-size: 18px;
        }
    </style>
    <script>
        function showGoodNews() {
            document.getElementById('good-news').style.display = 'block';
        }
    </script>
</head>
<body>
    <h1>With each bad news comes good news. Here is the one waiting for you.</h1>
    <button class="btn" onclick="showGoodNews()">Click here for good news</button>
    <p id="good-news">The good news is: You are capable of amazing things, and brighter days are ahead!</p>
</body>
</html>
