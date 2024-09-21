<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Hover Effects</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }

        .button {
            background-color: #4CAF50;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            border-radius: 5px;
            transition: all 0.3s ease;
        }

        .button:hover {
            background-color: #3e8e41;
            box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
            transform: translateY(-2px);
        }
    </style>
</head>
<body>
    <button class="button">Hover Me</button>
</body>
</html>
