<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Background Color</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            padding: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <h1>Click the Button to Change Background Color</h1>
    <button onclick="changeColor()">Change Color</button>

    <script>
        function changeColor() {
            const randomColor = "#" + Math.floor(Math.random()*16777215).toString(16);
            document.body.style.backgroundColor = randomColor;
        }
    </script>

</body>
</html>
