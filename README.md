# Almerro
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gombalan untuk Emely Mutiara Rafaela</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        h1 {
            font-size: 3rem;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        p {
            font-size: 1.5rem;
            margin: 20px 0;
            color: #ffe4e1;
        }

        button {
            background-color: #ff6f61;
            color: #fff;
            border: none;
            padding: 15px 30px;
            font-size: 1.2rem;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #ff3d2e;
        }

        .heart {
            font-size: 5rem;
            color: #ff6f61;
            animation: heartbeat 1.5s infinite;
        }

        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="heart">❤️</div>
        <h1>Hai Emely Mutiara Rafaela!</h1>
        <p>"Kamu tahu nggak, Emely? Kalau kamu bintang, aku adalah malam. Tanpamu, aku tidak bercahaya."</p>
        <button onclick="showLove()">Pencet Sayang</button>
        <p id="gombalan"></p>
    </div>

    <script>
        const gombalanList = [
            '"Kamu seperti kopi pagi, bikin aku semangat menjalani hari."',
            '"Kalau aku jadi hujan, maukah kamu jadi pelangi yang selalu muncul setelah aku?"',
            '"Cinta itu buta, tapi kalau sama kamu, aku nggak peduli."',
            '"Kalau kamu bunga, aku mau jadi embun yang selalu menemanimu."',
            '"Melihatmu tersenyum saja sudah cukup membuat hari-hariku bahagia."'
        ];

        function showLove() {
            const randomIndex = Math.floor(Math.random() * gombalanList.length);
            const gombalan = gombalanList[randomIndex];
            document.getElementById('gombalan').innerText = gombalan;
        }
    </script>
</body>
</html>
