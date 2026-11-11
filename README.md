<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Trung Tâm Phát Triển Âm Nhạc SEN HỒNG | Đào Tạo Âm Nhạc & Nhạc Cụ Đà Nẵng</title>
    <meta name="description" content="Trung tâm Phát triển Âm nhạc SEN HỒNG (amnhacsenhong.com) tại 362/10 Tôn Đức Thắng, Phường Hòa Khánh, TP. Đà Nẵng. Chuyên đào tạo Piano, Organ, Guitar, Trống, Violin, Thanh nhạc và cung cấp nhạc cụ chính hãng. Hotline: 0982.567.156.">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://amnhacsenhong.com/">
    <meta property="og:site_name" content="amnhacsenhong.com">
    <meta property="og:title" content="Trung Tâm Phát Triển Âm Nhạc SEN HỒNG - amnhacsenhong.com">
    <meta property="og:description" content="Đào tạo Piano, Organ, Guitar, Violin, Trống, Thanh nhạc & Phân phối nhạc cụ chính hãng tại 362/10 Tôn Đức Thắng, Hòa Khánh, Đà Nẵng. ĐT: 0982.567.156">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH">
    <meta property="og:image:alt" content="Logo Trung tâm Phát triển Âm nhạc SEN HỒNG">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        lotus: {
                            50: '#fdf2f7',
                            100: '#fce7f1',
                            200: '#fad0e4',
                            300: '#f7a9cd',
                            400: '#f175ac',
                            500: '#e6488d',
                            600: '#c81e5b', /* Màu hồng sen chủ đạo theo logo */
                            700: '#ab164b',
                            800: '#8e163f',
                            900: '#771737',
                        },
                        gold: {
                            500: '#d97706',
                            600: '#b45309',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền & lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome rộng 1500px trên máy tính */
        .container-flatsome {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 15px;
            padding-right: 15px;
        }

        /* Danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, tuyệt đối không xuống dòng giữa chừng tên danh mục */
        .desktop-cat-nav {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 6px;
        }
        .desktop-cat-link {
            white-space: nowrap;
            font-size: 12.5px;
            line-height: 1.2;
            font-weight: 600;
            padding: 7px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
            color: #ffffff;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }
        .desktop-cat-link:hover, .desktop-cat-link.active {
            background-color: rgba(255, 255, 255, 0.2);
            color: #fde047;
        }

        /* Nút danh mục nhỏ gọn ở trang chủ */
        .home-cat-pill {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            padding: 7px 12px;
            border-radius: 6px;
            border: 1px solid #f3d1df;
            background-color: #fff;
            color: #334155;
            transition: all 0.2s ease;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 5px;
        }
        .home-cat-pill:hover, .home-cat-pill.active {
            background-color: #c81e5b;
            color: #ffffff;
            border-color: #c81e5b;
        }

        /* Huy hiệu % giảm giá chuẩn Flatsome góc trên bên trái sản phẩm */
        .flatsome-sale-badge {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            background-color: #c81e5b;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            width: 42px;
            height: 42px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(200, 30, 91, 0.35);
            line-height: 1;
        }

        /* Tên sản phẩm: hiển thị đầy đủ, không bị cắt chữ hoặc tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            margin-bottom: 10px;
        }
        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            flex: 1;
            max-width: 120px;
            height: 2px;
            background-color: #f3d1df;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 30, 91, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 30, 91, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 30, 91, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- ================= TOP BAR (FLATSOME TOPBAR) ================= -->
    <div class="bg-lotus-900 text-white text-xs py-2 border-b border-lotus-800">
        <div class="container-flatsome flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
                <span class="font-semibold text-amber-300">
                    <i class="fa-solid fa-music mr-1"></i> TRUNG TÂM PHÁT TRIỂN ÂM NHẠC SEN HỒNG
                </span>
                <span class="hidden md:inline-block text-lotus-100">
                    <i class="fa-solid fa-location-dot mr-1 text-amber-300"></i> 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-4 text-lotus-100">
                <a href="https://amnhacsenhong.com" class="hover:text-white transition">
                    <i class="fa-solid fa-globe mr-1 text-amber-300"></i> amnhacsenhong.com
                </a>
                <a href="https://www.facebook.com/profile.php?id=61567857644286" target="_blank" rel="noopener noreferrer" class="hover:text-white transition">
                    <i class="fa-brands fa-facebook mr-1 text-amber-300"></i> Fanpage Sen Hồng
                </a>
            </div>
        </div>
    </div>

    <!-- ================= HEADER CHÍNH (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-100">
        <!-- Main Header Row -->
        <div class="container-flatsome py-2.5 flex items-center justify-between gap-3">
            <!-- Nút mở menu trên điện thoại -->
            <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2.5 rounded-lg bg-lotus-50 text-lotus-600 hover:bg-lotus-100 transition flex-shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>

            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#" class="flex items-center gap-2.5 min-w-0">
                <img 
                    src="https://lh3.googleusercontent.com/d/1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH" 
                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH&sz=w400';"
                    alt="Logo Trung tâm Phát triển Âm nhạc SEN HỒNG" 
                    class="h-10 sm:h-11 md:h-12 w-auto object-contain rounded-md flex-shrink-0 border border-lotus-100 bg-white p-0.5"
                >
                <div class="min-w-0">
                    <div class="text-xs sm:text-sm md:text-base font-extrabold text-lotus-600 tracking-tight leading-tight">
                        ÂM NHẠC SEN HỒNG
                    </div>
                    <div class="text-[10px] sm:text-xs text-slate-500 font-medium leading-tight">
                        amnhacsenhong.com • Đà Nẵng
                    </div>
                </div>
            </a>

            <!-- Ô tìm kiếm ở giữa trên máy tính (giống cấu trúc Flatsome Header) -->
            <div class="hidden md:flex flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input 
                        type="text" 
                        id="searchInputDesktop"
                        oninput="handleSearchProduct(this.value)"
                        placeholder="Tìm đàn Piano, Organ, Guitar, Khóa học âm nhạc..." 
                        class="w-full pl-3.5 pr-10 py-2 text-xs rounded-full border border-lotus-200 focus:outline-none focus:border-lotus-600 bg-lotus-50/40"
                    >
                    <button type="button" aria-label="Tìm kiếm" class="absolute right-1.5 top-1/2 -translate-y-1/2 w-7 h-7 rounded-full bg-lotus-600 text-white flex items-center justify-center text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- Khu vực dẫn hướng nhanh bên phải (Không để nút gọi ngay tránh tràn viền) -->
            <div class="flex items-center gap-2 flex-shrink-0">
                <a href="#form-bao-gia" class="text-xs font-semibold px-3 py-2 rounded-lg bg-lotus-50 text-lotus-700 hover:bg-lotus-100 transition">
                    <i class="fa-solid fa-file-signature mr-1"></i> Tư vấn & Báo giá
                </a>
                <a href="#bando-fanpage" class="hidden sm:inline-flex text-xs font-semibold px-3 py-2 rounded-lg border border-slate-200 text-slate-700 hover:border-lotus-600 hover:text-lotus-600 transition">
                    <i class="fa-solid fa-map-location-dot mr-1 text-lotus-600"></i> Chỉ đường
                </a>
            </div>
        </div>

        <!-- THANH DANH MỤC TRÊN MÁY TÍNH (Viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2, không xuống dòng tên danh mục) -->
        <nav class="hidden lg:block bg-lotus-600 border-t border-lotus-700">
            <div class="container-flatsome py-1.5">
                <div class="desktop-cat-nav">
                    <a href="#gioi-thieu" class="desktop-cat-link active"><i class="fa-solid fa-house text-[11px]"></i> Trang Chủ</a>
                    <a href="#gioi-thieu" class="desktop-cat-link">Giới Thiệu</a>
                    <a href="#khoa-hoc" class="desktop-cat-link">Khóa Học Piano</a>
                    <a href="#khoa-hoc" class="desktop-cat-link">Khóa Học Organ</a>
                    <a href="#khoa-hoc" class="desktop-cat-link">Khóa Học Guitar</a>
                    <a href="#khoa-hoc" class="desktop-cat-link">Khóa Học Đánh Trống</a>
                    <a href="#khoa-hoc" class="desktop-cat-link">Khóa Học Violin</a>
                    <a href="#khoa-hoc" class="desktop-cat-link">Khóa Học Thanh Nhạc</a>
                    <a href="#san-pham" onclick="filterProducts('piano-co')" class="desktop-cat-link">Đàn Piano Cơ</a>
                    <a href="#san-pham" onclick="filterProducts('piano-dien')" class="desktop-cat-link">Đàn Piano Điện</a>
                    <a href="#san-pham" onclick="filterProducts('organ')" class="desktop-cat-link">Đàn Organ</a>
                    <a href="#san-pham" onclick="filterProducts('guitar-acoustic')" class="desktop-cat-link">Đàn Guitar Acoustic</a>
                    <a href="#san-pham" onclick="filterProducts('guitar-classic')" class="desktop-cat-link">Đàn Guitar Classic</a>
                    <a href="#san-pham" onclick="filterProducts('ukulele')" class="desktop-cat-link">Đàn Ukulele</a>
                    <a href="#san-pham" onclick="filterProducts('trong-violin')" class="desktop-cat-link">Bộ Trống & Violin</a>
                    <a href="#form-bao-gia" class="desktop-cat-link">Thuê Nhạc Cụ & Phòng Tập</a>
                    <a href="#tin-tuc" class="desktop-cat-link">Kiến Thức & Tin Tức</a>
                    <a href="#bando-fanpage" class="desktop-cat-link">Liên Hệ</a>
                </div>
            </div>
        </nav>

        <!-- Thanh Danh Mục Ngang Gọn Đẹp Trên Điện Thoại -->
        <div class="lg:hidden bg-lotus-600 text-white border-t border-lotus-700">
            <div class="container-flatsome py-1.5 flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                <a href="#khoa-hoc" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Khóa Học Piano & Organ</a>
                <a href="#san-pham" onclick="filterProducts('piano-co')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Đàn Piano Cơ</a>
                <a href="#san-pham" onclick="filterProducts('piano-dien')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Đàn Piano Điện</a>
                <a href="#san-pham" onclick="filterProducts('organ')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Đàn Organ</a>
                <a href="#san-pham" onclick="filterProducts('guitar-acoustic')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Đàn Guitar</a>
                <a href="#san-pham" onclick="filterProducts('ukulele')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Đàn Ukulele</a>
                <a href="#form-bao-gia" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-white/15">Báo Giá</a>
            </div>
        </div>
    </header>

    <!-- ================= MENU TRƯỢT TRÊN ĐIỆN THOẠI (FLATSOME OFF-CANVAS MENU) ================= -->
    <div id="mobileMenuModal" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="fixed inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[85vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-lotus-600 text-white flex items-center justify-between">
                <span class="font-bold text-sm">DANH MỤC SEN HỒNG</span>
                <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded-full bg-white/20 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-3 border-b border-slate-100">
                <input 
                    type="text" 
                    oninput="handleSearchProduct(this.value)"
                    placeholder="Tìm nhạc cụ, khóa học..." 
                    class="w-full px-3 py-2 text-xs rounded-lg border border-slate-200 focus:outline-none focus:border-lotus-600"
                >
            </div>
            <div class="p-3 space-y-1 text-xs font-semibold text-slate-700">
                <div class="text-[11px] font-bold uppercase text-lotus-600 px-2 pt-1 pb-1">Khóa Học Âm Nhạc</div>
                <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Khóa Học Piano (Trẻ em & Người lớn)</a>
                <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Khóa Học Đàn Organ</a>
                <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Khóa Học Guitar Đệm Hát & Điện</a>
                <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Khóa Học Đánh Trống (Drum)</a>
                <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Khóa Học Đàn Violin</a>
                <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Khóa Học Thanh Nhạc</a>

                <div class="text-[11px] font-bold uppercase text-lotus-600 px-2 pt-3 pb-1 border-t border-slate-100">Danh Mục Nhạc Cụ</div>
                <a href="#san-pham" onclick="filterProducts('piano-co'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Đàn Piano Cơ</a>
                <a href="#san-pham" onclick="filterProducts('piano-dien'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Đàn Piano Điện</a>
                <a href="#san-pham" onclick="filterProducts('organ'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Đàn Organ</a>
                <a href="#san-pham" onclick="filterProducts('guitar-acoustic'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Đàn Guitar Acoustic</a>
                <a href="#san-pham" onclick="filterProducts('guitar-classic'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Đàn Guitar Classic</a>
                <a href="#san-pham" onclick="filterProducts('ukulele'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Đàn Ukulele</a>
                <a href="#san-pham" onclick="filterProducts('trong-violin'); toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Bộ Trống (Drum) & Đàn Violin</a>

                <div class="text-[11px] font-bold uppercase text-lotus-600 px-2 pt-3 pb-1 border-t border-slate-100">Thông Tin Trung Tâm</div>
                <a href="#hinh-anh-trung-tam" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Hình Ảnh Lớp Học Thực Tế</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Tin Tức & Kiến Thức Âm Nhạc</a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Yêu Cầu Tư Vấn & Báo Giá</a>
                <a href="#bando-fanpage" onclick="toggleMobileMenu()" class="block px-2.5 py-2 rounded hover:bg-lotus-50">Bản Đồ & Liên Hệ (0982.567.156)</a>
            </div>
        </div>
    </div>

    <!-- ================= SLIDER 2 BANNER TỰ TRƯỢT (THIẾT KẾ RIÊNG CHO MÁY TÍNH & ĐIỆN THOẠI, KÍCH THƯỚC BẰNG NHAU, CHỮ NHỎ GỌN TRONG ẢNH) ================= -->
    <section class="py-3 bg-lotus-50/50">
        <div class="container-flatsome">
            <div class="relative rounded-xl overflow-hidden shadow-md border border-lotus-100">

                <!-- ====== PHIÊN BẢN BANNER MÁY TÍNH (hidden md:block - 2 Slide bằng nhau h-[360px] lg:h-[400px]) ====== -->
                <div class="hidden md:block relative w-full h-[360px] lg:h-[400px]">
                    <!-- Desktop Slide 1 -->
                    <div id="desktopSlide0" class=" banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-lotus-900 via-lotus-700 to-lotus-600 flex items-center">
                        <div class="w-full h-full grid grid-cols-12 items-center px-12 lg:px-16 py-6 gap-6">
                            <!-- Chữ bên trong ảnh banner: chỉnh chữ nhỏ gọn nằm hết trong ảnh banner -->
                            <div class="col-span-7 text-white space-y-3 pr-4">
                                <div class="text-xs font-semibold uppercase tracking-wider text-amber-300">
                                    TRUNG TÂM PHÁT TRIỂN ÂM NHẠC SEN HỒNG • AMNHACSENHONG.COM
                                </div>
                                <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                    Đào Tạo Piano, Organ, Guitar, Violin & Thanh Nhạc Uy Tín Tại Đà Nẵng
                                </h1>
                                <p class="text-xs lg:text-sm text-lotus-100 leading-relaxed max-w-xl">
                                    Không gian học tập hiện đại, lộ trình bài bản cho trẻ em và người lớn. Đội ngũ giảng viên tận tâm giúp học viên nắm vững nhạc lý, kỹ thuật và tự tin biểu diễn.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-amber-200 font-medium">
                                    <span><i class="fa-solid fa-location-dot mr-1"></i> 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-phone mr-1"></i> Hotline: 0982.567.156</span>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#form-bao-gia" class="px-4 py-2 rounded-lg bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold text-xs transition">
                                        Đăng Ký Học Thử Ngay
                                    </a>
                                    <a href="#khoa-hoc" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs border border-white/30 transition">
                                        Xem Các Khóa Học
                                    </a>
                                </div>
                            </div>
                            <!-- Khung ảnh thực tế tại trung tâm nằm gọn bên trong banner -->
                            <div class="col-span-5 grid grid-cols-2 gap-2.5 h-[270px] lg:h-[300px]">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1WysImJqjsY9kl66gloCCdkYULXnUIrJz" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WysImJqjsY9kl66gloCCdkYULXnUIrJz&sz=w800';"
                                        alt="Lớp học âm nhạc Sen Hồng" 
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                                <div class="grid grid-rows-2 gap-2.5 h-full">
                                    <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg">
                                        <img 
                                            src="https://lh3.googleusercontent.com/d/18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q" 
                                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q&sz=w800';"
                                            alt="Học viên tại trung tâm Sen Hồng" 
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                    <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg">
                                        <img 
                                            src="https://lh3.googleusercontent.com/d/1QEMbY6Qb_TRLDIHrfCHug5AV7SwfzUMx" 
                                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1QEMbY6Qb_TRLDIHrfCHug5AV7SwfzUMx&sz=w800';"
                                            alt="Không gian đào tạo âm nhạc Sen Hồng" 
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 (Kích thước bằng nhau h-[360px] lg:h-[400px]) -->
                    <div id="desktopSlide1" class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-slate-900 via-lotus-800 to-lotus-600 flex items-center">
                        <div class="w-full h-full grid grid-cols-12 items-center px-12 lg:px-16 py-6 gap-6">
                            <div class="col-span-7 text-white space-y-3 pr-4">
                                <div class="text-xs font-semibold uppercase tracking-wider text-amber-300">
                                    SHOWROOM NHẠC CỤ SEN HỒNG • GIÁ TỐT & BẢO HÀNH UY TÍN
                                </div>
                                <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                    Chuyên Cung Cấp Đàn Piano Cơ, Piano Điện, Organ, Guitar & Ukulele Chính Hãng
                                </h2>
                                <p class="text-xs lg:text-sm text-lotus-100 leading-relaxed max-w-xl">
                                    Đa dạng các dòng đàn Yamaha, Kawai, Roland, Casio, Kurtzmann tuyển chọn. Hỗ trợ trả góp, bảo hành tận nhà, tặng kèm đầy đủ phụ kiện và giáo trình học đàn.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-amber-200 font-medium">
                                    <span><i class="fa-solid fa-location-dot mr-1"></i> 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-phone mr-1"></i> Tư vấn: 0982.567.156</span>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#san-pham" class="px-4 py-2 rounded-lg bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold text-xs transition">
                                        Xem Sản Phẩm Giảm Giá
                                    </a>
                                    <a href="#form-bao-gia" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs border border-white/30 transition">
                                        Nhận Báo Giá Ưu Đãi
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 grid grid-cols-2 gap-2.5 h-[270px] lg:h-[300px]">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-white h-full">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B&sz=w800';"
                                        alt="Sản phẩm nhạc cụ Sen Hồng" 
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                                <div class="grid grid-rows-2 gap-2.5 h-full">
                                    <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-white">
                                        <img 
                                            src="https://lh3.googleusercontent.com/d/1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ" 
                                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ&sz=w800';"
                                            alt="Đàn Piano thực tế tại Sen Hồng" 
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                    <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-white">
                                        <img 
                                            src="https://lh3.googleusercontent.com/d/1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76" 
                                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76&sz=w800';"
                                            alt="Nhạc cụ chính hãng Sen Hồng" 
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ====== PHIÊN BẢN BANNER ĐIỆN THOẠI MỚI (block md:hidden - Khác với máy tính để tối ưu chữ bên trong ảnh, chữ nhỏ gọn nằm hết trong khung) ====== -->
                <div class="block md:hidden relative w-full h-[270px] sm:h-[290px]">
                    <!-- Mobile Slide 1 -->
                    <div id="mobileSlide0" class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-b from-lotus-800 via-lotus-700 to-lotus-900 p-4 flex flex-col justify-between">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1WysImJqjsY9kl66gloCCdkYULXnUIrJz" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WysImJqjsY9kl66gloCCdkYULXnUIrJz&sz=w500';"
                                alt="Lớp nhạc Sen Hồng" 
                                class="w-16 h-16 rounded-lg object-cover border border-white/40 flex-shrink-0"
                            >
                            <div class="min-w-0">
                                <div class="text-[10px] font-bold text-amber-300 uppercase">AMNHACSENHONG.COM</div>
                                <h2 class="text-sm font-extrabold text-white leading-snug">
                                    Trung Tâm Phát Triển Âm Nhạc SEN HỒNG
                                </h2>
                                <p class="text-[11px] text-lotus-100">Đào tạo Piano • Organ • Guitar • Violin</p>
                            </div>
                        </div>
                        <div class="bg-black/25 rounded-lg p-2.5 text-[11px] text-white space-y-1 border border-white/10">
                            <p class="leading-normal">Lộ trình chuẩn cho Trẻ em & Người lớn. Phòng tập hiện đại, giáo viên tận tâm.</p>
                            <p class="text-amber-300 font-semibold"><i class="fa-solid fa-location-dot mr-1"></i>362/10 Tôn Đức Thắng, Hòa Khánh, Đà Nẵng</p>
                            <p class="text-amber-200 font-semibold"><i class="fa-solid fa-phone mr-1"></i>Hotline / Zalo: 0982.567.156</p>
                        </div>
                        <div class="flex items-center justify-between gap-2">
                            <a href="#form-bao-gia" class="flex-1 text-center py-1.5 rounded bg-amber-400 text-slate-900 font-bold text-[11px]">
                                Đăng Ký Học Thử
                            </a>
                            <a href="#khoa-hoc" class="flex-1 text-center py-1.5 rounded bg-white/15 text-white font-semibold text-[11px] border border-white/30">
                                Xem Khóa Học
                            </a>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 (Kích thước bằng nhau h-[270px] sm:h-[290px]) -->
                    <div id="mobileSlide1" class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-b from-slate-900 via-lotus-800 to-lotus-900 p-4 flex flex-col justify-between">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B&sz=w500';"
                                alt="Nhạc cụ Sen Hồng" 
                                class="w-16 h-16 rounded-lg object-cover border border-white/40 bg-white flex-shrink-0"
                            >
                            <div class="min-w-0">
                                <div class="text-[10px] font-bold text-amber-300 uppercase">NHẠC CỤ CHÍNH HÃNG ĐÀ NẴNG</div>
                                <h2 class="text-sm font-extrabold text-white leading-snug">
                                    Piano Cơ, Piano Điện, Organ & Guitar Giá Tốt
                                </h2>
                                <p class="text-[11px] text-lotus-100">Ưu đãi giảm giá đến 25% tại Showroom</p>
                            </div>
                        </div>
                        <div class="bg-black/25 rounded-lg p-2.5 text-[11px] text-white space-y-1 border border-white/10">
                            <p class="leading-normal">Đầy đủ đàn Yamaha, Kawai, Roland, Casio. Bảo hành uy tín, giao đàn tận nhà.</p>
                            <p class="text-amber-300 font-semibold"><i class="fa-solid fa-location-dot mr-1"></i>362/10 Tôn Đức Thắng, Hòa Khánh, Đà Nẵng</p>
                            <p class="text-amber-200 font-semibold"><i class="fa-solid fa-phone mr-1"></i>Tư vấn mua đàn: 0982.567.156</p>
                        </div>
                        <div class="flex items-center justify-between gap-2">
                            <a href="#san-pham" class="flex-1 text-center py-1.5 rounded bg-amber-400 text-slate-900 font-bold text-[11px]">
                                Xem Đàn Khuyến Mãi
                            </a>
                            <a href="#form-bao-gia" class="flex-1 text-center py-1.5 rounded bg-white/15 text-white font-semibold text-[11px] border border-white/30">
                                Nhận Báo Giá
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider Trái / Phải & Chấm tròn -->
                <button onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="hidden md:flex absolute left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/30 hover:bg-black/50 text-white items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="hidden md:flex absolute right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/30 hover:bg-black/50 text-white items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="setBannerSlide(0)" id="dotSlide0" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="setBannerSlide(1)" id="dotSlide1" aria-label="Banner 2" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= GIỚI THIỆU TRUNG TÂM ÂM NHẠC SEN HỒNG (GIỐNG BỐ CỤC HAOVINHMUSIC.VN) ================= -->
    <section id="gioi-thieu" class="py-10 bg-white">
        <div class="container-flatsome">
            <div class="text-center max-w-3xl mx-auto mb-8">
                <div class="flatsome-section-title">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-lotus-600 uppercase tracking-tight">
                        GIỚI THIỆU TRUNG TÂM PHÁT TRIỂN ÂM NHẠC SEN HỒNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                    Tại <strong>Trung tâm Phát triển Âm nhạc SEN HỒNG</strong>, chúng tôi tin rằng âm nhạc không chỉ là những nốt nhạc mà là ngôn ngữ nuôi dưỡng tâm hồn và trí tuệ. Với đội ngũ giảng viên giàu kinh nghiệm sư phạm, giáo trình bài bản cùng không gian học tập thân thiện tại Hòa Khánh, Đà Nẵng, Sen Hồng đồng hành cùng học viên trên hành trình chinh phục các loại nhạc cụ và tỏa sáng đam mê.
                </p>
            </div>

            <!-- 3 Cột Giá Trị Cốt Lõi (Flatsome Icon Boxes - đơn giản dễ làm lại trên UX Builder) -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-5">
                <div class="p-5 rounded-xl bg-lotus-50/60 border border-lotus-100 text-center space-y-2">
                    <div class="w-12 h-12 rounded-full bg-lotus-600 text-white flex items-center justify-center mx-auto text-lg">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-slate-800">Đào Tạo Tận Tâm & Bài Bản</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Phương pháp giảng dạy dễ hiểu, bám sát năng lực từng học viên từ cơ bản đến nâng cao. Học viên đọc hiểu bản nhạc và thực hành vững vàng ngay tại lớp.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-lotus-50/60 border border-lotus-100 text-center space-y-2">
                    <div class="w-12 h-12 rounded-full bg-lotus-600 text-white flex items-center justify-center mx-auto text-lg">
                        <i class="fa-solid fa-music"></i>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-slate-800">Cơ Sở Vật Chất Nhạc Cụ Hiện Đại</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Trang bị đầy đủ đàn Piano cơ, Piano điện, Organ, Guitar chất lượng cao giúp học viên trải nghiệm âm thanh chuẩn xác và luyện tập hiệu quả.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-lotus-50/60 border border-lotus-100 text-center space-y-2">
                    <div class="w-12 h-12 rounded-full bg-lotus-600 text-white flex items-center justify-center mx-auto text-lg">
                        <i class="fa-solid fa-award"></i>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-slate-800">Nhạc Cụ Chính Hãng Giá Gốc</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Phân phối đàn Piano, Organ, Guitar, Ukulele tuyển chọn kỹ lưỡng với chế độ bảo hành dài hạn và ưu đãi đặc biệt dành cho học viên của trung tâm.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= CÁC KHÓA HỌC ÂM NHẠC (THEO MẪU HAOVINHMUSIC.VN - KHÔNG DÙNG NHÃN DÁN) ================= -->
    <section id="khoa-hoc" class="py-10 bg-slate-50 border-t border-b border-slate-100">
        <div class="container-flatsome">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-lotus-600 uppercase">
                        CÁC KHÓA HỌC ÂM NHẠC TẠI SEN HỒNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">Chiêu sinh liên tục các lớp cho Trẻ em (từ 4 tuổi) và Người lớn tại 362/10 Tôn Đức Thắng, Đà Nẵng</p>
            </div>

            <!-- Lưới 6 khóa học (2 cột trên điện thoại, 3 cột trên máy tính) -->
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3.5 sm:gap-5">
                <!-- Khóa 1: Piano -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-video w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WysImJqjsY9kl66gloCCdkYULXnUIrJz" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WysImJqjsY9kl66gloCCdkYULXnUIrJz&sz=w800';"
                            alt="Khóa học Piano tại Sen Hồng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between space-y-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-lotus-600 product-title-full">KHÓA HỌC ĐÀN PIANO</h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">
                                Nắm vững kiến thức nhạc lý, kỹ thuật luyện ngón, đọc bản nhạc chuẩn xác và tự tin độc tấu, đệm hát các tác phẩm yêu thích.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="selectCourseInForm('Đăng ký Khóa học Đàn Piano')" class="inline-block text-center w-full py-2 rounded-lg bg-lotus-50 hover:bg-lotus-600 text-lotus-600 hover:text-white font-semibold text-xs transition">
                            ĐĂNG KÝ TƯ VẤN
                        </a>
                    </div>
                </div>

                <!-- Khóa 2: Organ -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-video w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q&sz=w800';"
                            alt="Khóa học Organ tại Sen Hồng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between space-y-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-lotus-600 product-title-full">KHÓA HỌC ĐÀN ORGAN</h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">
                                Làm chủ tiết tấu, hợp âm và hòa âm phong phú trên đàn Organ. Phù hợp cho cả thiếu nhi phát triển năng khiếu và người lớn đệm nhạc.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="selectCourseInForm('Đăng ký Khóa học Đàn Organ')" class="inline-block text-center w-full py-2 rounded-lg bg-lotus-50 hover:bg-lotus-600 text-lotus-600 hover:text-white font-semibold text-xs transition">
                            ĐĂNG KÝ TƯ VẤN
                        </a>
                    </div>
                </div>

                <!-- Khóa 3: Guitar Đệm Hát -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-video w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1QEMbY6Qb_TRLDIHrfCHug5AV7SwfzUMx" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1QEMbY6Qb_TRLDIHrfCHug5AV7SwfzUMx&sz=w800';"
                            alt="Khóa học Guitar Đệm Hát" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between space-y-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-lotus-600 product-title-full">KHÓA HỌC GUITAR ĐỆM HÁT & CỔ ĐIỂN</h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">
                                Thực hành hợp âm căn bản, điệu rải âm và quạt chả. Tự đệm đàn và hát cho các giai điệu Acoustic, Bolero, Pop Ballad yêu thích.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="selectCourseInForm('Đăng ký Khóa học Đàn Guitar')" class="inline-block text-center w-full py-2 rounded-lg bg-lotus-50 hover:bg-lotus-600 text-lotus-600 hover:text-white font-semibold text-xs transition">
                            ĐĂNG KÝ TƯ VẤN
                        </a>
                    </div>
                </div>

                <!-- Khóa 4: Đánh Trống -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-video w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1YkH2P-82IP7dYShf6pH7diST27DD1vY9" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YkH2P-82IP7dYShf6pH7diST27DD1vY9&sz=w800';"
                            alt="Khóa học Đánh Trống" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between space-y-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-lotus-600 product-title-full">KHÓA HỌC ĐÁNH TRỐNG (DRUM)</h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">
                                Rèn luyện khả năng cảm nhịp, phối hợp tay chân linh hoạt và thể hiện cá tính năng động qua các tiết tấu sôi động.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="selectCourseInForm('Đăng ký Khóa học Đánh Trống')" class="inline-block text-center w-full py-2 rounded-lg bg-lotus-50 hover:bg-lotus-600 text-lotus-600 hover:text-white font-semibold text-xs transition">
                            ĐĂNG KÝ TƯ VẤN
                        </a>
                    </div>
                </div>

                <!-- Khóa 5: Violin -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-video w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/17LshcRI03jDCtNXrjk_uwqo27K3vTdPC" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17LshcRI03jDCtNXrjk_uwqo27K3vTdPC&sz=w800';"
                            alt="Khóa học Đàn Violin" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between space-y-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-lotus-600 product-title-full">KHÓA HỌC ĐÀN VIOLIN & UKULELE</h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">
                                Rèn luyện sự tập trung, kiên nhẫn và khả năng thẩm âm tinh tế, phát triển tư duy nghệ thuật toàn diện cho học viên.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="selectCourseInForm('Đăng ký Khóa học Violin / Ukulele')" class="inline-block text-center w-full py-2 rounded-lg bg-lotus-50 hover:bg-lotus-600 text-lotus-600 hover:text-white font-semibold text-xs transition">
                            ĐĂNG KÝ TƯ VẤN
                        </a>
                    </div>
                </div>

                <!-- Khóa 6: Thanh Nhạc -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-video w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1j0ozpDq2Og6QJ4GpXe6jt_P08QBOh6VT" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1j0ozpDq2Og6QJ4GpXe6jt_P08QBOh6VT&sz=w800';"
                            alt="Khóa học Thanh Nhạc" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between space-y-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-lotus-600 product-title-full">KHÓA HỌC THANH NHẠC & BIỂU DIỄN</h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">
                                Mở khẩu hình, kiểm soát hơi thở, xử lý cao độ - tiết tấu và làm chủ sân khấu tự tin thể hiện các ca khúc yêu thích.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="selectCourseInForm('Đăng ký Khóa học Thanh Nhạc')" class="inline-block text-center w-full py-2 rounded-lg bg-lotus-50 hover:bg-lotus-600 text-lotus-600 hover:text-white font-semibold text-xs transition">
                            ĐĂNG KÝ TƯ VẤN
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM & SẢN PHẨM TRANG CHỦ (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, HUY HIỆU % GIẢM GIÁ GÓC TRÊN BÊN TRÁI GIỐNG FLATSOME) ================= -->
    <section id="san-pham" class="py-10 bg-white">
        <div class="container-flatsome">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-lotus-600 uppercase">
                        DANH MỤC NHẠC CỤ CHÍNH HÃNG TẠI SEN HỒNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Hình ảnh sản phẩm thực tế tại Trung tâm Phát triển Âm nhạc SEN HỒNG • Giá ưu đãi tốt nhất Đà Nẵng
                </p>
            </div>

            <!-- Thanh Danh Mục Sản Phẩm ở Trang Chủ (Chữ nhỏ gọn, viết liền trên 1 dòng không bị gãy chữ, đẹp trên cả máy tính và điện thoại) -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
                <button onclick="filterProducts('all')" data-cat="all" class="home-cat-pill active">
                    Tất Cả Nhạc Cụ
                </button>
                <button onclick="filterProducts('piano-co')" data-cat="piano-co" class="home-cat-pill">
                    Đàn Piano Cơ
                </button>
                <button onclick="filterProducts('piano-dien')" data-cat="piano-dien" class="home-cat-pill">
                    Đàn Piano Điện
                </button>
                <button onclick="filterProducts('organ')" data-cat="organ" class="home-cat-pill">
                    Đàn Organ
                </button>
                <button onclick="filterProducts('guitar-acoustic')" data-cat="guitar-acoustic" class="home-cat-pill">
                    Đàn Guitar Acoustic
                </button>
                <button onclick="filterProducts('guitar-classic')" data-cat="guitar-classic" class="home-cat-pill">
                    Đàn Guitar Classic
                </button>
                <button onclick="filterProducts('ukulele')" data-cat="ukulele" class="home-cat-pill">
                    Đàn Ukulele
                </button>
                <button onclick="filterProducts('trong-violin')" data-cat="trong-violin" class="home-cat-pill">
                    Bộ Trống & Đàn Violin
                </button>
            </div>

            <!-- LƯỚI SẢN PHẨM: Chia thành 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <div id="productGridContainer" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Các sản phẩm được render tự động từ mảng 12 sản phẩm (bao gồm đầy đủ 8 ảnh thực tế trong file Google Drive) -->
            </div>
        </div>
    </section>

    <!-- ================= HÌNH ẢNH HOẠT ĐỘNG THỰC TẾ TẠI TRUNG TÂM SEN HỒNG (ĐẦY ĐỦ 7 ẢNH TẠI TRUNG TÂM) ================= -->
    <section id="hinh-anh-trung-tam" class="py-10 bg-lotus-50/40 border-t border-b border-lotus-100">
        <div class="container-flatsome">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-lotus-600 uppercase">
                        HÌNH ẢNH LỚP HỌC & HOẠT ĐỘNG TẠI TRUNG TÂM SEN HỒNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Không gian học tập thực tế của học viên tại 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng
                </p>
            </div>

            <!-- Hiển thị đầy đủ 7 ảnh tại trung tâm từ Google Drive -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <!-- Ảnh trung tâm 1 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WysImJqjsY9kl66gloCCdkYULXnUIrJz" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WysImJqjsY9kl66gloCCdkYULXnUIrJz&sz=w800';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 1" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Giờ học thực hành đàn tại Trung tâm Sen Hồng</p>
                    </div>
                </div>

                <!-- Ảnh trung tâm 2 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q&sz=w800';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 2" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Hướng dẫn kỹ thuật ngón tận tình cho học viên</p>
                    </div>
                </div>

                <!-- Ảnh trung tâm 3 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1QEMbY6Qb_TRLDIHrfCHug5AV7SwfzUMx" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1QEMbY6Qb_TRLDIHrfCHug5AV7SwfzUMx&sz=w800';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 3" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Không gian lớp học Piano & Organ chuyên nghiệp</p>
                    </div>
                </div>

                <!-- Ảnh trung tâm 4 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1YkH2P-82IP7dYShf6pH7diST27DD1vY9" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YkH2P-82IP7dYShf6pH7diST27DD1vY9&sz=w800';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 4" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Học viên say mê luyện tập nhạc cụ mỗi ngày</p>
                    </div>
                </div>

                <!-- Ảnh trung tâm 5 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/17LshcRI03jDCtNXrjk_uwqo27K3vTdPC" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17LshcRI03jDCtNXrjk_uwqo27K3vTdPC&sz=w800';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 5" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Rèn luyện nhạc lý và thực hành biểu diễn</p>
                    </div>
                </div>

                <!-- Ảnh trung tâm 6 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1j0ozpDq2Og6QJ4GpXe6jt_P08QBOh6VT" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1j0ozpDq2Og6QJ4GpXe6jt_P08QBOh6VT&sz=w800';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 6" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Hoạt động giao lưu và phát triển năng khiếu âm nhạc</p>
                    </div>
                </div>

                <!-- Ảnh trung tâm 7 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs col-span-2 md:col-span-1 lg:col-span-2">
                    <div class="aspect-[4/3] lg:aspect-[16/6] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1J9mzZAXNHCS_uUzFE1n2sDKDGfj_IQcS" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1J9mzZAXNHCS_uUzFE1n2sDKDGfj_IQcS&sz=w900';"
                            alt="Lớp học đàn tại Trung tâm Âm nhạc Sen Hồng 7" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-semibold text-slate-700 product-title-full">Trung tâm Phát triển Âm nhạc SEN HỒNG - Nơi ươm mầm tài năng âm nhạc Đà Nẵng</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FORM YÊU CẦU TƯ VẤN KHÓA HỌC & BÁO GIÁ NHẠC CỤ TRANG CHỦ ================= -->
    <section id="form-bao-gia" class="py-10 bg-white">
        <div class="container-flatsome">
            <div class="bg-gradient-to-br from-lotus-700 via-lotus-600 to-lotus-800 rounded-2xl p-5 sm:p-8 text-white shadow-lg">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <!-- Cột thông tin bên trái -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="text-xs font-bold uppercase tracking-wider text-amber-300">
                            ĐĂNG KÝ TƯ VẤN & NHẬN BÁO GIÁ NHANH
                        </div>
                        <h2 class="text-lg sm:text-2xl font-extrabold leading-snug">
                            Yêu Cầu Báo Giá Nhạc Cụ & Đăng Ký Học Thử Tại Sen Hồng
                        </h2>
                        <p class="text-xs sm:text-sm text-lotus-100 leading-relaxed">
                            Quý phụ huynh, học viên và khách hàng cần tư vấn chọn mua đàn Piano, Organ, Guitar hoặc đăng ký lịch học phù hợp, vui lòng để lại thông tin. Trung tâm sẽ liên hệ ngay qua số điện thoại / Zalo!
                        </p>
                        <div class="space-y-2 pt-2 text-xs sm:text-sm">
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-amber-300 mt-1"></i>
                                <span><strong>Địa chỉ:</strong> 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <i class="fa-solid fa-phone-volume text-amber-300"></i>
                                <span><strong>Hotline / Zalo:</strong> 0982.567.156</span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <i class="fa-solid fa-globe text-amber-300"></i>
                                <span><strong>Website:</strong> amnhacsenhong.com</span>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form bên phải -->
                    <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-md">
                        <form id="quoteRequestForm" onsubmit="handleQuoteSubmit(event)" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên của bạn *</label>
                                    <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-lotus-600">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="custPhone" required placeholder="Ví dụ: 0982567156" class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-lotus-600">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục quan tâm *</label>
                                    <select id="custInterest" class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-lotus-600 bg-white">
                                        <option value="Báo giá Đàn Piano Cơ / Piano Điện">Báo giá Đàn Piano Cơ / Piano Điện</option>
                                        <option value="Báo giá Đàn Organ / Keyboard">Báo giá Đàn Organ / Keyboard</option>
                                        <option value="Báo giá Đàn Guitar / Ukulele">Báo giá Đàn Guitar / Ukulele</option>
                                        <option value="Đăng ký Khóa học Đàn Piano">Đăng ký Khóa học Đàn Piano</option>
                                        <option value="Đăng ký Khóa học Đàn Organ">Đăng ký Khóa học Đàn Organ</option>
                                        <option value="Đăng ký Khóa học Đàn Guitar">Đăng ký Khóa học Đàn Guitar</option>
                                        <option value="Đăng ký Khóa học Trống / Violin / Thanh Nhạc">Đăng ký Khóa học Trống / Violin / Thanh Nhạc</option>
                                        <option value="Thuê nhạc cụ & Phòng tập">Thuê nhạc cụ & Phòng tập</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Đối tượng học / Nhu cầu</label>
                                    <select id="custTarget" class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-lotus-600 bg-white">
                                        <option value="Mua nhạc cụ cho người mới học">Mua nhạc cụ cho người mới học</option>
                                        <option value="Khóa học cho Trẻ em (4 - 15 tuổi)">Khóa học cho Trẻ em (4 - 15 tuổi)</option>
                                        <option value="Khóa học cho Người lớn / Sinh viên">Khóa học cho Người lớn / Sinh viên</option>
                                        <option value="Luyện thi & Biểu diễn nâng cao">Luyện thi & Biểu diễn nâng cao</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú sản phẩm hoặc khung giờ muốn học</label>
                                <textarea id="custNote" rows="2" placeholder="Nhập tên đàn bạn muốn báo giá hoặc câu hỏi cần tư vấn..." class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-lotus-600"></textarea>
                            </div>

                            <button type="submit" class="w-full py-3 rounded-lg bg-lotus-600 hover:bg-lotus-700 text-white font-bold text-xs sm:text-sm transition shadow-sm">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ NGAY
                            </button>

                            <!-- Hộp thông báo xác nhận gửi thành công (thay thế alert) -->
                            <div id="formSuccessNotice" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC HOẠT ĐỘNG – KIẾN THỨC ÂM NHẠC GIỐNG HAOVINHMUSIC.VN) ================= -->
    <section id="tin-tuc" class="py-10 bg-slate-50 border-t border-b border-slate-100">
        <div class="container-flatsome">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-lotus-600 uppercase">
                        TIN TỨC HOẠT ĐỘNG – KIẾN THỨC ÂM NHẠC
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">Kinh nghiệm chọn mua đàn Piano, Organ, Guitar và hoạt động đào tạo tại Âm Nhạc Sen Hồng</p>
            </div>

            <!-- Lưới 4 bài viết chuẩn Flatsome Blog Posts -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B&sz=w800';"
                            alt="Nên mua đàn piano cơ hay piano điện cho người mới bắt đầu" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <div class="text-[11px] font-semibold text-lotus-600 uppercase">Kiến thức chọn đàn</div>
                            <h3 class="text-sm font-bold text-slate-800 mt-1 product-title-full">
                                Nên Mua Đàn Piano Cơ Hay Piano Điện? Tư Vấn Chọn Đàn Phù Hợp Cho Người Mới Học
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Phân tích ưu nhược điểm về độ nặng phím, chất âm và diện tích không gian để phụ huynh chọn cây đàn ưng ý nhất tại Đà Nẵng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-bold text-lotus-600 hover:underline pt-1 inline-flex items-center gap-1">
                            Nhận tư vấn chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WysImJqjsY9kl66gloCCdkYULXnUIrJz" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WysImJqjsY9kl66gloCCdkYULXnUIrJz&sz=w800';"
                            alt="Học và biểu diễn nhạc cụ giúp trẻ tự tin" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <div class="text-[11px] font-semibold text-lotus-600 uppercase">Hoạt động đào tạo</div>
                            <h3 class="text-sm font-bold text-slate-800 mt-1 product-title-full">
                                Học Và Biểu Diễn Nhạc Cụ – Phương Pháp Giúp Trẻ Tự Tin Thể Hiện Bản Thân
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Làm quen với Piano và Organ từ sớm giúp trẻ rèn luyện sự tập trung, phối hợp hai bán cầu não và bản lĩnh tự tin trước đám đông.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-bold text-lotus-600 hover:underline pt-1 inline-flex items-center gap-1">
                            Đăng ký học thử <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1NJNKfPHNR1cgIvvyMLg12_dTGAb0gq5-" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1NJNKfPHNR1cgIvvyMLg12_dTGAb0gq5-&sz=w800';"
                            alt="Hướng dẫn chọn đàn Organ cho trẻ em và người mới" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <div class="text-[11px] font-semibold text-lotus-600 uppercase">Kinh nghiệm âm nhạc</div>
                            <h3 class="text-sm font-bold text-slate-800 mt-1 product-title-full">
                                Cách Chọn Đàn Organ Yamaha & Kurtzmann Phù Hợp Cho Học Viên Mới Bắt Đầu
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Các tiêu chí về bàn phím cảm ứng lực (Touch Response), ngân hàng điệu đệm và chức năng tự học tích hợp trên đàn Organ.
                            </p>
                        </div>
                        <a href="#san-pham" onclick="filterProducts('organ')" class="text-xs font-bold text-lotus-600 hover:underline pt-1 inline-flex items-center gap-1">
                            Xem các mẫu đàn Organ <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX&sz=w800';"
                            alt="Cách phân biệt đàn Guitar Acoustic và Guitar Classic" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <div class="text-[11px] font-semibold text-lotus-600 uppercase">Kiến thức Guitar</div>
                            <h3 class="text-sm font-bold text-slate-800 mt-1 product-title-full">
                                Phân Biệt Đàn Guitar Acoustic Và Guitar Classic Cho Người Mới Tập Đệm Hát
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Tìm hiểu sự khác biệt giữa dây kim loại và dây nylon, kích thước cần đàn để lựa chọn cây đàn Guitar êm tay, chuẩn âm.
                            </p>
                        </div>
                        <a href="#san-pham" onclick="filterProducts('guitar-acoustic')" class="text-xs font-bold text-lotus-600 hover:underline pt-1 inline-flex items-center gap-1">
                            Xem danh mục Guitar <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU NHẠC CỤ ================= -->
    <section id="doi-tac" class="py-9 bg-white">
        <div class="container-flatsome">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-lotus-600 uppercase">
                        ĐỐI TÁC THƯƠNG HIỆU NHẠC CỤ CHÍNH HÃNG
                    </h2>
                </div>
                <p class="text-xs text-slate-500">Các thương hiệu đàn Piano, Organ, Guitar, Trống uy tín được phân phối & sử dụng giảng dạy tại Sen Hồng</p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">YAMAHA</span>
                    <span class="text-[10px] text-slate-500">Japan Piano & Organ</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">KAWAI</span>
                    <span class="text-[10px] text-slate-500">Acoustic & Digital</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">ROLAND</span>
                    <span class="text-[10px] text-slate-500">Digital Piano & Drum</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">CASIO</span>
                    <span class="text-[10px] text-slate-500">Celviano & Privia</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">KURTZMANN</span>
                    <span class="text-[10px] text-slate-500">Organ & Piano</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">CORDOBA</span>
                    <span class="text-[10px] text-slate-500">Classic Guitar</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">FENDER</span>
                    <span class="text-[10px] text-slate-500">Acoustic & Electric</span>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-lotus-500 transition">
                    <span class="text-sm font-black tracking-wider text-slate-800">SUZUKI</span>
                    <span class="text-[10px] text-slate-500">Violin & Musical</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ ================= -->
    <section id="bando-fanpage" class="py-10 bg-lotus-50/50 border-t border-lotus-100">
        <div class="container-flatsome">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-lotus-600 uppercase">
                        KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG ĐẾN TRUNG TÂM SEN HỒNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Địa chỉ: 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng • Điện thoại: 0982.567.156
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột 1: Đưa Fanpage ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between space-y-4">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-100 pb-3 mb-3">
                            <div class="flex items-center gap-3">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH&sz=w300';"
                                    alt="Logo Fanpage Âm nhạc Sen Hồng" 
                                    class="w-12 h-12 rounded-full object-contain border border-lotus-200 p-0.5 bg-white"
                                >
                                <div>
                                    <h3 class="text-sm sm:text-base font-extrabold text-slate-800">
                                        Trung tâm Phát triển Âm nhạc SEN HỒNG
                                    </h3>
                                    <p class="text-xs text-slate-500">Fanpage Facebook Chính Thức • Đà Nẵng</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=61567857644286" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#1877F2] text-white text-xs font-bold flex items-center gap-1.5 hover:opacity-90 transition flex-shrink-0">
                                <i class="fa-brands fa-facebook-f"></i> Theo dõi
                            </a>
                        </div>

                        <!-- Khung hiển thị trực quan Fanpage + Iframe Plugin Facebook -->
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50">
                            <div class="grid grid-cols-3 gap-1 p-1 bg-white">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1WysImJqjsY9kl66gloCCdkYULXnUIrJz" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WysImJqjsY9kl66gloCCdkYULXnUIrJz&sz=w400';"
                                    alt="Ảnh hoạt động Fanpage 1" 
                                    class="w-full h-24 object-cover rounded"
                                >
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B&sz=w400';"
                                    alt="Ảnh hoạt động Fanpage 2" 
                                    class="w-full h-24 object-cover rounded"
                                >
                                <img 
                                    src="https://lh3.googleusercontent.com/d/18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=18dRdiRLM5HXw0LSlwufbbV_yK9usmA7Q&sz=w400';"
                                    alt="Ảnh hoạt động Fanpage 3" 
                                    class="w-full h-24 object-cover rounded"
                                >
                            </div>
                            <div class="p-3 text-xs text-slate-700 space-y-1.5">
                                <p class="font-semibold text-slate-800">
                                    Cập nhật lịch khai giảng các lớp Piano, Organ, Guitar và hình ảnh đàn mới về mỗi ngày trên Fanpage!
                                </p>
                                <p class="text-slate-500">
                                    <i class="fa-solid fa-location-dot text-lotus-600 mr-1"></i> 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng
                                </p>
                            </div>
                            <!-- Nhúng Facebook Page Plugin chuẩn -->
                            <div class="w-full overflow-hidden flex justify-center bg-white border-t border-slate-100 py-2">
                                <iframe 
                                    title="Fanpage Trung tâm Phát triển Âm nhạc SEN HỒNG"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61567857644286&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                    width="340" 
                                    height="180" 
                                    style="border:none;overflow:hidden;max-width:100%;" 
                                    scrolling="no" 
                                    frameborder="0" 
                                    allowfullscreen="true" 
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>
                        </div>
                    </div>

                    <div class="grid grid-cols-2 gap-2.5 pt-1">
                        <a href="https://www.facebook.com/profile.php?id=61567857644286" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-[#1877F2] hover:opacity-95 text-white font-bold text-xs text-center transition">
                            <i class="fa-brands fa-facebook mr-1"></i> Mở Trang Fanpage
                        </a>
                        <a href="https://zalo.me/0982567156" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-lotus-600 hover:bg-lotus-700 text-white font-bold text-xs text-center transition">
                            <i class="fa-solid fa-comments mr-1"></i> Nhắn Tin Zalo
                        </a>
                    </div>
                </div>

                <!-- Cột 2: Đưa Google Map ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between space-y-3">
                    <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-100 pb-3">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-slate-800">
                                <i class="fa-solid fa-map-location-dot text-lotus-600 mr-1.5"></i> Bản Đồ Google Map Trung Tâm Âm Nhạc Sen Hồng
                            </h3>
                            <p class="text-xs text-slate-500 mt-0.5">
                                362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng • ĐT: 0982.567.156
                            </p>
                        </div>
                        <a href="https://share.google/JpH0yaj7l1f8rvFBX" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-lotus-600 hover:bg-lotus-700 text-white font-bold text-xs inline-flex items-center gap-1.5 transition">
                            <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Chỉ Đường
                        </a>
                    </div>

                    <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                    <div class="w-full h-[320px] sm:h-[360px] rounded-lg overflow-hidden border border-slate-200 relative bg-slate-100">
                        <iframe 
                            title="Bản đồ Trung tâm Phát triển Âm nhạc SEN HỒNG 362/10 Tôn Đức Thắng Đà Nẵng"
                            src="https://maps.google.com/maps?q=Trung%20t%C3%A2m%20ph%C3%A1t%20tri%E1%BB%83n%20%C3%82m%20nh%E1%BA%A1c%20Sen%20H%E1%BB%93ng%20362%2F10%20T%C3%B4n%20%C4%90%E1%BB%A9c%20Th%E1%BA%AFng%2C%20H%C3%B2a%20Kh%C3%A1nh%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            width="100%" 
                            height="100%" 
                            style="border:0;" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>

                    <div class="flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600 pt-1">
                        <span><i class="fa-solid fa-clock text-lotus-600 mr-1"></i> Giờ mở cửa: Tất cả các ngày trong tuần (Tư vấn 24/7)</span>
                        <a href="https://share.google/JpH0yaj7l1f8rvFBX" target="_blank" rel="noopener noreferrer" class="font-bold text-lotus-600 hover:underline">
                            Xem vị trí trên Google Map (share.google/JpH0yaj7l1f8rvFBX) <i class="fa-solid fa-up-right-from-square ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER (CHÂN TRANG CHUẨN MẪU HAOVINHMUSIC.VN & FLATSOME) ================= -->
    <footer class="bg-slate-900 text-slate-300 pt-10 pb-20 md:pb-10 border-t-4 border-lotus-600">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-slate-800">
                <!-- Cột 1: Thông tin trung tâm -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1owaLRNP1wABPAqw2XTuWtY053g2Fq-aH&sz=w300';"
                            alt="Logo Âm nhạc Sen Hồng" 
                            class="h-10 w-auto object-contain rounded bg-white p-0.5"
                        >
                        <div>
                            <div class="text-sm font-extrabold text-white">ÂM NHẠC SEN HỒNG</div>
                            <div class="text-[11px] text-amber-400">amnhacsenhong.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-400 leading-relaxed">
                        Trung tâm Phát triển Âm nhạc SEN HỒNG tự hào là địa chỉ đào tạo Piano, Organ, Guitar, Trống, Violin, Thanh nhạc và phân phối nhạc cụ uy tín tại TP. Đà Nẵng.
                    </p>
                    <div class="space-y-1.5 text-xs">
                        <p><i class="fa-solid fa-location-dot text-lotus-400 mr-1.5"></i> <strong>Địa chỉ:</strong> 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng</p>
                        <p><i class="fa-solid fa-phone text-lotus-400 mr-1.5"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0982567156" class="text-amber-300 font-bold">0982.567.156</a></p>
                        <p><i class="fa-solid fa-globe text-lotus-400 mr-1.5"></i> <strong>Website:</strong> amnhacsenhong.com</p>
                    </div>
                </div>

                <!-- Cột 2: Khóa học nổi bật -->
                <div class="space-y-2.5">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide border-b border-slate-800 pb-2">
                        KHÓA HỌC NỔI BẬT
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#khoa-hoc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Khóa học Đàn Piano (Trẻ em & Người lớn)</a></li>
                        <li><a href="#khoa-hoc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Khóa học Đàn Organ từ cơ bản đến nâng cao</a></li>
                        <li><a href="#khoa-hoc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Khóa học Guitar Đệm Hát & Guitar Điện</a></li>
                        <li><a href="#khoa-hoc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Khóa học Đánh Trống (Drum)</a></li>
                        <li><a href="#khoa-hoc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Khóa học Đàn Violin & Đàn Ukulele</a></li>
                        <li><a href="#khoa-hoc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Khóa học Thanh Nhạc & Biểu Diễn</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Mua nhạc cụ -->
                <div class="space-y-2.5">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide border-b border-slate-800 pb-2">
                        DANH MỤC MUA NHẠC CỤ
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProducts('piano-co')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Đàn Piano Cơ Nhật Bản</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('piano-dien')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Đàn Piano Điện Chính Hãng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('organ')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Đàn Organ Yamaha, Casio, Kurtzmann</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('guitar-acoustic')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Đàn Guitar Acoustic & Classic</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('ukulele')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Đàn Ukulele Soprano & Concert</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('trong-violin')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Bộ Trống (Drum) & Đàn Violin</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Hỗ trợ khách hàng -->
                <div class="space-y-2.5">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide border-b border-slate-800 pb-2">
                        HỖ TRỢ HỌC VIÊN & KHÁCH HÀNG
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#gioi-thieu" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Giới thiệu Trung tâm Âm nhạc Sen Hồng</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Chính sách bảo hành & Vận chuyển đàn</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Thuê nhạc cụ & Phòng tập đàn tại Đà Nẵng</a></li>
                        <li><a href="https://www.facebook.com/profile.php?id=61567857644286" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Fanpage Facebook Âm Nhạc Sen Hồng</a></li>
                        <li><a href="https://share.google/JpH0yaj7l1f8rvFBX" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-lotus-400"></i> Bản đồ Google Maps chỉ đường</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright © 2026 <strong>amnhacsenhong.com</strong> - Trung tâm Phát triển Âm nhạc SEN HỒNG | 362/10 Tôn Đức Thắng, Phường Hòa Khánh, Tp.Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH TRÊN MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a 
            href="https://www.facebook.com/profile.php?id=61567857644286" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Chat Facebook Fanpage"
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-sm">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a 
            href="https://zalo.me/0982567156" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Chat Zalo 0982.567.156"
            class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[10px]">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a 
            href="tel:0982567156" 
            aria-label="Gọi Hotline 0982.567.156"
            class="floating-pulse flex items-center gap-2 bg-lotus-600 hover:bg-lotus-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition"
        >
            <span class="w-7 h-7 rounded-full bg-amber-400 text-slate-900 flex items-center justify-center font-bold text-xs">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0982.567.156</span>
        </a>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ SLIDER, DANH MỤC SẢN PHẨM & FORM ================= -->
    <script>
        /* Danh sách sản phẩm thực tế (kết hợp đầy đủ 8 ảnh sản phẩm từ file Google Drive của Trung tâm Sen Hồng và các danh mục chuẩn từ haovinhmusic.vn) */
        const productsData = [
            {
                id: 1,
                name: "Đàn Piano Cơ Dáng Đứng Yamaha U1H Nhật Bản Tuyển Chọn",
                category: "piano-co",
                categoryLabel: "Đàn Piano Cơ",
                oldPrice: "42.000.000 ₫",
                newPrice: "35.700.000 ₫",
                discount: "-15%",
                driveId: "1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B"
            },
            {
                id: 2,
                name: "Đàn Piano Cơ Upright Kawai BL31 Âm Thanh Ấm Vang",
                category: "piano-co",
                categoryLabel: "Đàn Piano Cơ",
                oldPrice: "36.000.000 ₫",
                newPrice: "29.880.000 ₫",
                discount: "-17%",
                driveId: "1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ"
            },
            {
                id: 3,
                name: "Đàn Piano Điện Yamaha YDP-165 Arius 88 Phím Chuẩn Cơ",
                category: "piano-dien",
                categoryLabel: "Đàn Piano Điện",
                oldPrice: "28.500.000 ₫",
                newPrice: "23.940.000 ₫",
                discount: "-16%",
                driveId: "1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76"
            },
            {
                id: 4,
                name: "Đàn Piano Điện Roland RP-102 Kết Nối Bluetooth Hiện Đại",
                category: "piano-dien",
                categoryLabel: "Đàn Piano Điện",
                oldPrice: "21.000.000 ₫",
                newPrice: "17.850.000 ₫",
                discount: "-15%",
                driveId: "18c8z9UQJPM4fJkAHDeK7XpJ4LNJ7zRYI"
            },
            {
                id: 5,
                name: "Đàn Organ Yamaha PSR-E373 Cảm Ứng Lực Cho Người Mới Học",
                category: "organ",
                categoryLabel: "Đàn Organ",
                oldPrice: "6.500.000 ₫",
                newPrice: "5.460.000 ₫",
                discount: "-16%",
                driveId: "1NJNKfPHNR1cgIvvyMLg12_dTGAb0gq5-"
            },
            {
                id: 6,
                name: "Đàn Organ Kurtzmann K250 Phím Sáng Luyện Tập Chuyên Nghiệp",
                category: "organ",
                categoryLabel: "Đàn Organ",
                oldPrice: "5.200.000 ₫",
                newPrice: "4.160.000 ₫",
                discount: "-20%",
                driveId: "19fuYh7jbohm3KBx5ETE0JXUVBD031StW"
            },
            {
                id: 7,
                name: "Đàn Guitar Acoustic Yamaha F310 Chính Hãng Đệm Hát Chuẩn Âm",
                category: "guitar-acoustic",
                categoryLabel: "Đàn Guitar Acoustic",
                oldPrice: "4.200.000 ₫",
                newPrice: "3.570.000 ₫",
                discount: "-15%",
                driveId: "1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX"
            },
            {
                id: 8,
                name: "Đàn Guitar Classic Yamaha C40M Dây Nylon Êm Tay Cho Người Mới",
                category: "guitar-classic",
                categoryLabel: "Đàn Guitar Classic",
                oldPrice: "3.600.000 ₫",
                newPrice: "2.950.000 ₫",
                discount: "-18%",
                driveId: "1_8GxHwmFTXKXbh1yY0-TGlC49xb1MZSY"
            },
            {
                id: 9,
                name: "Đàn Piano Cơ Dáng Đứng Yamaha U3H Cao Cấp Cho Gia Đình",
                category: "piano-co",
                categoryLabel: "Đàn Piano Cơ",
                oldPrice: "48.000.000 ₫",
                newPrice: "41.280.000 ₫",
                discount: "-14%",
                driveId: "1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B"
            },
            {
                id: 10,
                name: "Đàn Piano Điện Casio Celviano AP-470 Thiết Kế Sang Trọng",
                category: "piano-dien",
                categoryLabel: "Đàn Piano Điện",
                oldPrice: "26.000.000 ₫",
                newPrice: "22.100.000 ₫",
                discount: "-15%",
                driveId: "1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ"
            },
            {
                id: 11,
                name: "Đàn Ukulele Concert Gỗ Mahogany Âm Sáng Kèm Bao Đàn",
                category: "ukulele",
                categoryLabel: "Đàn Ukulele",
                oldPrice: "1.100.000 ₫",
                newPrice: "880.000 ₫",
                discount: "-20%",
                driveId: "1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX"
            },
            {
                id: 12,
                name: "Bộ Trống Điện Yamaha DD-75 & Đàn Violin Luyện Tập Đa Năng",
                category: "trong-violin",
                categoryLabel: "Bộ Trống & Đàn Violin",
                oldPrice: "8.200.000 ₫",
                newPrice: "7.216.000 ₫",
                discount: "-12%",
                driveId: "1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76"
            }
        ];

        let currentCategoryFilter = 'all';
        let currentSearchQuery = '';

        /* Hàm hiển thị danh sách sản phẩm chuẩn Flatsome Product Box */
        function renderProducts() {
            const container = document.getElementById('productGridContainer');
            if (!container) return;

            const filtered = productsData.filter(item => {
                const matchCat = currentCategoryFilter === 'all' || item.category === currentCategoryFilter;
                const matchSearch = item.name.toLowerCase().includes(currentSearchQuery.toLowerCase()) ||
                                    item.categoryLabel.toLowerCase().includes(currentSearchQuery.toLowerCase());
                return matchCat && matchSearch;
            });

            if (filtered.length === 0) {
                container.innerHTML = `
                    <div class="col-span-full py-10 text-center text-slate-500 text-sm">
                        Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng liên hệ Hotline <strong>0982.567.156</strong> để được tư vấn trực tiếp!
                    </div>
                `;
                return;
            }

            container.innerHTML = filtered.map(item => `
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col justify-between relative group">
                    <!-- Huy hiệu % giảm giá giống Flatsome ở góc trên bên trái -->
                    <div class="flatsome-sale-badge">
                        ${item.discount}
                    </div>

                    <div>
                        <!-- Ảnh sản phẩm thực tế -->
                        <div class="aspect-square w-full overflow-hidden bg-slate-50 border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/${item.driveId}" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800';"
                                alt="${item.name}" 
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                            >
                        </div>

                        <!-- Thông tin sản phẩm: Tên sản phẩm hiển thị đầy đủ không bị tràn hay thiếu chữ -->
                        <div class="p-3 sm:p-4 space-y-1.5">
                            <div class="text-[10px] sm:text-[11px] font-semibold uppercase tracking-wide text-slate-400">
                                ${item.categoryLabel}
                            </div>
                            <h3 class="text-[13px] sm:text-sm md:text-[15px] font-bold text-slate-800 product-title-full">
                                ${item.name}
                            </h3>
                            <div class="pt-1 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <del class="text-[11px] sm:text-xs text-slate-400 font-medium">${item.oldPrice}</del>
                                <span class="text-xs sm:text-sm md:text-base font-extrabold text-lotus-600">${item.newPrice}</span>
                            </div>
                        </div>
                    </div>

                    <!-- Nút đặt mua / nhận báo giá -->
                    <div class="px-3 pb-3 sm:px-4 sm:pb-4">
                        <a 
                            href="#form-bao-gia" 
                            onclick="selectProductInForm('${item.name.replace(/'/g, "\\'")}')"
                            class="block w-full text-center py-2 px-2 rounded-lg bg-lotus-600 hover:bg-lotus-700 text-white font-semibold text-xs transition"
                        >
                            Nhận Báo Giá Ưu Đãi
                        </a>
                    </div>
                </div>
            `).join('');
        }

        /* Lọc theo danh mục */
        function filterProducts(category) {
            currentCategoryFilter = category;
            document.querySelectorAll('.home-cat-pill').forEach(btn => {
                if (btn.getAttribute('data-cat') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
            renderProducts();
        }

        /* Tìm kiếm sản phẩm */
        function handleSearchProduct(query) {
            currentSearchQuery = query || '';
            renderProducts();
        }

        /* Điền nhanh sản phẩm/khóa học vào Form báo giá */
        function selectProductInForm(productName) {
            const noteEl = document.getElementById('custNote');
            if (noteEl) {
                noteEl.value = "Tôi muốn tư vấn và nhận báo giá sản phẩm: " + productName;
            }
        }

        function selectCourseInForm(courseName) {
            const selectEl = document.getElementById('custInterest');
            const noteEl = document.getElementById('custNote');
            if (selectEl) {
                selectEl.value = courseName;
            }
            if (noteEl) {
                noteEl.value = "Tôi muốn tư vấn lịch học và học phí: " + courseName;
            }
        }

        /* Xử lý gửi Form Báo Giá & Tư Vấn (không dùng alert) */
        function handleQuoteSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const interest = document.getElementById('custInterest').value;
            const notice = document.getElementById('formSuccessNotice');

            notice.classList.remove('hidden');
            notice.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5 text-emerald-600"></i> Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu <strong>"${interest}"</strong> đã được ghi nhận. Trung tâm Phát triển Âm nhạc SEN HỒNG sẽ liên hệ lại với bạn ngay qua SĐT/Zalo <strong>0982.567.156</strong>.`;
            document.getElementById('quoteRequestForm').reset();
        }

        /* Đóng/mở menu trên điện thoại */
        function toggleMobileMenu() {
            const modal = document.getElementById('mobileMenuModal');
            if (modal) {
                modal.classList.toggle('hidden');
            }
        }

        /* Điều khiển Slider 2 ảnh Banner tự trượt (đồng bộ cả Desktop & Mobile) */
        let currentSlideIndex = 0;
        const totalSlides = 2;
        let bannerInterval = null;

        function updateBannerUI() {
            for (let i = 0; i < totalSlides; i++) {
                const dSlide = document.getElementById('desktopSlide' + i);
                const mSlide = document.getElementById('mobileSlide' + i);
                const dot = document.getElementById('dotSlide' + i);

                if (i === currentSlideIndex) {
                    if (dSlide) { dSlide.classList.remove('opacity-0', 'z-0'); dSlide.classList.add('opacity-100', 'z-10'); }
                    if (mSlide) { mSlide.classList.remove('opacity-0', 'z-0'); mSlide.classList.add('opacity-100', 'z-10'); }
                    if (dot) { dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all'; }
                } else {
                    if (dSlide) { dSlide.classList.remove('opacity-100', 'z-10'); dSlide.classList.add('opacity-0', 'z-0'); }
                    if (mSlide) { mSlide.classList.remove('opacity-100', 'z-10'); mSlide.classList.add('opacity-0', 'z-0'); }
                    if (dot) { dot.className = 'w-2 h-2 rounded-full bg-white/50 transition-all'; }
                }
            }
        }

        function changeBannerSlide(step) {
            currentSlideIndex = (currentSlideIndex + step + totalSlides) % totalSlides;
            updateBannerUI();
            resetBannerTimer();
        }

        function setBannerSlide(index) {
            currentSlideIndex = index;
            updateBannerUI();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentSlideIndex = (currentSlideIndex + 1) % totalSlides;
                updateBannerUI();
            }, 5000);
        }

        window.onload = function() {
            renderProducts();
            resetBannerTimer();
        };
    </script>
</body>
</html>
