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
/* Hiệu ứng tiêu đề header */
.header-animate {
    animation: slide-down 1.5s ease-out;
}

@keyframes slide-down {
    from {
        opacity: 0;
        transform: translateY(-50px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Hiệu ứng fade-in cho các section */
.fade-in {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 1s, transform 1s;
}

.fade-in.visible {
    opacity: 1;
    transform: translateY(0);
}

/* Hiệu ứng hover cho nút */
.btn-hover {
    color: white;
    background-color: #007BFF;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s, transform 0.3s;
}

.btn-hover:hover {
    background-color: #0056b3;
    transform: scale(1.1);
}

/* Hiệu ứng bounce cho footer */
.footer-bounce {
    animation: bounce 2s infinite;
}

@keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
    }
    40% {
        transform: translateY(-10px);
    }
    60% {
        transform: translateY(-5px);
    }
}
