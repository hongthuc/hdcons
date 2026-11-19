<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>HD-Cons | Thiết Kế Thi Công Nhà Phố Trọn Gói Đà Nẵng - hdcons.com</title>
    <meta name="description" content="HD-Cons (hdcons.com) chuyên Thiết kế Kiến trúc, Thi công Nhà phố, Biệt thự, Căn hộ trọn gói tại Đà Nẵng. Địa chỉ: 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng. Hotline: 0905.830.380 - 0988.747.551.">

    <!-- Ảnh Thumbnail (Logo HD-Cons) tự động hiển thị khi chia sẻ link website qua Zalo, Facebook -->
    <meta property="og:title" content="HD-Cons | Thiết Kế Thi Công Nhà Phố Trọn Gói Đà Nẵng - hdcons.com">
    <meta property="og:description" content="Thiết kế kiến trúc - Thi công phần thô - Hoàn thiện nội thất nhà phố uy tín tại Đà Nẵng. Hotline: 0905.830.380 - 0988.747.551.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://hdcons.com">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w1200">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w1200">
    <meta property="og:image:alt" content="Logo Thiết Kế Thi Công Nhà Phố HD-Cons">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="HD-Cons | Thiết Kế Thi Công Nhà Phố Đà Nẵng">
    <meta name="twitter:description" content="Thiết kế thi công nhà phố trọn gói uy tín tại 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng.">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w1200">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w256">

    <!-- Font Inter chuẩn sắc nét tiếng Việt -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 cho icon Flatsome & mạng xã hội -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            primary: '#16355B',   /* Xanh Navy đậm chuẩn kiến trúc - đồng bộ logo HD-Cons */
                            dark: '#0E2440',      /* Xanh Navy sâu cho Footer & Topbar */
                            accent: '#C98A1E',    /* Vàng đồng xây dựng sang trọng */
                            accentHover: '#A87012',
                            light: '#F4F6F9',
                            border: '#E5E9F0',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Biến màu chủ đạo dễ chỉnh nhanh theo màu logo hoặc khi dựng lại trên Flatsome */
        :root {
            --hd-primary: #16355B;
            --hd-dark: #0E2440;
            --hd-accent: #C98A1E;
            --hd-text: #222831;
            --hd-muted: #5C6773;
        }

        /* Reset an toàn tránh tràn viền ngang và lệch phải trên mọi màn hình */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            overflow-x: hidden;
            width: 100%;
            max-width: 100%;
        }

        body {
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: var(--hd-text);
            background-color: #FFFFFF;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            width: 100%;
            max-width: 100%;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chuẩn 95% chiều ngang màn hình máy tính, không tràn viền mobile */
        .hd-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 640px) {
            .hd-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        @media (min-width: 1024px) {
            .hd-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu Flatsome trên máy tính: chữ nhỏ gọn, tên danh mục không bao giờ xuống dòng */
        .nav-link-item {
            white-space: nowrap;
            word-break: keep-all;
            font-size: 12px;
            font-weight: 600;
            letter-spacing: 0.01em;
            transition: color 0.2s ease;
        }

        @media (min-width: 1280px) {
            .nav-link-item {
                font-size: 13px;
            }
        }

        /* Dropdown menu chuẩn Flatsome */
        .hd-dropdown {
            position: relative;
        }
        .hd-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            pointer-events: none;
        }
        .hd-dropdown:hover .hd-dropdown-menu,
        .hd-dropdown:focus-within .hd-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
            pointer-events: auto;
        }

        /* Thanh tiêu đề mục chuẩn Flatsome */
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .section-heading::after {
            content: '';
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: var(--hd-accent);
            border-radius: 9999px;
        }
        .section-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Banner Slider 2 ảnh kích thước tuyệt đối bằng nhau */
        .banner-wrapper {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: var(--hd-dark);
        }
        .banner-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .banner-slide {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
            position: relative;
            /* Đảm bảo 2 banner luôn có kích thước bằng nhau trên mọi thiết bị */
            height: 360px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }
        @media (min-width: 640px) {
            .banner-slide {
                height: 420px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slide {
                height: 490px;
            }
        }
        @media (min-width: 1440px) {
            .banner-slide {
                height: 540px;
            }
        }

        /* Ảnh sản phẩm/dự án đồng nhất tỉ lệ, zoom nhẹ kiểu Flatsome */
        .project-img-box {
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #EDF1F6;
        }
        .project-img-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }
        .project-card:hover .project-img-box img {
            transform: scale(1.05);
        }

        /* Tab danh mục ngang gọn đẹp không xuống dòng tên danh mục */
        .cat-tab-btn {
            white-space: nowrap;
            word-break: keep-all;
            transition: all 0.2s ease;
        }
        .cat-tab-btn.active {
            background-color: var(--hd-primary);
            color: #FFFFFF;
            border-color: var(--hd-primary);
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(201, 138, 30, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(201, 138, 30, 0); }
            100% { box-shadow: 0 0 0 0 rgba(201, 138, 30, 0); }
        }
        .pulse-ring {
            animation: softPulse 2.2s infinite;
        }

        /* Ẩn thanh cuộn phụ của dải danh mục mobile nhưng vẫn vuốt mượt */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800 pb-16 md:pb-0">

    <!-- ===================================================================== -->
    <!-- SECTION 1: TOP BAR THÔNG TIN LIÊN HỆ (UX Builder: Header Top Bar)     -->
    <!-- ===================================================================== -->
    <div class="bg-brand-dark text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
        <div class="hd-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0905830380" class="inline-flex items-center gap-1.5 hover:text-amber-300 transition-colors">
                    <i class="fa-solid fa-phone text-brand-accent"></i>
                    <span class="font-medium">0905.830.380 - 0988.747.551</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-brand-accent"></i>
                    <span>157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <span class="hidden sm:inline text-slate-300">Website: <strong class="text-white">hdcons.com</strong></span>
                <a href="https://www.facebook.com/profile.php?id=100063776191640" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook HD-Cons" class="inline-flex items-center gap-1 text-slate-200 hover:text-amber-300 transition-colors">
                    <i class="fa-brands fa-facebook text-sm"></i>
                    <span class="hidden sm:inline">Fanpage HD-Cons</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- SECTION 2: HEADER CHÍNH FLATSOME (Logo gọn nhỏ, Menu 1 hàng, Không nút Gọi ngay) -->
    <!-- ===================================================================== -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-brand-border shadow-sm">
        <div class="hd-container flex items-center justify-between gap-3 py-2.5">
            <!-- Logo HD-Cons chỉnh gọn nhỏ sắc nét -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
                <img
                    src="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w400"
                    alt="Logo Thiết Kế Thi Công Nhà Phố HD-Cons"
                    class="h-10 sm:h-11 w-auto max-w-[115px] sm:max-w-[135px] object-contain rounded"
                    onerror="handleDriveImageError(this, '1IggMv6W8S-yZGwUGWzicovHN7WGb830U', 'HD-CONS')"
                >
                <div class="leading-tight">
                    <div class="text-sm sm:text-base font-extrabold text-brand-primary tracking-tight whitespace-nowrap">HD - CONS</div>
                    <div class="text-[10px] sm:text-[11px] font-medium text-slate-500 whitespace-nowrap">Thiết Kế &amp; Thi Công Nhà Phố</div>
                </div>
            </a>

            <!-- Menu Desktop: Chữ nhỏ gọn viết liền trên 1 hàng (hoặc tối đa hàng 2 khi màn nhỏ, KHÔNG xuống dòng tên danh mục) -->
            <nav aria-label="Điều hướng chính" class="hidden lg:flex flex-wrap items-center justify-end gap-x-3 xl:gap-x-4 gap-y-1.5 min-w-0">
                <a href="#trang-chu" class="nav-link-item text-brand-primary hover:text-brand-accent py-1.5">TRANG CHỦ</a>
                <a href="#gioi-thieu" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5">GIỚI THIỆU</a>

                <!-- Dropdown Công trình thực tế (theo web mẫu tintruongthinh.com) -->
                <div class="hd-dropdown">
                    <a href="#cong-trinh-thuc-te" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5 inline-flex items-center gap-1">
                        <span>CÔNG TRÌNH THỰC TẾ</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="hd-dropdown-menu absolute left-0 top-full pt-2 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-brand-border py-1.5 text-xs">
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('phan-tho')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Thi công phần thô</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('hoan-thien')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Thi công hoàn thiện</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('noi-that')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Nội thất – Biệt thự – Căn hộ</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Lĩnh vực hoạt động -->
                <div class="hd-dropdown">
                    <a href="#linh-vuc-hoat-dong" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5 inline-flex items-center gap-1">
                        <span>LĨNH VỰC HOẠT ĐỘNG</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="hd-dropdown-menu absolute left-0 top-full pt-2 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-brand-border py-1.5 text-xs">
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Thi công phần thô</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Thi công hoàn thiện</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Thi công nội thất trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5">DỰ ÁN ĐÀ NẴNG</a>

                <!-- Dropdown Báo giá -->
                <div class="hd-dropdown">
                    <a href="#bao-gia" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5 inline-flex items-center gap-1">
                        <span>BÁO GIÁ</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="hd-dropdown-menu absolute right-0 top-full pt-2 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-brand-border py-1.5 text-xs">
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#doi-tac" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5">ĐỐI TÁC</a>
                <a href="#tin-tuc" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5">TIN TỨC</a>
                <a href="#lien-he-bao-gia" class="nav-link-item text-slate-700 hover:text-brand-accent py-1.5">LIÊN HỆ</a>
            </nav>

            <!-- Nút mở Menu Mobile (Không đặt nút Gọi ngay trên Header để tránh tràn viền) -->
            <button
                id="mobile-menu-btn"
                type="button"
                aria-label="Mở danh mục điều hướng"
                class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-brand-border text-brand-primary hover:bg-brand-light transition-colors shrink-0"
                onclick="toggleMobileMenu()"
            >
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Mobile trượt gọn gàng -->
        <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-brand-border shadow-md">
            <div class="hd-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-medium">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 text-brand-primary font-semibold">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Giới thiệu HD-Cons</a>
                <a href="#linh-vuc-hoat-dong" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Công trình thực tế thi công</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Dự án tiêu biểu tại Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Báo giá thiết kế &amp; thi công</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Đối tác cung ứng</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Tin tức &amp; Cẩm nang xây dựng</a>
                <a href="#lien-he-bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-slate-700">Liên hệ &amp; Gửi yêu cầu báo giá</a>
            </div>
        </div>
    </header>

    <!-- ===================================================================== -->
    <!-- SECTION 3: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Kích thước bằng nhau, chữ nằm trọn trong banner, cách xa viền) -->
    <!-- ===================================================================== -->
    <section id="trang-chu" class="w-full overflow-hidden bg-brand-dark">
        <div class="banner-wrapper" id="hero-slider">
            <div class="banner-track" id="hero-slider-track">

                <!-- BANNER 1 -->
                <div class="banner-slide">
                    <img
                        src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                        alt="Thiết Kế Thi Công Nhà Phố Trọn Gói HD-Cons Đà Nẵng"
                        class="absolute inset-0 w-full h-full object-cover object-center"
                        onerror="handleDriveImageError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'HD-CONS+DA+NANG')"
                    >
                    <!-- Lớp phủ chuyển sắc giúp chữ nổi bật sắc nét trên mọi nền ảnh -->
                    <div class="absolute inset-0 bg-gradient-to-r from-[#0E2440]/90 via-[#0E2440]/75 to-[#0E2440]/45"></div>

                    <!-- Vùng an toàn chữ cách xa hoàn toàn viền banner trên cả mobile và desktop -->
                    <div class="relative z-10 w-full max-w-4xl mx-auto px-12 sm:px-16 md:px-20 py-8 sm:py-12 text-center text-white">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-amber-300 mb-2 sm:mb-3">
                            THIẾT KẾ &amp; THI CÔNG NHÀ PHỐ HD - CONS
                        </p>
                        <h1 class="text-lg sm:text-2xl md:text-4xl font-extrabold leading-snug tracking-tight mb-3 sm:mb-4">
                            KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG TẠI ĐÀ NẴNG
                        </h1>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto mb-5 sm:mb-6">
                            Giải pháp thiết kế kiến trúc, thi công phần thô và hoàn thiện trọn gói chuẩn kỹ thuật, minh bạch vật tư, đúng tiến độ cam kết.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-2.5 sm:gap-3">
                            <a href="#lien-he-bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-semibold shadow transition-colors">
                                Nhận Báo Giá Miễn Phí
                            </a>
                            <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
                                Xem Dự Án Đà Nẵng
                            </a>
                        </div>
                    </div>
                </div>

                <!-- BANNER 2 (Cùng chính xác chiều cao & cấu trúc căn chỉnh an toàn như Banner 1) -->
                <div class="banner-slide">
                    <img
                        src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w1600"
                        alt="Thi Công Phần Thô Và Hoàn Thiện Trọn Gói HD-Cons"
                        class="absolute inset-0 w-full h-full object-cover object-center"
                        onerror="handleDriveImageError(this, '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO', 'THI+CONG+TRON+GOI')"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-[#0E2440]/90 via-[#0E2440]/75 to-[#0E2440]/45"></div>

                    <!-- Vùng an toàn chữ cách xa hoàn toàn viền banner trên cả mobile và desktop -->
                    <div class="relative z-10 w-full max-w-4xl mx-auto px-12 sm:px-16 md:px-20 py-8 sm:py-12 text-center text-white">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-amber-300 mb-2 sm:mb-3">
                            XÂY DỰNG TRỌN GÓI CHÌA KHÓA TRAO TAY
                        </p>
                        <h2 class="text-lg sm:text-2xl md:text-4xl font-extrabold leading-snug tracking-tight mb-3 sm:mb-4">
                            CAM KẾT CHẤT LƯỢNG CÔNG TRÌNH &amp; KHÔNG PHÁT SINH CHI PHÍ
                        </h2>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto mb-5 sm:mb-6">
                            Đội ngũ kiến trúc sư và kỹ sư giám sát trực tiếp tại công trình. Bảo hành kết cấu dài hạn, hỗ trợ hồ sơ xin phép xây dựng tận tâm.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-2.5 sm:gap-3">
                            <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-semibold shadow transition-colors">
                                Xem Công Trình Thực Tế
                            </a>
                            <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
                                Bảng Báo Giá 2026
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <!-- Nút điều hướng 2 bên banner gọn sát viền, không đè lên vùng chữ -->
            <button
                type="button"
                onclick="moveBanner(-1)"
                aria-label="Banner trước"
                class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
            >
                <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
            </button>
            <button
                type="button"
                onclick="moveBanner(1)"
                aria-label="Banner tiếp theo"
                class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
            >
                <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
            </button>

            <!-- Chấm chỉ báo 2 slide nằm gọn sát mép dưới -->
            <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                <button type="button" onclick="goToBanner(0)" id="banner-dot-0" aria-label="Xem banner 1" class="w-6 h-2 rounded-full bg-brand-accent transition-all"></button>
                <button type="button" onclick="goToBanner(1)" id="banner-dot-1" aria-label="Xem banner 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 4: DỊCH VỤ TIÊU BIỂU (Bố cục 3 cột giống mẫu Tín Trường Thịnh) -->
    <!-- ===================================================================== -->
    <section id="linh-vuc-hoat-dong" class="py-10 sm:py-14 bg-white">
        <div class="hd-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase tracking-wide">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    HD-Cons cung cấp giải pháp trọn gói từ tư vấn ý tưởng, thiết kế hồ sơ kỹ thuật đến thi công xây dựng và hoàn thiện nội thất nhà phố tại Đà Nẵng.
                </p>
            </div>

            <!-- 3 cột dịch vụ chủ lực dễ dựng lại bằng Row 3 Cols trên Flatsome UX Builder -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                <!-- Dịch vụ 1 -->
                <div class="bg-brand-light border border-brand-border rounded-xl overflow-hidden flex flex-col hover:shadow-md transition-shadow">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                        <img
                            src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w900"
                            alt="Thiết Kế Kiến Trúc Nội Thất HD-Cons"
                            class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'THIET+KE+KIEN+TRUC')"
                        >
                    </div>
                    <div class="p-4 sm:p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary uppercase mb-2">Thiết Kế Kiến Trúc</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thiết kế mặt tiền nhà phố hiện đại, tối ưu công năng lấy sáng, thông gió tự nhiên và phong thủy hài hòa cho từng gia đình.
                            </p>
                        </div>
                        <a href="#lien-he-bao-gia" class="mt-4 inline-flex items-center justify-center gap-1.5 text-xs sm:text-sm font-semibold text-brand-accent hover:text-brand-primary transition-colors">
                            <span>Tư vấn thiết kế</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-brand-light border border-brand-border rounded-xl overflow-hidden flex flex-col hover:shadow-md transition-shadow">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                        <img
                            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w900"
                            alt="Thi Công Xây Dựng Phần Thô & Trọn Gói HD-Cons"
                            class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'THI+CONG+XAY+DUNG')"
                        >
                    </div>
                    <div class="p-4 sm:p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary uppercase mb-2">Thi Công Xây Dựng</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thi công phần thô, nhân công hoàn thiện và xây nhà trọn gói chìa khóa trao tay. Kỹ sư giám sát chặt chẽ từng hạng mục kết cấu.
                            </p>
                        </div>
                        <a href="#lien-he-bao-gia" class="mt-4 inline-flex items-center justify-center gap-1.5 text-xs sm:text-sm font-semibold text-brand-accent hover:text-brand-primary transition-colors">
                            <span>Xem quy trình thi công</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-brand-light border border-brand-border rounded-xl overflow-hidden flex flex-col hover:shadow-md transition-shadow">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-200">
                        <img
                            src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w900"
                            alt="Thiết Kế Thi Công Nội Thất Nhà Phố HD-Cons"
                            class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_', 'THI+CONG+NOI+THAT')"
                        >
                    </div>
                    <div class="p-4 sm:p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary uppercase mb-2">Hoàn Thiện Nội Thất</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thiết kế và lắp đặt nội thất phòng khách, tủ bếp, phòng ngủ đồng bộ vật liệu cao cấp, thẩm mỹ tinh tế và tối ưu chi phí.
                            </p>
                        </div>
                        <a href="#lien-he-bao-gia" class="mt-4 inline-flex items-center justify-center gap-1.5 text-xs sm:text-sm font-semibold text-brand-accent hover:text-brand-primary transition-colors">
                            <span>Nhận báo giá nội thất</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 5: GIỚI THIỆU HD-CONS & THẾ MẠNH CỦA CHÚNG TÔI                -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-light border-y border-brand-border">
        <div class="hd-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                <!-- Nội dung giới thiệu -->
                <div class="lg:col-span-7">
                    <h2 class="section-heading section-heading-left text-lg sm:text-2xl font-bold text-brand-primary uppercase mb-4">
                        Thiết Kế Thi Công Nhà Phố HD - Cons
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>HD - Cons (hdcons.com)</strong> là đơn vị chuyên sâu trong lĩnh vực <strong>Tư vấn Thiết kế Kiến trúc – Thi công Xây dựng – Hoàn thiện Nội thất</strong> cho các công trình Nhà phố, Biệt thự, Căn hộ dịch vụ và Văn phòng tại khu vực Đà Nẵng và Quảng Nam.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
                        Với phương châm lấy <strong>“Chất Lượng Công Trình Làm Thước Đo Uy Tín”</strong>, đội ngũ kiến trúc sư và kỹ sư giám sát giàu kinh nghiệm của HD-Cons luôn đặt chữ TÂM trong từng hạng mục thi công: từ xử lý nền móng, đổ bê tông kết cấu cho đến hoàn thiện từng đường nét mặt tiền, mang đến không gian sống an toàn, bền đẹp và tiết kiệm tối đa chi phí cho gia chủ.
                    </p>
                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="bg-white rounded-lg p-3 border border-brand-border text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-primary">100+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình hoàn thiện</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 border border-brand-border text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-accent">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Vật tư đúng cam kết</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 border border-brand-border text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-primary">5 Năm</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                        </div>
                    </div>
                </div>

                <!-- Hình ảnh thực tế công trình HD-Cons -->
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden border border-brand-border shadow-sm bg-white p-2">
                        <div class="aspect-[4/3] rounded-lg overflow-hidden">
                            <img
                                src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w1000"
                                alt="Công trình thực tế do HD-Cons thiết kế thi công tại Đà Nẵng"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImageError(this, '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn', 'HD-CONS+DA+NANG')"
                            >
                        </div>
                    </div>
                </div>
            </div>

            <!-- Thế mạnh của chúng tôi (6 hộp gọn chuẩn mẫu tintruongthinh.com) -->
            <div class="text-center mb-6">
                <h3 class="section-heading text-base sm:text-xl font-bold text-brand-primary uppercase">
                    Thế Mạnh Của HD - Cons
                </h3>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-brand-border flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-compass-drafting text-base"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-primary mb-1">Đội ngũ KTS &amp; Kỹ sư chuyên nghiệp</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp đội ngũ kỹ sư công trường và thợ xây dựng lành nghề nhiều năm kinh nghiệm.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-brand-border flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-house-chimney-window text-base"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-primary mb-1">Cập nhật xu hướng thiết kế hiện đại</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Luôn tối ưu giải pháp không gian mở, thông thoáng và vật liệu xây dựng bền đẹp theo khí hậu miền Trung.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-brand-border flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-clipboard-check text-base"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-primary mb-1">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Báo cáo tiến độ và hình ảnh thi công hằng ngày giúp chủ đầu tư theo dõi sát sao công trình từ xa.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-brand-border flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-shield-halved text-base"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-primary mb-1">Bảo hành công trình lâu dài</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu dài hạn, hỗ trợ bảo trì nhanh chóng giúp gia chủ hoàn toàn yên tâm khi sử dụng.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-brand-border flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-file-invoice-dollar text-base"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-primary mb-1">Chi phí minh bạch, không phát sinh</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng chủng loại vật tư, cân đối ngân sách hợp lý và cam kết không phát sinh chi phí hợp đồng.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-brand-border flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-headset text-base"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-primary mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Khảo sát mặt bằng thực tế tại Đà Nẵng miễn phí, tư vấn phương án công năng và hồ sơ pháp lý nhanh gọn.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 6: CÔNG TRÌNH THỰC TẾ THI CÔNG XÂY DỰNG (9 ảnh thực tế từ Google Drive) -->
    <!-- ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
        <div class="hd-container">
            <div class="text-center mb-6">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase">
                    Công Trình Thực Tế Thi Công Xây Dựng
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Hình ảnh thực tế quá trình thi công phần thô, hoàn thiện mặt tiền và bàn giao nhà phố do đội ngũ kỹ sư HD-Cons trực tiếp thực hiện.
                </p>
            </div>

            <!-- Thanh lọc danh mục nhỏ gọn, viết liền không xuống dòng tên danh mục -->
            <div class="flex items-center justify-start sm:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6">
                <button type="button" onclick="filterConstruction('all')" data-filter="all" class="construction-tab cat-tab-btn active px-3.5 py-1.5 rounded-lg border border-brand-border text-xs font-semibold">
                    Tất cả
                </button>
                <button type="button" onclick="filterConstruction('phan-tho')" data-filter="phan-tho" class="construction-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Thi công phần thô
                </button>
                <button type="button" onclick="filterConstruction('hoan-thien')" data-filter="hoan-thien" class="construction-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Thi công hoàn thiện
                </button>
                <button type="button" onclick="filterConstruction('nha-pho')" data-filter="nha-pho" class="construction-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Nhà phố trọn gói
                </button>
                <button type="button" onclick="filterConstruction('noi-that')" data-filter="noi-that" class="construction-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Nội thất – Biệt thự
                </button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính, tên hiển thị trọn vẹn không bị cắt hay tràn -->
            <div id="construction-grid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <!-- Dữ liệu 9 ảnh thực tế được render chuẩn từ JS bên dưới -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 7: CÁC DỰ ÁN TIÊU BIỂU Ở ĐÀ NẴNG (10 ảnh dự án từ Google Drive) -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-light border-y border-brand-border">
        <div class="hd-container">
            <div class="text-center mb-6">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase">
                    Các Dự Án Tiêu Biểu Ở Đà Nẵng
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Tổng hợp các mẫu nhà phố, biệt thự và căn hộ do HD-Cons thiết kế và thi công thực tế tại Cẩm Lệ, Hòa Xuân, Hải Châu, Sơn Trà, Ngũ Hành Sơn và Liên Chiểu.
                </p>
            </div>

            <!-- Bộ lọc khu vực Đà Nẵng nhỏ gọn, không xuống dòng từng tên danh mục -->
            <div class="flex items-center justify-start sm:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6">
                <button type="button" onclick="filterDanang('all')" data-dn-filter="all" class="danang-tab cat-tab-btn active px-3.5 py-1.5 rounded-lg border border-brand-border text-xs font-semibold">
                    Tất cả Đà Nẵng
                </button>
                <button type="button" onclick="filterDanang('cam-le')" data-dn-filter="cam-le" class="danang-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Cẩm Lệ – Hòa Xuân
                </button>
                <button type="button" onclick="filterDanang('hai-chau')" data-dn-filter="hai-chau" class="danang-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Hải Châu – Thanh Khê
                </button>
                <button type="button" onclick="filterDanang('son-tra')" data-dn-filter="son-tra" class="danang-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Sơn Trà – Ngũ Hành Sơn
                </button>
                <button type="button" onclick="filterDanang('lien-chieu')" data-dn-filter="lien-chieu" class="danang-tab cat-tab-btn px-3.5 py-1.5 rounded-lg border border-brand-border bg-white text-slate-700 hover:border-brand-primary text-xs font-semibold">
                    Liên Chiểu
                </button>
            </div>

            <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 5 cột (2 hàng x 5) cực cân đối trên máy tính -->
            <div id="danang-projects-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Dữ liệu 10 dự án Đà Nẵng được render chuẩn từ JS bên dưới -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 8: DANH MỤC BÁO GIÁ (Theo danh mục mẫu Tín Trường Thịnh)       -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white">
        <div class="hd-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase">
                    Báo Giá Thiết Kế &amp; Thi Công Tham Khảo
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Đơn giá minh bạch theo từng gói dịch vụ. Miễn phí tư vấn phương án mặt bằng và hỗ trợ thủ tục xin giấy phép xây dựng khi ký hợp đồng thi công.
                </p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                <!-- Gói 1 -->
                <div class="border border-brand-border rounded-xl p-5 bg-white flex flex-col justify-between hover:border-brand-primary transition-colors">
                    <div>
                        <h3 class="text-sm font-bold text-brand-primary uppercase mb-2">Báo Giá Thiết Kế Kiến Trúc</h3>
                        <div class="text-xl font-extrabold text-brand-accent mb-3">Từ 120.000đ <span class="text-xs font-medium text-slate-500">/m²</span></div>
                        <ul class="space-y-2 text-xs text-slate-600">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Hồ sơ thiết kế kiến trúc &amp; 3D mặt tiền</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Bản vẽ kết cấu chịu lực chi tiết</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Bản vẽ hệ thống điện nước M&amp;E</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Hỗ trợ hồ sơ xin phép xây dựng</span></li>
                        </ul>
                    </div>
                    <a href="#lien-he-bao-gia" onclick="preselectService('Thiết kế kiến trúc')" class="mt-5 block text-center py-2.5 rounded-lg bg-brand-light hover:bg-brand-primary hover:text-white text-brand-primary text-xs font-semibold transition-colors">
                        Nhận báo giá chi tiết
                    </a>
                </div>

                <!-- Gói 2 -->
                <div class="border border-brand-border rounded-xl p-5 bg-white flex flex-col justify-between hover:border-brand-primary transition-colors">
                    <div>
                        <h3 class="text-sm font-bold text-brand-primary uppercase mb-2">Báo Giá Thi Công Phần Thô</h3>
                        <div class="text-xl font-extrabold text-brand-accent mb-3">Từ 3.600.000đ <span class="text-xs font-medium text-slate-500">/m²</span></div>
                        <ul class="space-y-2 text-xs text-slate-600">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Cung cấp toàn bộ vật tư phần thô chuẩn</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Thép Hòa Phát/Việt Nhật, dây Cadivi</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Nhân công hoàn thiện ốp lát, sơn nước</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Bảo hành kết cấu khung sườn 5 năm</span></li>
                        </ul>
                    </div>
                    <a href="#lien-he-bao-gia" onclick="preselectService('Thi công phần thô')" class="mt-5 block text-center py-2.5 rounded-lg bg-brand-light hover:bg-brand-primary hover:text-white text-brand-primary text-xs font-semibold transition-colors">
                        Nhận báo giá chi tiết
                    </a>
                </div>

                <!-- Gói 3 -->
                <div class="border border-brand-border rounded-xl p-5 bg-white flex flex-col justify-between hover:border-brand-primary transition-colors">
                    <div>
                        <h3 class="text-sm font-bold text-brand-primary uppercase mb-2">Báo Giá Thi Công Hoàn Thiện</h3>
                        <div class="text-xl font-extrabold text-brand-accent mb-3">Từ 2.400.000đ <span class="text-xs font-medium text-slate-500">/m²</span></div>
                        <ul class="space-y-2 text-xs text-slate-600">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Vật liệu gạch ốp lát, đá granite cầu thang</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Hệ thống cửa nhôm Xingfa, cửa phòng</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Sơn nước nội ngoại thất Dulux/Jotun</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Thiết bị vệ sinh &amp; chiếu sáng đồng bộ</span></li>
                        </ul>
                    </div>
                    <a href="#lien-he-bao-gia" onclick="preselectService('Thi công hoàn thiện')" class="mt-5 block text-center py-2.5 rounded-lg bg-brand-light hover:bg-brand-primary hover:text-white text-brand-primary text-xs font-semibold transition-colors">
                        Nhận báo giá chi tiết
                    </a>
                </div>

                <!-- Gói 4 -->
                <div class="border-2 border-brand-primary rounded-xl p-5 bg-brand-primary/[0.03] flex flex-col justify-between">
                    <div>
                        <h3 class="text-sm font-bold text-brand-primary uppercase mb-2">Báo Giá Thi Công Trọn Gói</h3>
                        <div class="text-xl font-extrabold text-brand-accent mb-3">Từ 5.800.000đ <span class="text-xs font-medium text-slate-500">/m²</span></div>
                        <ul class="space-y-2 text-xs text-slate-600">
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Chìa khóa trao tay từ phần thô đến hoàn thiện</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Tặng hồ sơ thiết kế kiến trúc &amp; xin phép</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Kỹ sư giám sát trực tiếp toàn thời gian</span></li>
                            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand-accent mt-0.5"></i><span>Cam kết không phát sinh chi phí hợp đồng</span></li>
                        </ul>
                    </div>
                    <a href="#lien-he-bao-gia" onclick="preselectService('Thi công trọn gói nhà phố')" class="mt-5 block text-center py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs font-semibold transition-colors">
                        Đăng ký tư vấn ngay
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 9: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ                    -->
    <!-- ===================================================================== -->
    <section id="lien-he-bao-gia" class="py-10 sm:py-14 bg-brand-primary text-white">
        <div class="hd-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Cột thông tin hỗ trợ -->
                <div class="lg:col-span-5">
                    <p class="text-xs font-semibold uppercase tracking-widest text-amber-300 mb-2">Miễn phí tư vấn &amp; dự toán</p>
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug mb-4">
                        Đăng Ký Nhận Báo Giá Thiết Kế &amp; Thi Công Nhà Phố
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-6">
                        Quý khách vui lòng để lại thông tin diện tích đất và nhu cầu xây dựng. Kỹ sư HD-Cons sẽ liên hệ tư vấn sơ bộ phương án mặt bằng và gửi bảng dự toán chi tiết trong vòng 30 phút.
                    </p>

                    <div class="space-y-3 text-xs sm:text-sm">
                        <div class="flex items-center gap-3">
                            <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0">
                                <i class="fa-solid fa-phone-volume"></i>
                            </span>
                            <div>
                                <div class="text-[11px] text-slate-300">Hotline tư vấn trực tiếp</div>
                                <a href="tel:0905830380" class="font-bold text-white hover:text-amber-300">0905.830.380</a>
                                <span class="mx-1 text-white/40">-</span>
                                <a href="tel:0988747551" class="font-bold text-white hover:text-amber-300">0988.747.551</a>
                            </div>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </span>
                            <div>
                                <div class="text-[11px] text-slate-300">Văn phòng giao dịch</div>
                                <div class="font-semibold text-white">157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng</div>
                            </div>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0">
                                <i class="fa-solid fa-globe"></i>
                            </span>
                            <div>
                                <div class="text-[11px] text-slate-300">Website chính thức</div>
                                <div class="font-semibold text-white">hdcons.com</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Cột Form yêu cầu báo giá -->
                <div class="lg:col-span-7">
                    <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                        <h3 class="text-base sm:text-lg font-bold text-brand-primary mb-4">Gửi Yêu Cầu Báo Giá Nhanh</h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên <span class="text-red-500">*</span></label>
                                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                            <div>
                                <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                                <input id="q-phone" type="tel" required placeholder="Ví dụ: 0905 xxx xxx" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                            <div>
                                <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                                <select id="q-type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn - Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                <select id="q-budget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1">Email (nếu có)</label>
                                <input id="q-email" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                            <div>
                                <label for="q-service" class="block text-xs font-semibold text-slate-700 mb-1">Nhu cầu dịch vụ</label>
                                <input id="q-service" type="text" placeholder="Thiết kế, phần thô, trọn gói..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                            </div>
                            <div class="sm:col-span-2">
                                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Diện tích đất &amp; Ghi chú yêu cầu</label>
                                <textarea id="q-note" rows="3" placeholder="Ví dụ: Đất 5x20m tại Hòa Xuân, dự kiến xây nhà phố 3 tầng hiện đại..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
                            </div>
                        </div>

                        <div class="mt-4 flex flex-col sm:flex-row items-stretch sm:items-center gap-3">
                            <button type="submit" class="flex-1 py-3 px-5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-sm font-bold shadow transition-colors">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Báo Giá
                            </button>
                            <a href="https://zalo.me/0905830380" target="_blank" rel="noopener noreferrer" class="py-3 px-5 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-light text-sm font-semibold text-center transition-colors">
                                Tư vấn qua Zalo
                            </a>
                        </div>

                        <!-- Hộp thông báo trạng thái gửi form (Không dùng alert) -->
                        <div id="quote-feedback" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm"></div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 10: DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ                      -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-white border-b border-brand-border">
        <div class="hd-container">
            <div class="text-center mb-7">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase">
                    Đối Tác Cung Ứng Vật Tư Uy Tín
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    HD-Cons hợp tác cùng các thương hiệu vật liệu xây dựng và thiết bị hoàn thiện chính hãng hàng đầu, đảm bảo chất lượng bền vững cho mọi công trình.
                </p>
            </div>

            <!-- Lưới đối tác gọn gàng 2 cột trên mobile, 5 cột trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0054A6]">HÒA PHÁT</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Thép Xây Dựng</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#D71920]">SÔNG GIANH</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Xi Măng Chất Lượng</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#1E4F91]">DULUX</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Sơn Nội Ngoại Thất</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0A2540]">JOTUN</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Sơn Cao Cấp</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0072BC]">BÌNH MINH</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Ống Nhựa Cấp Thoát</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#C8102E]">CADIVI</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Dây Cáp Điện</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#1A1A1A]">TOTO</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#2B2B2B]">AN CƯỜNG</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Gỗ Công Nghiệp</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#B57C19]">XINGFA</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Nhôm Kính Cao Cấp</span>
                </div>
                <div class="border border-brand-border rounded-xl p-4 bg-brand-light/50 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-primary transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#005B9A]">PANASONIC</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Thiết Bị Điện</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 11: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm)   -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-brand-light border-b border-brand-border">
        <div class="hd-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase">
                    Tin Tức &amp; Kinh Nghiệm Xây Nhà
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Chia sẻ kiến thức kỹ thuật thi công, phong thủy nhà phố và bí quyết quản lý chi phí xây dựng thực tế tại Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Danh sách bài viết được render từ JS -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 12: GOOGLE MAPS & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ         -->
    <!-- ===================================================================== -->
    <section id="ban-do-fanpage" class="py-10 sm:py-14 bg-white">
        <div class="hd-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-bold text-brand-primary uppercase">
                    Vị Trí Văn Phòng &amp; Kết Nối Fanpage HD - Cons
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Mời quý khách ghé trực tiếp văn phòng tại 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng hoặc theo dõi tiến độ các công trình mới nhất trên Fanpage HD-Cons.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                <!-- Cột 1: Bản đồ Google Map văn phòng HD-Cons -->
                <div class="lg:col-span-7 bg-brand-light border border-brand-border rounded-xl p-3 sm:p-4 flex flex-col">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                        <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
                            <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
                            <span>Bản Đồ Google Maps – 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng</span>
                        </div>
                        <a
                            href="https://www.google.com/maps/search/?api=1&query=157+Diệp+Minh+Châu,+Cẩm+Lệ,+Đà+Nẵng"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold text-brand-accent hover:text-brand-primary inline-flex items-center gap-1"
                        >
                            <span>Mở chỉ đường</span>
                            <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                        </a>
                    </div>
                    <div class="w-full h-[320px] sm:h-[360px] rounded-lg overflow-hidden border border-brand-border bg-slate-200 flex-1">
                        <iframe
                            title="Bản đồ văn phòng HD-Cons 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng"
                            src="https://maps.google.com/maps?q=157+Di%E1%BB%87p+Minh+Ch%C3%A2u,+H%C3%B2a+Xu%C3%A2n,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen
                        ></iframe>
                    </div>
                </div>

                <!-- Cột 2: Fanpage Facebook HD-Cons hiển thị trực tiếp ngoài trang chủ -->
                <div class="lg:col-span-5 bg-brand-light border border-brand-border rounded-xl p-3 sm:p-4 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 mb-3">
                            <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
                                <i class="fa-brands fa-facebook text-[#1877F2]"></i>
                                <span>Fanpage Facebook HD - Cons</span>
                            </div>
                            <a
                                href="https://www.facebook.com/profile.php?id=100063776191640"
                                target="_blank"
                                rel="noopener noreferrer"
                                class="text-xs font-semibold text-[#1877F2] hover:underline inline-flex items-center gap-1"
                            >
                                <span>Truy cập trang</span>
                                <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>

                        <!-- Card nhận diện Fanpage + Facebook Page Plugin -->
                        <div class="bg-white border border-brand-border rounded-lg overflow-hidden">
                            <div class="p-3 bg-gradient-to-r from-brand-primary to-brand-dark text-white flex items-center gap-3">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w256"
                                    alt="Avatar Fanpage HD-Cons"
                                    class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0"
                                    onerror="handleDriveImageError(this, '1IggMv6W8S-yZGwUGWzicovHN7WGb830U', 'HD')"
                                >
                                <div class="min-w-0 flex-1">
                                    <div class="text-sm font-bold leading-snug">Thiết Kế Thi Công Nhà Phố HD - Cons</div>
                                    <div class="text-[11px] text-slate-200 mt-0.5">Cập nhật hình ảnh công trình thực tế tại Đà Nẵng</div>
                                </div>
                            </div>

                            <!-- Nhúng Facebook Page Plugin chuẩn Flatsome -->
                            <div class="w-full h-[220px] sm:h-[250px] overflow-hidden bg-slate-50 flex items-center justify-center">
                                <iframe
                                    title="Fanpage Facebook Thiết Kế Thi Công Nhà Phố HD-Cons"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063776191640&tabs=timeline&width=500&height=250&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    class="w-full h-full border-0"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                ></iframe>
                            </div>

                            <div class="p-3 bg-slate-50 border-t border-brand-border flex items-center justify-between gap-2">
                                <span class="text-[11px] text-slate-600">Theo dõi tiến độ thi công hàng ngày</span>
                                <a
                                    href="https://www.facebook.com/profile.php?id=100063776191640"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    class="px-3 py-1.5 rounded-md bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs font-semibold inline-flex items-center gap-1.5 transition-colors shrink-0"
                                >
                                    <i class="fa-brands fa-facebook-f"></i>
                                    <span>Theo dõi Fanpage</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 13: FOOTER FLATSOME CHUẨN (Thông tin HD-Cons, Danh mục, Liên hệ) -->
    <!-- ===================================================================== -->
    <footer class="bg-brand-dark text-slate-200 pt-10 pb-8">
        <div class="hd-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-4">
                        <img
                            src="https://lh3.googleusercontent.com/d/1IggMv6W8S-yZGwUGWzicovHN7WGb830U=w300"
                            alt="Logo HD-Cons"
                            class="h-11 w-auto max-w-[120px] object-contain bg-white rounded-md p-1"
                            onerror="handleDriveImageError(this, '1IggMv6W8S-yZGwUGWzicovHN7WGb830U', 'HD-CONS')"
                        >
                        <div>
                            <div class="text-base font-extrabold text-white">THIẾT KẾ THI CÔNG NHÀ PHỐ HD - CONS</div>
                            <div class="text-xs text-amber-300">Website: hdcons.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-accent mt-1"></i>
                            <span>Trụ sở: 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-accent"></i>
                            <span>Hotline: <a href="tel:0905830380" class="text-white font-semibold hover:text-amber-300">0905.830.380</a> – <a href="tel:0988747551" class="text-white font-semibold hover:text-amber-300">0988.747.551</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-brand-accent"></i>
                            <a href="https://www.facebook.com/profile.php?id=100063776191640" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 break-all">
                                Facebook: Thiết Kế Thi Công Nhà Phố HD - Cons
                            </a>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition-colors">Thiết kế kiến trúc nhà phố</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition-colors">Thi công phần thô chuẩn kỹ thuật</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition-colors">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition-colors">Thiết kế &amp; thi công nội thất</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-4">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5">Danh Mục Trang Chủ</h4>
                    <div class="grid grid-cols-2 gap-2 text-xs sm:text-sm text-slate-300">
                        <a href="#cong-trinh-thuc-te" class="hover:text-amber-300 transition-colors">Công trình thực tế</a>
                        <a href="#du-an-da-nang" class="hover:text-amber-300 transition-colors">Dự án Đà Nẵng</a>
                        <a href="#bao-gia" class="hover:text-amber-300 transition-colors">Bảng báo giá</a>
                        <a href="#doi-tac" class="hover:text-amber-300 transition-colors">Đối tác vật tư</a>
                        <a href="#tin-tuc" class="hover:text-amber-300 transition-colors">Tin tức xây dựng</a>
                        <a href="#lien-he-bao-gia" class="hover:text-amber-300 transition-colors">Yêu cầu báo giá</a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright 2026 © Thiết Kế Thi Công Nhà Phố HD - Cons (hdcons.com).</div>
                <div>Địa chỉ: 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng.</div>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO - FACEBOOK - HOTLINE (MÁY TÍNH & MOBILE) -->
    <!-- ===================================================================== -->

    <!-- Phiên bản MÁY TÍNH: Cụm nút nổi gọn đẹp góc phải dưới màn hình -->
    <div class="hidden md:flex flex-col gap-2.5 fixed right-4 bottom-6 z-40">
        <!-- Nút Zalo -->
        <a
            href="https://zalo.me/0905830380"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Chat Zalo HD-Cons"
            class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054CC] text-white pl-3 pr-3.5 py-2.5 rounded-full shadow-lg transition-all"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a
            href="https://www.facebook.com/profile.php?id=100063776191640"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Facebook Fanpage HD-Cons"
            class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465CC] text-white pl-3 pr-3.5 py-2.5 rounded-full shadow-lg transition-all"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a
            href="tel:0905830380"
            aria-label="Gọi Hotline 0905.830.380"
            class="pulse-ring flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white pl-3 pr-3.5 py-2.5 rounded-full shadow-lg transition-all"
        >
            <span class="w-7 h-7 rounded-full bg-white text-brand-accent flex items-center justify-center">
                <i class="fa-solid fa-phone text-xs"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">0905.830.380</span>
        </a>

        <!-- Nút lên đầu trang -->
        <button
            id="scroll-top-btn"
            type="button"
            onclick="window.scrollTo({top: 0, behavior: 'smooth'})"
            aria-label="Lên đầu trang"
            class="hidden self-end w-10 h-10 rounded-full bg-brand-primary hover:bg-brand-dark text-white shadow-lg items-center justify-center transition-colors"
        >
            <i class="fa-solid fa-chevron-up text-xs"></i>
        </button>
    </div>

    <!-- Phiên bản ĐIỆN THOẠI: Thanh nút liên hệ cố định dưới đáy 3 nút rõ ràng dễ bấm -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-brand-border shadow-[0_-4px_16px_rgba(0,0,0,0.08)]">
        <div class="grid grid-cols-3 divide-x divide-slate-200">
            <a href="tel:0905830380" class="flex items-center justify-center gap-1.5 py-3 bg-brand-accent text-white text-xs font-bold active:opacity-90">
                <i class="fa-solid fa-phone-volume"></i>
                <span>Hotline</span>
            </a>
            <a href="https://zalo.me/0905830380" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-3 bg-[#0068FF] text-white text-xs font-bold active:opacity-90">
                <span class="px-1 py-0.5 rounded bg-white text-[#0068FF] text-[10px] font-extrabold leading-none">Zalo</span>
                <span>Chat Zalo</span>
            </a>
            <a href="https://www.facebook.com/profile.php?id=100063776191640" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-3 bg-[#1877F2] text-white text-xs font-bold active:opacity-90">
                <i class="fa-brands fa-facebook-f"></i>
                <span>Facebook</span>
            </a>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL XEM ẢNH CÔNG TRÌNH / CHI TIẾT BÀI VIẾT                          -->
    <!-- ===================================================================== -->
    <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/75 backdrop-blur-sm flex items-center justify-center p-3 sm:p-5" onclick="closeDetailModal(event)">
        <div class="bg-white rounded-xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl" onclick="event.stopPropagation()">
            <div class="flex items-center justify-between gap-3 px-4 sm:px-5 py-3.5 border-b border-brand-border sticky top-0 bg-white z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-bold text-brand-primary leading-snug">Chi tiết công trình</h3>
                <button type="button" onclick="hideDetailModal()" aria-label="Đóng cửa sổ" class="w-8 h-8 rounded-lg bg-brand-light hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modal-body" class="p-4 sm:p-5"></div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC & FORM BÁO GIÁ  -->
    <!-- ===================================================================== -->
    <script>
        /**
         * Hàm dự phòng thông minh khi tải ảnh từ Google Drive:
         * 1. Mặc định dùng lh3.googleusercontent.com/d/{id}=w1000 (nhanh & rõ nét)
         * 2. Nếu lỗi thử sang drive.google.com/thumbnail?id={id}&sz=w1000
         * 3. Nếu vẫn không khả dụng hiển thị ảnh placeholder chuyên nghiệp
         */
        function handleDriveImageError(imgEl, fileId, fallbackText) {
            const stage = imgEl.getAttribute('data-fallback-stage') || '0';
            if (stage === '0') {
                imgEl.setAttribute('data-fallback-stage', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (stage === '1') {
                imgEl.setAttribute('data-fallback-stage', '2');
                imgEl.src = 'https://placehold.co/800x600/16355B/FFFFFF?text=' + encodeURIComponent(fallbackText || 'HD-Cons');
            }
        }

        function getDriveUrl(fileId) {
            return 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
        }

        /* -------------------------------------------------------------------
         * DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE CỦA HD-CONS
         * ------------------------------------------------------------------- */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô Nhà Phố 3 Tầng Hiện Đại',
                category: 'phan-tho',
                tags: ['phan-tho', 'nha-pho'],
                categoryLabel: 'Thi công phần thô',
                location: 'Đà Nẵng',
                desc: 'Thi công khung kết cấu bê tông cốt thép nhà phố 3 tầng chuẩn hồ sơ thiết kế, giám sát kỹ thuật chặt chẽ từng công đoạn.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Kết Cấu Móng & Cốt Thép Nhà Phố',
                category: 'phan-tho',
                tags: ['phan-tho', 'nha-pho'],
                categoryLabel: 'Thi công phần thô',
                location: 'Đà Nẵng',
                desc: 'Công tác gia công lắp dựng cốt thép móng, dầm giằng chống lún đảm bảo khả năng chịu lực bền vững cho công trình.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Đổ Bê Tông Sàn Tầng Nhà Phố',
                category: 'phan-tho',
                tags: ['phan-tho', 'nha-pho'],
                categoryLabel: 'Thi công phần thô',
                location: 'Đà Nẵng',
                desc: 'Hệ giàn giáo chống sàn chắc chắn, kiểm tra độ sụt bê tông tươi và bảo dưỡng dưỡng ẩm đúng tiêu chuẩn xây dựng.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Xây Tường & Tô Trát Hoàn Thiện',
                category: 'hoan-thien',
                tags: ['hoan-thien', 'nha-pho'],
                categoryLabel: 'Thi công hoàn thiện',
                location: 'Đà Nẵng',
                desc: 'Thi công xây tường gạch chuẩn mạch, đóng lưới chống nứt vị trí tiếp giáp cột dầm và tô trát phẳng sắc nét.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Mặt Tiền Nhà Phố Hiện Đại Trọn Gói',
                category: 'hoan-thien',
                tags: ['hoan-thien', 'nha-pho'],
                categoryLabel: 'Nhà phố trọn gói',
                location: 'Đà Nẵng',
                desc: 'Hoàn thiện mặt tiền nhà phố hiện đại với hệ lam trang trí, cửa nhôm kính lấy sáng và sơn ngoại thất chống thấm.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Nhà Phố 2 Mặt Tiền Kinh Doanh',
                category: 'nha-pho',
                tags: ['nha-pho', 'hoan-thien'],
                categoryLabel: 'Nhà phố trọn gói',
                location: 'Đà Nẵng',
                desc: 'Giải pháp thiết kế và thi công nhà phố 2 mặt tiền thông thoáng, tối ưu diện tích kinh doanh tầng trệt và không gian ở tầng trên.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Hoàn Thiện Nội Thất Phòng Khách – Bếp',
                category: 'noi-that',
                tags: ['noi-that', 'hoan-thien'],
                categoryLabel: 'Thi công nội thất',
                location: 'Đà Nẵng',
                desc: 'Lắp đặt hoàn thiện không gian nội thất phòng khách liền bếp tinh tế, sử dụng gỗ công nghiệp chống ẩm và đá ốp cao cấp.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Biệt Thự Phố & Căn Hộ Dịch Vụ',
                category: 'noi-that',
                tags: ['noi-that', 'nha-pho'],
                categoryLabel: 'Biệt thự – Căn hộ',
                location: 'Đà Nẵng',
                desc: 'Hạng mục thiết kế thi công trọn gói biệt thự phố và căn hộ cho thuê, tối ưu công năng sử dụng và giá trị khai thác.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Nghiệm Thu & Bàn Giao Nhà Phố Trọn Gói HD-Cons',
                category: 'hoan-thien',
                tags: ['hoan-thien', 'nha-pho'],
                categoryLabel: 'Bàn giao công trình',
                location: 'Đà Nẵng',
                desc: 'Kiểm tra tổng thể hệ thống điện nước, chống thấm và vệ sinh công nghiệp sạch sẽ trước khi bàn giao chìa khóa cho chủ nhà.'
            }
        ];

        /* -------------------------------------------------------------------
         * DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE CỦA HD-CONS
         * ------------------------------------------------------------------- */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố 3 Tầng Khu Đô Thị Hòa Xuân – Cẩm Lệ',
                area: 'cam-le',
                areaLabel: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Thiết kế và thi công trọn gói nhà phố 3 tầng phong cách hiện đại tại khu đô thị sinh thái Hòa Xuân.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Nhà Phố Hiện Đại Đường Diệp Minh Châu – Cẩm Lệ',
                area: 'cam-le',
                areaLabel: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Công trình nhà phố tối ưu ánh sáng tự nhiên với giếng trời trung tâm và ban công trồng cây xanh mát.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Nhà Phố 2 Tầng 1 Tum Khu Nam Việt Á – Ngũ Hành Sơn',
                area: 'son-tra',
                areaLabel: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Nhà phố 2 tầng 1 tum bố trí 3 phòng ngủ rộng rãi, sân thượng thoáng mát phù hợp gia đình trẻ.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố Kết Hợp Văn Phòng Quận Hải Châu',
                area: 'hai-chau',
                areaLabel: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Thiết kế nhà phố kết hợp không gian làm việc hiện đại tại trung tâm thành phố Đà Nẵng.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Nhà Phố 3 Tầng Mặt Tiền Thoáng Quận Thanh Khê',
                area: 'hai-chau',
                areaLabel: 'Quận Thanh Khê, Đà Nẵng',
                desc: 'Giải pháp kiến trúc mặt tiền thanh lịch, tối ưu công năng sử dụng trên diện tích đất phố điển hình.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Căn Hộ Dịch Vụ Cho Thuê Quận Sơn Trà',
                area: 'son-tra',
                areaLabel: 'Quận Sơn Trà, Đà Nẵng',
                desc: 'Thi công trọn gói tòa căn hộ dịch vụ đầy đủ tiện nghi gần biển Mỹ Khê, tối ưu hiệu quả đầu tư.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Biệt Thự Phố Hiện Đại Khu Euro Village – Sơn Trà',
                area: 'son-tra',
                areaLabel: 'Quận Sơn Trà, Đà Nẵng',
                desc: 'Biệt thự phố sang trọng kết hợp sân vườn thoáng đãng và không gian nội thất cao cấp.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Nhà Phố 4 Tầng Khu Đô Thị Phước Lý – Cẩm Lệ',
                area: 'cam-le',
                areaLabel: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Nhà phố 4 tầng khang trang với thiết kế đối lưu không khí tốt và hoàn thiện vật liệu bền đẹp.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Nhà Phố 2 Mặt Tiền Quận Liên Chiểu – Đà Nẵng',
                area: 'lien-chieu',
                areaLabel: 'Quận Liên Chiểu, Đà Nẵng',
                desc: 'Thi công nhà phố góc 2 mặt tiền bề thế, khai thác tối đa ánh sáng và không gian thông thoáng.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Hoàn Thiện Trọn Gói Nhà Phố Hòa Minh – Liên Chiểu',
                area: 'lien-chieu',
                areaLabel: 'Quận Liên Chiểu, Đà Nẵng',
                desc: 'Công trình cải tạo và hoàn thiện trọn gói nhà phố hiện đại, bàn giao đúng tiến độ cam kết.'
            }
        ];

        /* -------------------------------------------------------------------
         * DỮ LIỆU BÀI VIẾT TRANG CHỦ (Cẩm nang xây dựng HD-Cons)
         * ------------------------------------------------------------------- */
        const articlesData = [
            {
                title: 'Hướng dẫn bảo dưỡng bê tông móng nhà phố đúng kỹ thuật',
                date: '15/11/2026',
                imageId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                summary: 'Quy trình tưới nước dưỡng ẩm bê tông trong 7 ngày đầu sau đổ giúp hạn chế nứt chân chim và đạt cường độ chịu lực tối đa.',
                content: 'Trong xây dựng nhà phố tại Đà Nẵng với khí hậu nắng gió đặc trưng, việc bảo dưỡng bê tông móng và sàn đúng kỹ thuật là yếu tố sống còn quyết định tuổi thọ công trình. Sau khi đổ bê tông từ 4–6 giờ, cần che phủ bao tải ẩm và tưới nước phun sương liên tục trong 7 ngày đầu để giữ độ ẩm ổn định, tránh hiện tượng mất nước đột ngột gây rạn nứt bề mặt.'
            },
            {
                title: 'Kinh nghiệm xây nhà phố trọn gói không phát sinh chi phí',
                date: '10/11/2026',
                imageId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                summary: 'Chuẩn bị hồ sơ thiết kế chi tiết và bảng chủng loại vật tư rõ ràng ngay từ đầu giúp chủ đầu tư chủ động hoàn toàn ngân sách.',
                content: 'Để xây nhà trọn gói không phát sinh chi phí, chủ đầu tư cần chốt kỹ mặt bằng công năng 2D, phối cảnh 3D và bảng phụ lục vật tư phần thô – hoàn thiện trước khi khởi công. Tại HD-Cons, mọi hạng mục đều được bóc tách khối lượng minh bạch, giúp gia chủ dễ dàng kiểm soát tài chính từ lúc khởi công đến khi nhận chìa khóa.'
            },
            {
                title: '03 lưu ý quan trọng khi thiết kế nhà phố thông thoáng tại Đà Nẵng',
                date: '04/11/2026',
                imageId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                summary: 'Tối ưu giếng trời, giải pháp chống nóng hướng Tây và hệ thống thoát nước mưa chuẩn kỹ thuật cho nhà phố miền Trung.',
                content: 'Nhà phố thường có chiều ngang 4m–5m và chiều sâu dài, vì vậy bố trí giếng trời kết hợp cầu thang giúp đối lưu gió và đưa ánh sáng tự nhiên vào sâu bên trong. Ngoài ra, với nhà hướng Tây tại Đà Nẵng, giải pháp tường 2 lớp, lam chắn nắng và kính cách nhiệt sẽ giảm đáng kể nhiệt lượng vào mùa hè.'
            },
            {
                title: 'Thủ tục xin giấy phép xây dựng nhà ở riêng lẻ tại TP. Đà Nẵng',
                date: '28/10/2026',
                imageId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                summary: 'Tổng hợp hồ sơ pháp lý, bản vẽ xin phép xây dựng và thời gian xử lý giúp gia chủ khởi công đúng ngày đẹp dự kiến.',
                content: 'Hồ sơ xin phép xây dựng nhà phố bao gồm: đơn đề nghị cấp phép, bản sao giấy chứng nhận quyền sử dụng đất và bộ bản vẽ thiết kế xin phép do đơn vị có chứng chỉ năng lực thực hiện. Khi lựa chọn gói thiết kế thi công tại HD-Cons, chúng tôi hỗ trợ trọn gói quy trình lập hồ sơ và theo dõi cấp phép nhanh chóng.'
            }
        ];

        /* -------------------------------------------------------------------
         * RENDER CÔNG TRÌNH THỰC TẾ (Không nhãn dán, tên hiển thị trọn vẹn)
         * ------------------------------------------------------------------- */
        function renderConstructionGrid(filterKey) {
            const container = document.getElementById('construction-grid');
            if (!container) return;

            const filtered = filterKey === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.tags.includes(filterKey));

            container.innerHTML = filtered.map((item, idx) => `
                <article
                    onclick="openProjectModal('construction', ${constructionProjects.indexOf(item)})"
                    class="project-card cursor-pointer bg-white border border-brand-border rounded-xl overflow-hidden flex flex-col hover:shadow-md hover:border-brand-primary/50 transition-all"
                >
                    <div class="project-img-box">
                        <img
                            src="${getDriveUrl(item.id)}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${item.id}', 'HD-CONS')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-primary leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="mt-1.5 text-[11px] sm:text-xs text-slate-500">
                            ${item.categoryLabel} • ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterConstruction(filterKey) {
            document.querySelectorAll('.construction-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-filter') === filterKey;
                btn.classList.toggle('active', isActive);
                if (!isActive) {
                    btn.classList.add('bg-white', 'text-slate-700');
                } else {
                    btn.classList.remove('bg-white', 'text-slate-700');
                }
            });
            renderConstructionGrid(filterKey);
        }

        /* -------------------------------------------------------------------
         * RENDER 10 DỰ ÁN Ở ĐÀ NẴNG (2 cột mobile, 5 cột desktop, không nhãn dán)
         * ------------------------------------------------------------------- */
        function renderDanangGrid(areaKey) {
            const container = document.getElementById('danang-projects-grid');
            if (!container) return;

            const filtered = areaKey === 'all'
                ? danangProjects
                : danangProjects.filter(item => item.area === areaKey);

            container.innerHTML = filtered.map(item => `
                <article
                    onclick="openProjectModal('danang', ${danangProjects.indexOf(item)})"
                    class="project-card cursor-pointer bg-white border border-brand-border rounded-xl overflow-hidden flex flex-col hover:shadow-md hover:border-brand-primary/50 transition-all"
                >
                    <div class="project-img-box">
                        <img
                            src="${getDriveUrl(item.id)}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${item.id}', 'DU+AN+DA+NANG')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-xs sm:text-[13px] font-bold text-brand-primary leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="mt-1.5 text-[11px] text-slate-500">
                            ${item.areaLabel}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterDanang(areaKey) {
            document.querySelectorAll('.danang-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-dn-filter') === areaKey;
                btn.classList.toggle('active', isActive);
                if (!isActive) {
                    btn.classList.add('bg-white', 'text-slate-700');
                } else {
                    btn.classList.remove('bg-white', 'text-slate-700');
                }
            });
            renderDanangGrid(areaKey);
        }

        /* -------------------------------------------------------------------
         * RENDER BÀI VIẾT TRANG CHỦ
         * ------------------------------------------------------------------- */
        function renderArticles() {
            const container = document.getElementById('articles-grid');
            if (!container) return;

            container.innerHTML = articlesData.map((art, idx) => `
                <article
                    onclick="openArticleModal(${idx})"
                    class="project-card cursor-pointer bg-white border border-brand-border rounded-xl overflow-hidden flex flex-col hover:shadow-md transition-all"
                >
                    <div class="project-img-box">
                        <img
                            src="${getDriveUrl(art.imageId)}"
                            alt="${art.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${art.imageId}', 'TIN+TUC')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 mb-1">${art.date}</div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-primary leading-snug break-words mb-1.5">
                                ${art.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed">
                                ${art.summary}
                            </p>
                        </div>
                        <span class="mt-2.5 inline-flex items-center gap-1 text-[11px] sm:text-xs font-semibold text-brand-accent">
                            <span>Đọc chi tiết</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </span>
                    </div>
                </article>
            `).join('');
        }

        /* -------------------------------------------------------------------
         * MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH & BÀI VIẾT
         * ------------------------------------------------------------------- */
        function openProjectModal(type, index) {
            const item = type === 'construction' ? constructionProjects[index] : danangProjects[index];
            if (!item) return;

            document.getElementById('modal-title').textContent = item.title;
            document.getElementById('modal-body').innerHTML = `
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img
                        src="${getDriveUrl(item.id)}"
                        alt="${item.title}"
                        class="w-full max-h-[60vh] object-contain mx-auto"
                        onerror="handleDriveImageError(this, '${item.id}', 'HD-CONS')"
                    >
                </div>
                <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">${item.desc}</p>
                <div class="flex flex-wrap items-center justify-between gap-3 pt-3 border-t border-brand-border">
                    <div class="text-xs text-slate-600">
                        <strong>Đơn vị thực hiện:</strong> Thiết Kế Thi Công Nhà Phố HD - Cons
                    </div>
                    <div class="flex items-center gap-2">
                        <a href="tel:0905830380" class="px-4 py-2 rounded-lg bg-brand-accent text-white text-xs font-bold">
                            Gọi 0905.830.380
                        </a>
                        <a href="#lien-he-bao-gia" onclick="hideDetailModal()" class="px-4 py-2 rounded-lg bg-brand-primary text-white text-xs font-bold">
                            Nhận báo giá mẫu này
                        </a>
                    </div>
                </div>
            `;
            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;

            document.getElementById('modal-title').textContent = art.title;
            document.getElementById('modal-body').innerHTML = `
                <div class="text-xs text-slate-500 mb-3">Ngày đăng: ${art.date} • Chuyên mục: Kinh nghiệm xây dựng HD-Cons</div>
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img
                        src="${getDriveUrl(art.imageId)}"
                        alt="${art.title}"
                        class="w-full max-h-[360px] object-cover"
                        onerror="handleDriveImageError(this, '${art.imageId}', 'TIN+TUC')"
                    >
                </div>
                <p class="text-sm font-semibold text-slate-800 leading-relaxed mb-3">${art.summary}</p>
                <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-5">${art.content}</p>
                <div class="p-4 rounded-lg bg-brand-light border border-brand-border text-xs sm:text-sm">
                    <strong>Cần tư vấn thiết kế &amp; thi công nhà phố tại Đà Nẵng?</strong><br>
                    Liên hệ ngay HD-Cons qua Hotline <strong>0905.830.380 - 0988.747.551</strong> hoặc ghé văn phòng 157 Diệp Minh Châu, Cẩm Lệ, Đà Nẵng để được tư vấn miễn phí.
                </div>
            `;
            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function closeDetailModal(e) {
            if (e.target.id === 'detail-modal') {
                hideDetailModal();
            }
        }

        function hideDetailModal() {
            document.getElementById('detail-modal').classList.add('hidden');
        }

        /* -------------------------------------------------------------------
         * SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
         * ------------------------------------------------------------------- */
        let currentBanner = 0;
        const totalBanners = 2;
        let bannerTimer = null;

        function updateBannerUI() {
            const track = document.getElementById('hero-slider-track');
            if (track) {
                track.style.transform = 'translateX(-' + (currentBanner * 100) + '%)';
            }
            for (let i = 0; i < totalBanners; i++) {
                const dot = document.getElementById('banner-dot-' + i);
                if (!dot) continue;
                if (i === currentBanner) {
                    dot.classList.remove('w-2.5', 'bg-white/60');
                    dot.classList.add('w-6', 'bg-brand-accent');
                } else {
                    dot.classList.remove('w-6', 'bg-brand-accent');
                    dot.classList.add('w-2.5', 'bg-white/60');
                }
            }
        }

        function moveBanner(step) {
            currentBanner = (currentBanner + step + totalBanners) % totalBanners;
            updateBannerUI();
            restartBannerAutoplay();
        }

        function goToBanner(idx) {
            currentBanner = idx;
            updateBannerUI();
            restartBannerAutoplay();
        }

        function restartBannerAutoplay() {
            if (bannerTimer) clearInterval(bannerTimer);
            bannerTimer = setInterval(() => {
                currentBanner = (currentBanner + 1) % totalBanners;
                updateBannerUI();
            }, 5000);
        }

        /* Hỗ trợ vuốt ngang banner trên điện thoại */
        function initBannerTouch() {
            const sliderEl = document.getElementById('hero-slider');
            if (!sliderEl) return;
            let startX = 0;
            sliderEl.addEventListener('touchstart', (e) => {
                startX = e.changedTouches[0].screenX;
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - startX;
                if (Math.abs(diff) > 45) {
                    moveBanner(diff < 0 ? 1 : -1);
                }
            }, { passive: true });
        }

        /* -------------------------------------------------------------------
         * MENU MOBILE & FORM YÊU CẦU BÁO GIÁ
         * ------------------------------------------------------------------- */
        function toggleMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            if (panel) panel.classList.toggle('hidden');
        }

        function closeMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            if (panel) panel.classList.add('hidden');
        }

        function preselectService(serviceName) {
            const input = document.getElementById('q-service');
            if (input) input.value = serviceName;
        }

        function handleQuoteSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const type = document.getElementById('q-type').value;
            const budget = document.getElementById('q-budget').value;
            const feedback = document.getElementById('quote-feedback');

            if (!name || !phone) return;

            feedback.innerHTML = `
                <div class="font-bold mb-1"><i class="fa-solid fa-circle-check mr-1"></i> Đã tiếp nhận yêu cầu báo giá thành công!</div>
                <div>Cảm ơn anh/chị <strong>${name}</strong> (${phone}). Kỹ sư HD-Cons sẽ liên hệ tư vấn công trình <strong>${type}</strong> (mức đầu tư: ${budget}) trong thời gian sớm nhất. Hotline hỗ trợ gấp: <strong>0905.830.380</strong>.</div>
            `;
            feedback.classList.remove('hidden');
            document.getElementById('quote-form').reset();
        }

        /* Hiện nút lên đầu trang khi cuộn xuống */
        window.addEventListener('scroll', () => {
            const btn = document.getElementById('scroll-top-btn');
            if (!btn) return;
            if (window.scrollY > 400) {
                btn.classList.remove('hidden');
                btn.classList.add('flex');
            } else {
                btn.classList.add('hidden');
                btn.classList.remove('flex');
            }
        });

        /* Khởi tạo toàn bộ dữ liệu khi trang tải xong */
        document.addEventListener('DOMContentLoaded', () => {
            renderConstructionGrid('all');
            renderDanangGrid('all');
            renderArticles();
            restartBannerAutoplay();
            initBannerTouch();
        });
    </script>
</body>
</html>
