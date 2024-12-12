<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lớp 12 Lý - Trường Chuyên Bến Tre</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header-animate">
        <h1>Lớp 12 Lý - Trường Chuyên Bến Tre</h1>
        <p>"Đoàn kết - Sáng tạo - Thành công"</p>
    </header>
    <nav>
        <a href="#about-class" class="btn-hover">Giới thiệu lớp</a>
        <a href="#about-school" class="btn-hover">Giới thiệu trường</a>
        <a href="#contact" class="btn-hover">Liên hệ</a>
    </nav>
    <section id="about-class" class="fade-in">
        <h2>Giới thiệu lớp</h2>
        <p>Lớp 12 Lý là một tập thể đoàn kết, nhiệt huyết với nhiều thành tích nổi bật trong học tập và các hoạt động ngoại khóa.</p>
        <img src="https://github.com/user-attachments/assets/dfe5084a-285b-4dfc-8d8d-a270ddb55299">="Ảnh lớp 12 Lý">
    </section>
    <section id="about-school" class="fade-in">
        <h2>Giới thiệu Trường Chuyên Bến Tre</h2>
        <p>Trường Chuyên Bến Tre là nơi nuôi dưỡng và phát triển các tài năng trẻ, với nhiều thành tích nổi bật trên các đấu trường quốc gia và quốc tế.</p>
        <img src="https://github.com/user-attachments/assets/158ee20e-3933-487e-8355-99ae74d5ed49>="Ảnh Trường Chuyên Bến Tre">
    </section>
    <footer id="contact" class="footer-bounce">
        <h2>Liên hệ</h2>
        <p>Địa chỉ: Số ... đường ..., Thành phố Bến Tre</p>
        <p>Email: info@chuyenbentre.edu.vn</p>
        <p>Điện thoại: 02973 ... ...</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #007BFF;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}

nav {
    display: flex;
    justify-content: center;
    background: #333;
    padding: 0.5rem 0;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 1rem;
}

nav a:hover {
    text-decoration: underline;
}

section {
    padding: 2rem;
    margin: 1rem auto;
    max-width: 900px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    padding: 1rem 0;
    background: #007BFF;
    color: #fff;
    margin-top: 1rem;
}
