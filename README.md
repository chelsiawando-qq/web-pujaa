# my-web
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Datang di Web Saya</title>
    <style>
        /* Menggunakan font modern */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
        }

        /* Hero Section dengan Gradien agar tidak flat */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        /* Container Formulir */
        .container {
            max-width: 600px;
            margin: -50px auto 50px auto; /* Menaikkan form sedikit ke atas hero */
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        h2 {
            color: #764ba2;
            text-align: center;
        }

        /* Styling Input */
        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input[type="text"], 
        input[type="email"], 
        textarea {
            width: 100%;
            padding: 12px;
            border: 2px solid #eee;
            border-radius: 8px;
            box-sizing: border-box; /* Agar padding tidak merusak lebar */
            transition: border-color 0.3s;
        }

        input:focus, textarea:focus {
            border-color: #667eea;
            outline: none;
        }

        /* Tombol Kirim */
        button {
            width: 100%;
            background: #764ba2;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            transition: transform 0.2s, background 0.3s;
        }

        button:hover {
            background: #667eea;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>

    <div class="hero">
        <h1>Halo, Selamat Datang!</h1>
        <p>Terima kasih telah berkunjung ke ruang digital saya.</p>
    </div>

    <div class="container">
        <h2>Tinggalkan Pesan</h2>
        <form action="#">
            <div class="form-group">
                <label for="name">Nama</label>
                <input type="text" id="name" placeholder="Masukkan nama Anda..." required>
            </div>
            
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" placeholder="nama@email.com" required>
            </div>

            <div class="form-group">
                <label for="message">Pesan</label>
                <textarea id="message" rows="5" placeholder="Tuliskan sesuatu untuk saya..."></textarea>
            </div>

            <button type="submit">Kirim Pesan Sekarang</button>
        </form>
    </div>

</body>
</html>
