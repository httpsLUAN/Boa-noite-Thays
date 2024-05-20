<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BOA NOITE THAYS</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: 'Arial', sans-serif;
        }
        .rainbow-text {
            font-size: 3em;
            font-weight: bold;
            background: linear-gradient(90deg, red, orange, yellow, green, blue, indigo, violet);
            -webkit-background-clip: text;
            color: transparent;
            animation: rainbow 3s ease infinite;
        }
        @keyframes rainbow {
            0%, 100% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
        }
    </style>
</head>
<body>
    <div class="rainbow-text">BOA NOITE THAYS</div>
</body>
</html>

