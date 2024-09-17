<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sinut on hakkeroitu</title>
    <style>
        body {
            background-color: black;
            font-family: Arial, sans-serif;
            margin: 0;
            height: 100vh;
            overflow: hidden;
            position: relative;
        }

        @keyframes blinkAndMove {
            0% {
                color: red;
                top: 20%;
                left: 30%;
            }
            25% {
                color: lime;
                top: 40%;
                left: 60%;
            }
            50% {
                color: red;
                top: 70%;
                left: 20%;
            }
            75% {
                color: lime;
                top: 50%;
                left: 50%;
            }
            100% {
                color: red;
                top: 20%;
                left: 30%;
            }
        }

        h1 {
            font-size: 60px;
            font-weight: bold;
            position: absolute;
            animation: blinkAndMove 1s infinite;
        }
    </style>
</head>
<body>
    <h1>Sinut on hakkeroitu</h1>
</body>
</html>
