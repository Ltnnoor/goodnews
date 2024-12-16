<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Good News</title>
    <style>
        body {
            background-color: #FFF1D7; /* Soft light yellow */
            color: #749BF1; /* Light blue font color */
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }

        .semi-circle {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            max-width: 80%;
            margin-top: 0;
            position: relative;
            transform: rotate(180deg); /* Flip the text to create a semi-circle */
            font-size: 24px;
            font-weight: bold;
        }

        .semi-circle span {
            display: inline-block;
            margin: 0 10px;
            transform-origin: center center;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        button {
            background-color: #749BF1; /* Light blue */
            color: white;
            font-size: 16px;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }

        button:hover {
            background-color: #6079A6; /* Slightly darker blue for hover effect */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="semi-circle">
            <span>With each bad news</span>
            <span>comes good ones.</span>
        </div>
        <button onclick="alert('Here’s the good news waiting for you!')">Click here for good news</button>
    </div>
</body>
</html>
