<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smoothie. | Fresh & Organic</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;1,400&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="navbar container">
            <a href="#" class="logo">Smoothie<span>.</span></a>
            <nav class="nav-links">
                <a href="#hero">Trang Chủ</a>
                <a href="#about">Về Chúng Tôi</a>
                <a href="#menu">Menu</a>
                <a href="#contact">Liên Hệ</a>
            </nav>
            <div class="menu-toggle" id="mobile-menu">
                <i class="fa-solid fa-bars"></i>
            </div>
        </div>
    </header>

    <section id="hero" class="hero-section">
        <div class="hero-container container">
            <div class="hero-content">
                <span class="sub-title">100% Tự Nhiên & Nguyên Chất</span>
                <h1>Chút Nhẹ Nhàng <br>Cho Ngày <span>Tươi Mát</span></h1>
                <p>Nâng niu cơ thể bạn mỗi ngày bằng những ly smoothie đậm vị trái cây nhiệt đới, không đường hóa học, trọn vẹn dưỡng chất organic.</p>
                <a href="#menu" class="btn">Khám Phá Menu <i class="fa-solid fa-arrow-right"></i></a>
            </div>
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1553530666-ba11a7da3888?auto=format&fit=crop&q=80&w=800" alt="Fresh Smoothie">
                <div class="floating-badge">
                    <i class="fa-solid fa-leaf"></i>
                    <span>Organic Certified</span>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about-section">
        <div class="about-container container">
            <div class="about-image">
                <img src="https://images.unsplash.com/photo-1610970881699-44a5587cabec?auto=format&fit=crop&q=80&w=800" alt="Fresh fruits">
            </div>
            <div class="about-content">
                <span class="section-tag">Câu Chuyện Của Mình</span>
                <h2>Sức Khỏe Đến Từ Sự Nguyên Bản</h2>
                <p>Tại Smoothie., tụi mình tin rằng một lối sống lành mạnh không cần phải quá phức tạp. Mỗi ly sinh tố được xay đều là sự kết hợp hoàn hảo giữa trái cây tươi chuẩn VietGAP và các loại hạt dinh dưỡng cao cấp.</p>
                <div class="about-features">
                    <div class="feature-item">
                        <i class="fa-solid fa-apple-whole"></i>
                        <div>
                            <h4>Trái Cây Tươi Mỗi Ngày</h4>
                            <p>Nhập mới trực tiếp từ nông trại organic vào mỗi buổi sáng.</p>
                        </div>
                    </div>
                    <div class="feature-item">
                        <i class="fa-solid fa-candy-cane"></i>
                        <div>
                            <h4>0% Đường Tinh Luyện</h4>
                            <p>Vị ngọt tự nhiên từ quả chín và mật ong nguyên chất.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="menu" class="menu-section">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Thực Đơn Tươi Mát</span>
                <h2>Lựa Chọn Của Bạn</h2>
                <div class="filter-buttons">
                    <button class="filter-btn active" data-filter="all">Tất Cả</button>
                    <button class="filter-btn" data-filter="detox">Detox & Green</button>
                    <button class="filter-btn" data-filter="energy">Năng Lượng</button>
                    <button class="filter-btn" data-filter="berry">Berry Love</button>
                </div>
            </div>

            <div class="menu-grid">
                <div class="menu-card" data-category="detox">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1610970881699-44a5587cabec?auto=format&fit=crop&q=80&w=600" alt="Green Detox">
                    </div>
                    <div class="card-info">
                        <span class="card-cat">Detox & Green</span>
                        <h3>Green Garden</h3>
                        <p class="ingredients">Cải xoăn kale, táo xanh, chuối, chanh tây và hạt chia.</p>
                        <div class="card-footer">
                            <span class="price">55.000đ</span>
                            <button class="view-detail" data-title="Green Garden" data-desc="Dòng sinh tố thanh lọc cơ thể tối ưu với hàm lượng chất xơ cực cao từ cải Kale kết hợp vị chua nhẹ của táo xanh. Thích hợp cho buổi sáng nhẹ nhàng." data-img="https://images.unsplash.com/photo-1610970881699-44a5587cabec?auto=format&fit=crop&q=80&w=600"><i class="fa-solid fa-eye"></i></button>
                        </div>
                    </div>
                </div>

                <div class="menu-card" data-category="energy">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1553530666-ba11a7da3888?auto=format&fit=crop&q=80&w=600" alt="Mango Energy">
                    </div>
                    <div class="card-info">
                        <span class="card-cat">Năng Lượng</span>
                        <h3>Tropical Mango</h3>
                        <p class="ingredients">Xoài chín, chanh dây, sữa hạnh nhân và yến mạch.</p>
                        <div class="card-footer">
                            <span class="price">60.000đ</span>
                            <button class="view-detail" data-title="Tropical Mango" data-desc="Nạp ngay năng lượng tràn đầy với vị xoài cát chín mọng hòa quyện cùng chút chua thanh của chanh dây. Cung cấp vitamin C dồi dào cho ngày làm việc năng suất." data-img="https://images.unsplash.com/photo-1553530666-ba11a7da3888?auto=format&fit=crop&q=80&w=600"><i class="fa-solid fa-eye"></i></button>
                        </div>
                    </div>
                </div>

                <div class="menu-card" data-category="berry">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1577805947697-89e18249d767?auto=format&fit=crop&q=80&w=600" alt="Berry Smoothie">
                    </div>
                    <div class="card-info">
                        <span class="card-cat">Berry Love</span>
                        <h3>Pinky Berry</h3>
                        <p class="ingredients">Dâu tây, việt quất, sữa chua Hy Lạp và mật ong.</p>
                        <div class="card-footer">
                            <span class="price">65.000đ</span>
                            <button class="view-detail" data-title="Pinky Berry" data-desc="Sự kết hợp ngọt ngào chống oxy hóa tuyệt vời từ các loại quả mọng. Sữa chua Hy Lạp giúp kết cấu mịn màng và bổ sung lợi khuẩn cho hệ tiêu hóa." data-img="https://images.unsplash.com/photo-1577805947697-89e18249d767?auto=format&fit=crop&q=80&w=600"><i class="fa-solid fa-eye"></i></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <div class="contact-container container">
            <div class="contact-info">
                <span class="section-tag">Liên Hệ</span>
                <h2>Ghé Chơi Với <br>Tụi Mình</h2>
                <p>Bạn có thắc mắc về công thức hay muốn đặt đơn hàng lớn? Đừng ngần ngại nhắn cho Smoothie. nhé!</p>
                <div class="info-links">
                    <div class="info-item">
                        <i class="fa-solid fa-location-dot"></i>
                        <span>Thành phố Hồ Chí Minh, Việt Nam</span>
                    </div>
                    <div class="info-item">
                        <i class="fa-solid fa-phone"></i>
                        <span>+84 901 234 567</span>
                    </div>
                    <div class="info-item">
                        <i class="fa-solid fa-envelope"></i>
                        <span>hello@smoothie.vn</span>
                    </div>
                </div>
            </div>
            <div class="contact-form">
                <form id="form-contact">
                    <div class="form-group">
                        <input type="text" placeholder="Tên của bạn" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Email liên hệ" required>
                    </div>
                    <div class="form-group">
                        <textarea rows="4" placeholder="Lời nhắn gửi đến Smoothie..." required></textarea>
                    </div>
                    <button type="submit" class="btn btn-block">Gửi Tin Nhắn</button>
                </form>
            </div>
        </div>
    </section>

    <footer>
        <div class="container footer-content">
            <p>&copy; 2026 Smoothie. All rights reserved. Crafted with tươi mát.</p>
            <div class="socials">
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
                <a href="#"><i class="fa-brands fa-facebook"></i></a>
                <a href="#"><i class="fa-brands fa-tiktok"></i></a>
            </div>
        </div>
    </footer>

    <div class="modal" id="detail-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <div class="modal-body">
                <img id="modal-img" src="" alt="">
                <div class="modal-text">
                    <h3 id="modal-title">Tên Món</h3>
                    <p id="modal-desc">Mô tả chi tiết món ăn ở đây...</p>
                </div>
            </div>
        </div>
    </div>

    <button id="backToTop"><i class="fa-solid fa-arrow-up"></i></button>

    <script src="script.js"></script>
</body>
</html>
