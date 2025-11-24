
 <!DOCTYPE html><html lang="vi">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Website Mẫu</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #0d0d0d;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        header {
            padding: 40px 0;
            background: linear-gradient(45deg, #ff00cc, #3333ff);
        }
        header h1 {
            font-size: 40px;
            margin: 0;
        }
        .section {
            padding: 40px 20px;
        }
        .btn {
            padding: 12px 25px;
            background: #00ffff;
            color: #000;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }
        footer {
            margin-top: 40px;
            padding: 20px;
            background: #111;
        }
    </style>
</head>
<body>
    <header>
        <h1>Website Mẫu</h1>
        <p>Tạo bằng điện thoại – đơn giản & đẹp</p>
    </header><div class="section">
    <h2>Giới thiệu</h2>
    <p>Đây là một trang web mẫu cơ bản để bạn học và chỉnh sửa.</p>
    <a href="#" class="btn">Khám phá thêm</a>
</div>

<div class="section" style="background: #111;">
    <h2>Dịch vụ</h2>
    <p>Bạn có thể thêm nội dung như: portfolio, dự án, âm nhạc, hình ảnh...</p>
</div>

<footer>
    <p>© 2025 - Website Mẫu bởi YungK</p>
</footer>

<!-- Music Section -->
<div class="section" style="background:#000;">
    <h2>Âm nhạc của tôi</h2>
    <p>Danh sách bài nhạc:</p>

    <style>
        .music-item {
            display: flex;
            align-items: center;
            gap: 15px;
            background: #111;
            padding: 15px;
            margin: 10px 0;
            border-radius: 12px;
            transition: 0.3s;
        }
        .music-item:hover {
            background: #222;
            box-shadow: 0 0 10px #0ff;
        }
        .music-item img {
            width: 70px;
            height: 70px;
            border-radius: 10px;
            object-fit: cover;
        }
        .music-item a {
            text-decoration: none;
            color: #0ff;
            font-size: 18px;
            font-weight: bold;
        }
    </style>

    <div class="music-item">
        <img src="cover1.jpg" />
        <a href="#">🔥 YungK - Ngu Thê Hận (Remake)</a>
    </div>

    <div class="music-item">
        <img src="cover2.jpg" />
        <a href="#">🎧 Obito - Chưa Xong (YungK Remix)</a>
    </div>

    <div class="music-item">
        <img src="cover3.jpg" />
        <a href="#">💿 Drill Great Drought (Prod. YungK)</a>
    </div>

    <div class="music-item">
        <img src="cover4.jpg" />
        <a href="#">🎵 Love Is Me - Wines (Prod. YungK)</a>
    </div>

    <h3>Trình phát nhạc nâng cao</h3>
    <audio id="player" controls style="width:90%; max-width:400px;"></audio>

    <script>
        const player = document.getElementById("player");
        // Danh sách bài nhạc mẫu
        const playlist = [
            "music1.mp3",
            "music2.mp3",
            "music3.mp3",
            "music4.mp3"
        ];
        player.src = playlist[0];
    </script>
</div>

</body>
</html> trình phát nhạc chuyên nghiệp hơn (có thanh chạy, visualizer)?
