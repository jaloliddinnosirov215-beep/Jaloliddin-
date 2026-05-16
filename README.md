# Jaloliddin-<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eye Loader</title>
    <style>
        body { margin: 0; display: flex; justify-content: center; align-items: center; height: 100vh; background: #1a1a1a; }
        .eye { width: 80px; height: 80px; background: #fff; border-radius: 50%; position: relative; display: flex; justify-content: center; align-items: center; animation: blink 3s infinite; }
        .pupil { width: 30px; height: 30px; background: #000; border-radius: 50%; animation: move 2s infinite linear; }
        @keyframes blink { 0%, 90%, 100% { transform: scaleY(1); } 95% { transform: scaleY(0.1); } }
        @keyframes move { 0% { transform: rotate(0deg) translateX(15px); } 100% { transform: rotate(360deg) translateX(15px); } }
    </style>
</head>
<body>
    <div class="eye"><div class="pupil"></div></div>
</body>
</html>
