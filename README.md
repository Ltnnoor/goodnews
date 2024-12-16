<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Good News</title>
    <style>
        body {
            background-color: #FFF1D7;
            color: #749BF1;
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        h1 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .news-container {
            display: none;
            margin-top: 20px;
            padding: 10px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        button {
            background-color: #749BF1;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #5776c8;
        }
    </style>
</head>
<body>
    <h1>With each bad news comes good news. Here is the ones waiting for you.</h1>
    <button onclick="toggleNews()">Click to see good news</button>
    
    <div id="news" class="news-container">
        <p>Good news! You now have less than a 0.001% chance of being hit by a cyclist.</p>
        <p>Good news! Your company will not be sold to fake Khaleejis.</p>
        <p>Good news! Noor is not going to any visa-required countries and is also having drinks with very cool people at her place tonight 7.30pm onwards !.</p>
    </div>

    <script>
        function toggleNews() {
            var news = document.getElementById("news");
            if (news.style.display === "none" || news.style.display === "") {
                news.style.display = "block";
            } else {
                news.style.display = "none";
            }
        }
    </script>
</body>
</html>
