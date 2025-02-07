<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moje Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #0a0a0a;
            color: #ffffff;
            font-family: Arial, sans-serif;
            text-align: center;
            overflow: hidden;
        }
        .stars {
            position: absolute;
            width: 100%;
            height: 100%;
            background: url('https://cdn.pixabay.com/photo/2013/07/12/12/57/stars-146501_960_720.png') repeat;
            animation: moveStars 50s linear infinite;
        }
        @keyframes moveStars {
            from { transform: translateY(0); }
            to { transform: translateY(-100%); }
        }
        .container {
            position: relative;
            top: 50%;
            transform: translateY(-50%);
        }
        h1 {
            font-size: 3em;
        }
        p {
            font-size: 1.2em;
            opacity: 0.7;
        }
    </style>
</head>
<body>
    <div class="stars"></div>
    <div class="container">
        <h1>Witaj w moim portfolio</h1>
        <p>Strona w budowie, ale gwiazdy już świecą!</p>
    </div>
</body>
</html>
