<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khalisha Salsabila Restika Santoso</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #fbeff2;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 200px;
            border-radius: 50%;
            margin-top: 10px;
        }
        button {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
        }
        button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Khalisha Salsabila Restika Santoso</h1>
        <img src="SHA11.jpg" alt="Foto Khalisha">
        <p>"Bulu matamu itu seperti pelindung bagi matamu yang bersinar, tapi sayangnya, mereka gagal melindungi aku dari jatuh terlalu dalam. Wajahmu bukan sekadar cantik, tapi seperti lukisan yang Tuhan buat dengan penuh cinta. Dan hatimu? Bahkan malaikat pun mungkin iri dengan kebaikanmu.".</p>
        <button onclick="showLoveMessage()">For You</button>
        <p id="message"></p>
    </div>
    <script>
        function showLoveMessage() {
            document.getElementById('message').innerText = "EVEN IF THE SKY FALLS I'D STILL BE STANDING BECAUSE THE ONLY THING THAT COULD TRULY BRING ME DOWN IS LOSING YOU.";
        }
    </script>
</body>
</html>
