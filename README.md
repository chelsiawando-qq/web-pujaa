# my-web
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Datang!</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Memastikan div mengisi seluruh tinggi viewport */
            background-color: #f0f2f5; /* Warna latar belakang body */
        }
        .welcome-container {
            background-color: #3498db; /* Warna biru cerah */
            color: white;
            padding: 40px 60px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            max-width: 800px;
            margin: 20px;
        }
        .welcome-container h1 {
            font-size: 3em;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }
        .welcome-container p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .welcome-container button {
            background-color: #e67e22; /* Warna oranye */
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 8px;
            font-size: 1.1em;
            cursor: pointer;
            margin-top: 25px;
            transition: background-color 0.3s ease;
        }
        .welcome-container button:hover {
            background-color: #d35400; /* Warna oranye lebih gelap saat hover */
        }
    </style>
</head>
<body>
    <div class="welcome-container">
        <h1>Selamat Datang di Website Saya!</h1>
        <p>Kami senang Anda berkunjung. Jelajahi berbagai informasi dan layanan yang kami tawarkan.</p>
        <button onclick="alert('Terima kasih sudah menjelajah!')">Mulai Sekarang</button>
    </div>
</body>
</html>
