<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG - Chuyên Đá Nội Ngoại & Cắt Đá CNC Tự Động</title>
  <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG (xuannhung.com) - Chuyên cung cấp các loại đá nội - ngoại: Đá Marble, Đá Granite, Đá Nhân Tạo, Đá Nung Kết, Đá Onyx. Nhận cắt đá bằng máy tự động CNC tại Đà Nẵng.">
  
  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://xuannhung.com/">
  <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG - Kho Đá Nội Ngoại & Cắt Đá CNC">
  <meta property="og:description" content="Chuyên cung cấp các loại đá nội - ngoại cao cấp. Nhận cắt đá bằng máy tự động CNC tại Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng. Hotline: 0985.505.467">
  <meta property="og:image" content="https://placehold.co/1200x630/0f2942/d4af37?text=XUAN+NHUNG+STONE+%7C+xuannhung.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://placehold.co/1200x630/0f2942/d4af37?text=XUAN+NHUNG+STONE+%7C+xuannhung.com">

  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">
  
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              dark: '#0c2238',     /* Xanh Navy đậm theo màu Logo */
              primary: '#13385c',  /* Xanh Lam Đá chủ đạo */
              accent: '#c89b3c',   /* Vàng Hoàng Gia theo màu Logo */
              goldlight: '#e6c36a',
              bglight: '#f5f7fa'
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            heading: ['Montserrat', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Reset chống tràn viền & chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Khung chuẩn 1500px trên máy tính theo yêu cầu (Flatsome row container) */
    .container-1500 {
      width: 100%;
      max-width: 1500px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .container-1500 {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    /* Chuẩn Flatsome Section Title */
    .section-title-container {
      margin-bottom: 18px;
      border-bottom: 2px solid #e2e8f0;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 8px;
    }
    .section-title-main {
      background: linear-gradient(135deg, #0c2238 0%, #13385c 100%);
      color: #ffffff;
      padding: 9px 18px;
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 14px;
      text-transform: uppercase;
      letter-spacing: 0.4px;
      border-top-left-radius: 6px;
      border-top-right-radius: 6px;
      border-left: 4px solid #c89b3c;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      margin-bottom: -2px;
      white-space: nowrap;
    }

    /* Danh mục chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng tên danh mục */
    .cat-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 6px;
    }
    .cat-pill {
      white-space: nowrap !important;
      word-break: keep-all !important;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-size: 11.5px;
      font-weight: 600;
      line-height: 1.25;
      padding: 5px 10px;
      border-radius: 4px;
      border: 1px solid #cbd5e1;
      background-color: #ffffff;
      color: #0c2238;
      transition: all 0.2s ease;
      cursor: pointer;
      flex-shrink: 0;
      box-shadow: 0 1px 2px rgba(12, 34, 56, 0.04);
    }
    .cat-pill:hover, .cat-pill.active {
      background-color: #0c2238;
      color: #e6c36a;
      border-color: #c89b3c;
    }

    /* Thanh menu danh mục chính trên máy tính: chữ nhỏ gọn, nằm trên 1 hàng, không gãy dòng */
    .desktop-main-nav {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 2px;
    }
    .desktop-nav-link {
      white-space: nowrap !important;
      word-break: keep-all !important;
      font-size: 11.5px;
      font-weight: 600;
      padding: 7px 8px;
      border-radius: 4px;
      color: #ffffff;
      transition: all 0.2s ease;
      display: inline-flex;
      align-items: center;
      gap: 4px;
      flex-shrink: 0;
    }
    .desktop-nav-link:hover, .desktop-nav-link.active {
      background-color: rgba(200, 155, 60, 0.22);
      color: #e6c36a;
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị cắt mất chữ, không tràn ra ngoài */
    .product-title {
      font-size: 13.5px;
      font-weight: 700;
      color: #0c2238;
      line-height: 1.38;
      word-wrap: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      margin-bottom: 6px;
    }
    @media (max-width: 640px) {
      .product-title {
        font-size: 12.5px;
      }
      .section-title-main {
        font-size: 12.5px;
        padding: 7px 12px;
      }
    }

    /* Hiệu ứng nút liên hệ nổi bật */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 155, 60, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 155, 60, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 155, 60, 0); }
    }
    .float-btn-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-accent selection:text-white">

  <!-- ==================== TOP BAR (THÔNG TIN CÔNG TY - CHUẨN FLATSOME) ==================== -->
  <div class="bg-brand-dark text-slate-200 border-b border-slate-700/80 text-xs py-1.5">
    <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate">
        <span class="text-brand-goldlight font-semibold"><i class="fa-solid fa-gem mr-1"></i>xuannhung.com</span>
        <span class="hidden sm:inline text-slate-400">|</span>
        <span class="hidden sm:inline truncate">Chuyên cung cấp đá nội - ngoại & Nhận cắt đá bằng máy tự động CNC</span>
      </div>
      <div class="flex items-center gap-3 text-[11px] sm:text-xs">
        <span class="hidden md:inline text-slate-300">
          <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng
        </span>
        <a href="https://www.facebook.com/xuan.nhung.kho.a" target="_blank" rel="noopener noreferrer" class="hover:text-brand-goldlight transition-colors">
          <i class="fa-brands fa-facebook mr-1"></i>Fanpage Kho Đá Xuân Nhung
        </a>
      </div>
    </div>
  </div>

  <!-- ==================== HEADER (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
    <div class="container-1500 py-2.5 flex items-center justify-between gap-3">
      
      <!-- Logo thiết kế mới chuyên nghiệp, chỉnh gọn nhỏ lại -->
      <a href="#top" class="flex items-center gap-2.5 group shrink-0">
        <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-gradient-to-br from-brand-dark via-brand-primary to-slate-900 flex items-center justify-center border border-brand-accent/70 shadow-sm shrink-0">
          <!-- SVG Logo Xuân Nhung Stone gọn nhỏ sắc nét -->
          <svg class="w-7 h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
            <polygon points="32,4 58,18 58,46 32,60 6,46 6,18" stroke="#e6c36a" stroke-width="3" fill="#0c2238"/>
            <polygon points="32,11 51,21 51,43 32,53 13,43 13,21" stroke="#c89b3c" stroke-width="1.2" stroke-dasharray="3 2" fill="none"/>
            <path d="M20 23L32 39L44 23M20 41L32 25L44 41" stroke="#e6c36a" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
            <circle cx="32" cy="32" r="3" fill="#ffffff"/>
          </svg>
        </div>
        <div class="leading-tight">
          <div class="font-heading font-extrabold text-brand-dark text-xs sm:text-sm md:text-base tracking-tight">
            CÔNG TY TNHH TM DV XUÂN NHUNG
          </div>
          <div class="text-[10.5px] sm:text-xs font-semibold text-brand-accent flex items-center gap-1.5">
            <span>ĐÁ NỘI - NGOẠI & CẮT ĐÁ CNC</span>
            <span class="hidden sm:inline text-slate-400">•</span>
            <span class="hidden sm:inline text-brand-primary font-bold">xuannhung.com</span>
          </div>
        </div>
      </a>

      <!-- Ô tìm kiếm gọn gàng trên máy tính -->
      <div class="hidden lg:flex items-center flex-1 max-w-md mx-2">
        <div class="relative w-full">
          <input id="searchInput" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm đá Marble, Granite, Nung kết, Cắt CNC..." class="w-full pl-3.5 pr-9 py-1.5 text-xs rounded-md border border-slate-300 focus:outline-none focus:border-brand-primary bg-slate-50">
          <button type="button" aria-label="Tìm kiếm" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-slate-500 hover:text-brand-primary text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>

      <!-- Nút mở Menu danh mục trên điện thoại (Không để nút gọi ngay trên Header) -->
      <button type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-1.5 rounded-md bg-brand-dark text-brand-goldlight text-xs font-semibold border border-brand-accent/50">
        <i class="fa-solid fa-bars"></i>
        <span>Danh Mục</span>
      </button>
    </div>

    <!-- Thanh Menu Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy chữ -->
    <nav class="bg-brand-dark border-t border-brand-accent/30 hidden lg:block">
      <div class="container-1500 py-1">
        <div class="desktop-main-nav">
          <a href="#top" onclick="filterAllCategories('all')" class="desktop-nav-link active"><i class="fa-solid fa-house text-[11px]"></i>Trang Nhất</a>
          <a href="#sec-marble" onclick="scrollToSection('sec-marble')" class="desktop-nav-link">Đá Marble</a>
          <a href="#sec-granite" onclick="scrollToSection('sec-granite')" class="desktop-nav-link">Đá Granite</a>
          <a href="#sec-nhantao" onclick="scrollToSection('sec-nhantao')" class="desktop-nav-link">Đá Nhân Tạo</a>
          <a href="#sec-nungket" onclick="scrollToSection('sec-nungket')" class="desktop-nav-link">Gạch Đá Nung Kết</a>
          <a href="#sec-onyx" onclick="scrollToSection('sec-onyx')" class="desktop-nav-link">Đá Onyx Xuyên Sáng</a>
          <a href="#sec-cnc" onclick="scrollToSection('sec-cnc')" class="desktop-nav-link">Cắt Đá Máy Tự Động CNC</a>
          <a href="#sec-hangmuc" onclick="scrollToSection('sec-hangmuc')" class="desktop-nav-link">Hạng Mục Thi Công</a>
          <a href="#sec-congty" onclick="scrollToSection('sec-congty')" class="desktop-nav-link">Kho Đá & Nhà Xưởng</a>
          <a href="#sec-duan" onclick="scrollToSection('sec-duan')" class="desktop-nav-link">Dự Án Đà Nẵng</a>
          <a href="#sec-doitac" onclick="scrollToSection('sec-doitac')" class="desktop-nav-link">Đối Tác</a>
          <a href="#sec-tintuc" onclick="scrollToSection('sec-tintuc')" class="desktop-nav-link">Bài Viết</a>
          <a href="#sec-baogia" onclick="scrollToSection('sec-baogia')" class="desktop-nav-link">Báo Giá & Bản Đồ</a>
        </div>
      </div>
    </nav>

    <!-- Menu Danh Mục Trên Điện Thoại -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-3 py-3 shadow-inner">
      <div class="mb-2.5">
        <input type="text" oninput="filterProductsBySearch(this.value)" placeholder="Nhập tên mẫu đá cần tìm..." class="w-full px-3 py-1.5 text-xs rounded border border-slate-300 bg-slate-50">
      </div>
      <div class="grid grid-cols-2 sm:grid-cols-3 gap-1.5">
        <a href="#sec-marble" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-layer-group text-brand-accent mr-1.5"></i>Đá Marble</a>
        <a href="#sec-granite" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-cubes text-brand-accent mr-1.5"></i>Đá Granite</a>
        <a href="#sec-nhantao" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-gem text-brand-accent mr-1.5"></i>Đá Nhân Tạo</a>
        <a href="#sec-nungket" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-border-all text-brand-accent mr-1.5"></i>Đá Nung Kết</a>
        <a href="#sec-onyx" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-sun text-brand-accent mr-1.5"></i>Đá Onyx & Khác</a>
        <a href="#sec-cnc" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-gears text-brand-accent mr-1.5"></i>Cắt Đá CNC</a>
        <a href="#sec-hangmuc" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-compass-drafting text-brand-accent mr-1.5"></i>Hạng Mục Đá</a>
        <a href="#sec-congty" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-warehouse text-brand-accent mr-1.5"></i>Ảnh Công Ty</a>
        <a href="#sec-duan" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-building text-brand-accent mr-1.5"></i>Dự Án Đà Nẵng</a>
        <a href="#sec-baogia" onclick="toggleMobileMenu()" class="cat-pill justify-start"><i class="fa-solid fa-file-signature text-brand-accent mr-1.5"></i>Báo Giá & Map</a>
      </div>
    </div>
  </header>

  <!-- ==================== HERO BANNER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU, RIÊNG BIỆT PC & MOBILE) ==================== -->
  <section id="top" class="py-3 bg-white border-b border-slate-200">
    <div class="container-1500">
      <div class="relative rounded-xl overflow-hidden shadow-md border border-slate-200 bg-brand-dark">

        <!-- SLIDE 1 -->
        <div id="hero-slide-0" class="hero-slide block transition-opacity duration-500">
          <!-- Bản thiết kế Banner dành riêng cho Máy Tính (Chữ gọn, nằm trọn trong ảnh, kích thước 400px cố định) -->
          <div class="hidden md:flex relative w-full h-[390px] items-center overflow-hidden bg-gradient-to-r from-[#09192b] via-[#123152] to-[#0c2238]">
            <img src="https://drive.google.com/thumbnail?id=1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1&sz=w1200" 
                 onerror="handleDriveImageError(this, '1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1', 'KHO DA XUAN NHUNG')"
                 alt="Kho Đá Xuân Nhung" class="absolute right-0 top-0 w-1/2 h-full object-cover opacity-45 mix-blend-luminosity">
            <div class="absolute inset-0 bg-gradient-to-r from-[#081729] via-[#0c2238]/95 to-transparent"></div>
            
            <div class="relative z-10 w-full px-12 py-8 grid grid-cols-12 items-center gap-6">
              <div class="col-span-7 space-y-3">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded bg-brand-accent/20 border border-brand-accent/50 text-brand-goldlight text-xs font-semibold">
                  <span>WEBSITE CHÍNH THỨC: XUANNHUNG.COM</span>
                </div>
                <h1 class="font-heading font-extrabold text-white text-2xl lg:text-3xl leading-snug">
                  CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ <span class="text-brand-goldlight">XUÂN NHUNG</span>
                </h1>
                <p class="text-slate-200 text-sm lg:text-base font-medium leading-relaxed max-w-xl">
                  Chuyên cung cấp các loại <strong class="text-brand-goldlight">Đá Nội - Ngoại</strong> cao cấp: Đá Marble, Đá Granite, Đá Nhân Tạo, Gạch Đá Nung Kết, Đá Onyx Xuyên Sáng. Nguồn đá slab lớn có sẵn tại kho Đà Nẵng.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-4 text-xs text-slate-300">
                  <span><i class="fa-solid fa-phone-volume text-brand-goldlight mr-1.5"></i>Hotline/Zalo: <strong class="text-white">0985.505.467</strong></span>
                  <span><i class="fa-solid fa-location-dot text-brand-goldlight mr-1.5"></i>Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng</span>
                </div>
                <div class="pt-2 flex items-center gap-3">
                  <a href="#sec-marble" class="px-4 py-2 rounded bg-brand-accent hover:bg-brand-goldlight text-brand-dark font-bold text-xs uppercase tracking-wide transition">
                    Xem Kho Đá Thực Tế
                  </a>
                  <a href="#sec-baogia" class="px-4 py-2 rounded border border-brand-goldlight/60 text-brand-goldlight hover:bg-white/10 font-semibold text-xs transition">
                    Nhận Báo Giá Tại Kho
                  </a>
                </div>
              </div>
              <div class="col-span-5 grid grid-cols-2 gap-2.5">
                <img src="https://drive.google.com/thumbnail?id=1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8&sz=w600"
                     onerror="handleDriveImageError(this, '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8', 'DA MARBLE CAO CAP')"
                     alt="Đá Nội Ngoại Xuân Nhung" class="w-full h-36 object-cover rounded-lg border-2 border-brand-accent/60 shadow-lg">
                <img src="https://drive.google.com/thumbnail?id=1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb&sz=w600"
                     onerror="handleDriveImageError(this, '1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb', 'DA GRANITE TU NHIEN')"
                     alt="Đá Hoa Cương Xuân Nhung" class="w-full h-36 object-cover rounded-lg border-2 border-brand-accent/60 shadow-lg">
                <img src="https://drive.google.com/thumbnail?id=1S4vTgOECmc4VGxkIMDOHjP7trZQnlvuJ&sz=w600"
                     onerror="handleDriveImageError(this, '1S4vTgOECmc4VGxkIMDOHjP7trZQnlvuJ', 'KHO SLAB DA LON')"
                     alt="Kho Đá Xuân Nhung" class="col-span-2 w-full h-32 object-cover rounded-lg border-2 border-brand-accent/60 shadow-lg">
              </div>
            </div>
          </div>

          <!-- Bản thiết kế Banner dành riêng cho Điện Thoại (Thiết kế khác máy tính, chữ nhỏ gọn nằm hết trong khung 240px, không tràn viền) -->
          <div class="flex md:hidden relative w-full h-[240px] items-center justify-between px-4 py-3 bg-gradient-to-br from-[#081729] via-[#123254] to-[#0c2238] overflow-hidden">
            <div class="w-[62%] pr-2 space-y-1.5 z-10">
              <span class="inline-block px-2 py-0.5 rounded bg-brand-accent/25 border border-brand-accent/50 text-brand-goldlight text-[10px] font-bold">
                XUANNHUNG.COM
              </span>
              <h2 class="font-heading font-extrabold text-white text-[13px] leading-snug">
                CÔNG TY TNHH TM DV <span class="text-brand-goldlight">XUÂN NHUNG</span>
              </h2>
              <p class="text-slate-200 text-[11px] leading-tight">
                Chuyên cung cấp các loại <strong>Đá Nội - Ngoại</strong>: Marble, Granite, Nung Kết, Onyx.
              </p>
              <div class="text-[10.5px] text-brand-goldlight font-semibold pt-0.5">
                <i class="fa-solid fa-phone mr-1"></i>0985.505.467
              </div>
              <div class="pt-1">
                <a href="#sec-baogia" class="inline-block px-2.5 py-1 rounded bg-brand-accent text-brand-dark font-bold text-[10.5px]">
                  Yêu Cầu Báo Giá
                </a>
              </div>
            </div>
            <div class="w-[38%] h-full flex flex-col justify-center gap-1.5 z-10">
              <img src="https://drive.google.com/thumbnail?id=1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8&sz=w400"
                   onerror="handleDriveImageError(this, '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8', 'DA MARBLE')"
                   alt="Đá Nội Ngoại" class="w-full h-24 object-cover rounded border border-brand-accent/70">
              <img src="https://drive.google.com/thumbnail?id=1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1&sz=w400"
                   onerror="handleDriveImageError(this, '1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1', 'KHO DA')"
                   alt="Kho Đá Xuân Nhung" class="w-full h-20 object-cover rounded border border-brand-accent/70">
            </div>
          </div>
        </div>

        <!-- SLIDE 2 (KÍCH THƯỚC BẰNG HỆT SLIDE 1) -->
        <div id="hero-slide-1" class="hero-slide hidden transition-opacity duration-500">
          <!-- Bản thiết kế Banner Slide 2 dành riêng cho Máy Tính (390px) -->
          <div class="hidden md:flex relative w-full h-[390px] items-center overflow-hidden bg-gradient-to-r from-[#0c2238] via-[#163a5f] to-[#09192b]">
            <img src="https://drive.google.com/thumbnail?id=1VF5hSCendde9cU58uSTusKaAiTt6zeFd&sz=w1200" 
                 onerror="handleDriveImageError(this, '1VF5hSCendde9cU58uSTusKaAiTt6zeFd', 'MAY CAT DA TU DONG CNC')"
                 alt="Cắt đá bằng máy tự động CNC" class="absolute right-0 top-0 w-1/2 h-full object-cover opacity-45 mix-blend-luminosity">
            <div class="absolute inset-0 bg-gradient-to-r from-[#09192b] via-[#0c2238]/95 to-transparent"></div>
            
            <div class="relative z-10 w-full px-12 py-8 grid grid-cols-12 items-center gap-6">
              <div class="col-span-7 space-y-3">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded bg-brand-accent/20 border border-brand-accent/50 text-brand-goldlight text-xs font-semibold">
                  <span>CÔNG NGHỆ GIA CÔNG ĐÁ HIỆN ĐẠI</span>
                </div>
                <h2 class="font-heading font-extrabold text-white text-2xl lg:text-3xl leading-snug">
                  NHẬN CẮT ĐÁ BẰNG <span class="text-brand-goldlight">MÁY TỰ ĐỘNG CNC</span> CHÍNH XÁC CAO
                </h2>
                <p class="text-slate-200 text-sm lg:text-base font-medium leading-relaxed max-w-xl">
                  Gia công cắt đá tự động CNC theo bản vẽ: mặt bàn bếp, đảo bếp, cầu thang, tam cấp, lavabo, hoa văn sảnh biệt thự & khách sạn. Đường cắt sắc nét, tiến độ nhanh chóng.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-4 text-xs text-slate-300">
                  <span><i class="fa-solid fa-gears text-brand-goldlight mr-1.5"></i>Xưởng máy CNC tự động công suất lớn</span>
                  <span><i class="fa-solid fa-phone-volume text-brand-goldlight mr-1.5"></i>Liên hệ: <strong class="text-white">0985.505.467</strong></span>
                </div>
                <div class="pt-2 flex items-center gap-3">
                  <a href="#sec-cnc" class="px-4 py-2 rounded bg-brand-accent hover:bg-brand-goldlight text-brand-dark font-bold text-xs uppercase tracking-wide transition">
                    Dịch Vụ Cắt Đá CNC
                  </a>
                  <a href="#sec-congty" class="px-4 py-2 rounded border border-brand-goldlight/60 text-brand-goldlight hover:bg-white/10 font-semibold text-xs transition">
                    Hình Ảnh Xưởng & Máy CNC
                  </a>
                </div>
              </div>
              <div class="col-span-5 grid grid-cols-2 gap-2.5">
                <img src="https://drive.google.com/thumbnail?id=1VF5hSCendde9cU58uSTusKaAiTt6zeFd&sz=w600"
                     onerror="handleDriveImageError(this, '1VF5hSCendde9cU58uSTusKaAiTt6zeFd', 'MAY CAT CNC TU DONG')"
                     alt="Máy cắt đá CNC" class="w-full h-36 object-cover rounded-lg border-2 border-brand-accent/60 shadow-lg">
                <img src="https://drive.google.com/thumbnail?id=1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6&sz=w600"
                     onerror="handleDriveImageError(this, '1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6', 'GIA CONG DA CNC')"
                     alt="Xưởng gia công đá CNC" class="w-full h-36 object-cover rounded-lg border-2 border-brand-accent/60 shadow-lg">
                <img src="https://drive.google.com/thumbnail?id=1gtlB9c4YldD_u1e4SM9KWLxCRgQhXFEI&sz=w600"
                     onerror="handleDriveImageError(this, '1gtlB9c4YldD_u1e4SM9KWLxCRgQhXFEI', 'XUONG DA XUAN NHUNG')"
                     alt="Nhà xưởng Xuân Nhung" class="col-span-2 w-full h-32 object-cover rounded-lg border-2 border-brand-accent/60 shadow-lg">
              </div>
            </div>
          </div>

          <!-- Bản thiết kế Banner Slide 2 dành riêng cho Điện Thoại (240px bằng Slide 1, chữ nhỏ gọn không tràn viền) -->
          <div class="flex md:hidden relative w-full h-[240px] items-center justify-between px-4 py-3 bg-gradient-to-br from-[#0c2238] via-[#163a5f] to-[#081729] overflow-hidden">
            <div class="w-[62%] pr-2 space-y-1.5 z-10">
              <span class="inline-block px-2 py-0.5 rounded bg-brand-accent/25 border border-brand-accent/50 text-brand-goldlight text-[10px] font-bold">
                GIA CÔNG CNC TỰ ĐỘNG
              </span>
              <h2 class="font-heading font-extrabold text-white text-[13px] leading-snug">
                NHẬN CẮT ĐÁ BẰNG <span class="text-brand-goldlight">MÁY TỰ ĐỘNG CNC</span>
              </h2>
              <p class="text-slate-200 text-[11px] leading-tight">
                Cắt mặt bếp, cầu thang, lavabo, hoa văn đá tự động chính xác theo bản vẽ.
              </p>
              <div class="text-[10.5px] text-brand-goldlight font-semibold pt-0.5">
                <i class="fa-solid fa-location-dot mr-1"></i>Xã Xuân Phú, TP Đà Nẵng
              </div>
              <div class="pt-1">
                <a href="#sec-cnc" class="inline-block px-2.5 py-1 rounded bg-brand-accent text-brand-dark font-bold text-[10.5px]">
                  Xem Xưởng Cắt CNC
                </a>
              </div>
            </div>
            <div class="w-[38%] h-full flex flex-col justify-center gap-1.5 z-10">
              <img src="https://drive.google.com/thumbnail?id=1VF5hSCendde9cU58uSTusKaAiTt6zeFd&sz=w400"
                   onerror="handleDriveImageError(this, '1VF5hSCendde9cU58uSTusKaAiTt6zeFd', 'MAY CAT CNC')"
                   alt="Máy cắt đá CNC" class="w-full h-24 object-cover rounded border border-brand-accent/70">
              <img src="https://drive.google.com/thumbnail?id=1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6&sz=w400"
                   onerror="handleDriveImageError(this, '1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6', 'XUONG CNC')"
                   alt="Gia công CNC" class="w-full h-20 object-cover rounded border border-brand-accent/70">
            </div>
          </div>
        </div>

        <!-- Nút chuyển Slide & Chấm chỉ báo -->
        <button type="button" onclick="changeHeroSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/40 hover:bg-brand-accent text-white hover:text-brand-dark flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button type="button" onclick="changeHeroSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/40 hover:bg-brand-accent text-white hover:text-brand-dark flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" id="hero-dot-0" onclick="setHeroSlide(0)" aria-label="Slide 1" class="w-6 h-1.5 rounded-full bg-brand-accent transition-all"></button>
          <button type="button" id="hero-dot-1" onclick="setHeroSlide(1)" aria-label="Slide 2" class="w-2.5 h-1.5 rounded-full bg-white/50 transition-all"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- ==================== THANH DANH MỤC SẢN PHẨM TỔNG HỢP (TỐI ƯU TRÊN MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
  <section class="py-3 bg-slate-100 border-b border-slate-200">
    <div class="container-1500">
      <div class="bg-white rounded-lg p-3 border border-slate-200 shadow-sm">
        <div class="text-xs font-bold text-brand-dark uppercase mb-2 flex items-center gap-1.5">
          <i class="fa-solid fa-table-cells-large text-brand-accent"></i>
          <span>Danh Mục Sản Phẩm & Dịch Vụ Kho Đá Xuân Nhung:</span>
        </div>
        <!-- Danh mục viết liền trên 1 hàng chữ nhỏ gọn, hoặc xuống hàng 2 nguyên cụm, không bao giờ gãy tên danh mục -->
        <div class="cat-nav-list" id="globalCategoryBar">
          <button type="button" onclick="filterAllCategories('all')" data-cat="all" class="cat-pill active">Tất Cả Sản Phẩm</button>
          <button type="button" onclick="scrollToSection('sec-marble')" class="cat-pill">Đá Marble Tự Nhiên</button>
          <button type="button" onclick="scrollToSection('sec-granite')" class="cat-pill">Đá Granite (Hoa Cương)</button>
          <button type="button" onclick="scrollToSection('sec-nhantao')" class="cat-pill">Đá Nhân Tạo & Sứ Vân</button>
          <button type="button" onclick="scrollToSection('sec-nungket')" class="cat-pill">Gạch Đá Nung Kết</button>
          <button type="button" onclick="scrollToSection('sec-onyx')" class="cat-pill">Đá Onyx Xuyên Sáng</button>
          <button type="button" onclick="scrollToSection('sec-onyx')" class="cat-pill">Đá Quartzite</button>
          <button type="button" onclick="scrollToSection('sec-onyx')" class="cat-pill">Đá Bazan & Limestone</button>
          <button type="button" onclick="scrollToSection('sec-cnc')" class="cat-pill">Cắt Đá Máy Tự Động CNC</button>
          <button type="button" onclick="scrollToSection('sec-hangmuc')" class="cat-pill">Đá Làm Bàn Bếp</button>
          <button type="button" onclick="scrollToSection('sec-hangmuc')" class="cat-pill">Đá Làm Cầu Thang</button>
          <button type="button" onclick="scrollToSection('sec-hangmuc')" class="cat-pill">Đá Ốp Mặt Tiền</button>
          <button type="button" onclick="scrollToSection('sec-hangmuc')" class="cat-pill">Đá Làm Lavabo</button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 1. DANH MỤC ĐÁ MARBLE (GIỐNG WEB MẪU DAIGIAPHUC.COM) ==================== -->
  <!-- Lưu ý: Tuyệt đối KHÔNG để nhãn dán (sticker/badge) trên ảnh sản phẩm ở trang chủ, chia 2 cột trên điện thoại -->
  <section id="sec-marble" class="py-6">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-gem text-brand-goldlight"></i>
          <span>ĐÁ MARBLE</span>
        </h2>
        <div class="cat-nav-list" data-filter-group="marble">
          <button type="button" onclick="filterSectionProducts('marble', 'all', this)" class="cat-pill active">Tất cả</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Trắng', this)" class="cat-pill">Màu Trắng</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Kem', this)" class="cat-pill">Màu Kem</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Vàng', this)" class="cat-pill">Màu Vàng</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Nâu', this)" class="cat-pill">Màu Nâu</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Xám', this)" class="cat-pill">Màu Xám</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Đen', this)" class="cat-pill">Màu Đen</button>
          <button type="button" onclick="filterSectionProducts('marble', 'Màu Xanh', this)" class="cat-pill">Màu Xanh</button>
        </div>
      </div>

      <!-- Grid: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
      <div id="grid-marble" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4"></div>
    </div>
  </section>

  <!-- ==================== 2. DANH MỤC ĐÁ GRANITE (HOA CƯƠNG NỘI - NGOẠI) ==================== -->
  <section id="sec-granite" class="py-6 bg-white border-y border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-cubes text-brand-goldlight"></i>
          <span>ĐÁ GRANITE</span>
        </h2>
        <div class="cat-nav-list" data-filter-group="granite">
          <button type="button" onclick="filterSectionProducts('granite', 'all', this)" class="cat-pill active">Tất cả</button>
          <button type="button" onclick="filterSectionProducts('granite', 'Màu Trắng', this)" class="cat-pill">Màu Trắng</button>
          <button type="button" onclick="filterSectionProducts('granite', 'Màu Vàng', this)" class="cat-pill">Màu Vàng</button>
          <button type="button" onclick="filterSectionProducts('granite', 'Màu Đen', this)" class="cat-pill">Màu Đen</button>
          <button type="button" onclick="filterSectionProducts('granite', 'Màu Xanh', this)" class="cat-pill">Màu Xanh</button>
          <button type="button" onclick="filterSectionProducts('granite', 'Màu Đỏ', this)" class="cat-pill">Màu Đỏ</button>
          <button type="button" onclick="filterSectionProducts('granite', 'Màu Xám', this)" class="cat-pill">Màu Xám</button>
        </div>
      </div>

      <div id="grid-granite" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4"></div>
    </div>
  </section>

  <!-- ==================== 3. DANH MỤC ĐÁ NHÂN TẠO & GẠCH ĐÁ NUNG KẾT ==================== -->
  <section id="sec-nhantao" class="py-6">
    <div id="sec-nungket" class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-layer-group text-brand-goldlight"></i>
          <span>ĐÁ NHÂN TẠO & ĐÁ NUNG KẾT</span>
        </h2>
        <div class="cat-nav-list" data-filter-group="nhantao">
          <button type="button" onclick="filterSectionProducts('nhantao', 'all', this)" class="cat-pill active">Tất cả</button>
          <button type="button" onclick="filterSectionProducts('nhantao', 'Đá Nung Kết', this)" class="cat-pill">Gạch Đá Nung Kết</button>
          <button type="button" onclick="filterSectionProducts('nhantao', 'Đá Sứ Vân', this)" class="cat-pill">Đá Sứ Vân</button>
          <button type="button" onclick="filterSectionProducts('nhantao', 'Đá Quartz', this)" class="cat-pill">Đá Nhân Tạo Quartz</button>
          <button type="button" onclick="filterSectionProducts('nhantao', 'Màu Trắng', this)" class="cat-pill">Màu Trắng</button>
          <button type="button" onclick="filterSectionProducts('nhantao', 'Màu Vàng', this)" class="cat-pill">Màu Vàng</button>
          <button type="button" onclick="filterSectionProducts('nhantao', 'Màu Xanh', this)" class="cat-pill">Màu Xanh</button>
        </div>
      </div>

      <div id="grid-nhantao" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4"></div>
    </div>
  </section>

  <!-- ==================== 4. DANH MỤC ĐÁ KHÁC & GIA CÔNG CẮT ĐÁ MÁY TỰ ĐỘNG CNC ==================== -->
  <section id="sec-onyx" class="py-6 bg-white border-y border-slate-200">
    <div id="sec-cnc" class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-gears text-brand-goldlight"></i>
          <span>ĐÁ KHÁC & CẮT ĐÁ MÁY TỰ ĐỘNG CNC</span>
        </h2>
        <div class="cat-nav-list" data-filter-group="other">
          <button type="button" onclick="filterSectionProducts('other', 'all', this)" class="cat-pill active">Tất cả</button>
          <button type="button" onclick="filterSectionProducts('other', 'Cắt Đá CNC', this)" class="cat-pill">Cắt Đá Máy Tự Động CNC</button>
          <button type="button" onclick="filterSectionProducts('other', 'Đá Onyx Xuyên Sáng', this)" class="cat-pill">Đá Onyx Xuyên Sáng</button>
          <button type="button" onclick="filterSectionProducts('other', 'Đá Quartzite', this)" class="cat-pill">Đá Quartzite</button>
          <button type="button" onclick="filterSectionProducts('other', 'Đá Bazan', this)" class="cat-pill">Đá Bazan & Limestone</button>
        </div>
      </div>

      <div id="grid-other" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4"></div>
    </div>
  </section>

  <!-- ==================== 5. ĐA DẠNG SỰ LỰA CHỌN (HẠNG MỤC ỨNG DỤNG GIỐNG WEB MẪU) ==================== -->
  <section id="sec-hangmuc" class="py-6">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-compass-drafting text-brand-goldlight"></i>
          <span>ĐA DẠNG SỰ LỰA CHỌN - HẠNG MỤC THI CÔNG</span>
        </h2>
        <div class="cat-nav-list">
          <span class="cat-pill">Đá Làm Bàn Bếp</span>
          <span class="cat-pill">Đá Làm Cầu Thang</span>
          <span class="cat-pill">Đá Ốp Mặt Tiền</span>
          <span class="cat-pill">Đá Lát Nền</span>
          <span class="cat-pill">Đá Làm Tam Cấp</span>
          <span class="cat-pill">Đá Làm Lavabo</span>
        </div>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
          <img src="https://drive.google.com/thumbnail?id=1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8&sz=w500"
               onerror="handleDriveImageError(this, '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8', 'DA LAM BAN BEP')"
               alt="Đá làm bàn bếp" class="w-full h-32 object-cover">
          <div class="p-2.5 text-center">
            <h3 class="product-title text-xs uppercase mb-1">ĐÁ LÀM BÀN BẾP</h3>
            <p class="text-[11px] text-slate-600">Cắt CNC bo cạnh, khoét chậu bếp chuẩn xác</p>
          </div>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
          <img src="https://drive.google.com/thumbnail?id=1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb&sz=w500"
               onerror="handleDriveImageError(this, '1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb', 'DA LAM CAU THANG')"
               alt="Đá làm cầu thang" class="w-full h-32 object-cover">
          <div class="p-2.5 text-center">
            <h3 class="product-title text-xs uppercase mb-1">ĐÁ LÀM CẦU THANG</h3>
            <p class="text-[11px] text-slate-600">Đá Granite & Marble độ bền vĩnh cửu</p>
          </div>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
          <img src="https://drive.google.com/thumbnail?id=1JVJXQg2jxFs5euhF1u4uliLWAdglUpBJ&sz=w500"
               onerror="handleDriveImageError(this, '1JVJXQg2jxFs5euhF1u4uliLWAdglUpBJ', 'DA OP MAT TIEN')"
               alt="Đá ốp mặt tiền" class="w-full h-32 object-cover">
          <div class="p-2.5 text-center">
            <h3 class="product-title text-xs uppercase mb-1">ĐÁ ỐP MẶT TIỀN</h3>
            <p class="text-[11px] text-slate-600">Chống thấm, bền màu trước nắng mưa</p>
          </div>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
          <img src="https://drive.google.com/thumbnail?id=1ARY5qwlmpgmWzydfjdiJTPX7-naaYqYq&sz=w500"
               onerror="handleDriveImageError(this, '1ARY5qwlmpgmWzydfjdiJTPX7-naaYqYq', 'DA LAT NEN')"
               alt="Đá lát nền" class="w-full h-32 object-cover">
          <div class="p-2.5 text-center">
            <h3 class="product-title text-xs uppercase mb-1">ĐÁ LÁT NỀN</h3>
            <p class="text-[11px] text-slate-600">Khổ slab lớn, hoa văn CNC sảnh biệt thự</p>
          </div>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
          <img src="https://drive.google.com/thumbnail?id=1wPp6NETrV8JE09oaf7UUO3BZL6tOHBO5&sz=w500"
               onerror="handleDriveImageError(this, '1wPp6NETrV8JE09oaf7UUO3BZL6tOHBO5', 'DA LAM TAM CAP')"
               alt="Đá làm tam cấp" class="w-full h-32 object-cover">
          <div class="p-2.5 text-center">
            <h3 class="product-title text-xs uppercase mb-1">ĐÁ LÀM TAM CẤP</h3>
            <p class="text-[11px] text-slate-600">Chịu lực cao, chống trơn trượt hiệu quả</p>
          </div>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
          <img src="https://drive.google.com/thumbnail?id=1vL_BADqK9VUKKjIEDG7-5Z44ayXxxJnu&sz=w500"
               onerror="handleDriveImageError(this, '1vL_BADqK9VUKKjIEDG7-5Z44ayXxxJnu', 'DA LAM LAVABO')"
               alt="Đá làm Lavabo" class="w-full h-32 object-cover">
          <div class="p-2.5 text-center">
            <h3 class="product-title text-xs uppercase mb-1">ĐÁ LÀM LAVABO</h3>
            <p class="text-[11px] text-slate-600">Chậu rửa đá nguyên khối & bàn lavabo CNC</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 6. GIỚI THIỆU & 7 HÌNH ẢNH THỰC TẾ CÔNG TY, KHO ĐÁ, MÁY CNC ==================== -->
  <section id="sec-congty" class="py-6 bg-white border-y border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-warehouse text-brand-goldlight"></i>
          <span>HÌNH ẢNH THỰC TẾ CÔNG TY, KHO ĐÁ & MÁY CẮT CNC XUÂN NHUNG</span>
        </h2>
        <div class="text-xs font-semibold text-brand-primary">
          <i class="fa-solid fa-check-circle text-brand-accent mr-1"></i>Chuyên đá nội - ngoại & Cắt đá bằng máy tự động CNC
        </div>
      </div>

      <!-- Khối giới thiệu ngắn chuẩn mẫu Đại Gia Phúc -->
      <div class="bg-slate-50 rounded-lg p-4 border border-slate-200 mb-4 grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
        <div class="lg:col-span-5 space-y-2">
          <h3 class="font-heading font-bold text-brand-dark text-base sm:text-lg">
            CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG
          </h3>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
            Tọa lạc tại <strong>Thửa đất số 213, tờ bản đồ số 1, Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng</strong>, Công ty TNHH Thương Mại Dịch Vụ Xuân Nhung là tổng kho chuyên cung cấp sỉ và lẻ các dòng đá tự nhiên & nhân tạo nội - ngoại nhập khẩu (Granite, Marble, Nung kết, Onyx, Quartzite).
          </p>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
            Đặc biệt, xưởng được đầu tư hệ thống <strong>máy cắt đá tự động CNC công nghệ mới</strong>, nhận gia công cắt quy cách, bo cạnh, phào chỉ, hoa văn CNC cho các đại lý, thợ đá, nhà thầu xây dựng và chủ đầu tư tại Đà Nẵng – Quảng Nam và khu vực miền Trung.
          </p>
          <div class="pt-1 flex flex-wrap gap-2">
            <a href="tel:0985505467" class="px-3.5 py-2 rounded bg-brand-dark text-brand-goldlight font-bold text-xs inline-flex items-center gap-1.5">
              <i class="fa-solid fa-phone"></i>Liên hệ: 0985.505.467
            </a>
            <a href="https://share.google/SSyPNnbBgEuDFBLND" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded border border-brand-primary text-brand-primary hover:bg-brand-primary hover:text-white font-semibold text-xs inline-flex items-center gap-1.5 transition">
              <i class="fa-solid fa-map-location-dot"></i>Chỉ Đường Tới Kho Đá
            </a>
          </div>
        </div>

        <!-- 7 Ảnh thực tế công ty từ 7 link Google Drive được cung cấp -->
        <div class="lg:col-span-7 grid grid-cols-2 sm:grid-cols-4 gap-2.5" id="companyGalleryGrid">
          <!-- Render bằng JS từ đúng 7 ID Google Drive của công ty -->
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 7. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ ==================== -->
  <section id="sec-duan" class="py-6">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-building-columns text-brand-goldlight"></i>
          <span>DỰ ÁN CUNG CẤP & THI CÔNG ĐÁ TẠI ĐÀ NẴNG</span>
        </h2>
        <div class="cat-nav-list" data-filter-group="duan">
          <button type="button" onclick="filterProjects('all', this)" class="cat-pill active">Tất Cả Dự Án</button>
          <button type="button" onclick="filterProjects('Biệt Thự Đà Nẵng', this)" class="cat-pill">Biệt Thự Đà Nẵng</button>
          <button type="button" onclick="filterProjects('Khách Sạn & Resort', this)" class="cat-pill">Khách Sạn & Resort</button>
          <button type="button" onclick="filterProjects('Nhà Phố & Khu Đô Thị', this)" class="cat-pill">Nhà Phố & Khu Đô Thị</button>
          <button type="button" onclick="filterProjects('Gia Công Cắt Đá CNC', this)" class="cat-pill">Gia Công Cắt Đá CNC</button>
        </div>
      </div>

      <div id="grid-duan" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4"></div>
    </div>
  </section>

  <!-- ==================== 8. DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ ==================== -->
  <section id="sec-tintuc" class="py-6 bg-white border-y border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-newspaper text-brand-goldlight"></i>
          <span>DANH MỤC BÀI VIẾT & KINH NGHIỆM CHỌN ĐÁ</span>
        </h2>
        <div class="cat-nav-list" data-filter-group="news">
          <button type="button" onclick="filterNews('all', this)" class="cat-pill active">Tất Cả Bài Viết</button>
          <button type="button" onclick="filterNews('Vật Liệu Đá', this)" class="cat-pill">Vật Liệu Đá</button>
          <button type="button" onclick="filterNews('Công Nghệ Cắt CNC', this)" class="cat-pill">Công Nghệ Cắt CNC</button>
          <button type="button" onclick="filterNews('Ứng Dụng Thi Công', this)" class="cat-pill">Ứng Dụng Thi Công</button>
          <button type="button" onclick="filterNews('Phong Thủy Chọn Đá', this)" class="cat-pill">Phong Thủy Chọn Đá</button>
        </div>
      </div>

      <div id="grid-news" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4"></div>
    </div>
  </section>

  <!-- ==================== 9. FORM YÊU CẦU BÁO GIÁ + FANPAGE FACEBOOK + GOOGLE MAPS NGOÀI TRANG CHỦ ==================== -->
  <section id="sec-baogia" class="py-6">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-headset text-brand-goldlight"></i>
          <span>YÊU CẦU BÁO GIÁ • FANPAGE FACEBOOK • BẢN ĐỒ KHO ĐÁ XUÂN NHUNG</span>
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
        
        <!-- Cột 1: Form Yêu Cầu Và Báo Giá Trang Chủ (4 cột) -->
        <div class="lg:col-span-4 bg-white rounded-lg border border-slate-200 shadow-sm p-4">
          <div class="border-b border-slate-200 pb-2.5 mb-3">
            <h3 class="font-heading font-bold text-brand-dark text-sm uppercase flex items-center gap-2">
              <i class="fa-solid fa-file-invoice-dollar text-brand-accent"></i>
              <span>ĐĂNG KÝ TƯ VẤN & NHẬN BÁO GIÁ SỈ/LẺ</span>
            </h3>
            <p class="text-xs text-slate-600 mt-1">
              Gửi thông tin kích thước hoặc loại đá, phòng kinh doanh Xuân Nhung sẽ báo giá ngay qua điện thoại/Zalo.
            </p>
          </div>

          <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-2.5 text-xs">
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Họ và tên khách hàng / Đơn vị *</label>
              <input type="text" id="qName" required placeholder="Nhập họ và tên của bạn..." class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand-primary">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
              <input type="tel" id="qPhone" required placeholder="Ví dụ: 0985.505.467" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand-primary">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Chủ đề / Hạng mục quan tâm</label>
              <select id="qCategory" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand-primary bg-white">
                <option value="Mua Đá Marble / Granite nguyên tấm">Mua Đá Marble / Granite Nội - Ngoại</option>
                <option value="Gia công cắt đá bằng máy tự động CNC">Đặt Cắt Đá Bằng Máy Tự Động CNC</option>
                <option value="Đá Nung Kết / Đá Nhân Tạo / Onyx">Đá Nung Kết / Đá Nhân Tạo / Onyx</option>
                <option value="Thi công Đá Bàn Bếp / Cầu Thang / Mặt Tiền">Thi công Bàn Bếp, Cầu Thang, Mặt Tiền</option>
                <option value="Hợp tác Đại lý / Nhà thầu tại Đà Nẵng">Hợp tác Đại lý / Nhà thầu tại Đà Nẵng</option>
              </select>
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Nội dung yêu cầu (Kích thước, số lượng, mẫu đá)</label>
              <textarea id="qNote" rows="3" placeholder="Nhập tên đá hoặc quy cách cần cắt CNC..." class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand-primary"></textarea>
            </div>
            <button type="submit" class="w-full py-2.5 rounded bg-brand-dark hover:bg-brand-primary text-brand-goldlight font-bold uppercase tracking-wide transition flex items-center justify-center gap-2">
              <i class="fa-solid fa-paper-plane"></i>
              <span>Gửi Yêu Cầu Báo Giá Ngay</span>
            </button>
          </form>

          <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs">
            <div class="font-bold mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá!</div>
            <p id="quoteSuccessText"></p>
          </div>
        </div>

        <!-- Cột 2: Đưa Fanpage Facebook Ra Ngoài Trang Chủ (4 cột) -->
        <div class="lg:col-span-4 bg-white rounded-lg border border-slate-200 shadow-sm p-4 flex flex-col justify-between">
          <div>
            <div class="border-b border-slate-200 pb-2.5 mb-3">
              <h3 class="font-heading font-bold text-brand-dark text-sm uppercase flex items-center gap-2">
                <i class="fa-brands fa-facebook text-[#1877F2]"></i>
                <span>FANPAGE FACEBOOK KHO ĐÁ XUÂN NHUNG</span>
              </h3>
              <p class="text-xs text-slate-600 mt-1">
                Kết nối trực tiếp qua trang Facebook chính thức để xem lô đá mới về kho mỗi ngày.
              </p>
            </div>

            <!-- Khung Fanpage trực quan + Iframe Plugin Facebook -->
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
              <div class="relative h-28 bg-gradient-to-r from-brand-dark to-brand-primary p-3 flex items-end">
                <img src="https://drive.google.com/thumbnail?id=1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1&sz=w600"
                     onerror="handleDriveImageError(this, '1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1', 'FANPAGE XUAN NHUNG')"
                     alt="Bìa Fanpage Xuân Nhung" class="absolute inset-0 w-full h-full object-cover opacity-40">
                <div class="relative z-10 flex items-center gap-3">
                  <div class="w-12 h-12 rounded-lg bg-brand-dark border-2 border-brand-goldlight flex items-center justify-center text-brand-goldlight font-bold text-base shrink-0 shadow">
                    XN
                  </div>
                  <div class="text-white">
                    <a href="https://www.facebook.com/xuan.nhung.kho.a" target="_blank" rel="noopener noreferrer" class="font-bold text-sm hover:underline flex items-center gap-1">
                      <span>Kho Đá Xuân Nhung</span>
                      <i class="fa-solid fa-circle-check text-sky-400 text-xs"></i>
                    </a>
                    <div class="text-[11px] text-slate-200">Cung cấp đá nội ngoại & Cắt đá CNC tự động</div>
                  </div>
                </div>
              </div>

              <div class="p-3 space-y-2 text-xs text-slate-700">
                <div class="flex items-start gap-2">
                  <i class="fa-solid fa-building text-brand-primary mt-0.5"></i>
                  <span><strong>CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG</strong></span>
                </div>
                <div class="flex items-start gap-2">
                  <i class="fa-solid fa-location-dot text-brand-primary mt-0.5"></i>
                  <span>Thửa đất số 213, tờ bản đồ số 1, Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng</span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-phone text-brand-primary"></i>
                  <span>Hotline / Zalo: <strong class="text-brand-dark">0985.505.467</strong></span>
                </div>

                <!-- Ảnh hoạt động mới trên Fanpage -->
                <div class="grid grid-cols-3 gap-1.5 pt-1">
                  <img src="https://drive.google.com/thumbnail?id=1SG32Xn3btcfXs6btMdXq2keoxftzwcos&sz=w300"
                       onerror="handleDriveImageError(this, '1SG32Xn3btcfXs6btMdXq2keoxftzwcos', 'SLAB DA MOI')"
                       alt="Ảnh Fanpage 1" class="w-full h-16 object-cover rounded border border-slate-200">
                  <img src="https://drive.google.com/thumbnail?id=1OGU9B0Q2vUpX3tybx-UD6j5rBkZBZDlD&sz=w300"
                       onerror="handleDriveImageError(this, '1OGU9B0Q2vUpX3tybx-UD6j5rBkZBZDlD', 'DA HOA CUONG')"
                       alt="Ảnh Fanpage 2" class="w-full h-16 object-cover rounded border border-slate-200">
                  <img src="https://drive.google.com/thumbnail?id=1wlqj9aCEXlFwcKs4Tfjvc5uUGxbtySDb&sz=w300"
                       onerror="handleDriveImageError(this, '1wlqj9aCEXlFwcKs4Tfjvc5uUGxbtySDb', 'CAT DA CNC')"
                       alt="Ảnh Fanpage 3" class="w-full h-16 object-cover rounded border border-slate-200">
                </div>
              </div>
            </div>
          </div>

          <div class="pt-3 flex items-center gap-2">
            <a href="https://www.facebook.com/xuan.nhung.kho.a" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs text-center transition flex items-center justify-center gap-2">
              <i class="fa-brands fa-facebook-f"></i>
              <span>Truy Cập Facebook: fb.com/xuan.nhung.kho.a</span>
            </a>
          </div>
        </div>

        <!-- Cột 3: Đưa Ảnh & Bản Đồ Google Map Ra Ngoài Trang Chủ (4 cột) -->
        <div class="lg:col-span-4 bg-white rounded-lg border border-slate-200 shadow-sm p-4 flex flex-col justify-between">
          <div>
            <div class="border-b border-slate-200 pb-2.5 mb-3">
              <h3 class="font-heading font-bold text-brand-dark text-sm uppercase flex items-center gap-2">
                <i class="fa-solid fa-map-location-dot text-red-600"></i>
                <span>BẢN ĐỒ GOOGLE MAPS KHO ĐÁ XUÂN NHUNG</span>
              </h3>
              <p class="text-xs text-slate-600 mt-1">
                Thửa đất số 213, tờ bản đồ số 1, Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng
              </p>
            </div>

            <!-- Bản đồ Google Maps nhúng trực tiếp + nút mở link https://share.google/SSyPNnbBgEuDFBLND -->
            <div class="rounded-lg overflow-hidden border border-slate-300 relative h-44 bg-slate-100 mb-2">
              <iframe 
                title="Bản đồ Công ty TNHH TM DV Xuân Nhung"
                src="https://www.google.com/maps?q=Th%C3%B4n+Ph%C3%BA+V%C4%A9nh,+X%C3%A3+Xu%C3%A2n+Ph%C3%BA,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>

            <!-- Hình ảnh trực quan vị trí Google Maps ngoài trang chủ -->
            <a href="https://share.google/SSyPNnbBgEuDFBLND" target="_blank" rel="noopener noreferrer" class="block rounded-lg border border-slate-200 p-2 bg-slate-50 hover:bg-slate-100 transition">
              <div class="flex items-center gap-2.5">
                <div class="w-10 h-10 rounded bg-emerald-600 text-white flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-location-crosshairs text-base"></i>
                </div>
                <div class="text-xs leading-tight">
                  <div class="font-bold text-brand-dark">Vị trí Google Maps: Kho Đá Xuân Nhung</div>
                  <div class="text-[11px] text-slate-600 mt-0.5">Thửa đất số 213, tờ bản đồ số 1, Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng</div>
                </div>
              </div>
            </a>
          </div>

          <div class="pt-3">
            <a href="https://share.google/SSyPNnbBgEuDFBLND" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-3 rounded bg-emerald-700 hover:bg-emerald-800 text-white font-bold text-xs text-center transition flex items-center justify-center gap-2">
              <i class="fa-solid fa-diamond-turn-right"></i>
              <span>Mở Google Maps Chỉ Đường Đến Kho Đá</span>
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ==================== 10. DANH MỤC ĐỐI TÁC CỦA CHÚNG TÔI ==================== -->
  <section id="sec-doitac" class="py-6 bg-white border-t border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <h2 class="section-title-main">
          <i class="fa-solid fa-handshake text-brand-goldlight"></i>
          <span>ĐỐI TÁC CUNG ỨNG & NHÀ THẦU XÂY DỰNG ĐỒNG HÀNH</span>
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-accent transition">
          <div class="font-heading font-extrabold text-brand-dark text-xs">SACMI ITALY</div>
          <span class="text-[11px] text-slate-500 mt-0.5">Công Nghệ Đá Nung Kết</span>
        </div>
        <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-accent transition">
          <div class="font-heading font-extrabold text-brand-dark text-xs">CNC STONE TECH</div>
          <span class="text-[11px] text-slate-500 mt-0.5">Hệ Thống Máy Cắt Đá CNC</span>
        </div>
        <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-accent transition">
          <div class="font-heading font-extrabold text-brand-dark text-xs">INDIA GRANITE EXPORTS</div>
          <span class="text-[11px] text-slate-500 mt-0.5">Đối Tác Đá Granite Ấn Độ</span>
        </div>
        <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-accent transition">
          <div class="font-heading font-extrabold text-brand-dark text-xs">TURKEY MARBLE SLAB</div>
          <span class="text-[11px] text-slate-500 mt-0.5">Nhập Khẩu Đá Marble</span>
        </div>
        <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-accent transition">
          <div class="font-heading font-extrabold text-brand-dark text-xs">DA NANG CONS</div>
          <span class="text-[11px] text-slate-500 mt-0.5">Nhà Thầu Xây Dựng Đà Nẵng</span>
        </div>
        <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-accent transition">
          <div class="font-heading font-extrabold text-brand-dark text-xs">QUANG NAM STONE</div>
          <span class="text-[11px] text-slate-500 mt-0.5">Mỏ Đá Tự Nhiên Nội Địa</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FOOTER CHUẨN MẪU ĐẠI GIA PHÚC ==================== -->
  <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brand-accent">
    <div class="container-1500">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-slate-700/80 text-xs">
        
        <!-- Thông tin công ty -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded bg-brand-primary border border-brand-accent flex items-center justify-center shrink-0">
              <span class="font-heading font-extrabold text-brand-goldlight text-sm">XN</span>
            </div>
            <div>
              <h3 class="font-heading font-extrabold text-white text-sm uppercase">
                CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG
              </h3>
              <p class="text-brand-goldlight text-[11px] font-semibold">Website: xuannhung.com | MST: 4000466334</p>
            </div>
          </div>
          <p class="text-slate-300 leading-relaxed">
            Chuyên cung cấp các loại đá nội - ngoại: Đá Marble, Đá Granite, Đá Nhân Tạo, Gạch Đá Nung Kết, Đá Onyx Xuyên Sáng. Nhận cắt đá bằng máy tự động CNC theo mọi quy cách công trình.
          </p>
          <ul class="space-y-1.5 text-slate-200">
            <li><i class="fa-solid fa-location-dot text-brand-goldlight mr-2"></i><strong>Địa chỉ:</strong> Thửa đất số 213, tờ bản đồ số 1, Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-brand-goldlight mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0985505467" class="text-brand-goldlight font-bold hover:underline">0985.505.467</a></li>
            <li><i class="fa-brands fa-facebook text-brand-goldlight mr-2"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/xuan.nhung.kho.a" target="_blank" rel="noopener noreferrer" class="hover:underline">facebook.com/xuan.nhung.kho.a</a></li>
            <li><i class="fa-solid fa-map text-brand-goldlight mr-2"></i><strong>Google Maps:</strong> <a href="https://share.google/SSyPNnbBgEuDFBLND" target="_blank" rel="noopener noreferrer" class="hover:underline">Xem vị trí Kho Đá Xuân Nhung</a></li>
          </ul>
        </div>

        <!-- Danh mục sản phẩm chính -->
        <div class="lg:col-span-4 space-y-2">
          <h4 class="font-heading font-bold text-brand-goldlight uppercase text-xs border-b border-slate-700 pb-1.5">
            DANH MỤC ĐÁ NỘI - NGOẠI & GIA CÔNG
          </h4>
          <div class="grid grid-cols-2 gap-1.5 text-slate-300">
            <a href="#sec-marble" class="hover:text-brand-goldlight">• Đá Marble Tự Nhiên</a>
            <a href="#sec-granite" class="hover:text-brand-goldlight">• Đá Granite Hoa Cương</a>
            <a href="#sec-nhantao" class="hover:text-brand-goldlight">• Đá Nhân Tạo Quartz</a>
            <a href="#sec-nungket" class="hover:text-brand-goldlight">• Gạch Đá Nung Kết</a>
            <a href="#sec-onyx" class="hover:text-brand-goldlight">• Đá Onyx Xuyên Sáng</a>
            <a href="#sec-onyx" class="hover:text-brand-goldlight">• Đá Quartzite & Bazan</a>
            <a href="#sec-cnc" class="hover:text-brand-goldlight">• Cắt Đá Máy Tự Động CNC</a>
            <a href="#sec-hangmuc" class="hover:text-brand-goldlight">• Đá Bàn Bếp & Cầu Thang</a>
          </div>
        </div>

        <!-- Hỗ trợ khách hàng -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="font-heading font-bold text-brand-goldlight uppercase text-xs border-b border-slate-700 pb-1.5">
            CAM KẾT CHẤT LƯỢNG
          </h4>
          <ul class="space-y-1.5 text-slate-300">
            <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Nguồn đá nội - ngoại tuyển chọn loại 1</li>
            <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Cắt đá bằng máy tự động CNC chuẩn từng mm</li>
            <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Giá gốc tại kho Xuân Nhung - Đà Nẵng</li>
            <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Vận chuyển tận công trình nhanh chóng</li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>© 2026 CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XUÂN NHUNG (xuannhung.com). All Rights Reserved.</div>
        <div>Chuyên cung cấp các loại đá nội - ngoại | Nhận cắt đá bằng máy tự động CNC</div>
      </div>
    </div>
  </footer>

  <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH PC & MOBILE ==================== -->
  <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo nổi bật -->
    <a href="https://zalo.me/0985505467" target="_blank" rel="noopener noreferrer" 
       class="group flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg border-2 border-white transition">
      <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline font-bold text-xs pr-1">Chat Zalo: 0985.505.467</span>
    </a>

    <!-- Nút Facebook nổi bật -->
    <a href="https://www.facebook.com/xuan.nhung.kho.a" target="_blank" rel="noopener noreferrer" 
       class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg border-2 border-white transition">
      <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="hidden sm:inline font-bold text-xs pr-1">Fanpage Xuân Nhung</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0985505467" 
       class="float-btn-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full px-3 py-2 sm:px-4 sm:py-2.5 shadow-xl border-2 border-brand-goldlight transition">
      <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <div class="leading-tight pr-1">
        <div class="text-[10px] text-amber-200 font-semibold">Hotline Báo Giá</div>
        <div class="font-extrabold text-xs sm:text-sm">0985.505.467</div>
      </div>
    </a>
  </div>

  <!-- ==================== MODAL XEM CHI TIẾT SẢN PHẨM ==================== -->
  <div id="productModal" class="fixed inset-0 z-50 hidden bg-black/70 flex items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="bg-brand-dark text-white px-4 py-3 flex items-center justify-between">
        <h3 id="modalTitle" class="font-heading font-bold text-sm sm:text-base text-brand-goldlight">Chi Tiết Mẫu Đá</h3>
        <button type="button" onclick="closeProductModal()" class="w-7 h-7 rounded-full bg-white/10 hover:bg-white/20 text-white flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 grid grid-cols-1 sm:grid-cols-2 gap-4 items-center">
        <img id="modalImg" src="" alt="Mẫu đá" class="w-full h-60 object-cover rounded-lg border border-slate-200">
        <div class="space-y-2 text-xs sm:text-sm">
          <div id="modalCode" class="text-xs font-bold text-brand-primary"></div>
          <div id="modalSpecs" class="space-y-1.5 text-slate-700"></div>
          <div class="pt-3 flex flex-col gap-2">
            <a href="tel:0985505467" class="w-full py-2.5 px-3 rounded bg-red-600 text-white font-bold text-center text-xs">
              <i class="fa-solid fa-phone mr-1.5"></i>Gọi Báo Giá: 0985.505.467
            </a>
            <a href="https://zalo.me/0985505467" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-3 rounded bg-[#0068ff] text-white font-bold text-center text-xs">
              Nhắn Zalo Nhận Ảnh Slab Thực Tế
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== JAVASCRIPT DỮ LIỆU THỰC TẾ & TƯƠNG TÁC ==================== -->
  <script>
    // Cơ chế tải ảnh Google Drive kèm fallback thông minh nếu trình duyệt chặn cookie bên thứ 3
    function handleDriveImageError(imgEl, fileId, labelText) {
      const currentAttempt = parseInt(imgEl.getAttribute('data-attempt') || '0', 10);
      if (currentAttempt === 0) {
        imgEl.setAttribute('data-attempt', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
      } else if (currentAttempt === 1) {
        imgEl.setAttribute('data-attempt', '2');
        const encoded = encodeURIComponent(labelText || 'XUAN NHUNG STONE');
        imgEl.src = 'https://placehold.co/800x600/13385c/e6c36a?text=' + encoded;
      }
    }

    // 11 File ID ảnh sản phẩm thực tế từ Google Drive do khách hàng cung cấp:
    // 1. 1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8
    // 2. 1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb
    // 3. 1JVJXQg2jxFs5euhF1u4uliLWAdglUpBJ
    // 4. 1ARY5qwlmpgmWzydfjdiJTPX7-naaYqYq
    // 5. 1wPp6NETrV8JE09oaf7UUO3BZL6tOHBO5
    // 6. 1vL_BADqK9VUKKjIEDG7-5Z44ayXxxJnu
    // 7. 1K3IfK2xOLKipdh6D31qMVXyxXBej2lrm
    // 8. 1CFLX-VWMNL09cp8p4UjXgDipZKylLy_W
    // 9. 1SG32Xn3btcfXs6btMdXq2keoxftzwcos
    // 10. 1OGU9B0Q2vUpX3tybx-UD6j5rBkZBZDlD
    // 11. 1wlqj9aCEXlFwcKs4Tfjvc5uUGxbtySDb

    const PRODUCTS_DATA = {
      marble: [
        {
          code: 'XN-M545',
          name: 'Đá Marble Volakas White Vân Mây Tự Nhiên',
          category: 'Đá Marble',
          color: 'Màu Trắng',
          origin: 'Hy Lạp / Nhập khẩu',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm - 20mm',
          driveId: '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8'
        },
        {
          code: 'XN-M543',
          name: 'Đá Marble Cream Nova Hoàng Gia',
          category: 'Đá Marble',
          color: 'Màu Kem',
          origin: 'Thổ Nhĩ Kỳ (Turkey)',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb'
        },
        {
          code: 'XN-M542',
          name: 'Đá Marble Carrara White Italia',
          category: 'Đá Marble',
          color: 'Màu Trắng',
          origin: 'Italia',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm - 20mm',
          driveId: '1JVJXQg2jxFs5euhF1u4uliLWAdglUpBJ'
        },
        {
          code: 'XN-M510',
          name: 'Đá Marble Black Emperador Vân Nâu Đen',
          category: 'Đá Marble',
          color: 'Màu Đen',
          origin: 'Tây Ban Nha / Turkey',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1ARY5qwlmpgmWzydfjdiJTPX7-naaYqYq'
        },
        {
          code: 'XN-M509',
          name: 'Đá Marble Astana Silver Xám Vân Đá',
          category: 'Đá Marble',
          color: 'Màu Xám',
          origin: 'Turkey',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1wPp6NETrV8JE09oaf7UUO3BZL6tOHBO5'
        },
        {
          code: 'XN-M508',
          name: 'Đá Marble Venetian Brown Nâu Sang Trọng',
          category: 'Đá Marble',
          color: 'Màu Nâu',
          origin: 'Italia',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1vL_BADqK9VUKKjIEDG7-5Z44ayXxxJnu'
        },
        {
          code: 'XN-M523',
          name: 'Đá Marble Verde Antico Xanh Ngọc Tự Nhiên',
          category: 'Đá Marble',
          color: 'Màu Xanh',
          origin: 'Nhập khẩu',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1K3IfK2xOLKipdh6D31qMVXyxXBej2lrm'
        },
        {
          code: 'XN-M513',
          name: 'Đá Marble Travertine Vàng Kem Cổ Điển',
          category: 'Đá Marble',
          color: 'Màu Vàng',
          origin: 'Turkey',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1CFLX-VWMNL09cp8p4UjXgDipZKylLy_W'
        }
      ],
      granite: [
        {
          code: 'XN-G549',
          name: 'Đá Granite Colonial White Trắng Ấn Độ',
          category: 'Đá Granite',
          color: 'Màu Trắng',
          origin: 'Ấn Độ',
          size: 'Khổ lớn',
          thickness: '18mm - 20mm',
          driveId: '1SG32Xn3btcfXs6btMdXq2keoxftzwcos'
        },
        {
          code: 'XN-G540',
          name: 'Đá Granite Black Forest Đen Vân Rừng',
          category: 'Đá Granite',
          color: 'Màu Đen',
          origin: 'Ấn Độ',
          size: 'Khổ lớn',
          thickness: '20mm',
          driveId: '1OGU9B0Q2vUpX3tybx-UD6j5rBkZBZDlD'
        },
        {
          code: 'XN-G524',
          name: 'Đá Granite River Gold Vàng Ánh Kim',
          category: 'Đá Granite',
          color: 'Màu Vàng',
          origin: 'Ấn Độ',
          size: 'Khổ lớn',
          thickness: '18mm',
          driveId: '1wlqj9aCEXlFwcKs4Tfjvc5uUGxbtySDb'
        },
        {
          code: 'XN-G519',
          name: 'Đá Granite Trắng Suối Lau Nội Địa',
          category: 'Đá Granite',
          color: 'Màu Trắng',
          origin: 'Việt Nam',
          size: 'Khổ lớn & Cắt quy cách CNC',
          thickness: '18mm - 20mm',
          driveId: '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8'
        },
        {
          code: 'XN-G501',
          name: 'Đá Granite Apple Green Xanh Tự Nhiên',
          category: 'Đá Granite',
          color: 'Màu Xanh',
          origin: 'Ấn Độ',
          size: 'Khổ lớn',
          thickness: '18mm',
          driveId: '1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb'
        },
        {
          code: 'XN-G493',
          name: 'Đá Granite Via Lactea Đen Vân Trắng Brazil',
          category: 'Đá Granite',
          color: 'Màu Đen',
          origin: 'Brazil',
          size: 'Khổ lớn',
          thickness: '20mm',
          driveId: '1JVJXQg2jxFs5euhF1u4uliLWAdglUpBJ'
        },
        {
          code: 'XN-G489',
          name: 'Đá Granite Solarius Vàng Sa Mạc Brazil',
          category: 'Đá Granite',
          color: 'Màu Vàng',
          origin: 'Brazil',
          size: 'Khổ lớn',
          thickness: '20mm',
          driveId: '1ARY5qwlmpgmWzydfjdiJTPX7-naaYqYq'
        },
        {
          code: 'XN-G477',
          name: 'Đá Granite Đỏ Ruby Ấn Độ Cao Cấp',
          category: 'Đá Granite',
          color: 'Màu Đỏ',
          origin: 'Ấn Độ',
          size: 'Khổ lớn',
          thickness: '18mm',
          driveId: '1wPp6NETrV8JE09oaf7UUO3BZL6tOHBO5'
        }
      ],
      nhantao: [
        {
          code: 'XN-NK552',
          name: 'Đá Nung Kết Calacatta Golden Vân Vàng',
          category: 'Đá Nung Kết',
          color: 'Màu Trắng',
          origin: 'Việt Nam / Công nghệ Ý',
          size: 'Khổ lớn 160x320cm',
          thickness: '14mm - 20mm',
          driveId: '1vL_BADqK9VUKKjIEDG7-5Z44ayXxxJnu'
        },
        {
          code: 'XN-NK551',
          name: 'Đá Nung Kết Xanh Ngọc Bích Cao Cấp',
          category: 'Đá Nung Kết',
          color: 'Màu Xanh',
          origin: 'Nhập khẩu',
          size: 'Khổ lớn',
          thickness: '14mm',
          driveId: '1K3IfK2xOLKipdh6D31qMVXyxXBej2lrm'
        },
        {
          code: 'XN-NK541',
          name: 'Đá Quartz Nhân Tạo Aurora Snow Chống Thấm',
          category: 'Đá Quartz',
          color: 'Màu Trắng',
          origin: 'Việt Nam',
          size: '160x320cm',
          thickness: '20mm',
          driveId: '1CFLX-VWMNL09cp8p4UjXgDipZKylLy_W'
        },
        {
          code: 'XN-SV514',
          name: 'Đá Blue Roma (Sứ Vân Cao Cấp)',
          category: 'Đá Sứ Vân',
          color: 'Màu Xanh',
          origin: 'Nhập khẩu',
          size: 'Khổ lớn',
          thickness: '18mm',
          driveId: '1SG32Xn3btcfXs6btMdXq2keoxftzwcos'
        },
        {
          code: 'XN-SV490',
          name: 'Đá Luxury Gold (Sứ Vân Vàng Sang Trọng)',
          category: 'Đá Sứ Vân',
          color: 'Màu Vàng',
          origin: 'Nhập khẩu',
          size: 'Khổ lớn',
          thickness: '18mm',
          driveId: '1OGU9B0Q2vUpX3tybx-UD6j5rBkZBZDlD'
        },
        {
          code: 'XN-SV507',
          name: 'Đá Carrara Sứ Vân Trắng Chống Trầy Xước',
          category: 'Đá Sứ Vân',
          color: 'Màu Trắng',
          origin: 'Nhập khẩu',
          size: 'Khổ lớn',
          thickness: '18mm',
          driveId: '1wlqj9aCEXlFwcKs4Tfjvc5uUGxbtySDb'
        },
        {
          code: 'XN-NK539',
          name: 'Đá Nung Kết Taj Mahal Kem Vân Mây',
          category: 'Đá Nung Kết',
          color: 'Màu Vàng',
          origin: 'Việt Nam',
          size: 'Khổ lớn',
          thickness: '14mm - 18mm',
          driveId: '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8'
        },
        {
          code: 'XN-NK538',
          name: 'Đá Nung Kết Mont Blanc Xuyên Vân',
          category: 'Đá Nung Kết',
          color: 'Màu Trắng',
          origin: 'Việt Nam',
          size: 'Khổ lớn',
          thickness: '14mm - 20mm',
          driveId: '1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb'
        }
      ],
      other: [
        {
          code: 'XN-CNC01',
          name: 'Gia Công Cắt Đá Mặt Bếp & Đảo Bếp Bằng Máy Tự Động CNC',
          category: 'Cắt Đá CNC',
          color: 'Cắt Đá CNC',
          origin: 'Xưởng Đá Xuân Nhung',
          size: 'Cắt theo bản vẽ CAD/CNC',
          thickness: '14mm - 30mm',
          driveId: '1VF5hSCendde9cU58uSTusKaAiTt6zeFd'
        },
        {
          code: 'XN-CNC02',
          name: 'Cắt Hoa Văn Đá Sảnh & Tranh Đá Đối Xứng Bằng Máy CNC',
          category: 'Cắt Đá CNC',
          color: 'Cắt Đá CNC',
          origin: 'Xưởng Đá Xuân Nhung',
          size: 'Gia công chính xác 100%',
          thickness: '18mm - 20mm',
          driveId: '1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6'
        },
        {
          code: 'XN-OX01',
          name: 'Đá Onyx Xuyên Sáng Hoàng Kim Trang Trí Vách Tivi & Sảnh',
          category: 'Đá Onyx Xuyên Sáng',
          color: 'Đá Onyx Xuyên Sáng',
          origin: 'Nhập khẩu',
          size: 'Khổ lớn (Slab)',
          thickness: '18mm',
          driveId: '1JVJXQg2jxFs5euhF1u4uliLWAdglUpBJ'
        },
        {
          code: 'XN-QZ544',
          name: 'Đá Tự Nhiên Chantilly Quartzite Siêu Cứng Brazil',
          category: 'Đá Quartzite',
          color: 'Đá Quartzite',
          origin: 'Brazil',
          size: 'Khổ lớn (Slab)',
          thickness: '20mm',
          driveId: '1ARY5qwlmpgmWzydfjdiJTPX7-naaYqYq'
        }
      ]
    };

    // 7 File ID hình ảnh thực tế công ty từ Google Drive:
    const COMPANY_DRIVE_IMAGES = [
      { id: '1EMZRIKjZkw6x2FSBcX4UBlZj4lxnFPa1', title: 'Tổng Kho Đá Nội - Ngoại Xuân Nhung Đà Nẵng' },
      { id: '1S4vTgOECmc4VGxkIMDOHjP7trZQnlvuJ', title: 'Khu Trưng Bày Đá Slab Khổ Lớn Tại Kho' },
      { id: '1VF5hSCendde9cU58uSTusKaAiTt6zeFd', title: 'Hệ Thống Máy Cắt Đá Tự Động CNC Hiện Đại' },
      { id: '1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6', title: 'Dây Chuyền Gia Công Cắt Đá CNC Tự Động' },
      { id: '1gtlB9c4YldD_u1e4SM9KWLxCRgQhXFEI', title: 'Kho Đá Granite & Marble Nhập Khẩu' },
      { id: '1k57YHIbkn5pg7JyqBrX4FTEbnqs-TxPd', title: 'Bốc Xếp & Vận Chuyển Đá Tận Công Trình' },
      { id: '1EoLtCRySVKF2HCer7MHt1oXSzha7oIk6', title: 'Đội Ngũ Kỹ Thuật Gia Công Đá Xuân Nhung' }
    ];

    // Danh sách Dự án tại Đà Nẵng
    const DANANG_PROJECTS = [
      {
        title: 'Cung Cấp & Ốp Đá Marble Biệt Thự Khu Đô Thị Sinh Thái Hòa Xuân - Đà Nẵng',
        category: 'Biệt Thự Đà Nẵng',
        location: 'Phường Hòa Xuân, TP Đà Nẵng',
        items: 'Mặt tiền, cầu thang, bàn bếp cắt CNC',
        driveId: '1rXnQeq7fz9yVPrugsEoVJXO4msQUjwE8'
      },
      {
        title: 'Thi Công Đá Sảnh & Quầy Lễ Tân Khách Sạn Ven Biển Võ Nguyên Giáp',
        category: 'Khách Sạn & Resort',
        location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
        items: 'Đá Marble Volakas & Onyx xuyên sáng',
        driveId: '1_MbeSUi0ocCNhT6f0LPHOvVHKgdwYEIb'
      },
      {
        title: 'Gia Công Cắt Đá CNC Mặt Bếp & Cầu Thang Khu Đô Thị FPT City Đà Nẵng',
        category: 'Nhà Phố & Khu Đô Thị',
        location: 'Khu Đô Thị FPT City, Ngũ Hành Sơn, Đà Nẵng',
        items: 'Đá Nung Kết & Đá Granite Ấn Độ',
        driveId: '1VF5hSCendde9cU58uSTusKaAiTt6zeFd'
      },
      {
        title: 'Cắt CNC Hoa Văn Đá Tự Nhiên Biệt Thự Đường Bạch Đằng - Hải Châu',
        category: 'Gia Công Cắt Đá CNC',
        location: 'Quận Hải Châu, TP Đà Nẵng',
        items: 'Gia công cắt máy tự động CNC theo bản vẽ',
        driveId: '1jFwf2xH3pK6U38AxjkUx61q0BFRFn-Z6'
      }
    ];

    // Danh sách Bài viết trang chủ
    const HOME_NEWS = [
      {
        title: 'Ưu Điểm Của Cắt Đá Bằng Máy Tự Động CNC Tại Xưởng Đá Xuân Nhung Đà Nẵng',
        category: 'Công Nghệ Cắt CNC',
        desc: 'Công nghệ cắt đá bằng máy tự động CNC giúp đường cắt chuẩn xác tuyệt đối đến từng milimet, bo cạnh thẩm mỹ cho mặt bếp, cầu thang và lavabo.',
        driveId: '1VF5hSCendde9cU58uSTusKaAiTt6zeFd'
      },
      {
        title: 'Đá Nung Kết Và Đá Quartz Nhân Tạo Khác Nhau Thế Nào Khi Làm Mặt Bàn Bếp?',
        category: 'Vật Liệu Đá',
        desc: 'So sánh chi tiết độ chịu nhiệt, chống thấm, chống trầy xước giữa đá nung kết khổ lớn và đá nhân tạo gốc thạch anh Quartz trước khi thi công bếp.',
        driveId: '1vL_BADqK9VUKKjIEDG7-5Z44ayXxxJnu'
      },
      {
        title: 'Kinh Nghiệm Chọn Đá Granite & Đá Marble Ốp Mặt Tiền, Cầu Thang Bền Đẹp',
        category: 'Ứng Dụng Thi Công',
        desc: 'Hướng dẫn phân biệt các dòng đá hoa cương nội - ngoại và đá cẩm thạch phù hợp với khí hậu miền Trung, giữ độ bóng đẹp hàng chục năm.',
        driveId: '1SG32Xn3btcfXs6btMdXq2keoxftzwcos'
      },
      {
        title: 'Tư Vấn Chọn Màu Đá Bàn Bếp Và Đá Lát Sảnh Hợp Phong Thủy Gia Chủ',
        category: 'Phong Thủy Chọn Đá',
        desc: 'Gợi ý cách phối màu đá Trắng Vân Mây, Vàng Hoàng Gia, Đen Kim Sa và Xanh Ngọc giúp không gian sống sang trọng, thu hút tài lộc.',
        driveId: '1K3IfK2xOLKipdh6D31qMVXyxXBej2lrm'
      }
    ];

    // Tạo thẻ sản phẩm chuẩn Flatsome (Không gắn nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên sản phẩm đầy đủ không bị cắt chữ)
    function createProductCardHTML(item) {
      const imgUrl = 'https://drive.google.com/thumbnail?id=' + item.driveId + '&sz=w700';
      const safeName = item.name.replace(/'/g, "\\'");
      const safeCode = item.code.replace(/'/g, "\\'");
      const safeOrigin = item.origin.replace(/'/g, "\\'");
      const safeSize = item.size.replace(/'/g, "\\'");
      const safeThickness = item.thickness.replace(/'/g, "\\'");
      const safeCategory = item.category.replace(/'/g, "\\'");

      return `
        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-accent transition flex flex-col justify-between">
          <div>
            <div class="overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal('${safeCode}', '${safeName}', '${item.driveId}', '${safeCategory}', '${safeOrigin}', '${safeSize}', '${safeThickness}')">
              <img src="${imgUrl}"
                   onerror="handleDriveImageError(this, '${item.driveId}', '${safeCode}')"
                   alt="${item.name}"
                   loading="lazy"
                   class="w-full h-36 sm:h-48 object-cover hover:scale-105 transition duration-300">
            </div>
            <div class="p-2.5 sm:p-3">
              <h3 class="product-title cursor-pointer hover:text-brand-primary" onclick="openProductModal('${safeCode}', '${safeName}', '${item.driveId}', '${safeCategory}', '${safeOrigin}', '${safeSize}', '${safeThickness}')">
                ${item.name}
              </h3>
              <div class="text-[11px] sm:text-xs text-slate-600 space-y-0.5 border-t border-slate-100 pt-1.5">
                <div><span class="font-semibold text-slate-700">Mã SP:</span> ${item.code}</div>
                <div><span class="font-semibold text-slate-700">Xuất xứ:</span> ${item.origin}</div>
                <div><span class="font-semibold text-slate-700">Kích thước:</span> ${item.size}</div>
                <div><span class="font-semibold text-slate-700">Độ dày:</span> ${item.thickness}</div>
              </div>
            </div>
          </div>
          <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 flex items-center gap-1.5">
            <a href="tel:0985505467" class="flex-1 py-1.5 px-2 rounded bg-brand-dark hover:bg-brand-primary text-brand-goldlight font-bold text-[11px] text-center transition">
              Liên hệ báo giá
            </a>
            <button type="button" onclick="openProductModal('${safeCode}', '${safeName}', '${item.driveId}', '${safeCategory}', '${safeOrigin}', '${safeSize}', '${safeThickness}')" class="py-1.5 px-2.5 rounded border border-slate-300 hover:border-brand-accent text-slate-700 text-[11px] font-semibold transition">
              Chi tiết
            </button>
          </div>
        </div>
      `;
    }

    // Hiển thị danh sách sản phẩm theo từng nhóm
    function renderProductGroup(groupKey, filterValue) {
      const container = document.getElementById('grid-' + groupKey);
      if (!container) return;
      const list = PRODUCTS_DATA[groupKey] || [];
      const filtered = (!filterValue || filterValue === 'all')
        ? list
        : list.filter(function(item) {
            return item.color === filterValue || item.category === filterValue;
          });

      if (filtered.length === 0) {
        container.innerHTML = '<div class="col-span-full py-6 text-center text-xs text-slate-500">Đang cập nhật thêm mẫu đá trong danh mục này. Vui lòng liên hệ 0985.505.467 để nhận ảnh tại kho.</div>';
        return;
      }
      container.innerHTML = filtered.map(createProductCardHTML).join('');
    }

    // Lọc sản phẩm trong từng section
    function filterSectionProducts(groupKey, filterValue, btnEl) {
      if (btnEl && btnEl.parentElement) {
        const buttons = btnEl.parentElement.querySelectorAll('.cat-pill');
        buttons.forEach(function(b) { b.classList.remove('active'); });
        btnEl.classList.add('active');
      }
      renderProductGroup(groupKey, filterValue);
    }

    // Tìm kiếm sản phẩm toàn trang
    function filterProductsBySearch(keyword) {
      const kw = (keyword || '').trim().toLowerCase();
      ['marble', 'granite', 'nhantao', 'other'].forEach(function(groupKey) {
        const container = document.getElementById('grid-' + groupKey);
        if (!container) return;
        const list = PRODUCTS_DATA[groupKey] || [];
        const matched = !kw ? list : list.filter(function(item) {
          return item.name.toLowerCase().includes(kw) ||
                 item.code.toLowerCase().includes(kw) ||
                 item.color.toLowerCase().includes(kw) ||
                 item.category.toLowerCase().includes(kw) ||
                 item.origin.toLowerCase().includes(kw);
        });
        container.innerHTML = matched.map(createProductCardHTML).join('');
      });
    }

    // Lọc tất cả danh mục về trạng thái mặc định
    function filterAllCategories(mode) {
      ['marble', 'granite', 'nhantao', 'other'].forEach(function(groupKey) {
        renderProductGroup(groupKey, 'all');
      });
    }

    // Hiển thị 7 ảnh thực tế công ty, kho đá & máy cắt đá CNC
    function renderCompanyGallery() {
      const grid = document.getElementById('companyGalleryGrid');
      if (!grid) return;
      grid.innerHTML = COMPANY_DRIVE_IMAGES.map(function(img, idx) {
        const imgUrl = 'https://drive.google.com/thumbnail?id=' + img.id + '&sz=w600';
        const spanClass = idx === 0 ? 'col-span-2 sm:col-span-2' : '';
        return `
          <div class="${spanClass} bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
            <img src="${imgUrl}"
                 onerror="handleDriveImageError(this, '${img.id}', 'XUAN NHUNG STONE')"
                 alt="${img.title}"
                 loading="lazy"
                 class="w-full h-32 sm:h-36 object-cover">
            <div class="p-2 text-[11px] font-semibold text-brand-dark leading-snug">
              ${img.title}
            </div>
          </div>
        `;
      }).join('');
    }

    // Hiển thị Dự án tại Đà Nẵng (Không dán nhãn đè lên ảnh)
    function renderProjects(filterValue) {
      const grid = document.getElementById('grid-duan');
      if (!grid) return;
      const list = (!filterValue || filterValue === 'all')
        ? DANANG_PROJECTS
        : DANANG_PROJECTS.filter(function(p) { return p.category === filterValue; });

      grid.innerHTML = list.map(function(proj) {
        const imgUrl = 'https://drive.google.com/thumbnail?id=' + proj.driveId + '&sz=w600';
        return `
          <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
            <div>
              <img src="${imgUrl}"
                   onerror="handleDriveImageError(this, '${proj.driveId}', 'DU AN DA NANG')"
                   alt="${proj.title}"
                   loading="lazy"
                   class="w-full h-36 sm:h-44 object-cover">
              <div class="p-2.5 sm:p-3">
                <h3 class="product-title">${proj.title}</h3>
                <div class="text-[11px] text-slate-600 space-y-0.5 pt-1 border-t border-slate-100">
                  <div><strong>Khu vực:</strong> ${proj.location}</div>
                  <div><strong>Hạng mục:</strong> ${proj.items}</div>
                </div>
              </div>
            </div>
          </div>
        `;
      }).join('');
    }

    function filterProjects(filterValue, btnEl) {
      if (btnEl && btnEl.parentElement) {
        btnEl.parentElement.querySelectorAll('.cat-pill').forEach(function(b) { b.classList.remove('active'); });
        btnEl.classList.add('active');
      }
      renderProjects(filterValue);
    }

    // Hiển thị Bài viết trang chủ
    function renderNews(filterValue) {
      const grid = document.getElementById('grid-news');
      if (!grid) return;
      const list = (!filterValue || filterValue === 'all')
        ? HOME_NEWS
        : HOME_NEWS.filter(function(n) { return n.category === filterValue; });

      grid.innerHTML = list.map(function(post) {
        const imgUrl = 'https://drive.google.com/thumbnail?id=' + post.driveId + '&sz=w600';
        return `
          <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
            <div>
              <img src="${imgUrl}"
                   onerror="handleDriveImageError(this, '${post.driveId}', 'BAI VIET DA XUAN NHUNG')"
                   alt="${post.title}"
                   loading="lazy"
                   class="w-full h-40 object-cover">
              <div class="p-3">
                <div class="text-[11px] font-bold text-brand-accent uppercase mb-1">${post.category}</div>
                <h3 class="product-title">${post.title}</h3>
                <p class="text-xs text-slate-600 leading-relaxed">${post.desc}</p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1">
              <a href="#sec-baogia" class="text-xs font-bold text-brand-primary hover:text-brand-accent inline-flex items-center gap-1">
                <span>Tư vấn & Báo giá chi tiết</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>
        `;
      }).join('');
    }

    function filterNews(filterValue, btnEl) {
      if (btnEl && btnEl.parentElement) {
        btnEl.parentElement.querySelectorAll('.cat-pill').forEach(function(b) { b.classList.remove('active'); });
        btnEl.classList.add('active');
      }
      renderNews(filterValue);
    }

    // Điều khiển Hero Banner tự trượt (2 Slide kích thước bằng nhau)
    let currentHeroIndex = 0;
    let heroInterval = null;

    function setHeroSlide(index) {
      currentHeroIndex = index;
      const s0 = document.getElementById('hero-slide-0');
      const s1 = document.getElementById('hero-slide-1');
      const d0 = document.getElementById('hero-dot-0');
      const d1 = document.getElementById('hero-dot-1');
      if (!s0 || !s1) return;

      if (currentHeroIndex === 0) {
        s0.classList.remove('hidden');
        s0.classList.add('block');
        s1.classList.remove('block');
        s1.classList.add('hidden');
        if (d0 && d1) {
          d0.className = 'w-6 h-1.5 rounded-full bg-brand-accent transition-all';
          d1.className = 'w-2.5 h-1.5 rounded-full bg-white/50 transition-all';
        }
      } else {
        s1.classList.remove('hidden');
        s1.classList.add('block');
        s0.classList.remove('block');
        s0.classList.add('hidden');
        if (d0 && d1) {
          d1.className = 'w-6 h-1.5 rounded-full bg-brand-accent transition-all';
          d0.className = 'w-2.5 h-1.5 rounded-full bg-white/50 transition-all';
        }
      }
    }

    function changeHeroSlide(step) {
      const next = (currentHeroIndex + step + 2) % 2;
      setHeroSlide(next);
    }

    function startHeroSlider() {
      if (heroInterval) clearInterval(heroInterval);
      heroInterval = setInterval(function() {
        changeHeroSlide(1);
      }, 5500);
    }

    // Cuộn mượt tới danh mục
    function scrollToSection(id) {
      const el = document.getElementById(id);
      if (el) {
        el.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }

    // Đóng/mở menu trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      if (drawer) {
        drawer.classList.toggle('hidden');
      }
    }

    // Mở Modal xem chi tiết mẫu đá
    function openProductModal(code, name, driveId, category, origin, size, thickness) {
      const modal = document.getElementById('productModal');
      const titleEl = document.getElementById('modalTitle');
      const imgEl = document.getElementById('modalImg');
      const codeEl = document.getElementById('modalCode');
      const specsEl = document.getElementById('modalSpecs');
      if (!modal) return;

      titleEl.textContent = name;
      imgEl.removeAttribute('data-attempt');
      imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w800';
      imgEl.onerror = function() {
        handleDriveImageError(imgEl, driveId, code);
      };
      codeEl.textContent = 'Mã sản phẩm: ' + code + ' | Danh mục: ' + category;
      specsEl.innerHTML = `
        <div><strong>• Xuất xứ:</strong> ${origin}</div>
        <div><strong>• Kích thước:</strong> ${size}</div>
        <div><strong>• Độ dày:</strong> ${thickness}</div>
        <div><strong>• Dịch vụ gia công:</strong> Nhận cắt đá bằng máy tự động CNC theo kích thước thực tế</div>
        <div><strong>• Kho hàng:</strong> Thửa đất số 213, tờ bản đồ số 1, Thôn Phú Vĩnh, Xã Xuân Phú, TP Đà Nẵng</div>
      `;
      modal.classList.remove('hidden');
    }

    function closeProductModal() {
      const modal = document.getElementById('productModal');
      if (modal) modal.classList.add('hidden');
    }

    // Xử lý gửi Form Yêu Cầu Báo Giá trên trang chủ
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const cat = document.getElementById('qCategory').value;
      const box = document.getElementById('quoteSuccessBox');
      const text = document.getElementById('quoteSuccessText');

      if (box && text) {
        text.textContent = 'Cảm ơn ' + name + ' (' + phone + '). Yêu cầu báo giá "' + cat + '" đã được gửi đến Phòng Kinh Doanh Đá Xuân Nhung (Hotline/Zalo: 0985.505.467).';
        box.classList.remove('hidden');
      }
      document.getElementById('quoteForm').reset();
    }

    // Khởi tạo toàn bộ dữ liệu khi tải trang
    window.addEventListener('DOMContentLoaded', function() {
      renderProductGroup('marble', 'all');
      renderProductGroup('granite', 'all');
      renderProductGroup('nhantao', 'all');
      renderProductGroup('other', 'all');
      renderCompanyGallery();
      renderProjects('all');
      renderNews('all');
      startHeroSlider();
    });
  </script>
</body>
</html>
