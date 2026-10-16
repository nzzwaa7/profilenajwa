<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Najwa Muthmainnah | Web Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            min-height: 100vh;
            display: flex;
            align-items: center;
            background: linear-gradient(120deg, #fdfbfb, #f0e6ee);
            padding: 30px 50px;
        }

        .container {
            display: flex;
            align-items: center;
            gap: 50px;
            max-width: 1100px;
            margin: 0 auto;
            width: 100%;
        }

        .image-box {
            flex-shrink: 0;
        }

        .image-box img {
            width: 320px;
            height: 400px;
            object-fit: cover;
            border-radius: 16px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
            border: 4px solid #fff;
        }

        .text-box {
            flex: 1;
        }

        h1 {
            font-size: 2.4rem;
            color: #2c2c2c;
            line-height: 1.5;
        }

        .name {
            color: #9b59b6;
        }

        .role {
            font-size: 1.4rem;
            color: #666;
            margin-top: 12px;
            font-weight: 500;
        }

        /* Untuk HP */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                text-align: center;
                gap: 30px;
            }
            h1 {
                font-size: 1.6rem;
            }
            .image-box img {
                width: 260px;
                height: 320px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Gambar di Kiri -->
        <div class="image-box">
            <img src="najwa.jpg" alt="Najwa Muthmainnah">
        </div>

        <!-- Teks di Kanan -->
        <div class="text-box">
            <h1>Hello, my name is<br>
            <span class="name">Najwa Muthmainnah</span></h1>
            <p class="role">💻 Web Developer</p>
        </div>
    </div>
</body>
</html>

