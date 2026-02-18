# web-pujaa
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Datang di Web Puja</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Lora:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* General Styles */
        body {
            font-family: 'Lora', serif; /* Font serif untuk kesan elegan */
            margin: 0;
            padding: 0;
            background-color: #f8f8f8; /* Warna latar belakang sangat terang */
            color: #333;
            overflow-x: hidden; /* Mencegah scroll horizontal */
        }

        /* Hero Section - The Main Visual */
        .hero {
            position: relative;
            width: 100%;
            height: 100vh; /* Mengisi seluruh tinggi layar */
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            overflow: hidden; /* Pastikan gambar tidak keluar */
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://via.placeholder.com/1500x800/dcdcdc/ffffff?text=Gambar+Estetik+Anda+Disini'); /* Placeholder image */
            /* GANTI URL INI dengan gambar Anda yang estetik dan berkualitas tinggi! */
            background-size: cover;
            background-position: center;
            filter: brightness(0.7) grayscale(0.2); /* Sedikit gelap dan monokrom untuk kesan tenang */
            z-index: 1;
            transition: all 0.5s ease-in-out;
        }
        
        /* Optional: Parallax effect for image */
        .hero:hover::before {
            transform: scale(1.05); /* Sedikit zoom saat hover */
        }

        .hero-content {
            position: relative;
            z-index: 2; /* Pastikan teks di atas gambar */
            max-width: 800px;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.3); /* Latar belakang semi-transparan untuk teks */
            border-radius: 10px;
        }

        .hero h1 {
            font-family: 'Playfair Display', serif; /* Font dekoratif untuk judul utama */
            font-size: 4.5rem; /* Ukuran font besar */
            margin-bottom: 10px;
            letter-spacing: 2px; /* Jarak antar huruf */
            text-shadow: 2px 2px 8px rgba(0,0,0,0.5); /* Bayangan teks agar lebih menonjol */
        }

        .hero p {
            font-size: 1.5rem;
            line-height: 1.6;
            margin-top: 20px;
            text-shadow: 1px 1px 5px rgba(0,0,0,0.4);
        }

        /* Subtle Animation on Load */
        @keyframes fadeInScale {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }

        .hero-content {
            animation: fadeInScale 1.5s ease-out forwards;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 3rem;
            }
            .hero p {
                font-size: 1.2rem;
            }
        }

        @media (max-width: 480px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            .hero p {
                font-size: 1rem;
            }
            .hero-content {
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <div class="hero">
        <div class="hero-content">
            <h1>Selamat Datang di Dunia Puja</h1>
            <p>Ruang untuk inspirasi, ketenangan, dan cerita yang mengalir.</p>
        </div>
    </div>

</body>
</html>
