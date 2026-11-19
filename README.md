<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH NGUYỄN AN THẠNH | Thiết Kế & Thi Công Xây Dựng Tại Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH NGUYỄN AN THẠNH (nguyenanthanh.com) chuyên Thiết kế Kiến trúc, Thi công phần thô, Thi công hoàn thiện, Xây nhà trọn gói và Nội thất uy tín tại Đà Nẵng. Hotline: 0907.651.779." />

  <!-- Open Graph / Thumbnail Logo khi chia sẻ đường link trang web -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="CÔNG TY TNHH NGUYỄN AN THẠNH" />
  <meta property="og:url" content="https://nguyenanthanh.com/" />
  <meta property="og:title" content="CÔNG TY TNHH NGUYỄN AN THẠNH - Thiết Kế & Thi Công Xây Dựng Đà Nẵng" />
  <meta property="og:description" content="Chuyên thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện và xây nhà trọn gói chuyên nghiệp tại Đà Nẵng. Hotline: 0907.651.779." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w1200" />
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w1200" />
  <meta property="og:image:alt" content="Logo CÔNG TY TNHH NGUYỄN AN THẠNH" />

  <!-- Twitter Card Thumbnail -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH NGUYỄN AN THẠNH | nguyenanthanh.com" />
  <meta name="twitter:description" content="Thiết kế kiến trúc - Thi công xây dựng trọn gói tại Đà Nẵng. Hotline: 0907.651.779." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w1200" />

  <!-- Favicon dùng logo công ty -->
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w128" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome 6 Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

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
              primary: '#0D3B66',
              dark: '#082644',
              light: '#16538A',
              accent: '#C98A2B',
              accentHover: '#B0761E',
              soft: '#F4F7FA',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* ================================================================
       BIẾN MÀU CHỦ ĐẠO (Dễ đồng bộ nhanh trong Flatsome Customize)
       ================================================================ */
    :root {
      --brand-primary: #0D3B66;
      --brand-dark: #082644;
      --brand-accent: #C98A2B;
      --brand-bg-soft: #F5F7FA;
      --text-main: #1E293B;
      --text-muted: #526071;
      --border-light: #E2E8F0;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
    }

    body {
      margin: 0;
      padding: 0;
      width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: var(--text-main);
      background-color: #FFFFFF;
      -webkit-font-smoothing: antialiased;
    }

    /* Khung rộng 95% trên máy tính, đảm bảo cân đối và không tràn viền */
    .nat-container {
      width: 95%;
      max-width: 1680px;
      margin-left: auto;
      margin-right: auto;
    }

    /* Thanh gạch tiêu đề chuẩn phong cách Flatsome */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-heading::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 56px;
      height: 3px;
      background-color: var(--brand-accent);
      border-radius: 999px;
    }
    .flatsome-heading-left::after {
      left: 0;
      transform: none;
    }

    /* Dropdown Menu Flatsome gọn gàng */
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .nav-item-has-children:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Slider 2 Banner bằng nhau tuyệt đối, chữ nằm gọn trong vùng an toàn */
    .banner-slider-viewport {
      position: relative;
      width: 100%;
      overflow: hidden;
    }
    .banner-track {
      display: flex;
      width: 100%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .banner-slide {
      flex: 0 0 100%;
      width: 100%;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      /* Chiều cao đồng nhất cho cả 2 banner trên mọi màn hình */
      min-height: 330px;
    }
    @media (min-width: 640px) {
      .banner-slide {
        min-height: 400px;
      }
    }
    @media (min-width: 1024px) {
      .banner-slide {
        min-height: 490px;
      }
    }

    /* Hiệu ứng mượt cho nút liên hệ nổi */
    @keyframes softPulse {
      0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.45); }
      70% { box-shadow: 0 0 0 11px rgba(220, 38, 38, 0); }
      100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
    }
    .hotline-pulse {
      animation: softPulse 2.2s infinite;
    }

    /* Ẩn thanh cuộn phụ trên thanh danh mục mobile nếu cần */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>

<body class="bg-white text-slate-800">

  <!-- =================================================================
       1. TOP BAR ĐƠN GIẢN (Không chứa tùy chọn chỉnh sửa UX Builder)
       ================================================================= -->
  <div class="bg-[#082644] text-slate-100 text-xs py-2 border-b border-white/10">
    <div class="nat-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-phone text-[#C98A2B]"></i>
          <a href="tel:0907651779" class="hover:text-[#C98A2B] transition font-medium">0907.651.779</a>
        </span>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-[#C98A2B]"></i>
          <span>K138/H97/40/04 Hoàng Văn Thái, P. Hòa Khánh, TP. Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="hidden md:inline text-slate-300">nguyenanthanh.com</span>
        <a href="https://www.facebook.com/ngochung.nguyen.9828?locale=vi_VN" target="_blank" rel="noopener noreferrer" aria-label="Facebook Nguyễn An Thạnh" class="hover:text-[#C98A2B] transition">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
        <a href="https://zalo.me/0907651779" target="_blank" rel="noopener noreferrer" aria-label="Zalo Nguyễn An Thạnh" class="hover:text-[#C98A2B] transition font-semibold">
          Zalo
        </a>
      </div>
    </div>
  </div>

  <!-- =================================================================
       2. HEADER CHÍNH (Logo gọn nhỏ + Menu 1 hàng liền mạch, KHÔNG nút gọi ngay)
       ================================================================= -->
  <header id="site-header" class="sticky top-0 z-40 bg-white/98 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="nat-container">
      <div class="flex items-center justify-between h-16 md:h-[70px] gap-3">

        <!-- Logo công ty chỉnh gọn nhỏ -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
          <img
            id="brand-logo-img"
            src="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w400"
            alt="Logo CÔNG TY TNHH NGUYỄN AN THẠNH"
            referrerpolicy="no-referrer"
            onerror="handleLogoError(this)"
            class="h-9 sm:h-10 md:h-11 w-auto max-w-[115px] object-contain rounded"
          />
          <div class="leading-tight">
            <span class="block text-[13px] sm:text-sm font-extrabold tracking-tight text-[#0D3B66] whitespace-nowrap">
              NGUYỄN AN THẠNH
            </span>
            <span class="block text-[10px] font-medium text-[#C98A2B] tracking-wide whitespace-nowrap">
              XÂY DỰNG &amp; KIẾN TRÚC
            </span>
          </div>
        </a>

        <!-- Menu Desktop: viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng -->
        <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end flex-1 min-w-0">
          <ul class="flex items-center flex-nowrap gap-3 xl:gap-5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-slate-700">
            <li class="shrink-0">
              <a href="#trang-chu" class="whitespace-nowrap py-2 text-[#0D3B66] hover:text-[#C98A2B] transition">Trang chủ</a>
            </li>
            <li class="shrink-0">
              <a href="#gioi-thieu" class="whitespace-nowrap py-2 hover:text-[#C98A2B] transition">Giới thiệu</a>
            </li>
            <li class="relative nav-item-has-children shrink-0">
              <a href="#linh-vuc" class="whitespace-nowrap py-2 inline-flex items-center gap-1 hover:text-[#C98A2B] transition">
                <span>Lĩnh vực hoạt động</span>
                <i class="fa-solid fa-chevron-down text-[9px]"></i>
              </a>
              <ul class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
                <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-1.5 text-[12.5px] font-medium normal-case">
                  <li><a href="#san-pham" onclick="filterProducts('thiet-ke')" class="block px-4 py-2 hover:bg-slate-50 hover:text-[#0D3B66]">Thiết kế Kiến trúc – Nội thất</a></li>
                  <li><a href="#san-pham" onclick="filterProducts('phan-tho')" class="block px-4 py-2 hover:bg-slate-50 hover:text-[#0D3B66]">Thi công phần thô</a></li>
                  <li><a href="#san-pham" onclick="filterProducts('hoan-thien')" class="block px-4 py-2 hover:bg-slate-50 hover:text-[#0D3B66]">Thi công hoàn thiện</a></li>
                  <li><a href="#san-pham" onclick="filterProducts('tron-goi')" class="block px-4 py-2 hover:bg-slate-50 hover:text-[#0D3B66]">Thi công nội thất &amp; trọn gói</a></li>
                </div>
              </ul>
            </li>
            <li class="shrink-0">
              <a href="#san-pham" class="whitespace-nowrap py-2 hover:text-[#C98A2B] transition">Công trình thực tế</a>
            </li>
            <li class="shrink-0">
              <a href="#du-an-da-nang" class="whitespace-nowrap py-2 hover:text-[#C98A2B] transition">Dự án Đà Nẵng</a>
            </li>
            <li class="shrink-0">
              <a href="#bao-gia" class="whitespace-nowrap py-2 hover:text-[#C98A2B] transition">Báo giá</a>
            </li>
            <li class="shrink-0">
              <a href="#bai-viet" class="whitespace-nowrap py-2 hover:text-[#C98A2B] transition">Tin tức</a>
            </li>
            <li class="shrink-0">
              <a href="#lien-he" class="whitespace-nowrap py-2 hover:text-[#C98A2B] transition">Liên hệ</a>
            </li>
          </ul>
        </nav>

        <!-- Nút mở menu trên điện thoại & máy tính bảng -->
        <button
          id="mobile-menu-btn"
          type="button"
          aria-label="Mở menu điều hướng"
          aria-expanded="false"
          onclick="toggleMobileMenu()"
          class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-[#0D3B66] hover:bg-slate-50 transition shrink-0"
        >
          <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
        </button>
      </div>
    </div>

    <!-- Menu Mobile xổ xuống gọn gàng -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="nat-container py-3">
        <ul class="flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
          <li><a href="#trang-chu" onclick="closeMobileMenu()" class="block py-2.5 text-[#0D3B66]">Trang chủ</a></li>
          <li><a href="#gioi-thieu" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Giới thiệu công ty</a></li>
          <li><a href="#linh-vuc" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Lĩnh vực hoạt động</a></li>
          <li><a href="#san-pham" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Công trình thực tế &amp; Sản phẩm</a></li>
          <li><a href="#du-an-da-nang" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Dự án tại Đà Nẵng</a></li>
          <li><a href="#doi-tac" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Đối tác tiêu biểu</a></li>
          <li><a href="#bao-gia" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Yêu cầu báo giá</a></li>
          <li><a href="#bai-viet" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Tin tức xây dựng</a></li>
          <li><a href="#lien-he" onclick="closeMobileMenu()" class="block py-2.5 hover:text-[#C98A2B]">Liên hệ &amp; Bản đồ</a></li>
        </ul>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- =================================================================
         3. HAI ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Kích thước bằng nhau,
            ảnh và chữ nằm gọn trong khung, chữ cách xa viền ảnh, không bị cắt chữ)
         ================================================================= -->
    <section class="w-full bg-slate-900">
      <div class="banner-slider-viewport" id="hero-slider">
        <div class="banner-track" id="banner-track">

          <!-- BANNER 1 -->
          <div class="banner-slide">
            <!-- Ảnh nền thực tế tràn khung kín bên trong banner -->
            <img
              src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
              alt="Thi công xây dựng chuyên nghiệp - Công ty TNHH Nguyễn An Thạnh"
              referrerpolicy="no-referrer"
              onerror="handleDriveImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'Cong+Ty+TNHH+Nguyen+An+Thanh')"
              class="absolute inset-0 w-full h-full object-cover object-center"
            />
            <!-- Lớp phủ tối tạo độ tương phản chữ rõ ràng -->
            <div class="absolute inset-0 bg-gradient-to-r from-[#082644]/90 via-[#0D3B66]/78 to-[#082644]/55"></div>

            <!-- Nội dung chữ cách xa 4 viền ảnh banner (Safe padding trên cả mobile & desktop) -->
            <div class="relative z-10 w-full max-w-[1280px] mx-auto px-10 sm:px-16 md:px-20 lg:px-24 py-12 sm:py-16 md:py-20">
              <div class="max-w-2xl text-white">
                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-[#F3C677] mb-2.5">
                  CÔNG TY TNHH NGUYỄN AN THẠNH • ĐÀ NẴNG
                </p>
                <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-tight mb-3.5">
                  Thiết Kế Kiến Trúc &amp; Thi Công Xây Dựng Trọn Gói
                </h1>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-6">
                  An toàn – Chất lượng – Đúng tiến độ cho mọi công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại Đà Nẵng &amp; Miền Trung.
                </p>
                <div class="flex flex-wrap items-center gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-[#C98A2B] hover:bg-[#B0761E] text-white text-xs sm:text-sm font-semibold transition shadow">
                    Nhận Báo Giá Miễn Phí
                  </a>
                  <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                    Xem Dự Án Đà Nẵng
                  </a>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="banner-slide">
            <img
              src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
              alt="Dự án nhà phố biệt thự tại Đà Nẵng - Nguyễn An Thạnh"
              referrerpolicy="no-referrer"
              onerror="handleDriveImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'Du+An+Tieu+Bieu+Da+Nang')"
              class="absolute inset-0 w-full h-full object-cover object-center"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-[#082644]/90 via-[#0D3B66]/78 to-[#082644]/55"></div>

            <!-- Nội dung chữ cách xa viền đồng bộ hoàn toàn với Banner 1 -->
            <div class="relative z-10 w-full max-w-[1280px] mx-auto px-10 sm:px-16 md:px-20 lg:px-24 py-12 sm:py-16 md:py-20">
              <div class="max-w-2xl text-white">
                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-[#F3C677] mb-2.5">
                  UY TÍN TẠO DỰNG NIỀM TIN • NGUYENANTHANH.COM
                </p>
                <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-tight mb-3.5">
                  Thi Công Phần Thô &amp; Hoàn Thiện Chuẩn Kỹ Thuật
                </h2>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-6">
                  Đội ngũ kỹ sư giàu kinh nghiệm, giám sát trực tiếp tại công trình, minh bạch vật tư và bảo hành kết cấu dài hạn.
                </p>
                <div class="flex flex-wrap items-center gap-3">
                  <a href="#san-pham" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-[#C98A2B] hover:bg-[#B0761E] text-white text-xs sm:text-sm font-semibold transition shadow">
                    Xem Công Trình Thực Tế
                  </a>
                  <a href="tel:0907651779" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                    Hotline: 0907.651.779
                  </a>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển trái / phải nhỏ gọn đặt sát mép ngoài vùng chữ -->
        <button
          type="button"
          onclick="prevSlide()"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[#C98A2B] text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button
          type="button"
          onclick="nextSlide()"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[#C98A2B] text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo 2 banner -->
        <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
          <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Banner 1" class="w-7 h-2 rounded-full bg-[#C98A2B] transition-all"></button>
          <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Banner 2" class="w-2.5 h-2 rounded-full bg-white/55 hover:bg-white transition-all"></button>
        </div>
      </div>
    </section>

    <!-- =================================================================
         4. DỊCH VỤ TIÊU BIỂU (Cấu trúc 3 cột Flatsome giống mẫu tintruongthinh.com)
         ================================================================= -->
    <section id="linh-vuc" class="py-12 md:py-16 bg-white">
      <div class="nat-container">
        <div class="text-center mb-9">
          <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66]">
            Dịch Vụ Tiêu Biểu
          </h2>
          <p class="text-slate-500 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            Giải pháp đồng bộ từ khâu tư vấn thiết kế đến thi công xây dựng hoàn thiện và bàn giao chìa khóa trao tay.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-5 lg:gap-6">
          <!-- Khối 1: Thiết kế -->
          <div class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w900"
                alt="Thiết kế kiến trúc và nội thất"
                referrerpolicy="no-referrer"
                onerror="handleDriveImgError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'Thiet+Ke+Kien+Truc')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-5 text-center">
              <h3 class="text-base sm:text-lg font-bold uppercase text-[#0D3B66] mb-2">Thiết Kế Kiến Trúc</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4">
                Tối ưu công năng sử dụng, thẩm mỹ hiện đại, hợp phong thủy cho nhà phố, biệt thự, căn hộ và văn phòng.
              </p>
              <a href="#san-pham" onclick="filterProducts('thiet-ke')" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[#C98A2B] hover:text-[#0D3B66] transition">
                <span>Xem chi tiết</span>
                <i class="fa-solid fa-arrow-right text-xs"></i>
              </a>
            </div>
          </div>

          <!-- Khối 2: Thi công xây dựng -->
          <div class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w900"
                alt="Thi công phần thô và trọn gói"
                referrerpolicy="no-referrer"
                onerror="handleDriveImgError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 'Thi+Cong+Xay+Dung')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-5 text-center">
              <h3 class="text-base sm:text-lg font-bold uppercase text-[#0D3B66] mb-2">Thi Công Xây Dựng</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4">
                Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chuẩn kỹ thuật, sử dụng vật liệu chính hãng.
              </p>
              <a href="#san-pham" onclick="filterProducts('phan-tho')" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[#C98A2B] hover:text-[#0D3B66] transition">
                <span>Xem chi tiết</span>
                <i class="fa-solid fa-arrow-right text-xs"></i>
              </a>
            </div>
          </div>

          <!-- Khối 3: Hoàn thiện & Nội thất -->
          <div class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w900"
                alt="Thi công hoàn thiện và nội thất"
                referrerpolicy="no-referrer"
                onerror="handleDriveImgError(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_', 'Thi+Cong+Noi+That')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-5 text-center">
              <h3 class="text-base sm:text-lg font-bold uppercase text-[#0D3B66] mb-2">Hoàn Thiện &amp; Nội Thất</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4">
                Thi công hoàn thiện công trình, lắp đặt điện nước M&amp;E và nội thất tinh tế, bàn giao đúng tiến độ cam kết.
              </p>
              <a href="#san-pham" onclick="filterProducts('hoan-thien')" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[#C98A2B] hover:text-[#0D3B66] transition">
                <span>Xem chi tiết</span>
                <i class="fa-solid fa-arrow-right text-xs"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================
         5. GIỚI THIỆU CÔNG TY TNHH NGUYỄN AN THẠNH
         ================================================================= -->
    <section id="gioi-thieu" class="py-12 md:py-16 bg-[#F5F7FA] border-y border-slate-200/80">
      <div class="nat-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <div class="lg:col-span-6">
            <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66] mb-5">
              CÔNG TY TNHH NGUYỄN AN THẠNH
            </h2>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-4">
              <strong>CÔNG TY TNHH NGUYỄN AN THẠNH</strong> là đơn vị chuyên Tư vấn Thiết kế – Thi công Xây dựng – Hoàn thiện công trình dân dụng và công nghiệp tại Thành phố Đà Nẵng và khu vực Miền Trung.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-6">
              Với phương châm đặt chất lượng và chữ <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do Nguyễn An Thạnh thực hiện đều tuân thủ nghiêm ngặt quy trình kỹ thuật, bảo đảm <strong>An toàn – Bền vững – Thẩm mỹ – Tiết kiệm chi phí</strong> cho chủ đầu tư.
            </p>

            <div class="grid grid-cols-3 gap-3 sm:gap-4 mb-6">
              <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-[#0D3B66]">100%</div>
                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Vật tư đúng chuẩn</div>
              </div>
              <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-[#C98A2B]">24/7</div>
                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Tư vấn kỹ thuật</div>
              </div>
              <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-[#0D3B66]">5 Năm</div>
                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Bảo hành kết cấu</div>
              </div>
            </div>

            <a href="#bao-gia" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-[#0D3B66] hover:bg-[#082644] text-white text-sm font-semibold transition">
              <span>Đăng ký tư vấn miễn phí</span>
              <i class="fa-solid fa-angle-right"></i>
            </a>
          </div>

          <div class="lg:col-span-6">
            <div class="grid grid-cols-2 gap-3 sm:gap-4">
              <div class="rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[4/3] bg-white">
                <img
                  src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800"
                  alt="Hình ảnh thi công thực tế Nguyễn An Thạnh 1"
                  referrerpolicy="no-referrer"
                  onerror="handleDriveImgError(this, '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO', 'Thi+Cong+Thuc+Te')"
                  class="w-full h-full object-cover"
                />
              </div>
              <div class="rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[4/3] bg-white">
                <img
                  src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800"
                  alt="Hình ảnh thi công thực tế Nguyễn An Thạnh 2"
                  referrerpolicy="no-referrer"
                  onerror="handleDriveImgError(this, '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t', 'Cong+Trinh+Da+Nang')"
                  class="w-full h-full object-cover"
                />
              </div>
              <div class="col-span-2 rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[16/8] bg-white">
                <img
                  src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w1000"
                  alt="Toàn cảnh thi công xây dựng Công ty TNHH Nguyễn An Thạnh"
                  referrerpolicy="no-referrer"
                  onerror="handleDriveImgError(this, '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_', 'Nguyen+An+Thanh+Construction')"
                  class="w-full h-full object-cover"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================
         6. THẾ MẠNH CỦA CHÚNG TÔI (6 Icon Boxes chuẩn Flatsome)
         ================================================================= -->
    <section class="py-12 md:py-16 bg-white">
      <div class="nat-container">
        <div class="text-center mb-9">
          <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66]">
            Thế Mạnh Của Chúng Tôi
          </h2>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/50 hover:bg-white hover:shadow-md transition flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-[#0D3B66] text-white flex items-center justify-center shrink-0">
              <i class="fa-solid fa-helmet-safety text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-bold text-[#0D3B66] mb-1">Đội ngũ kỹ sư chuyên nghiệp</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư, tổ đội thi công lành nghề giàu kinh nghiệm thực chiến.</p>
            </div>
          </div>

          <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/50 hover:bg-white hover:shadow-md transition flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-[#C98A2B] text-white flex items-center justify-center shrink-0">
              <i class="fa-solid fa-compass-drafting text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-bold text-[#0D3B66] mb-1">Giải pháp thiết kế hiện đại</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Cập nhật xu hướng kiến trúc mới, tối ưu ánh sáng tự nhiên, thông gió và công năng sử dụng.</p>
            </div>
          </div>

          <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/50 hover:bg-white hover:shadow-md transition flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-[#0D3B66] text-white flex items-center justify-center shrink-0">
              <i class="fa-solid fa-clipboard-check text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-bold text-[#0D3B66] mb-1">Giám sát tiến độ chuẩn xác</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Báo cáo tiến độ từng hạng mục rõ ràng, cam kết bàn giao công trình đúng thời hạn hợp đồng.</p>
            </div>
          </div>

          <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/50 hover:bg-white hover:shadow-md transition flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-[#C98A2B] text-white flex items-center justify-center shrink-0">
              <i class="fa-solid fa-shield-halved text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-bold text-[#0D3B66] mb-1">Bảo hành công trình lâu dài</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện minh bạch, hỗ trợ kỹ thuật nhanh chóng khi khách hàng cần.</p>
            </div>
          </div>

          <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/50 hover:bg-white hover:shadow-md transition flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-[#0D3B66] text-white flex items-center justify-center shrink-0">
              <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-bold text-[#0D3B66] mb-1">Chi phí minh bạch, hợp lý</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Dự toán bóc tách khối lượng chi tiết, không phát sinh chi phí bất hợp lý trong suốt quá trình thi công.</p>
            </div>
          </div>

          <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/50 hover:bg-white hover:shadow-md transition flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-[#C98A2B] text-white flex items-center justify-center shrink-0">
              <i class="fa-solid fa-headset text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-bold text-[#0D3B66] mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Tư vấn phương án xây dựng, dự trù kinh phí và thủ tục xin phép xây dựng hoàn toàn miễn phí.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================
         7. DANH MỤC SẢN PHẨM & CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ảnh Drive thực tế)
            - Danh mục máy tính viết liền 1 hàng chữ nhỏ gọn, không xuống dòng tên danh mục
            - Sản phẩm chia 2 cột trên điện thoại, tên không tràn viền hay thiếu chữ
            - KHÔNG để nhãn dán (badge/sticker) đè lên ảnh sản phẩm
         ================================================================= -->
    <section id="san-pham" class="py-12 md:py-16 bg-[#F5F7FA] border-t border-slate-200/80">
      <div class="nat-container">
        <div class="text-center mb-6">
          <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66]">
            Danh Mục Sản Phẩm &amp; Thi Công Thực Tế
          </h2>
          <p class="text-slate-500 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            Hình ảnh thi công thực tế tại công trường do đội ngũ CÔNG TY TNHH NGUYỄN AN THẠNH trực tiếp triển khai.
          </p>
        </div>

        <!-- Thanh danh mục nhỏ gọn, viết liền 1 hàng trên máy tính, tối ưu đẹp trên điện thoại -->
        <div class="mb-7 flex justify-center">
          <div id="product-tabs" class="flex flex-wrap md:flex-nowrap items-center justify-center gap-1.5 sm:gap-2 bg-white p-1.5 rounded-xl border border-slate-200 shadow-sm max-w-full">
            <button type="button" data-cat="all" onclick="filterProducts('all')" class="prod-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition bg-[#0D3B66] text-white">
              Tất cả hạng mục
            </button>
            <button type="button" data-cat="thiet-ke" onclick="filterProducts('thiet-ke')" class="prod-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-slate-100">
              Thiết kế kiến trúc
            </button>
            <button type="button" data-cat="phan-tho" onclick="filterProducts('phan-tho')" class="prod-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-slate-100">
              Thi công phần thô
            </button>
            <button type="button" data-cat="hoan-thien" onclick="filterProducts('hoan-thien')" class="prod-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-slate-100">
              Thi công hoàn thiện
            </button>
            <button type="button" data-cat="tron-goi" onclick="filterProducts('tron-goi')" class="prod-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-slate-100">
              Thi công trọn gói &amp; Nội thất
            </button>
          </div>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 3-4 cột máy tính -->
        <div id="products-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-3 sm:gap-5">
          <!-- Render tự động bằng JS từ 9 ảnh thực tế Google Drive -->
        </div>
      </div>
    </section>

    <!-- =================================================================
         8. DANH MỤC CÁC DỰ ÁN TẠI ĐÀ NẴNG (10 ảnh dự án Google Drive)
            - Danh mục gọn đẹp 1 hàng trên máy tính
            - Chia 2 cột trên điện thoại, tên dự án hiển thị đầy đủ
            - KHÔNG nhãn dán trên ảnh
         ================================================================= -->
    <section id="du-an-da-nang" class="py-12 md:py-16 bg-white border-t border-slate-200/80">
      <div class="nat-container">
        <div class="text-center mb-6">
          <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66]">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <p class="text-slate-500 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            Tuyển tập công trình Nhà phố, Biệt thự, Khách sạn – Căn hộ và Văn phòng đã triển khai tại Đà Nẵng.
          </p>
        </div>

        <!-- Danh mục lọc dự án Đà Nẵng 1 hàng gọn đẹp -->
        <div class="mb-7 flex justify-center">
          <div id="project-tabs" class="flex flex-wrap md:flex-nowrap items-center justify-center gap-1.5 sm:gap-2 bg-[#F5F7FA] p-1.5 rounded-xl border border-slate-200 max-w-full">
            <button type="button" data-pcat="all" onclick="filterProjects('all')" class="proj-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition bg-[#0D3B66] text-white">
              Tất cả dự án
            </button>
            <button type="button" data-pcat="nha-pho" onclick="filterProjects('nha-pho')" class="proj-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-white">
              Nhà phố
            </button>
            <button type="button" data-pcat="biet-thu" onclick="filterProjects('biet-thu')" class="proj-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-white">
              Biệt thự
            </button>
            <button type="button" data-pcat="can-ho" onclick="filterProjects('can-ho')" class="proj-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-white">
              Khách sạn – Căn hộ
            </button>
            <button type="button" data-pcat="van-phong" onclick="filterProjects('van-phong')" class="proj-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold transition text-slate-700 hover:bg-white">
              Văn phòng &amp; Dân dụng
            </button>
          </div>
        </div>

        <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 4-5 cột gọn gàng trên máy tính -->
        <div id="projects-grid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render tự động bằng JS từ 10 ảnh dự án Đà Nẵng -->
        </div>
      </div>
    </section>

    <!-- =================================================================
         9. DANH MỤC CÁC ĐỐI TÁC TIÊU BIỂU
         ================================================================= -->
    <section id="doi-tac" class="py-12 md:py-14 bg-[#F5F7FA] border-y border-slate-200/80">
      <div class="nat-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-heading text-xl sm:text-2xl font-extrabold uppercase text-[#0D3B66]">
            Đối Tác Vật Tư &amp; Đồng Hành
          </h2>
          <p class="text-slate-500 text-xs sm:text-sm mt-3">
            Cam kết sử dụng vật liệu xây dựng chính hãng từ các thương hiệu uy tín hàng đầu.
          </p>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">HÒA PHÁT</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">SÔNG GIANH</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Xi măng cao cấp</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">DULUX</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Sơn trang trí</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">JOTUN</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Sơn ngoại thất</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">CADIVI</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">TIỀN PHONG</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Ống cấp thoát nước</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">PANASONIC</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị điện</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-[#C98A2B] transition">
            <span class="text-sm font-extrabold tracking-tight text-[#0D3B66]">VIGLACERA</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Gạch &amp; Thiết bị</span>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================
         10. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
         ================================================================= -->
    <section id="bao-gia" class="py-12 md:py-16 bg-[#0D3B66] text-white">
      <div class="nat-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <!-- Thông tin cam kết báo giá -->
          <div class="lg:col-span-5">
            <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-white mb-5">
              Yêu Cầu Tư Vấn &amp; Báo Giá
            </h2>
            <p class="text-sm text-slate-200 leading-relaxed mb-6">
              Quý khách đang có nhu cầu thiết kế kiến trúc, thi công phần thô, hoàn thiện hay xây nhà trọn gói tại Đà Nẵng? Hãy để lại thông tin, kỹ sư của <strong>CÔNG TY TNHH NGUYỄN AN THẠNH</strong> sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết hoàn toàn miễn phí.
            </p>
            <div class="space-y-3 text-sm">
              <div class="flex items-center gap-3">
                <i class="fa-solid fa-check-circle text-[#C98A2B]"></i>
                <span>Khảo sát hiện trạng thực tế miễn phí tại Đà Nẵng</span>
              </div>
              <div class="flex items-center gap-3">
                <i class="fa-solid fa-check-circle text-[#C98A2B]"></i>
                <span>Bóc tách dự toán rõ ràng, minh bạch từng hạng mục</span>
              </div>
              <div class="flex items-center gap-3">
                <i class="fa-solid fa-check-circle text-[#C98A2B]"></i>
                <span>Hỗ trợ hồ sơ xin giấy phép xây dựng trọn gói</span>
              </div>
            </div>
          </div>

          <!-- Form nhập liệu chuẩn Flatsome Contact Form 7 -->
          <div class="lg:col-span-7">
            <form id="quote-form" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-4">
                <div>
                  <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                  <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#0D3B66] focus:ring-1 focus:ring-[#0D3B66]" />
                </div>
                <div>
                  <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại *</label>
                  <input id="q-phone" type="tel" required placeholder="VD: 0907.651.779" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#0D3B66] focus:ring-1 focus:ring-[#0D3B66]" />
                </div>
                <div>
                  <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                  <select id="q-type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-[#0D3B66]">
                    <option value="Nhà phố">Nhà phố</option>
                    <option value="Biệt thự">Biệt thự</option>
                    <option value="Khách sạn - Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê</option>
                    <option value="Văn phòng - Thương mại">Văn phòng – Thương mại</option>
                    <option value="Thi công phần thô">Thi công phần thô</option>
                    <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa nhà</option>
                  </select>
                </div>
                <div>
                  <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                  <select id="q-budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-[#0D3B66]">
                    <option value="Chưa xác định">Chưa xác định</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
              </div>

              <div class="mb-4">
                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1.5">Diện tích &amp; yêu cầu chi tiết</label>
                <textarea id="q-note" rows="3" placeholder="VD: Diện tích đất 5x20m, xây 3 tầng tại Hòa Khánh, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#0D3B66] focus:ring-1 focus:ring-[#0D3B66]"></textarea>
              </div>

              <!-- Thông báo kết quả gửi form (không dùng alert) -->
              <div id="quote-feedback" class="hidden mb-4 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>

              <button type="submit" class="w-full py-3 rounded-lg bg-[#C98A2B] hover:bg-[#B0761E] text-white font-bold text-sm uppercase tracking-wide transition shadow">
                Gửi Yêu Cầu Báo Giá Ngay
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================
         11. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm xây dựng)
         ================================================================= -->
    <section id="bai-viet" class="py-12 md:py-16 bg-white">
      <div class="nat-container">
        <div class="text-center mb-9">
          <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66]">
            Tin Tức &amp; Kinh Nghiệm Xây Dựng
          </h2>
          <p class="text-slate-500 text-xs sm:text-sm mt-3">
            Kiến thức hữu ích về thiết kế, báo giá và quy trình thi công xây dựng tại Đà Nẵng.
          </p>
        </div>

        <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
          <!-- Render bài viết bằng JS để hỗ trợ xem chi tiết ngay trong modal -->
        </div>
      </div>
    </section>

    <!-- =================================================================
         12. KẾT NỐI FACEBOOK & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
         ================================================================= -->
    <section id="lien-he" class="py-12 md:py-16 bg-[#F5F7FA] border-t border-slate-200/80">
      <div class="nat-container">
        <div class="text-center mb-9">
          <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold uppercase text-[#0D3B66]">
            Kết Nối Facebook &amp; Bản Đồ Chỉ Đường
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
          <!-- Khối Facebook trực tiếp ngoài trang chủ -->
          <div class="lg:col-span-5 flex flex-col">
            <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col h-full">
              <div class="bg-[#1877F2] px-5 py-3.5 text-white flex items-center justify-between">
                <div class="flex items-center gap-2.5">
                  <i class="fa-brands fa-facebook text-xl"></i>
                  <span class="font-bold text-sm">Kết Nối Facebook Chính Thức</span>
                </div>
                <span class="text-[11px] opacity-90">Đang hoạt động</span>
              </div>

              <!-- Ảnh bìa công trình + thông tin trang Facebook -->
              <div class="relative h-36 bg-slate-200 overflow-hidden">
                <img
                  src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w900"
                  alt="Facebook Công ty TNHH Nguyễn An Thạnh"
                  referrerpolicy="no-referrer"
                  onerror="handleDriveImgError(this, '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT', 'Facebook+Nguyen+An+Thanh')"
                  class="w-full h-full object-cover"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/65 via-black/20 to-transparent"></div>
              </div>

              <div class="p-5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="flex items-center gap-3.5 -mt-12 relative z-10 mb-3">
                    <div class="w-16 h-16 rounded-full bg-white p-1 shadow-md border border-slate-200 overflow-hidden shrink-0 flex items-center justify-center">
                      <img
                        src="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w200"
                        alt="Avatar Nguyễn An Thạnh"
                        referrerpolicy="no-referrer"
                        onerror="handleLogoError(this)"
                        class="w-full h-full object-contain rounded-full"
                      />
                    </div>
                    <div class="pt-5 min-w-0">
                      <h3 class="font-bold text-base text-slate-900 leading-snug">Nguyễn Ngọc Hùng – Nguyễn An Thạnh</h3>
                      <p class="text-xs text-slate-500">Thiết kế &amp; Thi công xây dựng tại Đà Nẵng</p>
                    </div>
                  </div>

                  <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4">
                    Theo dõi Facebook để cập nhật hình ảnh thực tế các công trình đang thi công mỗi ngày, chia sẻ kinh nghiệm xây nhà và nhắn tin tư vấn trực tiếp.
                  </p>

                  <div class="space-y-2 text-xs text-slate-600 mb-5 bg-slate-50 p-3.5 rounded-xl border border-slate-200/80">
                    <div class="flex items-start gap-2">
                      <i class="fa-solid fa-location-dot text-[#0D3B66] mt-0.5"></i>
                      <span>K138/H97/40/04 Hoàng Văn Thái, P. Hòa Khánh, TP. Đà Nẵng</span>
                    </div>
                    <div class="flex items-center gap-2">
                      <i class="fa-solid fa-phone text-[#0D3B66]"></i>
                      <a href="tel:0907651779" class="font-semibold text-[#0D3B66] hover:underline">0907.651.779</a>
                    </div>
                    <div class="flex items-center gap-2">
                      <i class="fa-solid fa-globe text-[#0D3B66]"></i>
                      <span>nguyenanthanh.com</span>
                    </div>
                  </div>
                </div>

                <div class="grid grid-cols-2 gap-2.5">
                  <a
                    href="https://www.facebook.com/ngochung.nguyen.9828?locale=vi_VN"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs sm:text-sm font-semibold transition"
                  >
                    <i class="fa-brands fa-facebook-f"></i>
                    <span>Xem Facebook</span>
                  </a>
                  <a
                    href="https://zalo.me/0907651779"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg bg-[#0068FF] hover:bg-[#0055D4] text-white text-xs sm:text-sm font-semibold transition"
                  >
                    <i class="fa-solid fa-comment-dots"></i>
                    <span>Nhắn Zalo</span>
                  </a>
                </div>
              </div>
            </div>
          </div>

          <!-- Khối Bản đồ Google Map ngoài trang chủ -->
          <div class="lg:col-span-7 flex flex-col">
            <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col h-full">
              <div class="px-5 py-3.5 bg-[#0D3B66] text-white flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 text-sm font-bold">
                  <i class="fa-solid fa-map-location-dot text-[#C98A2B]"></i>
                  <span>Bản Đồ Trụ Sở Công Ty Tại Đà Nẵng</span>
                </div>
                <a
                  href="https://www.google.com/maps/search/?api=1&query=K138/H97/40/04+Ho%C3%A0ng+V%C4%83n+Th%C3%A1i,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="text-xs font-semibold text-[#F3C677] hover:underline"
                >
                  Mở trên Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
                </a>
              </div>
              <div class="w-full flex-1 min-h-[320px] sm:min-h-[360px] bg-slate-100">
                <iframe
                  title="Bản đồ CÔNG TY TNHH NGUYỄN AN THẠNH - Hoàng Văn Thái, Hòa Khánh, Đà Nẵng"
                  src="https://maps.google.com/maps?q=Ho%C3%A0ng+V%C4%83n+Th%C3%A1i,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                  class="w-full h-full min-h-[320px] sm:min-h-[360px] border-0"
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                  allowfullscreen
                ></iframe>
              </div>
              <div class="px-5 py-3 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 flex flex-wrap items-center justify-between gap-2">
                <span><strong>Địa chỉ:</strong> K138/H97/40/04 Hoàng Văn Thái, Phường Hòa Khánh, Thành phố Đà Nẵng</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- =================================================================
       13. FOOTER CHUYÊN NGHIỆP PHONG CÁCH FLATSOME
       ================================================================= -->
  <footer class="bg-[#082644] text-slate-300 pt-12 pb-6">
    <div class="nat-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-9 border-b border-white/10">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-3 mb-4">
            <div class="bg-white rounded-lg p-1.5 inline-flex items-center justify-center">
              <img
                src="https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY=w240"
                alt="Logo CÔNG TY TNHH NGUYỄN AN THẠNH"
                referrerpolicy="no-referrer"
                onerror="handleLogoError(this)"
                class="h-9 w-auto max-w-[100px] object-contain"
              />
            </div>
            <div>
              <h3 class="text-white font-extrabold text-sm sm:text-base uppercase">CÔNG TY TNHH NGUYỄN AN THẠNH</h3>
              <p class="text-xs text-[#F3C677]">nguyenanthanh.com</p>
            </div>
          </div>
          <ul class="space-y-2.5 text-xs sm:text-sm text-slate-300">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-[#C98A2B] mt-1"></i>
              <span>Địa chỉ: K138/H97/40/04 Hoàng Văn Thái, Phường Hòa Khánh, Thành phố Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-[#C98A2B]"></i>
              <span>Hotline / Zalo: <a href="tel:0907651779" class="text-white font-semibold hover:text-[#F3C677]">0907.651.779</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-building-columns text-[#C98A2B]"></i>
              <span>Mã số thuế: 0402162515</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-[#C98A2B]"></i>
              <a href="https://www.facebook.com/ngochung.nguyen.9828?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="hover:text-white transition">
                Facebook: Nguyễn Ngọc Hùng (Nguyễn An Thạnh)
              </a>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h4 class="text-white font-bold uppercase text-sm mb-4 pb-2 border-b border-white/10 inline-block">
            Lĩnh Vực Hoạt Động
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham" onclick="filterProducts('thiet-ke')" class="hover:text-[#F3C677] transition">Thiết kế kiến trúc – nội thất</a></li>
            <li><a href="#san-pham" onclick="filterProducts('phan-tho')" class="hover:text-[#F3C677] transition">Thi công phần thô</a></li>
            <li><a href="#san-pham" onclick="filterProducts('hoan-thien')" class="hover:text-[#F3C677] transition">Thi công hoàn thiện</a></li>
            <li><a href="#san-pham" onclick="filterProducts('tron-goi')" class="hover:text-[#F3C677] transition">Thi công xây nhà trọn gói</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-[#F3C677] transition">Dự án tại Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Liên kết nhanh -->
        <div class="lg:col-span-4">
          <h4 class="text-white font-bold uppercase text-sm mb-4 pb-2 border-b border-white/10 inline-block">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm mb-4">
            <li><a href="#gioi-thieu" class="hover:text-[#F3C677] transition">Giới thiệu công ty</a></li>
            <li><a href="#bao-gia" class="hover:text-[#F3C677] transition">Đăng ký nhận báo giá miễn phí</a></li>
            <li><a href="#doi-tac" class="hover:text-[#F3C677] transition">Đối tác cung cấp vật tư</a></li>
            <li><a href="#bai-viet" class="hover:text-[#F3C677] transition">Tin tức &amp; kinh nghiệm xây nhà</a></li>
          </ul>
          <p class="text-xs text-slate-400">
            Thời gian làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30). Tư vấn Hotline &amp; Zalo 24/7.
          </p>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <p>Copyright &copy; 2026 <strong>CÔNG TY TNHH NGUYỄN AN THẠNH</strong> (nguyenanthanh.com). All rights reserved.</p>
        <p>Thiết kế &amp; Thi công Xây dựng Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- =================================================================
       14. CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
           (Tương thích mượt mà trên cả máy tính và điện thoại)
       ================================================================= -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook nổi -->
    <a
      href="https://www.facebook.com/ngochung.nguyen.9828?locale=vi_VN"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Liên hệ Facebook"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465CC] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <i class="fa-brands fa-facebook-f text-base sm:text-lg w-5 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo nổi -->
    <a
      href="https://zalo.me/0907651779"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo 0907.651.779"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <span class="font-extrabold text-xs sm:text-sm w-5 text-center leading-none">Z</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi có hiệu ứng nhấn mạnh -->
    <a
      href="tel:0907651779"
      aria-label="Gọi Hotline 0907.651.779"
      class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <i class="fa-solid fa-phone-volume text-base sm:text-lg w-5 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold tracking-wide">0907.651.779</span>
    </a>
  </div>

  <!-- =================================================================
       15. MODAL XEM CHI TIẾT HÌNH ẢNH / DỰ ÁN / BÀI VIẾT
       ================================================================= -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/75 p-4" onclick="closeDetailModal(event)">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl" onclick="event.stopPropagation()">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-bold text-[#0D3B66] pr-4">Chi tiết</h3>
        <button type="button" onclick="hideDetailModal()" aria-label="Đóng cửa sổ" class="w-8 h-8 rounded-full hover:bg-slate-100 flex items-center justify-center text-slate-600 shrink-0">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="p-5">
        <div id="modal-img-wrap" class="w-full rounded-xl overflow-hidden bg-slate-100 mb-4">
          <img id="modal-img" src="" alt="" referrerpolicy="no-referrer" class="w-full max-h-[420px] object-contain bg-slate-900/5 mx-auto" />
        </div>
        <p id="modal-meta" class="text-xs font-semibold text-[#C98A2B] mb-2"></p>
        <div id="modal-desc" class="text-sm text-slate-700 leading-relaxed space-y-2.5"></div>
        <div class="mt-5 pt-4 border-t border-slate-200 flex flex-wrap items-center justify-between gap-3">
          <span class="text-xs text-slate-500">Cần tư vấn hạng mục này? Gọi ngay <strong>0907.651.779</strong></span>
          <a href="#bao-gia" onclick="hideDetailModal()" class="inline-flex items-center gap-1.5 px-4 py-2 rounded-lg bg-[#0D3B66] hover:bg-[#082644] text-white text-xs font-semibold transition">
            Nhận báo giá
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- =================================================================
       JAVASCRIPT ĐIỀU KHIỂN SLIDER, DỮ LIỆU ẢNH GOOGLE DRIVE & TƯƠNG TÁC
       ================================================================= -->
  <script>
    /**
     * Xử lý fallback tự động cho Logo từ Google Drive
     * Thử lần lượt các biến thể ID (dấu gạch dưới, dấu gạch ngang, nối liền) trước khi dùng SVG fallback
     */
    const logoCandidates = [
      'https://drive.google.com/thumbnail?id=1bm609vf8SUuBIi5A5_1uu1jHUwK1eVQY&sz=w400',
      'https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A5-1uu1jHUwK1eVQY=w400',
      'https://drive.google.com/thumbnail?id=1bm609vf8SUuBIi5A5-1uu1jHUwK1eVQY&sz=w400',
      'https://lh3.googleusercontent.com/d/1bm609vf8SUuBIi5A51uu1jHUwK1eVQY=w400',
      'https://placehold.co/180x80/0D3B66/FFFFFF?text=NAT'
    ];

    function handleLogoError(img) {
      const step = parseInt(img.dataset.logoStep || '0', 10);
      if (step < logoCandidates.length) {
        img.dataset.logoStep = String(step + 1);
        img.src = logoCandidates[step];
      }
    }

    /**
     * Xử lý fallback tự động cho ảnh công trình / dự án Google Drive
     */
    function handleDriveImgError(img, fileId, fallbackLabel) {
      const step = parseInt(img.dataset.errStep || '0', 10);
      if (step === 0) {
        img.dataset.errStep = '1';
        img.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
      } else if (step === 1) {
        img.dataset.errStep = '2';
        img.src = `https://placehold.co/800x600/0D3B66/FFFFFF?text=${fallbackLabel}`;
      }
    }

    function getDriveImgUrl(fileId) {
      return `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
    }

    /* ================================================================
       DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (Đúng 9 link Google Drive)
       ================================================================ */
    const constructionProducts = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        category: 'phan-tho',
        catLabel: 'Thi công phần thô',
        title: 'Thi công móng băng & kết cấu khung bê tông cốt thép',
        desc: 'Hạng mục gia công lắp dựng cốt thép móng, đà kiềng và cột trụ đúng tiêu chuẩn thiết kế kết cấu, đảm bảo độ bền vững lâu dài cho công trình nhà ở dân dụng.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        category: 'thiet-ke',
        catLabel: 'Thiết kế kiến trúc',
        title: 'Thiết kế & thi công mặt tiền nhà phố hiện đại',
        desc: 'Giải pháp kiến trúc mặt tiền thông thoáng, cân đối hình khối hiện đại, tối ưu lấy sáng và chống nóng phù hợp khí hậu miền Trung – Đà Nẵng.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        category: 'phan-tho',
        catLabel: 'Thi công phần thô',
        title: 'Thi công đổ bê tông sàn tầng & dầm chịu lực',
        desc: 'Quy trình lắp dựng cốp pha, đan thép sàn hai lớp và đổ bê tông thương phẩm đúng mác kỹ thuật, bảo dưỡng giữ ẩm chuẩn quy định.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        category: 'hoan-thien',
        catLabel: 'Thi công hoàn thiện',
        title: 'Thi công hoàn thiện ốp lát & sơn nước ngoại thất',
        desc: 'Công tác tô trát tường phẳng chuẩn, chống thấm kỹ lưỡng, ốp lát gạch men và hoàn thiện sơn nước sắc nét từng góc cạnh.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        category: 'phan-tho',
        catLabel: 'Thi công phần thô',
        title: 'Thi công xây tường bao & phân chia không gian nội thất',
        desc: 'Xây tường gạch ống đúng kỹ thuật mạch vữa no đều, căng dây kiểm tra độ thẳng đứng giúp bề mặt tường bền chắc, hạn chế nứt chân chim.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        category: 'hoan-thien',
        catLabel: 'Thi công hoàn thiện',
        title: 'Thi công hệ thống điện nước âm tường M&E hoàn chỉnh',
        desc: 'Lắp đặt hệ thống ống cấp thoát nước và dây dẫn điện đi âm gọn gàng, kiểm tra áp lực đường ống và an toàn điện trước khi bàn giao.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        category: 'tron-goi',
        catLabel: 'Thi công trọn gói & Nội thất',
        title: 'Thi công xây nhà trọn gói chìa khóa trao tay',
        desc: 'Dịch vụ tổng thầu từ xin phép xây dựng, thiết kế, thi công phần thô đến hoàn thiện và lắp đặt thiết bị sẵn sàng dọn vào ở.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        category: 'tron-goi',
        catLabel: 'Thi công trọn gói & Nội thất',
        title: 'Thi công cải tạo & nâng tầng công trình nhà ở',
        desc: 'Khảo sát đánh giá kết cấu hiện hữu, gia cố móng cột và cải tạo nâng cấp không gian sống khang trang, tối ưu ngân sách.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        category: 'thiet-ke',
        catLabel: 'Thiết kế kiến trúc',
        title: 'Thi công hoàn thiện không gian nội thất & trần thạch cao',
        desc: 'Hoàn thiện trần thạch cao giật cấp, hệ đèn chiếu sáng và bố trí nội thất đồng bộ theo bản vẽ 3D, mang lại sự sang trọng và tiện nghi.'
      }
    ];

    /* ================================================================
       DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Đúng 10 link Google Drive)
       ================================================================ */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        category: 'nha-pho',
        catLabel: 'Nhà phố • Liên Chiểu, Đà Nẵng',
        title: 'Nhà phố hiện đại 3 tầng – Hòa Khánh, Liên Chiểu',
        desc: 'Công trình nhà phố kết hợp không gian sinh hoạt gia đình thoáng rộng, thi công trọn gói phần thô và hoàn thiện tại phường Hòa Khánh, TP. Đà Nẵng.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        category: 'biet-thu',
        catLabel: 'Biệt thự • Hòa Xuân, Đà Nẵng',
        title: 'Biệt thự phố 2 mặt tiền – Khu đô thị Hòa Xuân',
        desc: 'Thiết kế kiến trúc sang trọng với hệ ban công xanh mát, thi công kết cấu bền vững và hoàn thiện vật liệu cao cấp tại Cẩm Lệ, Đà Nẵng.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        category: 'can-ho',
        catLabel: 'Khách sạn – Căn hộ • Sơn Trà, Đà Nẵng',
        title: 'Căn hộ dịch vụ cho thuê cao cấp – Quận Sơn Trà',
        desc: 'Dự án căn hộ lưu trú tối ưu số lượng phòng khép kín, đầy đủ tiện nghi và hệ thống PCCC, cấp thoát nước đạt chuẩn.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        category: 'nha-pho',
        catLabel: 'Nhà phố • Hải Châu, Đà Nẵng',
        title: 'Nhà phố kết hợp kinh doanh – Trung tâm Hải Châu',
        desc: 'Thiết kế tầng trệt thông thoáng phục vụ kinh doanh, các tầng trên đảm bảo riêng tư, hiện đại và tối ưu ánh sáng tự nhiên.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        category: 'can-ho',
        catLabel: 'Khách sạn – Căn hộ • Ngũ Hành Sơn, Đà Nẵng',
        title: 'Khách sạn lưu trú ven biển – Khu vực Mỹ Khê',
        desc: 'Thi công phần thô và hoàn thiện ngoại thất chống ăn mòn muối biển, đảm bảo thẩm mỹ và tuổi thọ công trình cao.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        category: 'van-phong',
        catLabel: 'Văn phòng • Thanh Khê, Đà Nẵng',
        title: 'Tòa nhà văn phòng làm việc – Quận Thanh Khê',
        desc: 'Không gian làm việc chuyên nghiệp, hệ vách kính cường lực lấy sáng và hệ thống điều hòa, điện mạng đồng bộ.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        category: 'nha-pho',
        catLabel: 'Nhà phố • Liên Chiểu, Đà Nẵng',
        title: 'Nhà ở gia đình 2 tầng mái bằng – Hoàng Văn Thái',
        desc: 'Công trình nhà ở dân dụng tối ưu chi phí đầu tư, bố trí 3 phòng ngủ rộng rãi và sân trước thoáng mát.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        category: 'biet-thu',
        catLabel: 'Biệt thự • Hòa Vang, Đà Nẵng',
        title: 'Biệt thự sân vườn nghỉ dưỡng – Huyện Hòa Vang',
        desc: 'Sự kết hợp hài hòa giữa kiến trúc hiện đại và mảng xanh sân vườn, tạo không gian thư giãn lý tưởng cho gia đình.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        category: 'nha-pho',
        catLabel: 'Nhà phố • Cẩm Lệ, Đà Nẵng',
        title: 'Nhà phố 3 tầng phong cách tối giản – Cẩm Lệ',
        desc: 'Đường nét kiến trúc tinh gọn, vật liệu hoàn thiện trang nhã, bàn giao đúng tiến độ và làm hài lòng chủ đầu tư.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        category: 'van-phong',
        catLabel: 'Dân dụng & Thương mại • Đà Nẵng',
        title: 'Công trình nhà phố thương mại – Khu đô thị Tây Bắc',
        desc: 'Dự án thi công hoàn thiện trọn gói mặt bằng kinh doanh kết hợp nhà ở tại khu vực Tây Bắc TP. Đà Nẵng.'
      }
    ];

    /* ================================================================
       DỮ LIỆU CÁC BÀI VIẾT TRANG CHỦ
       ================================================================ */
    const articlesData = [
      {
        imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '15/11/2026',
        title: 'Báo giá thi công xây nhà trọn gói tại Đà Nẵng mới nhất',
        excerpt: 'Cập nhật đơn giá thiết kế, thi công phần thô và xây nhà trọn gói cùng cách tính diện tích xây dựng chuẩn xác.',
        content: 'Đơn giá thi công xây dựng tại Đà Nẵng phụ thuộc vào quy mô công trình, điều kiện thi công hẻm hay mặt tiền và gói vật tư hoàn thiện chủ đầu tư lựa chọn. CÔNG TY TNHH NGUYỄN AN THẠNH luôn khảo sát thực tế và lập bảng bóc tách dự toán chi tiết để khách hàng kiểm soát ngân sách hiệu quả ngay từ đầu.'
      },
      {
        imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        date: '08/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật',
        excerpt: 'Bảo dưỡng bê tông đúng cách trong 7 ngày đầu giúp kết cấu đạt cường độ tối đa và tránh nứt bề mặt.',
        content: 'Sau khi đổ bê tông từ 4–6 giờ, cần tiến hành che phủ giữ ẩm và tưới nước bảo dưỡng đều đặn trong ít nhất 7 ngày liên tiếp. Việc bảo dưỡng kỹ lưỡng đặc biệt quan trọng trong điều kiện nắng gió tại miền Trung nhằm đảm bảo cường độ chịu lực tối ưu cho móng, dầm và sàn.'
      },
      {
        imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        date: '29/10/2026',
        title: '05 lưu ý quan trọng trước khi khởi công xây nhà phố',
        excerpt: 'Chuẩn bị kỹ hồ sơ pháp lý, thiết kế kỹ thuật và lựa chọn nhà thầu uy tín giúp quá trình xây nhà suôn sẻ.',
        content: 'Trước khi khởi công, chủ đầu tư nên hoàn tất hồ sơ xin giấy phép xây dựng, chốt phương án mặt bằng công năng chi tiết, dự trù khoản kinh phí dự phòng khoảng 5–10% và ký hợp đồng thi công minh bạch chủng loại vật tư với nhà thầu có kinh nghiệm.'
      },
      {
        imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        date: '18/10/2026',
        title: 'Kinh nghiệm chống thấm hiệu quả cho nhà ở khu vực Đà Nẵng',
        excerpt: 'Giải pháp xử lý chống thấm sàn mái, nhà vệ sinh và tường ngoài bền bỉ qua nhiều mùa mưa bão.',
        content: 'Đà Nẵng có mùa mưa kéo dài với lượng mưa lớn, do đó công tác chống thấm sàn sân thượng, ban công, khu vực vệ sinh và tường giáp ranh cần được thi công nhiều lớp bằng vật liệu chuyên dụng và thử nước nghiệm thu 48 giờ trước khi ốp lát hoàn thiện.'
      }
    ];

    /* ================================================================
       RENDER DANH MỤC SẢN PHẨM & DỰ ÁN (Không nhãn dán, 2 cột trên mobile)
       ================================================================ */
    function renderProducts(category = 'all') {
      const grid = document.getElementById('products-grid');
      const items = category === 'all'
        ? constructionProducts
        : constructionProducts.filter(item => item.category === category);

      grid.innerHTML = items.map(item => `
        <article
          onclick="openItemModal('${item.id}', '${escapeQuote(item.title)}', '${escapeQuote(item.catLabel)}', '${escapeQuote(item.desc)}')"
          class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveImgUrl(item.id)}"
              alt="${escapeHtml(item.title)}"
              loading="lazy"
              referrerpolicy="no-referrer"
              onerror="handleDriveImgError(this, '${item.id}', 'Thi+Cong+Xay+Dung')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
            />
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-[#0D3B66] leading-snug break-words">
              ${escapeHtml(item.title)}
            </h3>
            <p class="text-[11px] sm:text-xs text-[#C98A2B] font-medium mt-1.5">
              ${escapeHtml(item.catLabel)}
            </p>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(category) {
      renderProducts(category);
      document.querySelectorAll('.prod-tab').forEach(btn => {
        const active = btn.dataset.cat === category;
        btn.classList.toggle('bg-[#0D3B66]', active);
        btn.classList.toggle('text-white', active);
        btn.classList.toggle('text-slate-700', !active);
        btn.classList.toggle('hover:bg-slate-100', !active);
      });
    }

    function renderProjects(category = 'all') {
      const grid = document.getElementById('projects-grid');
      const items = category === 'all'
        ? danangProjects
        : danangProjects.filter(item => item.category === category);

      grid.innerHTML = items.map(item => `
        <article
          onclick="openItemModal('${item.id}', '${escapeQuote(item.title)}', '${escapeQuote(item.catLabel)}', '${escapeQuote(item.desc)}')"
          class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveImgUrl(item.id)}"
              alt="${escapeHtml(item.title)}"
              loading="lazy"
              referrerpolicy="no-referrer"
              onerror="handleDriveImgError(this, '${item.id}', 'Du+An+Da+Nang')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-[#0D3B66] leading-snug break-words">
              ${escapeHtml(item.title)}
            </h3>
            <p class="text-[11px] text-slate-500 mt-1.5">
              ${escapeHtml(item.catLabel)}
            </p>
          </div>
        </article>
      `).join('');
    }

    function filterProjects(category) {
      renderProjects(category);
      document.querySelectorAll('.proj-tab').forEach(btn => {
        const active = btn.dataset.pcat === category;
        btn.classList.toggle('bg-[#0D3B66]', active);
        btn.classList.toggle('text-white', active);
        btn.classList.toggle('text-slate-700', !active);
        btn.classList.toggle('hover:bg-white', !active);
      });
    }

    function renderArticles() {
      const grid = document.getElementById('articles-grid');
      grid.innerHTML = articlesData.map(art => `
        <article
          onclick="openItemModal('${art.imgId}', '${escapeQuote(art.title)}', 'Tin tức xây dựng • ${art.date}', '${escapeQuote(art.content)}')"
          class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col"
        >
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveImgUrl(art.imgId)}"
              alt="${escapeHtml(art.title)}"
              loading="lazy"
              referrerpolicy="no-referrer"
              onerror="handleDriveImgError(this, '${art.imgId}', 'Tin+Tuc+Xay+Dung')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-400 mb-1.5">
                <i class="fa-regular fa-calendar mr-1"></i>${art.date}
              </div>
              <h3 class="text-sm font-bold text-[#0D3B66] group-hover:text-[#C98A2B] leading-snug mb-2 transition">
                ${escapeHtml(art.title)}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                ${escapeHtml(art.excerpt)}
              </p>
            </div>
            <span class="inline-flex items-center gap-1 text-xs font-semibold text-[#C98A2B] mt-3">
              Đọc tiếp <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </span>
          </div>
        </article>
      `).join('');
    }

    /* ================================================================
       SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
       ================================================================ */
    let currentSlide = 0;
    const totalSlides = 2;
    let slideTimer = null;

    function updateSlider() {
      const track = document.getElementById('banner-track');
      if (!track) return;
      track.style.transform = `translateX(-${currentSlide * 100}%)`;

      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById(`dot-${i}`);
        if (!dot) continue;
        if (i === currentSlide) {
          dot.className = 'w-7 h-2 rounded-full bg-[#C98A2B] transition-all';
        } else {
          dot.className = 'w-2.5 h-2 rounded-full bg-white/55 hover:bg-white transition-all';
        }
      }
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateSlider();
      resetSliderTimer();
    }

    function prevSlide() {
      currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      updateSlider();
      resetSliderTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSlider();
      resetSliderTimer();
    }

    function resetSliderTimer() {
      if (slideTimer) clearInterval(slideTimer);
      slideTimer = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSlider();
      }, 5500);
    }

    // Hỗ trợ vuốt trái/phải trên màn hình điện thoại cho Banner
    function initTouchSwipe() {
      const sliderEl = document.getElementById('hero-slider');
      if (!sliderEl) return;
      let startX = 0;
      sliderEl.addEventListener('touchstart', (e) => {
        startX = e.changedTouches[0].screenX;
      }, { passive: true });
      sliderEl.addEventListener('touchend', (e) => {
        const endX = e.changedTouches[0].screenX;
        if (startX - endX > 45) nextSlide();
        if (endX - startX > 45) prevSlide();
      }, { passive: true });
    }

    /* ================================================================
       MENU MOBILE & MODAL CHI TIẾT & FORM BÁO GIÁ
       ================================================================ */
    function toggleMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      const icon = document.getElementById('mobile-menu-icon');
      const btn = document.getElementById('mobile-menu-btn');
      const isHidden = menu.classList.contains('hidden');
      menu.classList.toggle('hidden', !isHidden);
      btn.setAttribute('aria-expanded', String(isHidden));
      icon.className = isHidden ? 'fa-solid fa-xmark text-lg' : 'fa-solid fa-bars text-lg';
    }

    function closeMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      const icon = document.getElementById('mobile-menu-icon');
      const btn = document.getElementById('mobile-menu-btn');
      menu.classList.add('hidden');
      btn.setAttribute('aria-expanded', 'false');
      icon.className = 'fa-solid fa-bars text-lg';
    }

    function openItemModal(imgId, title, meta, desc) {
      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-img');
      img.dataset.errStep = '0';
      img.src = getDriveImgUrl(imgId);
      img.alt = title;
      img.onerror = function() {
        handleDriveImgError(this, imgId, 'Nguyen+An+Thanh');
      };
      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-meta').textContent = meta;
      document.getElementById('modal-desc').textContent = desc;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function hideDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function closeDetailModal(e) {
      if (e.target.id === 'detail-modal') hideDetailModal();
    }

    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('q-name').value.trim();
      const phone = document.getElementById('q-phone').value.trim();
      const type = document.getElementById('q-type').value;
      const budget = document.getElementById('q-budget').value;
      const feedback = document.getElementById('quote-feedback');

      if (!name || !phone) {
        feedback.textContent = 'Vui lòng nhập đầy đủ họ tên và số điện thoại liên hệ.';
        feedback.className = 'mb-4 p-3 rounded-lg bg-red-50 border border-red-200 text-red-700 text-xs sm:text-sm font-medium';
        return;
      }

      feedback.innerHTML = `Cảm ơn <strong>${escapeHtml(name)}</strong>! CÔNG TY TNHH NGUYỄN AN THẠNH đã tiếp nhận yêu cầu báo giá hạng mục <strong>${escapeHtml(type)}</strong> (${escapeHtml(budget)}). Chúng tôi sẽ gọi lại số <strong>${escapeHtml(phone)}</strong> trong thời gian sớm nhất.`;
      feedback.className = 'mb-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium';
      document.getElementById('quote-form').reset();
    }

    function escapeHtml(str) {
      return String(str)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;')
        .replace(/'/g, '&#39;');
    }

    function escapeQuote(str) {
      return String(str).replace(/\\/g, '\\\\').replace(/'/g, "\\'");
    }

    // Khởi tạo toàn bộ giao diện khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderProducts('all');
      renderProjects('all');
      renderArticles();
      updateSlider();
      resetSliderTimer();
      initTouchSwipe();
    });
  </script>
</body>
</html>
