<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - thienquy.net | Thiết Bị Cơ Khí, Vòng Bi, Dụng Cụ Công Nghiệp</title>
  <meta name="description" content="CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (thienquy.net) - Chuyên cung cấp vòng bi SKF, Nachi, Koyo, NSK, linh kiện bán dẫn IGBT, máy hàn, dụng cụ cầm tay, bulong ốc vít, phụ kiện cơ khí công nghiệp tại 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng. Hotline: 0978.102.434">

  <!-- Open Graph Thumbnail khi gửi link trang web (Zalo, Facebook, Messenger) -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="thienquy.net - CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ">
  <meta property="og:url" content="https://thienquy.net/">
  <meta property="og:title" content="CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - Vật Tư Cơ Khí & Thiết Bị Công Nghiệp Chính Hãng">
  <meta property="og:description" content="Nhà cung cấp thiết bị kỹ thuật, vòng bi công nghiệp, linh kiện điện tử công suất, dụng cụ đồ nghề, máy hàn cắt & vật tư kim khí uy tín. Đ/c: 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng - ĐT: 0978.102.434">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m=w1200">
  <meta property="og:image:alt" content="CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - thienquy.net">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - thienquy.net">
  <meta name="twitter:description" content="Chuyên cung cấp thiết bị cơ khí, vòng bi, dụng cụ cầm tay, linh kiện công nghiệp. Hotline: 0978.102.434">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m=w1200">

  <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Roboto chuẩn Flatsome) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            flatsome: {
              primary: '#0f4c81',    /* Xanh kỹ thuật chủ đạo */
              secondary: '#e65100',  /* Cam cơ khí điểm nhấn */
              red: '#d32f2f',        /* Đỏ giảm giá Flatsome */
              dark: '#1e293b',
              light: '#f8fafc'
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Chuẩn hóa giao diện Flatsome đơn giản, chống tràn viền & chống lệch phải 100% trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      scroll-behavior: smooth;
      font-family: 'Inter', sans-serif;
      background-color: #f4f6f8;
      color: #334155;
      -webkit-text-size-adjust: 100%;
    }
    header, main, section, footer, aside, div {
      max-width: 100%;
    }
    img, iframe, svg, video {
      max-width: 100%;
    }
    /* Chống tự động phóng to trên iPhone khi chạm vào ô tìm kiếm / form */
    @media (max-width: 767px) {
      input, select, textarea {
        font-size: 16px !important;
      }
    }

    /* Chỉnh sửa & làm nét Logo Thiên Quý */
    .logo-frame {
      position: relative;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      background: #ffffff;
      border-radius: 10px;
      padding: 4px 8px;
      border: 1.5px solid #e2e8f0;
      box-shadow: 0 2px 8px rgba(15, 76, 129, 0.08);
    }
    .logo-enhanced {
      object-fit: contain;
      filter: contrast(1.12) saturate(1.15) brightness(1.02);
      transition: transform 0.25s ease;
    }
    .logo-frame:hover .logo-enhanced {
      transform: scale(1.03);
    }

    /* Flatsome Product Box & Quick View */
    .product-small {
      background: #ffffff;
      border-radius: 8px;
      border: 1px solid #e2e8f0;
      overflow: hidden;
      transition: all 0.25s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
      min-width: 0;
    }
    .product-small:hover {
      box-shadow: 0 10px 25px -5px rgba(15, 76, 129, 0.14);
      border-color: #cbd5e1;
      transform: translateY(-2px);
    }
    .box-image {
      position: relative;
      width: 100%;
      padding-top: 100%; /* Tỷ lệ vuông 1:1 chuẩn Flatsome */
      overflow: hidden;
      background: #f8fafc;
    }
    .box-image img {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.4s ease;
    }
    .product-small:hover .box-image img {
      transform: scale(1.06);
    }

    /* Nút Xem Nhanh (Quick View) trượt từ dưới ảnh lên giống Flatsome */
    .quick-view-bar {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: rgba(15, 76, 129, 0.92);
      color: #ffffff;
      text-align: center;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      padding: 8px 6px;
      transform: translateY(100%);
      transition: transform 0.25s ease, background-color 0.2s ease;
      cursor: pointer;
      z-index: 10;
    }
    .quick-view-bar:hover {
      background: #e65100;
    }
    .product-small:hover .quick-view-bar {
      transform: translateY(0);
    }
    /* Trên điện thoại vẫn có nút icon xem nhanh gọn gàng */
    @media (max-width: 767px) {
      .quick-view-bar {
        transform: translateY(0);
        background: rgba(15, 76, 129, 0.85);
        padding: 4px 4px;
        font-size: 10px;
      }
    }

    /* Badge % giảm giá tròn/bo góc chuẩn Flatsome */
    .flatsome-onsale {
      position: absolute;
      top: 10px;
      left: 10px;
      z-index: 12;
      background-color: #d32f2f;
      color: #ffffff;
      font-weight: 700;
      font-size: 12px;
      width: 42px;
      height: 42px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(211, 47, 47, 0.35);
      line-height: 1;
    }
    @media (max-width: 640px) {
      .flatsome-onsale {
        width: 34px;
        height: 34px;
        font-size: 10.5px;
        top: 6px;
        left: 6px;
      }
    }

    /* Flatsome Section Title */
    .section-title-container {
      margin-bottom: 1rem;
    }
    .section-title-main {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #e2e8f0;
      padding-bottom: 10px;
      position: relative;
      min-width: 0;
    }
    .section-title-main::after {
      content: '';
      position: absolute;
      bottom: -2px;
      left: 0;
      width: 140px;
      height: 3px;
      background-color: #0f4c81;
    }

    /* Desktop Mega Category Item tối ưu đẹp mắt */
    .cat-menu-item {
      transition: all 0.2s ease;
      border-left: 3px solid transparent;
    }
    .cat-menu-item:hover {
      background-color: #f0f7ff;
      color: #0f4c81;
      border-left-color: #e65100;
      padding-left: 14px;
    }

    /* Nút liên hệ nổi bật có hiệu ứng sóng lan tỏa */
    @keyframes pulse-ring {
      0% { transform: scale(0.9); opacity: 0.8; }
      70% { transform: scale(1.38); opacity: 0; }
      100% { transform: scale(1.38); opacity: 0; }
    }
    .floating-btn-ring::before {
      content: '';
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background-color: inherit;
      z-index: -1;
      animation: pulse-ring 1.8s cubic-bezier(0.24, 0, 0.38, 1) infinite;
    }

    /* Tùy chỉnh thanh cuộn ngang mượt trên điện thoại */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col w-full overflow-x-hidden">

  <!-- =====================================================================
       1. TOP BAR ĐƠN GIẢN (Không có tùy chọn chỉnh sửa UX Builder)
  ====================================================================== -->
  <div id="top-bar" class="bg-flatsome-primary text-white text-xs py-2 border-b border-blue-900 w-full overflow-hidden">
    <div class="max-w-7xl mx-auto px-3 sm:px-6 flex items-center justify-between gap-2 min-w-0">
      <div class="flex items-center gap-3 min-w-0 flex-1 overflow-hidden">
        <span class="font-semibold tracking-wide flex items-center gap-1.5 min-w-0 truncate text-[11px] sm:text-xs">
          <i class="fa-solid fa-building-shield text-amber-400 shrink-0"></i>
          <span class="truncate">CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - thienquy.net</span>
        </span>
        <span class="hidden lg:inline-flex items-center gap-1.5 text-blue-100 shrink-0">
          <i class="fa-solid fa-location-dot text-amber-400"></i>
          258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 text-blue-100 shrink-0">
        <a href="mailto:thienquytm@gmail.com" class="hover:text-white flex items-center gap-1">
          <i class="fa-regular fa-envelope"></i> thienquytm@gmail.com
        </a>
        <span>|</span>
        <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener" class="hover:text-white flex items-center gap-1">
          <i class="fa-brands fa-facebook"></i> Fanpage Thiên Quý
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       2. HEADER CHÍNH CHUẨN FLATSOME (Không để nút Gọi Ngay để tránh tràn viền)
  ====================================================================== -->
  <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200 w-full overflow-hidden">
    <!-- Header Main -->
    <div class="header-main max-w-7xl mx-auto px-3 sm:px-6 py-2.5 sm:py-3">
      <div class="flex items-center justify-between gap-2 sm:gap-5 min-w-0">
        
        <!-- Nút mở Danh mục trên Mobile -->
        <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden w-10 h-10 rounded-lg bg-slate-100 text-slate-700 hover:bg-flatsome-primary hover:text-white transition flex items-center justify-center shrink-0">
          <i class="fa-solid fa-bars text-base"></i>
        </button>

        <!-- Logo Đã Chỉnh Đẹp Lại + Tên Công Ty -->
        <a href="#trang-chu" class="flex items-center gap-2 sm:gap-3 min-w-0 flex-1 lg:flex-initial overflow-hidden">
          <div class="logo-frame w-11 h-11 sm:w-15 sm:h-15 shrink-0">
            <img 
              src="https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl=w500" 
              data-drive-id="1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl"
              alt="Logo Công Ty TNHH Kỹ Thuật Thiên Quý" 
              class="logo-enhanced w-full h-full"
              onerror="handleDriveImgError(this)">
          </div>
          <div class="min-w-0 flex-1 overflow-hidden">
            <div class="text-xs sm:text-sm font-extrabold text-flatsome-primary tracking-tight uppercase leading-tight truncate">
              KỸ THUẬT THIÊN QUÝ
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-flatsome-secondary tracking-wide truncate">
              thienquy.net
            </div>
            <div class="hidden sm:block text-[11px] text-slate-500 truncate">
              Thiết Bị Cơ Khí - Vòng Bi - Công Nghiệp
            </div>
          </div>
        </a>

        <!-- Thanh Tìm Kiếm Sản Phẩm (Desktop) -->
        <div class="hidden md:flex flex-1 max-w-xl mx-auto min-w-0">
          <div class="relative flex w-full">
            <input 
              id="desktop-search-input"
              type="text" 
              placeholder="Tìm vòng bi SKF, IGBT, máy hàn, bulong, đá cắt, dụng cụ..." 
              class="w-full pl-4 pr-12 py-2.5 text-sm bg-slate-50 border border-slate-300 rounded-l-lg focus:outline-none focus:border-flatsome-primary focus:bg-white transition"
            >
            <button 
              id="desktop-search-btn"
              type="button" 
              class="px-5 bg-flatsome-primary hover:bg-blue-900 text-white rounded-r-lg transition flex items-center justify-center shrink-0"
              aria-label="Tìm kiếm">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </div>
        </div>

        <!-- Cụm nút chức năng gọn nhẹ (Không để nút gọi ngay tránh tràn viền) -->
        <div class="flex items-center gap-1.5 sm:gap-2 shrink-0">
          <a href="#form-bao-gia" class="px-2.5 py-2 sm:px-3 sm:py-2 rounded-lg bg-slate-100 hover:bg-flatsome-primary hover:text-white text-slate-700 text-xs sm:text-sm font-semibold transition flex items-center gap-1.5" title="Yêu cầu báo giá">
            <i class="fa-solid fa-file-invoice text-flatsome-secondary"></i>
            <span class="hidden sm:inline">Báo giá</span>
          </a>
          <a href="#ban-do-fanpage" class="px-2.5 py-2 sm:px-3 sm:py-2 rounded-lg bg-slate-100 hover:bg-flatsome-primary hover:text-white text-slate-700 text-xs sm:text-sm font-semibold transition flex items-center gap-1.5" title="Chỉ đường Google Maps">
            <i class="fa-solid fa-map-location-dot text-flatsome-primary"></i>
            <span class="hidden xl:inline">Bản đồ</span>
          </a>
        </div>

      </div>

      <!-- Thanh tìm kiếm trên điện thoại -->
      <div class="mt-2 md:hidden w-full">
        <div class="relative flex w-full">
          <input 
            id="mobile-search-input"
            type="text" 
            placeholder="Tìm tên sản phẩm, vòng bi, dụng cụ..." 
            class="w-full min-w-0 pl-3 pr-10 py-2 text-sm bg-slate-50 border border-slate-300 rounded-l-lg focus:outline-none focus:border-flatsome-primary"
          >
          <button 
            id="mobile-search-btn"
            type="button" 
            class="px-4 bg-flatsome-primary text-white rounded-r-lg text-sm shrink-0 flex items-center justify-center"
            aria-label="Tìm kiếm">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- Header Bottom Navigation (Chuẩn Flatsome Desktop) -->
    <div class="header-bottom hidden lg:block bg-flatsome-primary text-white">
      <div class="max-w-7xl mx-auto px-6 flex items-center justify-between">
        <div class="flex items-center w-full">
          <!-- Nút Danh Mục Sản Phẩm Cố Định đồng bộ độ rộng w-80 với cột danh mục bên dưới -->
          <div class="bg-flatsome-secondary px-4 py-3 font-bold text-sm uppercase tracking-wider flex items-center justify-between w-80 shrink-0 rounded-t-sm">
            <span class="flex items-center gap-2.5">
              <i class="fa-solid fa-bars-staggered"></i>
              <span>DANH MỤC SẢN PHẨM</span>
            </span>
            <span class="text-[11px] bg-black/20 px-2 py-0.5 rounded font-semibold">10 Nhóm</span>
          </div>
          <!-- Menu Ngang -->
          <nav class="flex items-center text-sm font-semibold pl-2">
            <a href="#trang-chu" class="px-3.5 py-3 hover:bg-blue-800 transition">TRANG CHỦ</a>
            <a href="#danh-muc-san-pham" class="px-3.5 py-3 hover:bg-blue-800 transition">DANH MỤC</a>
            <a href="#san-pham-noi-bat" class="px-3.5 py-3 hover:bg-blue-800 transition">SẢN PHẨM KHUYẾN MÃI</a>
            <a href="#hinh-anh-thuc-te" class="px-3.5 py-3 hover:bg-blue-800 transition">KHO HÀNG THỰC TẾ</a>
            <a href="#tin-tuc-ky-thuat" class="px-3.5 py-3 hover:bg-blue-800 transition">BÀI VIẾT KỸ THUẬT</a>
            <a href="#form-bao-gia" class="px-3.5 py-3 hover:bg-blue-800 transition">YÊU CẦU BÁO GIÁ</a>
            <a href="#ban-do-fanpage" class="px-3.5 py-3 hover:bg-blue-800 transition">LIÊN HỆ & BẢN ĐỒ</a>
          </nav>
        </div>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       3. HERO SECTION: DANH MỤC MÁY TÍNH + 2 ẢNH BANNER TỰ TRƯỢT
  ====================================================================== -->
  <main id="trang-chu" class="flex-1 w-full min-w-0 overflow-x-hidden">
    <section class="py-3 sm:py-6 w-full">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        <div class="flex flex-col lg:flex-row gap-4 sm:gap-5 items-stretch min-w-0">
          
          <!-- CỘT TRÁI: Danh mục sản phẩm tối ưu trên máy tính (Flatsome Vertical Mega Menu rộng w-80, hiển thị tên đầy đủ + thương hiệu con) -->
          <aside class="hidden lg:flex lg:flex-col w-80 shrink-0 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden justify-between">
            <ul id="desktop-sidebar-categories" class="divide-y divide-slate-100 text-slate-700 flex-1 flex flex-col justify-between">
              <!-- Được render tự động từ dữ liệu danh mục chuẩn mẫu Trang Tú Phương + Fanpage Thiên Quý -->
            </ul>
          </aside>

          <!-- CỘT PHẢI: 2 Ảnh Banner Tự Trượt (Auto Slider) + 4 Cam Kết Dịch Vụ -->
          <div class="flex-1 min-w-0 w-full flex flex-col justify-between gap-3 sm:gap-4">
            
            <!-- Slider 2 Banner Tự Trượt dùng ảnh thực tế Google Drive -->
            <div id="hero-banner-slider" class="relative w-full h-[220px] sm:h-[340px] md:h-[400px] rounded-xl overflow-hidden shadow-sm border border-slate-200 bg-slate-900 group">
              
              <!-- Slide 1 -->
              <div class="banner-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10" data-slide="0">
                <img 
                  src="https://lh3.googleusercontent.com/d/1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m=w1200" 
                  data-drive-id="1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m"
                  alt="Banner 1 - Công Ty TNHH Kỹ Thuật Thiên Quý" 
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this)">
                <div class="absolute inset-0 bg-gradient-to-r from-slate-950/90 via-slate-900/65 to-slate-900/20 flex items-center">
                  <div class="px-4 py-4 sm:p-10 w-full max-w-xl text-white">
                    <p class="text-amber-400 text-[10px] sm:text-sm font-bold uppercase tracking-wider mb-1 truncate">
                      CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - THIENQUY.NET
                    </p>
                    <h1 class="text-base sm:text-3xl md:text-4xl font-extrabold leading-snug sm:leading-tight mb-1.5 sm:mb-3">
                      Thiết Bị Cơ Khí, Vòng Bi & Vật Tư Công Nghiệp Chính Hãng
                    </h1>
                    <p class="text-[11px] sm:text-sm text-slate-200 mb-3 sm:mb-6 line-clamp-2 sm:line-clamp-3">
                      Chuyên phân phối Vòng bi SKF, Nachi, Koyo, NSK, Linh kiện công suất IGBT, Máy hàn cắt, Dụng cụ cầm tay và Phụ kiện xây dựng tại TP Đà Nẵng & toàn quốc.
                    </p>
                    <div class="flex flex-wrap gap-2">
                      <a href="#san-pham-noi-bat" class="px-3.5 py-2 sm:px-5 sm:py-2.5 bg-flatsome-secondary hover:bg-orange-700 text-white font-bold text-xs sm:text-sm rounded-lg transition shadow">
                        Xem Sản Phẩm
                      </a>
                      <a href="#form-bao-gia" class="px-3.5 py-2 sm:px-5 sm:py-2.5 bg-white/95 hover:bg-white text-flatsome-primary font-bold text-xs sm:text-sm rounded-lg transition">
                        Nhận Báo Giá Sỉ
                      </a>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Slide 2 -->
              <div class="banner-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0" data-slide="1">
                <img 
                  src="https://lh3.googleusercontent.com/d/1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N=w1200" 
                  data-drive-id="1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N"
                  alt="Banner 2 - Kho Vật Tư Thiết Bị Kỹ Thuật Thiên Quý" 
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this)">
                <div class="absolute inset-0 bg-gradient-to-r from-blue-950/90 via-blue-900/65 to-blue-900/20 flex items-center">
                  <div class="px-4 py-4 sm:p-10 w-full max-w-xl text-white">
                    <p class="text-amber-400 text-[10px] sm:text-sm font-bold uppercase tracking-wider mb-1 truncate">
                      ĐỐI TÁC TIN CẬY CỦA NHÀ MÁY & CÔNG TRÌNH
                    </p>
                    <h2 class="text-base sm:text-3xl md:text-4xl font-extrabold leading-snug sm:leading-tight mb-1.5 sm:mb-3">
                      Giải Pháp Dụng Cụ Đồ Nghề & Phụ Tùng Máy Đồng Bộ
                    </h2>
                    <p class="text-[11px] sm:text-sm text-slate-200 mb-3 sm:mb-6 line-clamp-2 sm:line-clamp-3">
                      Địa chỉ: 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng. Hỗ trợ kỹ thuật tận tâm, giao hàng nhanh chóng, chiết khấu cao cho đại lý và dự án.
                    </p>
                    <div class="flex flex-wrap gap-2">
                      <a href="#form-bao-gia" class="px-3.5 py-2 sm:px-5 sm:py-2.5 bg-flatsome-secondary hover:bg-orange-700 text-white font-bold text-xs sm:text-sm rounded-lg transition shadow">
                        Gửi Danh Mục Báo Giá
                      </a>
                      <a href="#ban-do-fanpage" class="px-3.5 py-2 sm:px-5 sm:py-2.5 bg-white/95 hover:bg-white text-flatsome-primary font-bold text-xs sm:text-sm rounded-lg transition">
                        Xem Địa Chỉ Bản Đồ
                      </a>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Nút điều hướng Prev / Next -->
              <button id="banner-prev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-flatsome-primary text-white flex items-center justify-center transition">
                <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
              </button>
              <button id="banner-next" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-flatsome-primary text-white flex items-center justify-center transition">
                <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
              </button>

              <!-- Chấm chỉ báo 2 Banner -->
              <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                <button type="button" data-goto="0" class="banner-dot w-6 h-1.5 sm:w-7 sm:h-2 rounded-full bg-amber-400 transition-all" aria-label="Slide 1"></button>
                <button type="button" data-goto="1" class="banner-dot w-2 h-1.5 sm:w-2.5 sm:h-2 rounded-full bg-white/60 hover:bg-white transition-all" aria-label="Slide 2"></button>
              </div>
            </div>

            <!-- 4 Ô Cam Kết Dịch Vụ: Chia đúng 2 cột cân đối trên điện thoại (grid-cols-2) và 4 cột trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 sm:gap-3.5 w-full">
              <div class="bg-white p-2.5 sm:p-3 rounded-xl border border-slate-200 flex items-center gap-2 sm:gap-3 shadow-sm min-w-0 overflow-hidden">
                <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-blue-50 text-flatsome-primary flex items-center justify-center shrink-0 text-sm sm:text-lg">
                  <i class="fa-solid fa-boxes-stacked"></i>
                </div>
                <div class="min-w-0 flex-1">
                  <div class="text-[11px] sm:text-sm font-bold text-slate-800 truncate">Sản phẩm đa dạng</div>
                  <div class="text-[10px] sm:text-[11px] text-slate-500 truncate">Sẵn kho vật tư kỹ thuật</div>
                </div>
              </div>
              <div class="bg-white p-2.5 sm:p-3 rounded-xl border border-slate-200 flex items-center gap-2 sm:gap-3 shadow-sm min-w-0 overflow-hidden">
                <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-orange-50 text-flatsome-secondary flex items-center justify-center shrink-0 text-sm sm:text-lg">
                  <i class="fa-solid fa-award"></i>
                </div>
                <div class="min-w-0 flex-1">
                  <div class="text-[11px] sm:text-sm font-bold text-slate-800 truncate">Uy tín – Tận tâm</div>
                  <div class="text-[10px] sm:text-[11px] text-slate-500 truncate">Cam kết đúng thông số</div>
                </div>
              </div>
              <div class="bg-white p-2.5 sm:p-3 rounded-xl border border-slate-200 flex items-center gap-2 sm:gap-3 shadow-sm min-w-0 overflow-hidden">
                <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-emerald-50 text-emerald-600 flex items-center justify-center shrink-0 text-sm sm:text-lg">
                  <i class="fa-solid fa-truck-fast"></i>
                </div>
                <div class="min-w-0 flex-1">
                  <div class="text-[11px] sm:text-sm font-bold text-slate-800 truncate">Giao hàng toàn quốc</div>
                  <div class="text-[10px] sm:text-[11px] text-slate-500 truncate">Nhanh chóng & tiết kiệm</div>
                </div>
              </div>
              <div class="bg-white p-2.5 sm:p-3 rounded-xl border border-slate-200 flex items-center gap-2 sm:gap-3 shadow-sm min-w-0 overflow-hidden">
                <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-purple-50 text-purple-600 flex items-center justify-center shrink-0 text-sm sm:text-lg">
                  <i class="fa-solid fa-headset"></i>
                </div>
                <div class="min-w-0 flex-1">
                  <div class="text-[11px] sm:text-sm font-bold text-slate-800 truncate">Tư vấn kỹ thuật 24/7</div>
                  <div class="text-[10px] sm:text-[11px] text-slate-500 truncate">Hỗ trợ tra mã chuẩn xác</div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         4. DANH MỤC SẢN PHẨM TỐI ƯU ĐẸP TRÊN MÁY TÍNH (5 CỘT x 2 HÀNG = 10 DANH MỤC) & ĐIỆN THOẠI (2 CỘT)
    ====================================================================== -->
    <section id="danh-muc-san-pham" class="py-4 sm:py-7 w-full">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 sm:p-6 shadow-sm">
          
          <div class="section-title-container">
            <div class="section-title-main">
              <h2 class="text-sm sm:text-xl font-extrabold text-flatsome-primary uppercase tracking-tight flex items-center gap-2 min-w-0">
                <i class="fa-solid fa-layer-group text-flatsome-secondary shrink-0"></i>
                <span class="truncate">DANH MỤC SẢN PHẨM CHÍNH</span>
              </h2>
              <button onclick="filterProductsByCategory('all')" class="text-xs sm:text-sm font-semibold text-flatsome-primary hover:text-flatsome-secondary flex items-center gap-1 shrink-0">
                <span>Xem tất cả</span>
                <i class="fa-solid fa-angle-right"></i>
              </button>
            </div>
          </div>

          <!-- Lưới Danh Mục: 2 cột trên điện thoại, 5 cột x 2 hàng (đủ 10 danh mục) trên máy tính -->
          <div id="visual-category-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4 w-full">
            <!-- Được tạo tự động bằng JS với ảnh thực tế Google Drive -->
          </div>

        </div>
      </div>
    </section>

    <!-- =====================================================================
         5. DANH SÁCH SẢN PHẨM THEO DANH MỤC (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT MÁY TÍNH)
    ====================================================================== -->
    <section id="san-pham-noi-bat" class="py-4 sm:py-6 w-full">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        
        <!-- Tiêu đề & Thanh lọc nhanh tách dòng để không bao giờ gây tràn ngang trên điện thoại -->
        <div class="section-title-container">
          <div class="section-title-main">
            <h2 id="current-category-heading" class="text-sm sm:text-xl font-extrabold text-flatsome-primary uppercase tracking-tight flex items-center gap-2 min-w-0">
              <i class="fa-solid fa-screwdriver-wrench text-flatsome-secondary shrink-0"></i>
              <span class="truncate">SẢN PHẨM THỰC TẾ TẠI KHO THIÊN QUÝ</span>
            </h2>
          </div>
          <!-- Các nút lọc danh mục tự xuống dòng gọn đẹp, không đẩy rộng khung trang -->
          <div class="flex flex-wrap items-center gap-1.5 pt-3 w-full" id="category-filter-pills">
            <!-- Nút lọc nhanh -->
          </div>
        </div>

        <!-- LƯỚI SẢN PHẨM CHUẨN FLATSOME: 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2), 4 CỘT TRÊN MÁY TÍNH (lg:grid-cols-4) -->
        <div id="main-product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-5 w-full">
          <!-- 16 Sản phẩm với 16 ảnh thực tế Google Drive sẽ được render tại đây -->
        </div>

      </div>
    </section>

    <!-- =====================================================================
         6. CÁC CHUYÊN MỤC SẢN PHẨM CHỦ LỰC (BỐ CỤC KHỐI ĐƠN GIẢN DỄ LÀM LẠI TRÊN UX BUILDER)
    ====================================================================== -->
    <section id="nhom-nganh-hang" class="py-6 space-y-8">
      <div class="max-w-7xl mx-auto px-3 sm:px-6 space-y-8" id="category-sections-container">
        <!-- Các khối danh mục theo mẫu trangtuphuong.com.vn + Fanpage Thiên Quý -->
      </div>
    </section>

    <!-- =====================================================================
         7. HÌNH ẢNH THỰC TẾ TẠI KHO & CỬA HÀNG THIÊN QUÝ (16 ẢNH GOOGLE DRIVE)
    ====================================================================== -->
    <section id="hinh-anh-thuc-te" class="py-6 sm:py-8">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
          <div class="section-title-container">
            <div class="section-title-main">
              <h2 class="text-base sm:text-xl font-extrabold text-flatsome-primary uppercase tracking-tight flex items-center gap-2">
                <i class="fa-solid fa-camera text-flatsome-secondary"></i>
                HÌNH ẢNH VẬT TƯ & THIẾT BỊ THỰC TẾ TẠI THIÊN QUÝ
              </h2>
              <span class="text-xs text-slate-500 hidden sm:inline">100% hình chụp thực tế tại kho 258 Trần Cao Vân</span>
            </div>
          </div>

          <div id="real-gallery-grid" class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
            <!-- 16 ảnh thực tế từ Google Drive -->
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         8. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KIẾN THỨC KỸ THUẬT)
    ====================================================================== -->
    <section id="tin-tuc-ky-thuat" class="py-6 sm:py-8 w-full">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
          
          <div class="section-title-container">
            <div class="section-title-main">
              <h2 class="text-sm sm:text-xl font-extrabold text-flatsome-primary uppercase tracking-tight flex items-center gap-2 min-w-0">
                <i class="fa-solid fa-newspaper text-flatsome-secondary shrink-0"></i>
                <span class="truncate">DANH MỤC BÀI VIẾT & TƯ VẤN KỸ THUẬT</span>
              </h2>
            </div>
            <!-- Tab Danh Mục Bài Viết tự động xuống dòng gọn gàng trên mobile -->
            <div id="blog-category-tabs" class="flex flex-wrap items-center gap-1.5 pt-3 w-full">
              <button type="button" onclick="filterBlogPosts('all')" data-blog-cat="all" class="blog-tab-btn px-3 py-1.5 rounded-lg text-xs font-bold bg-flatsome-primary text-white transition">
                Tất cả bài viết
              </button>
              <button type="button" onclick="filterBlogPosts('vong-bi')" data-blog-cat="vong-bi" class="blog-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition">
                Vòng bi SKF - Nachi - Koyo
              </button>
              <button type="button" onclick="filterBlogPosts('ban-dan')" data-blog-cat="ban-dan" class="blog-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition">
                Linh kiện IGBT & Điện
              </button>
              <button type="button" onclick="filterBlogPosts('dung-cu')" data-blog-cat="dung-cu" class="blog-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition">
                Dụng cụ cầm tay & Máy cơ khí
              </button>
            </div>
          </div>

          <!-- Lưới Bài Viết: Chia 2 cột trên điện thoại (grid-cols-2) và 4 cột trên máy tính -->
          <div id="blog-posts-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-5 w-full">
            <!-- Render tự động các bài viết kỹ thuật kèm ảnh thực tế -->
          </div>

        </div>
      </div>
    </section>

    <!-- =====================================================================
         9. FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ
    ====================================================================== -->
    <section id="form-bao-gia" class="py-6 sm:py-8">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="grid grid-cols-1 lg:grid-cols-12">
            
            <!-- Cột thông tin hỗ trợ báo giá -->
            <div class="lg:col-span-5 bg-flatsome-primary text-white p-6 sm:p-8 flex flex-col justify-between">
              <div>
                <p class="text-amber-400 text-xs font-bold uppercase tracking-widest mb-2">
                  PHÒNG KINH DOANH & KỸ THUẬT THIÊN QUÝ
                </p>
                <h2 class="text-xl sm:text-2xl font-extrabold mb-3 leading-snug">
                  GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ VẬT TƯ NHANH
                </h2>
                <p class="text-xs sm:text-sm text-blue-100 leading-relaxed mb-6">
                  Quý khách hàng, nhà thầu, xưởng cơ khí cần báo giá số lượng lớn các mặt hàng vòng bi, linh kiện IGBT, đá mài, đá cắt, dụng cụ cầm tay, bulong ốc vít... vui lòng điền thông tin. Chúng tôi phản hồi báo giá trong vòng 15 phút!
                </p>

                <div class="space-y-4 text-xs sm:text-sm">
                  <div class="flex items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center shrink-0 text-amber-400">
                      <i class="fa-solid fa-phone-volume"></i>
                    </div>
                    <div>
                      <div class="text-blue-200 text-xs">Hotline / Zalo báo giá trực tiếp:</div>
                      <a href="tel:0978102434" class="text-base sm:text-lg font-extrabold text-white hover:text-amber-300">0978.102.434</a>
                    </div>
                  </div>

                  <div class="flex items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center shrink-0 text-amber-400">
                      <i class="fa-solid fa-location-dot"></i>
                    </div>
                    <div>
                      <div class="text-blue-200 text-xs">Địa chỉ trụ sở & kho hàng:</div>
                      <div class="font-semibold">258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</div>
                    </div>
                  </div>

                  <div class="flex items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center shrink-0 text-amber-400">
                      <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div>
                      <div class="text-blue-200 text-xs">Email tiếp nhận đơn hàng:</div>
                      <div class="font-semibold">thienquytm@gmail.com</div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="mt-6 pt-5 border-t border-blue-800 flex items-center justify-between text-xs text-blue-200">
                <span>Mã số thuế: <strong class="text-white">4001249332</strong></span>
                <span>Website: <strong class="text-white">thienquy.net</strong></span>
              </div>
            </div>

            <!-- Cột Form nhập thông tin báo giá -->
            <div class="lg:col-span-7 p-5 sm:p-8">
              <form id="quote-request-form" class="space-y-4" onsubmit="submitQuoteForm(event)">
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div>
                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">
                      Họ và tên / Đơn vị <span class="text-red-600">*</span>
                    </label>
                    <input 
                      type="text" 
                      id="quote-name" 
                      required 
                      placeholder="Nhập họ tên hoặc tên công ty..."
                      class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-flatsome-primary"
                    >
                  </div>
                  <div>
                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">
                      Số điện thoại / Zalo <span class="text-red-600">*</span>
                    </label>
                    <input 
                      type="tel" 
                      id="quote-phone" 
                      required 
                      placeholder="Ví dụ: 0978102434"
                      class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-flatsome-primary"
                    >
                  </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div>
                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">
                      Danh mục vật tư quan tâm
                    </label>
                    <select 
                      id="quote-category"
                      class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-flatsome-primary bg-white"
                    >
                      <option value="Vòng bi công nghiệp (SKF, Nachi, Koyo, NSK)">Vòng bi công nghiệp (SKF, Nachi, Koyo, NSK)</option>
                      <option value="Linh kiện bán dẫn IGBT / Thiết bị điện">Linh kiện bán dẫn IGBT / Thiết bị điện</option>
                      <option value="Dụng cụ đồ nghề & Dụng cụ cầm tay">Dụng cụ đồ nghề & Dụng cụ cầm tay</option>
                      <option value="Máy hàn, Rùa cắt, Máy cắt Plasma">Máy hàn, Rùa cắt, Máy cắt Plasma</option>
                      <option value="Ty ren, Bulong, Đai ốc & Phụ kiện">Ty ren, Bulong, Đai ốc & Phụ kiện</option>
                      <option value="Đá cắt, Đá mài, Que hàn, Nhám xếp">Đá cắt, Đá mài, Que hàn, Nhám xếp</option>
                      <option value="Mũi khoan, Mũi đục, Lưỡi cắt bê tông">Mũi khoan, Mũi đục, Lưỡi cắt bê tông</option>
                      <option value="Bánh xe đẩy, Coppha, Thiết bị nâng hạ">Bánh xe đẩy, Coppha, Thiết bị nâng hạ</option>
                      <option value="Báo giá tổng hợp theo danh mục đính kèm">Báo giá tổng hợp nhiều hạng mục</option>
                    </select>
                  </div>
                  <div>
                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">
                      Địa chỉ nhận hàng /Email
                    </label>
                    <input 
                      type="text" 
                      id="quote-address" 
                      placeholder="Nhập địa chỉ giao hàng hoặc Email..."
                      class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-flatsome-primary"
                    >
                  </div>
                </div>

                <div>
                  <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">
                    Nội dung chi tiết / Mã sản phẩm & Số lượng cần báo giá <span class="text-red-600">*</span>
                  </label>
                  <textarea 
                    id="quote-message" 
                    rows="3" 
                    required
                    placeholder="Ví dụ: Báo giá 10 vòng bi SKF 6205, 5 mô đun IGBT ESM200SH60FA, 50 viên đá cắt Inox 100..."
                    class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-flatsome-primary"
                  ></textarea>
                </div>

                <div id="quote-feedback" class="hidden p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>

                <div class="flex flex-wrap items-center gap-3 pt-1">
                  <button 
                    type="submit" 
                    class="px-6 py-3 rounded-lg bg-flatsome-secondary hover:bg-orange-700 text-white font-bold text-sm transition shadow flex items-center gap-2"
                  >
                    <i class="fa-solid fa-paper-plane"></i>
                    <span>GỬI YÊU CẦU BÁO GIÁ</span>
                  </button>
                  <a 
                    href="https://zalo.me/0978102434" 
                    target="_blank" 
                    rel="noopener"
                    class="px-5 py-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-sm transition flex items-center gap-2"
                  >
                    <i class="fa-solid fa-comment-dots"></i>
                    <span>Gửi Nhanh Qua Zalo 0978.102.434</span>
                  </a>
                </div>
              </form>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         10. ĐƯA GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
    ====================================================================== -->
    <section id="ban-do-fanpage" class="py-6 sm:py-8">
      <div class="max-w-7xl mx-auto px-3 sm:px-6">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
          
          <!-- CỘT 1 (7/12): BẢN ĐỒ GOOGLE MAPS TRỰC TIẾP TRÊN TRANG CHỦ -->
          <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm flex flex-col justify-between">
            <div>
              <div class="section-title-container">
                <div class="section-title-main">
                  <h2 class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-tight flex items-center gap-2">
                    <i class="fa-solid fa-map-location-dot text-flatsome-secondary"></i>
                    BẢN ĐỒ ĐỊA CHỈ CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
                  </h2>
                  <a 
                    href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" 
                    target="_blank" 
                    rel="noopener"
                    class="text-xs font-bold text-white bg-flatsome-primary hover:bg-blue-900 px-3 py-1.5 rounded-lg transition flex items-center gap-1.5 shrink-0"
                  >
                    <i class="fa-solid fa-diamond-turn-right"></i>
                    <span>Mở Google Maps</span>
                  </a>
                </div>
              </div>

              <div class="mb-3 flex flex-wrap items-center justify-between gap-2 text-xs sm:text-sm text-slate-600 bg-slate-50 p-3 rounded-lg border border-slate-200">
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-location-dot text-red-600 text-base"></i>
                  <span><strong>Địa chỉ:</strong> 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</span>
                </div>
                <a href="tel:0978102434" class="font-bold text-flatsome-primary hover:underline">
                  <i class="fa-solid fa-phone mr-1"></i>0978.102.434
                </a>
              </div>

              <!-- Khung Google Maps trực quan ngoài trang chủ -->
              <div class="relative w-full h-[300px] sm:h-[340px] rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                <iframe 
                  title="Bản đồ Công Ty TNHH Kỹ Thuật Thiên Quý - 258 Trần Cao Vân"
                  src="https://maps.google.com/maps?q=258%20Tr%E1%BA%A7n%20Cao%20V%C3%A2n,%20Tam%20K%E1%BB%B3&t=&z=16&ie=UTF8&iwloc=&output=embed"
                  class="w-full h-full border-0"
                  allowfullscreen="" 
                  loading="lazy" 
                  referrerpolicy="no-referrer-when-downgrade">
                </iframe>
              </div>
            </div>

            <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-500">
              <span>Bấm vào nút bên phải để dẫn đường trực tiếp trên ứng dụng Google Maps</span>
              <a 
                href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" 
                target="_blank" 
                rel="noopener"
                class="font-bold text-flatsome-secondary hover:underline flex items-center gap-1"
              >
                <span>Xem vị trí trên Google Maps</span>
                <i class="fa-solid fa-arrow-up-right-from-square"></i>
              </a>
            </div>
          </div>

          <!-- CỘT 2 (5/12): ĐƯA FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ -->
          <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm flex flex-col justify-between min-w-0 overflow-hidden">
            <div>
              <div class="section-title-container">
                <div class="section-title-main">
                  <h2 class="text-sm sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-tight flex items-center gap-2 min-w-0">
                    <i class="fa-brands fa-facebook text-blue-600 shrink-0"></i>
                    <span class="truncate">FANPAGE FACEBOOK THIÊN QUÝ</span>
                  </h2>
                  <a 
                    href="https://www.facebook.com/ctthienquy" 
                    target="_blank" 
                    rel="noopener"
                    class="text-xs font-bold text-blue-600 hover:underline flex items-center gap-1 shrink-0"
                  >
                    <span>Theo dõi</span>
                    <i class="fa-solid fa-arrow-up-right-from-square"></i>
                  </a>
                </div>
              </div>

              <!-- Thẻ nhận diện Fanpage chính thức kèm ảnh thực tế + Nhúng Facebook Page Plugin -->
              <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 mb-3 w-full">
                <div class="relative h-28 bg-slate-900">
                  <img 
                    src="https://lh3.googleusercontent.com/d/17Og6NDOXnrYWgR68UU0NOY-q6JpbdtgD=w800" 
                    data-drive-id="17Og6NDOXnrYWgR68UU0NOY-q6JpbdtgD"
                    alt="Ảnh bìa Fanpage Công Ty Kỹ Thuật Thiên Quý" 
                    class="w-full h-full object-cover opacity-80"
                    onerror="handleDriveImgError(this)">
                  <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                  <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0">
                      <img 
                        src="https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl=w300" 
                        data-drive-id="1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl"
                        alt="Logo Thiên Quý" 
                        class="w-full h-full object-contain"
                        onerror="handleDriveImgError(this)">
                    </div>
                    <div class="text-white min-w-0">
                      <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener" class="font-bold text-sm hover:underline block truncate">
                        CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
                      </a>
                      <div class="text-[11px] text-slate-200 truncate">@ctthienquy • Thiết bị cơ khí & Vật tư công nghiệp</div>
                    </div>
                  </div>
                </div>

                <!-- Nhúng Iframe Fanpage Facebook chuẩn không tràn màn hình nhỏ -->
                <div class="p-2 flex justify-center bg-white w-full overflow-hidden">
                  <iframe 
                    title="Fanpage Facebook Công Ty TNHH Kỹ Thuật Thiên Quý"
                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fctthienquy&tabs=timeline&width=300&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                    width="300" 
                    height="210" 
                    style="border:none;overflow:hidden;width:100%;max-width:300px;" 
                    scrolling="no" 
                    frameborder="0" 
                    allowfullscreen="true" 
                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                  </iframe>
                </div>
              </div>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-2 pt-2 border-t border-slate-100">
              <a 
                href="https://www.facebook.com/ctthienquy" 
                target="_blank" 
                rel="noopener"
                class="w-full py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs sm:text-sm flex items-center justify-center gap-2 transition shadow-sm"
              >
                <i class="fa-brands fa-facebook-messenger text-base"></i>
                <span>Nhắn Tin Trực Tiếp Trên Fanpage Thiên Quý</span>
              </a>
            </div>
          </div>

        </div>
      </div>
    </section>
  </main>

  <!-- =====================================================================
       11. FOOTER CHUẨN FLATSOME
  ====================================================================== -->
  <footer id="footer" class="bg-slate-900 text-slate-300 pt-10 pb-20 md:pb-8 border-t-4 border-flatsome-secondary">
    <div class="max-w-7xl mx-auto px-3 sm:px-6">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-slate-800">
        
        <!-- Thông tin công ty -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <div class="logo-frame w-14 h-14 bg-white shrink-0">
              <img 
                src="https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl=w300" 
                data-drive-id="1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl"
                alt="Logo Công Ty TNHH Kỹ Thuật Thiên Quý" 
                class="logo-enhanced w-full h-full"
                onerror="handleDriveImgError(this)">
            </div>
            <div>
              <h3 class="text-white font-extrabold text-base sm:text-lg leading-snug">
                CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
              </h3>
              <p class="text-amber-400 text-xs font-bold">Website: thienquy.net | MST: 4001249332</p>
            </div>
          </div>
          <p class="text-xs sm:text-sm text-slate-400 leading-relaxed">
            Chuyên cung cấp sỉ & lẻ vòng bi công nghiệp (SKF, Nachi, Koyo, NSK), mô đun bán dẫn IGBT, máy hàn, máy cắt plasma, dụng cụ đồ nghề, dụng cụ cầm tay, bulong đai ốc, đá mài đá cắt và phụ kiện công trình uy tín.
          </p>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
              <span><strong>Địa chỉ:</strong> 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-amber-400"></i>
              <span><strong>Điện thoại / Zalo:</strong> <a href="tel:0978102434" class="text-white font-bold hover:text-amber-400">0978.102.434</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-envelope text-amber-400"></i>
              <span><strong>Email:</strong> <a href="mailto:thienquytm@gmail.com" class="hover:text-white">thienquytm@gmail.com</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-amber-400"></i>
              <span><strong>Website:</strong> <a href="https://thienquy.net" class="hover:text-white">https://thienquy.net</a></span>
            </li>
          </ul>
        </div>

        <!-- Danh mục sản phẩm chính -->
        <div class="lg:col-span-4">
          <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 border-b border-slate-800 pb-2">
            DANH MỤC SẢN PHẨM CHỦ LỰC
          </h4>
          <ul class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs sm:text-sm">
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('vong-bi')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Vòng bi SKF, Nachi, Koyo</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('ban-dan-dien')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Linh kiện IGBT & Điện</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('dung-cu-do-nghe')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Dụng cụ đồ nghề</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('dung-cu-cam-tay')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Dụng cụ cầm tay</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('may-han-cat')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Máy hàn, Máy cắt Plasma</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('ty-ren-bulong')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Ty ren, Bulong, Đai ốc</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('da-cat-da-mai')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Đá cắt, Đá mài, Que hàn</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('mui-khoan-luoi-cat')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Mũi khoan, Lưỡi cắt</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('nham-xep-danh-ri')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Nhám xếp, Chổi đánh rỉ</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProductsByCategory('coppha-banh-xe')" class="hover:text-amber-400 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-xs text-slate-500"></i> Bánh xe đẩy, Coppha</a></li>
          </ul>
        </div>

        <!-- Chính sách khách hàng & Liên kết nhanh -->
        <div class="lg:col-span-3">
          <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 border-b border-slate-800 pb-2">
            HỖ TRỢ KHÁCH HÀNG
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm mb-4">
            <li><a href="#form-bao-gia" class="hover:text-amber-400">Chính sách báo giá sỉ & đại lý</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-400">Chính sách giao hàng toàn quốc</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-400">Chính sách bảo hành chính hãng</a></li>
            <li><a href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" target="_blank" rel="noopener" class="hover:text-amber-400">Chỉ đường đến 258 Trần Cao Vân</a></li>
          </ul>
          <div class="flex items-center gap-2.5">
            <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener" class="w-9 h-9 rounded-lg bg-blue-600 hover:bg-blue-500 text-white flex items-center justify-center transition" title="Facebook Fanpage">
              <i class="fa-brands fa-facebook-f"></i>
            </a>
            <a href="https://zalo.me/0978102434" target="_blank" rel="noopener" class="w-9 h-9 rounded-lg bg-sky-500 hover:bg-sky-400 text-white flex items-center justify-center font-bold text-xs transition" title="Zalo 0978.102.434">
              Zalo
            </a>
            <a href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" target="_blank" rel="noopener" class="w-9 h-9 rounded-lg bg-emerald-600 hover:bg-emerald-500 text-white flex items-center justify-center transition" title="Google Maps">
              <i class="fa-solid fa-location-dot"></i>
            </a>
          </div>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright © 2026 <strong>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (thienquy.net)</strong>. All rights reserved.</div>
        <div>Thiết kế theo cấu trúc chuẩn Flatsome UX Builder.</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       12. MENU DANH MỤC TRƯỢT TRÊN ĐIỆN THOẠI (OFF-CANVAS MOBILE MENU)
  ====================================================================== -->
  <div id="mobile-drawer-backdrop" class="fixed inset-0 bg-black/60 z-50 hidden transition-opacity"></div>
  <aside id="mobile-drawer" class="fixed top-0 left-0 bottom-0 w-80 max-w-[85vw] bg-white z-50 -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
    <div class="p-4 bg-flatsome-primary text-white flex items-center justify-between">
      <div class="flex items-center gap-2.5">
        <div class="w-9 h-9 rounded bg-white p-1 shrink-0">
          <img 
            src="https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl=w200" 
            data-drive-id="1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl"
            alt="Logo Thiên Quý" 
            class="w-full h-full object-contain"
            onerror="handleDriveImgError(this)">
        </div>
        <div>
          <div class="font-bold text-xs uppercase">KỸ THUẬT THIÊN QUÝ</div>
          <div class="text-[11px] text-amber-300">thienquy.net</div>
        </div>
      </div>
      <button id="close-mobile-menu" type="button" class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-white">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>

    <div class="p-3 bg-slate-100 text-xs font-bold text-slate-700 uppercase tracking-wider border-b border-slate-200">
      Danh Mục Sản Phẩm
    </div>

    <div class="flex-1 overflow-y-auto divide-y divide-slate-100" id="mobile-category-list">
      <!-- Danh mục trên điện thoại -->
    </div>

    <div class="p-4 bg-slate-50 border-t border-slate-200 space-y-2 text-xs">
      <div class="font-bold text-slate-700">258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</div>
      <div class="flex gap-2">
        <a href="tel:0978102434" class="flex-1 py-2 bg-red-600 text-white text-center font-bold rounded-lg">
          <i class="fa-solid fa-phone mr-1"></i> 0978.102.434
        </a>
        <a href="https://zalo.me/0978102434" target="_blank" rel="noopener" class="flex-1 py-2 bg-blue-600 text-white text-center font-bold rounded-lg">
          Chat Zalo
        </a>
      </div>
    </div>
  </aside>

  <!-- =====================================================================
       13. MODAL XEM NHANH SẢN PHẨM (FLATSOME QUICK VIEW LIGHTBOX)
  ====================================================================== -->
  <div id="quick-view-modal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3 sm:p-6 overflow-y-auto">
    <div class="bg-white rounded-xl max-w-3xl w-full overflow-hidden shadow-2xl border border-slate-200 relative my-auto">
      <button 
        type="button" 
        onclick="closeQuickView()" 
        class="absolute top-3 right-3 z-20 w-9 h-9 rounded-full bg-slate-100 hover:bg-red-600 hover:text-white text-slate-700 flex items-center justify-center transition"
        aria-label="Đóng xem nhanh">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>

      <div class="grid grid-cols-1 md:grid-cols-2">
        <!-- Cột ảnh sản phẩm -->
        <div class="relative bg-slate-100 p-4 flex items-center justify-center min-h-[260px] sm:min-h-[340px]">
          <div id="qv-discount-badge" class="flatsome-onsale">-15%</div>
          <img id="qv-image" src="" alt="Ảnh sản phẩm" class="max-h-[300px] w-auto object-contain rounded-lg">
        </div>

        <!-- Cột thông tin chi tiết chuẩn Flatsome -->
        <div class="p-5 sm:p-6 flex flex-col justify-between">
          <div>
            <div id="qv-category" class="text-xs font-bold text-flatsome-secondary uppercase tracking-wider mb-1"></div>
            <h3 id="qv-title" class="text-lg sm:text-xl font-extrabold text-slate-800 leading-snug mb-2"></h3>
            <div class="w-10 h-1 bg-slate-200 mb-3"></div>

            <!-- Giá giảm giá & Giá gốc -->
            <div class="flex items-baseline gap-2.5 mb-4">
              <del id="qv-old-price" class="text-sm text-slate-400 font-medium"></del>
              <ins id="qv-new-price" class="text-xl sm:text-2xl font-extrabold text-flatsome-red no-underline"></ins>
            </div>

            <p id="qv-desc" class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4"></p>

            <div class="bg-slate-50 p-3 rounded-lg border border-slate-200 text-xs space-y-1.5 text-slate-700 mb-5">
              <div><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> <strong>Đơn vị cung cấp:</strong> CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ</div>
              <div><i class="fa-solid fa-location-dot text-flatsome-primary mr-1.5"></i> <strong>Kho hàng:</strong> 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</div>
              <div><i class="fa-solid fa-shield-halved text-flatsome-secondary mr-1.5"></i> <strong>Cam kết:</strong> Hàng chuẩn thông số kỹ thuật, giao nhanh toàn quốc</div>
            </div>
          </div>

          <div class="space-y-2.5">
            <div class="flex flex-col sm:flex-row gap-2">
              <button 
                type="button" 
                id="qv-quote-btn"
                class="flex-1 py-2.5 px-4 rounded-lg bg-flatsome-secondary hover:bg-orange-700 text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition flex items-center justify-center gap-2"
              >
                <i class="fa-solid fa-file-signature"></i>
                <span>Đưa Vào Form Báo Giá</span>
              </button>
              <a 
                href="https://zalo.me/0978102434" 
                target="_blank" 
                rel="noopener"
                class="flex-1 py-2.5 px-4 rounded-lg bg-flatsome-primary hover:bg-blue-900 text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition flex items-center justify-center gap-2"
              >
                <i class="fa-solid fa-comment-dots"></i>
                <span>Mua Qua Zalo</span>
              </a>
            </div>
            <a 
              href="tel:0978102434" 
              class="w-full py-2 px-4 rounded-lg border border-slate-300 hover:bg-slate-100 text-slate-700 font-bold text-xs flex items-center justify-center gap-2 transition"
            >
              <i class="fa-solid fa-phone text-red-600"></i>
              <span>Tư vấn kỹ thuật: 0978.102.434</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       14. MODAL XEM CHI TIẾT BÀI VIẾT KỸ THUẬT
  ====================================================================== -->
  <div id="blog-reader-modal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3 sm:p-6 overflow-y-auto">
    <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200 relative my-auto">
      <div class="p-4 sm:p-5 bg-flatsome-primary text-white flex items-center justify-between">
        <span id="bm-category" class="text-xs font-bold uppercase tracking-wider text-amber-300">Chuyên mục kỹ thuật</span>
        <button type="button" onclick="closeBlogModal()" class="w-8 h-8 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center text-white">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-5 sm:p-6 max-h-[80vh] overflow-y-auto space-y-4">
        <h3 id="bm-title" class="text-lg sm:text-xl font-extrabold text-slate-800"></h3>
        <img id="bm-image" src="" alt="Ảnh bài viết" class="w-full h-56 object-cover rounded-lg border border-slate-200">
        <div id="bm-content" class="text-sm text-slate-700 leading-relaxed space-y-3"></div>
        <div class="p-4 rounded-lg bg-blue-50 border border-blue-200 text-xs sm:text-sm text-slate-700">
          <strong>Liên hệ tư vấn & đặt hàng tại CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ:</strong><br>
          Địa chỉ: 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng | Hotline/Zalo: <a href="tel:0978102434" class="font-bold text-red-600">0978.102.434</a>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       15. CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
       (Trên điện thoại tự thu gọn thành nút tròn tinh tế không che nội dung)
  ====================================================================== -->
  <div class="fixed bottom-4 right-2.5 sm:right-5 z-40 flex flex-col items-end gap-2.5 sm:gap-3">
    
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/ctthienquy" 
      target="_blank" 
      rel="noopener"
      class="group flex items-center justify-center sm:justify-start gap-2.5 bg-[#1877F2] text-white w-11 h-11 sm:w-auto sm:h-auto sm:pl-3.5 sm:pr-4 sm:py-2.5 rounded-full shadow-lg hover:scale-105 transition"
      title="Fanpage Công Ty Kỹ Thuật Thiên Quý"
    >
      <span class="relative w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold tracking-wide">Facebook</span>
    </a>

    <!-- Nút Chat Zalo Nổi Bật -->
    <a 
      href="https://zalo.me/0978102434" 
      target="_blank" 
      rel="noopener"
      class="group flex items-center justify-center sm:justify-start gap-2.5 bg-[#0068FF] text-white w-11 h-11 sm:w-auto sm:h-auto sm:pl-3.5 sm:pr-4 sm:py-2.5 rounded-full shadow-lg hover:scale-105 transition"
      title="Chat Zalo 0978.102.434"
    >
      <span class="relative w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[10px] shrink-0 floating-btn-ring">
        Zalo
      </span>
      <span class="hidden sm:inline text-xs font-bold tracking-wide">Zalo: 0978.102.434</span>
    </a>

    <!-- Nút Gọi Hotline Nổi Bật -->
    <a 
      href="tel:0978102434" 
      class="group flex items-center justify-center sm:justify-start gap-2.5 bg-red-600 text-white w-11 h-11 sm:w-auto sm:h-auto sm:pl-3.5 sm:pr-4 sm:py-2.5 rounded-full shadow-xl hover:bg-red-700 hover:scale-105 transition"
      title="Gọi Hotline 0978.102.434"
    >
      <span class="relative w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0 floating-btn-ring">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <div class="hidden sm:block leading-tight">
        <div class="text-[10px] text-red-100 font-medium">Hotline 24/7</div>
        <div class="text-xs font-extrabold tracking-wide">0978.102.434</div>
      </div>
    </a>

  </div>

  <!-- =====================================================================
       16. JAVASCRIPT XỬ LÝ DỮ LIỆU THỰC TẾ, SLIDER, XEM NHANH, TÌM KIẾM
  ====================================================================== -->
  <script>
    /* ---------------------------------------------------------------------
       Hàm tự động chuyển đổi link dự phòng cho ảnh Google Drive
       Đảm bảo chỉ dùng đúng 16 ảnh thực tế + 1 logo từ Google Drive của khách
    ---------------------------------------------------------------------- */
    function handleDriveImgError(imgEl) {
      const driveId = imgEl.getAttribute('data-drive-id');
      if (!driveId) return;
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
      } else if (step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
      }
    }

    function getDriveUrl(id, width = 800) {
      return `https://lh3.googleusercontent.com/d/${id}=w${width}`;
    }

    /* ---------------------------------------------------------------------
       Danh sách 16 File ID ảnh thực tế trong Google Drive người dùng cung cấp
    ---------------------------------------------------------------------- */
    const DRIVE_IMAGE_IDS = [
      '1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m', // 1
      '1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N', // 2
      '17Og6NDOXnrYWgR68UU0NOY-q6JpbdtgD', // 3
      '1uj0yENXnY0WE8aWyT-Wx9LZFddvmCGQx', // 4
      '1DjIRF9GbXvPzqhLASIkc65g_25l1Yh7Q', // 5
      '18iRse5KupLoIllKmpLt0ON3QlUSLAxuc', // 6
      '1VSKFmUEiiYZYaqixWRtRQJJndSgmZ2VZ', // 7
      '1q5QWr9EaK6tLB8CX7UthGZSguBpdCdrz', // 8
      '1HwjU6a4rEHSnW_i5KgAf8rEd_bzHgEpL', // 9
      '1N7ZouNs_zi40NPsfoZ2A2juIy3zgAYAp', // 10
      '1GXepKE86d13FhQ6qgBE7zBw214hidDYG', // 11
      '1aqW4YkymcQEjg092JNmc7JyKRqlZv2QY', // 12
      '1bfBtK7uR9Mt9sJoJCHVkrPSebdF-sNUL', // 13
      '167K9BLAJbX0N0JdqFDGT9epQ_83P-OH_', // 14
      '1OuSlLHE7UF2lr-y-JIxyJ53PbGtu-yHn', // 15
      '1kErVKOWfq5UhE2F56T2VaXVg6Ve8qmOO'  // 16
    ];

    /* ---------------------------------------------------------------------
       Danh mục sản phẩm kết hợp từ web mẫu trangtuphuong.com.vn & Fanpage Thiên Quý
    ---------------------------------------------------------------------- */
    const CATEGORIES = [
      {
        id: 'vong-bi',
        name: 'Vòng Bi Công Nghiệp (SKF, Nachi, Koyo, NSK)',
        shortName: 'Vòng Bi - Bạc Đạn',
        icon: 'fa-solid fa-gear',
        driveId: DRIVE_IMAGE_IDS[2],
        subItems: ['Vòng bi SKF', 'Vòng bi Nachi', 'Vòng bi Koyo - NSK', 'Gối đỡ vòng bi']
      },
      {
        id: 'ban-dan-dien',
        name: 'Linh Kiện Bán Dẫn IGBT & Thiết Bị Điện',
        shortName: 'Linh Kiện IGBT & Điện',
        icon: 'fa-solid fa-microchip',
        driveId: DRIVE_IMAGE_IDS[3],
        subItems: ['Mô đun công suất IGBT', 'Khởi động từ - Aptomat', 'Biến tần & Nguồn', 'Phụ kiện tủ điện']
      },
      {
        id: 'dung-cu-do-nghe',
        name: 'Dụng Cụ Đồ Nghề (Asaki, Harkcaput, Tủ Đồ Nghề)',
        shortName: 'Dụng Cụ Đồ Nghề',
        icon: 'fa-solid fa-wrench',
        driveId: DRIVE_IMAGE_IDS[4],
        subItems: ['Bộ dụng cụ sửa chữa', 'Kìm cắt - Kìm bấm cos', 'Cờ lê - Mỏ lết - Tuýp', 'Súng xịt hơi']
      },
      {
        id: 'dung-cu-cam-tay',
        name: 'Dụng Cụ Cầm Tay (Bosch, Makita, Hitachi, Ken)',
        shortName: 'Dụng Cụ Cầm Tay',
        icon: 'fa-solid fa-screwdriver-wrench',
        driveId: DRIVE_IMAGE_IDS[5],
        subItems: ['Máy mài góc cầm tay', 'Máy khoan búa - Khoan pin', 'Máy cắt sắt bàn', 'Máy khoan rút lõi bê tông']
      },
      {
        id: 'may-han-cat',
        name: 'Máy Hàn, Rùa Cắt, Máy Cắt Plasma',
        shortName: 'Máy Hàn & Cắt Plasma',
        icon: 'fa-solid fa-fire-flame-curved',
        driveId: DRIVE_IMAGE_IDS[6],
        subItems: ['Máy hàn que điện tử', 'Máy hàn MIG / TIG', 'Máy cắt Plasma IGBT', 'Rùa cắt xách tay']
      },
      {
        id: 'ty-ren-bulong',
        name: 'Ty Ren, Bulong, Đai Ốc, Ubolt & Lưới Xây Dựng',
        shortName: 'Ty Ren & Bulong Ốc Vít',
        icon: 'fa-solid fa-bolt',
        driveId: DRIVE_IMAGE_IDS[7],
        subItems: ['Ty ren & Bát chuồn', 'Đai treo ống - Kẹp treo', 'Bulong - Đai ốc Inox/Thép', 'Lưới xây dựng - Lưới bao che']
      },
      {
        id: 'da-cat-da-mai',
        name: 'Đá Cắt, Đá Mài, Que Hàn Điện Công Nghiệp',
        shortName: 'Đá Cắt, Đá Mài, Que Hàn',
        icon: 'fa-solid fa-compact-disc',
        driveId: DRIVE_IMAGE_IDS[8],
        subItems: ['Đá cắt sắt - Đá cắt Inox', 'Đá mài Nhật NRT / Arba', 'Que hàn chịu lực', 'Phụ kiện hàn cắt']
      },
      {
        id: 'mui-khoan-luoi-cat',
        name: 'Mũi Khoan, Mũi Đục, Lưỡi Cắt Bê Tông & Gỗ',
        shortName: 'Mũi Khoan & Lưỡi Cắt',
        icon: 'fa-solid fa-circle-dot',
        driveId: DRIVE_IMAGE_IDS[9],
        subItems: ['Mũi khoan bê tông - Inox', 'Mũi khoan Nachi thép gió', 'Lưỡi cắt bê tông - Đá Granite', 'Lưỡi cắt gạch - Lưỡi cắt gỗ']
      },
      {
        id: 'nham-xep-danh-ri',
        name: 'Nhám Xếp, Giấy Nhám, Chổi Đánh Rỉ, Nỉ Đánh Bóng',
        shortName: 'Nhám Xếp & Đánh Bóng',
        icon: 'fa-solid fa-fan',
        driveId: DRIVE_IMAGE_IDS[10],
        subItems: ['Nhám xếp (Flap Disc)', 'Chổi đánh rỉ sắt/đồng', 'Nỉ trắng lông cừu - Xơ dừa', 'Sáp đánh bóng kim loại']
      },
      {
        id: 'coppha-banh-xe',
        name: 'Coppha Dàn Giáo, Bánh Xe Đẩy, Thang Nhôm & Cáp Nâng Hạ',
        shortName: 'Bánh Xe, Coppha & Nâng Hạ',
        icon: 'fa-solid fa-dolly',
        driveId: DRIVE_IMAGE_IDS[11],
        subItems: ['Bánh xe đẩy công nghiệp', 'Cùm xoay - Kích tăng dàn giáo', 'Kệ đa năng - Thang nhôm chữ A', 'Dây cáp thép - Xích - Palang']
      }
    ];

    /* ---------------------------------------------------------------------
       16 Sản phẩm thực tế tương ứng với 16 ảnh từ Google Drive
       Có đầy đủ Giá gốc, Giá khuyến mãi và % Giảm giá chuẩn Flatsome
    ---------------------------------------------------------------------- */
    const PRODUCTS = [
      {
        id: 1,
        name: 'Vòng Bi Công Nghiệp SKF Chính Hãng (Đầy Đủ Mã 6204, 6205, 6308, UCFL)',
        category: 'vong-bi',
        categoryName: 'Vòng Bi - Bạc Đạn',
        driveId: DRIVE_IMAGE_IDS[0],
        oldPrice: 220000,
        newPrice: 175000,
        discount: 20,
        desc: 'Vòng bi cầu & vòng bi đũa SKF chính hãng chịu tải cao, tốc độ vòng quay ổn định, chuyên dùng cho động cơ điện và dây chuyền máy công nghiệp tại Thiên Quý.'
      },
      {
        id: 2,
        name: 'Vòng Bi Bạc Đạn Nachi / Koyo / NSK Nhật Bản Chịu Nhiệt Độ Cao',
        category: 'vong-bi',
        categoryName: 'Vòng Bi - Bạc Đạn',
        driveId: DRIVE_IMAGE_IDS[1],
        oldPrice: 185000,
        newPrice: 150000,
        discount: 19,
        desc: 'Dòng vòng bi Nachi, Koyo, NSK nhập khẩu chính ngạch, phớt chắn bụi kín khít, độ bền vượt trội cho bảo trì nhà máy cơ khí, chế biến gỗ, dệt may.'
      },
      {
        id: 3,
        name: 'Mô Đun Công Suất Bán Dẫn IGBT ESM200SH60FA 200A 600V Hàn Quốc',
        category: 'ban-dan-dien',
        categoryName: 'Linh Kiện IGBT & Điện',
        driveId: DRIVE_IMAGE_IDS[2],
        oldPrice: 1450000,
        newPrice: 1180000,
        discount: 19,
        desc: 'Linh kiện bán dẫn / Mô đun công suất IGBT ESM200SH60FA dòng 200A điện áp 600V xuất xứ Hàn Quốc, chuyên dùng cho biến tần, máy hàn công nghiệp và tủ điều khiển.'
      },
      {
        id: 4,
        name: 'Thiết Bị Đóng Cắt, Khởi Động Từ & Phụ Kiện Tủ Điện Công Nghiệp',
        category: 'ban-dan-dien',
        categoryName: 'Linh Kiện IGBT & Điện',
        driveId: DRIVE_IMAGE_IDS[3],
        oldPrice: 680000,
        newPrice: 560000,
        discount: 18,
        desc: 'Cung cấp đồng bộ aptomat MCCB/MCB, khởi động từ, rơ le nhiệt, nguồn tổ ong và phụ kiện lắp đặt tủ điện nhà xưởng công nghiệp.'
      },
      {
        id: 5,
        name: 'Bộ Dụng Cụ Đồ Nghề Sửa Chữa Đa Năng Chuyên Nghiệp Asaki / Harkcaput',
        category: 'dung-cu-do-nghe',
        categoryName: 'Dụng Cụ Đồ Nghề',
        driveId: DRIVE_IMAGE_IDS[4],
        oldPrice: 1250000,
        newPrice: 990000,
        discount: 21,
        desc: 'Bộ đồ nghề cơ khí gồm cờ lê, đầu khẩu tuýp, kìm điện, tua vít thép hợp kim Chrome Vanadium cứng cáp, chống gỉ sét.'
      },
      {
        id: 6,
        name: 'Kìm Bấm Cos, Kìm Cắt Cáp & Kìm Rút Đinh Rive Công Nghiệp Asaki',
        category: 'dung-cu-do-nghe',
        categoryName: 'Dụng Cụ Đồ Nghề',
        driveId: DRIVE_IMAGE_IDS[5],
        oldPrice: 240000,
        newPrice: 195000,
        discount: 19,
        desc: 'Kìm bấm cos 0.5~6.0mm2, kìm cắt cáp và kìm rút đinh rive cán bọc cao su chống trượt, trợ lực nhẹ nhàng cho thợ điện & cơ khí.'
      },
      {
        id: 7,
        name: 'Máy Mài Góc Cầm Tay Công Suất Lớn 1200W (Makita / Hitachi / Bosch)',
        category: 'dung-cu-cam-tay',
        categoryName: 'Dụng Cụ Cầm Tay',
        driveId: DRIVE_IMAGE_IDS[6],
        oldPrice: 1590000,
        newPrice: 1320000,
        discount: 17,
        desc: 'Máy mài góc cầm tay lõi đồng 100%, tốc độ không tải cao, vỏ cách điện an toàn, chuyên mài mối hàn và cắt kim loại cường độ cao.'
      },
      {
        id: 8,
        name: 'Máy Khoan Búa & Máy Khoan Pin Cầm Tay Đa Năng Kèm Bộ Sạc Nhanh',
        category: 'dung-cu-cam-tay',
        categoryName: 'Dụng Cụ Cầm Tay',
        driveId: DRIVE_IMAGE_IDS[7],
        oldPrice: 1890000,
        newPrice: 1550000,
        discount: 18,
        desc: 'Máy khoan búa 3 chức năng và máy khoan siết bulong dùng pin dung lượng cao, đáp ứng thi công cơ điện M&E và công trình xây dựng.'
      },
      {
        id: 9,
        name: 'Máy Hàn Điện Tử IGBT & Máy Cắt Kim Loại Công Nghệ Plasma Weldcom / Jasic',
        category: 'may-han-cat',
        categoryName: 'Máy Hàn & Cắt Plasma',
        driveId: DRIVE_IMAGE_IDS[8],
        oldPrice: 4200000,
        newPrice: 3490000,
        discount: 17,
        desc: 'Máy hàn que điện tử, máy hàn MIG và máy cắt Plasma công nghệ Inverter IGBT tiết kiệm điện, mồi hồ quang nhạy, mối hàn ngấu đẹp.'
      },
      {
        id: 10,
        name: 'Bulong Cường Độ Cao, Đai Ốc Inox, Ty Ren Suốt & Đai Treo Ống Công Trình',
        category: 'ty-ren-bulong',
        categoryName: 'Ty Ren & Bulong Ốc Vít',
        driveId: DRIVE_IMAGE_IDS[9],
        oldPrice: 95000,
        newPrice: 78000,
        discount: 18,
        desc: 'Phân phối sỉ & lẻ bulong liên kết cấp bền 8.8/10.9, bulong Inox 304, ty ren M8-M16, nở đạn, cùm Ubolt và kẹp treo ống PCCC.'
      },
      {
        id: 11,
        name: 'Đá Cắt Inox NRT 100, Đá Mài Sắt Arba 125 & Que Hàn Chịu Lực Chính Hãng',
        category: 'da-cat-da-mai',
        categoryName: 'Đá Cắt, Đá Mài, Que Hàn',
        driveId: DRIVE_IMAGE_IDS[10],
        oldPrice: 145000,
        newPrice: 115000,
        discount: 21,
        desc: 'Đá cắt sắt, đá cắt Inox siêu bén ít ba via, đá mài kim loại độ hạt chuẩn và que hàn điện chịu lực đóng hộp/thùng giá sỉ.'
      },
      {
        id: 12,
        name: 'Bộ Mũi Khoan Thép Gió Nachi, Mũi Khoan Bê Tông & Mũi Rút Lõi Tường',
        category: 'mui-khoan-luoi-cat',
        categoryName: 'Mũi Khoan & Lưỡi Cắt',
        driveId: DRIVE_IMAGE_IDS[11],
        oldPrice: 320000,
        newPrice: 265000,
        discount: 17,
        desc: 'Đầy đủ kích cỡ mũi khoan sắt/Inox Nachi, mũi khoan bê tông chuôi gài SDS Plus, mũi khoét lỗ gạch đá và mũi rút lõi điện lạnh.'
      },
      {
        id: 13,
        name: 'Lưỡi Cắt Bê Tông, Lưỡi Cắt Đá Granite, Lưỡi Cắt Gạch & Lưỡi Cưa Gỗ',
        category: 'mui-khoan-luoi-cat',
        categoryName: 'Mũi Khoan & Lưỡi Cắt',
        driveId: DRIVE_IMAGE_IDS[12],
        oldPrice: 450000,
        newPrice: 370000,
        discount: 18,
        desc: 'Lưỡi cắt kim cương chuyên xẻ đá Granite, cắt đường bê tông phi 114 - 350 - 500mm và lưỡi cưa gỗ hợp kim sắc bén.'
      },
      {
        id: 14,
        name: 'Nhám Xếp Kingdomz, Chổi Cước Đánh Rỉ Sắt & Bánh Nỉ Đánh Bóng Inox',
        category: 'nham-xep-danh-ri',
        categoryName: 'Nhám Xếp & Đánh Bóng',
        driveId: DRIVE_IMAGE_IDS[13],
        oldPrice: 180000,
        newPrice: 145000,
        discount: 19,
        desc: 'Nhám xếp độ hạt A40-A120, chổi cước thép đánh rỉ bề mặt kim loại, bánh vải, bánh xơ dừa và sáp đánh bóng Inox chuyên dụng.'
      },
      {
        id: 15,
        name: 'Bánh Xe Đẩy Công Nghiệp Chịu Tải, Xe Đẩy Hàng & Phụ Kiện Coppha Dàn Giáo',
        category: 'coppha-banh-xe',
        categoryName: 'Bánh Xe, Coppha & Nâng Hạ',
        driveId: DRIVE_IMAGE_IDS[14],
        oldPrice: 380000,
        newPrice: 310000,
        discount: 18,
        desc: 'Càng bánh xe đẩy PU/Cao su/Gang có khóa xoay 360 độ, bánh xe dàn giáo D150/D200, cùm xoay BS1139, kích tăng U và bát chuồn.'
      },
      {
        id: 16,
        name: 'Dây Cáp Thép Lụa, Xích Chịu Lực, Tăng Đơ, Ma Ní & Thiết Bị Nâng Hạ',
        category: 'coppha-banh-xe',
        categoryName: 'Bánh Xe, Coppha & Nâng Hạ',
        driveId: DRIVE_IMAGE_IDS[15],
        oldPrice: 750000,
        newPrice: 620000,
        discount: 17,
        desc: 'Dây cáp thép mạ kẽm/bọc nhựa, xích đen chịu tải, móc cẩu, ốc siết cáp, tăng đơ và palang xích phục vụ cẩu lắp nhà xưởng.'
      }
    ];

    /* ---------------------------------------------------------------------
       Danh sách bài viết trang chủ (Tin tức kỹ thuật từ Fanpage Thiên Quý & Web mẫu)
    ---------------------------------------------------------------------- */
    const BLOG_POSTS = [
      {
        id: 101,
        category: 'vong-bi',
        categoryLabel: 'Vòng Bi - Bạc Đạn',
        title: '3 Dấu Hiệu Vòng Bi Cần Thay Thế Ngay & Địa Chỉ Mua Vòng Bi SKF, Nachi, Koyo, NSK Uy Tín',
        date: '15/10/2026',
        driveId: DRIVE_IMAGE_IDS[0],
        excerpt: 'Nhận biết sớm tiếng ồn bất thường, nhiệt độ cụm ổ đỡ tăng cao và độ rung lắc trục máy giúp doanh nghiệp tránh dừng máy đột ngột...',
        content: `
          <p>Trong quá trình vận hành máy móc công nghiệp, vòng bi (bạc đạn) đóng vai trò chịu tải và giảm ma sát cho các trục quay. Dưới đây là <strong>3 dấu hiệu quan trọng</strong> cho thấy vòng bi cần được kiểm tra và thay thế kịp thời:</p>
          <p><strong>1. Tiếng ồn rít hoặc lạo xạo bất thường:</strong> Khi rãnh lăn hoặc viên bi bị rỗ, tróc bề mặt hoặc thiếu mỡ bôi trơn, ổ bi sẽ phát ra tiếng kêu lớn hơn bình thường.</p>
          <p><strong>2. Nhiệt độ cụm gối đỡ tăng cao:</strong> Nếu nhiệt độ vỏ gối đỡ vượt ngưỡng cho phép, nguyên nhân thường do quá tải, lắp lệch tâm hoặc vòng bi đã bị bó kẹt.</p>
          <p><strong>3. Độ rung động cơ & máy móc tăng mạnh:</strong> Độ rơ dọc trục/hướng kính vượt tiêu chuẩn làm trục quay mất cân bằng, ảnh hưởng trực tiếp đến phớt chắn dầu và bánh răng.</p>
          <p>Tại <strong>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng)</strong>, chúng tôi luôn sẵn kho các dòng vòng bi SKF, Nachi, Koyo, NSK chính hãng với giá chiết khấu tốt nhất cho nhà máy và thợ bảo trì.</p>
        `
      },
      {
        id: 102,
        category: 'ban-dan',
        categoryLabel: 'Linh Kiện IGBT & Điện',
        title: 'Review Chi Tiết Mô Đun Công Suất Bán Dẫn IGBT ESM200SH60FA 200A 600V Hàn Quốc',
        date: '10/10/2026',
        driveId: DRIVE_IMAGE_IDS[2],
        excerpt: 'Tìm hiểu thông số kỹ thuật, sơ đồ chân và ứng dụng thực tế của mô đun IGBT ESM200SH60FA 200A 600V trong biến tần và máy hàn công nghiệp...',
        content: `
          <p>Mô đun công suất bán dẫn <strong>IGBT ESM200SH60FA (200A - 600V)</strong> xuất xứ Hàn Quốc là linh kiện chủ lực trong các bộ nghịch lưu biến tần, bộ nguồn xung công suất lớn và máy hàn cắt công nghiệp.</p>
          <p><strong>Ưu điểm nổi bật:</strong> Điện áp bão hòa thấp giúp giảm tổn hao nhiệt, khả năng đóng ngắt tần số cao ổn định, đế tản nhiệt đồng nguyên chất giúp truyền nhiệt nhanh qua keo tản nhiệt xuống cánh nhôm.</p>
          <p>Khi thay thế IGBT, kỹ thuật viên cần kiểm tra kỹ mạch kích Gate (driver) và làm sạch bề mặt tản nhiệt trước khi siết ốc đều lực.</p>
        `
      },
      {
        id: 103,
        category: 'dung-cu',
        categoryLabel: 'Dụng Cụ & Máy Cơ Khí',
        title: 'Những Điều Cần Lưu Ý Khi Chọn Mua Máy Khoan Cầm Tay, Máy Mài & Đá Cắt Kim Loại',
        date: '05/10/2026',
        driveId: DRIVE_IMAGE_IDS[6],
        excerpt: 'Hướng dẫn chọn đúng công suất máy mài góc, máy khoan búa và cách phối hợp đá cắt Inox, nhám xếp đảm bảo an toàn lao động...',
        content: `
          <p>Việc lựa chọn đúng dụng cụ điện cầm tay và vật tư tiêu hao giúp tăng năng suất làm việc và đảm bảo an toàn tuyệt đối cho người thợ:</p>
          <p><strong>• Chọn theo công suất và đường kính đá:</strong> Với công việc cơ khí dân dụng và công trình, máy mài góc đá 100mm (720W - 950W) hoặc đá 125mm (1200W) là lựa chọn tối ưu.</p>
          <p><strong>• Sử dụng đúng chủng loại đá cắt/đá mài:</strong> Tuyệt đối không dùng lưỡi cưa gỗ lắp vào máy mài góc tốc độ cao. Luôn kiểm tra vòng tua tối đa (RPM) ghi trên nhãn viên đá cắt.</p>
        `
      },
      {
        id: 104,
        category: 'dung-cu',
        categoryLabel: 'Vật Tư Công Trình',
        title: 'Bảng Quy Cách Ty Ren, Bulong Cường Độ Cao, Cùm Giàn Giáo & Bánh Xe Đẩy Công Nghiệp',
        date: '28/09/2026',
        driveId: DRIVE_IMAGE_IDS[14],
        excerpt: 'Tổng hợp kích thước tiêu chuẩn của ty ren M8-M16, bát chuồn, cùm xoay BS1139 và cách chọn tải trọng bánh xe đẩy cho nhà xưởng...',
        content: `
          <p>Để thi công hệ thống cơ điện M&E, PCCC và lắp dựng coppha công trình an toàn, việc chọn đúng quy cách vật tư kim khí rất quan trọng:</p>
          <p><strong>1. Hệ treo ống:</strong> Gồm nở đạn (nở đóng), ty ren mạ kẽm (M8, M10, M12), đai treo ống (cùm treo) và ốc tán lục giác.</p>
          <p><strong>2. Bánh xe đẩy công nghiệp:</strong> Khi tính tải trọng cho xe đẩy 4 bánh, nên chia tổng trọng lượng hàng hóa cho 3 (hệ số an toàn khi đường gồ ghề) để chọn đường kính bánh xe 100mm, 125mm, 150mm hoặc 200mm phù hợp.</p>
        `
      }
    ];

    /* ---------------------------------------------------------------------
       Định dạng tiền tệ VNĐ
    ---------------------------------------------------------------------- */
    function formatVND(amount) {
      return amount.toLocaleString('vi-VN') + '₫';
    }

    /* ---------------------------------------------------------------------
       Render Danh Mục Máy Tính (Sidebar) & Điện Thoại (Drawer + Lưới Visual)
    ---------------------------------------------------------------------- */
    function renderAllCategories() {
      const desktopSidebar = document.getElementById('desktop-sidebar-categories');
      const mobileList = document.getElementById('mobile-category-list');
      const visualGrid = document.getElementById('visual-category-grid');
      const filterPills = document.getElementById('category-filter-pills');

      // 1. Desktop Vertical Menu: Thiết kế đẹp, có khung icon, tên danh mục rõ ràng và dòng mô tả nhóm hàng phụ bên dưới
      desktopSidebar.innerHTML = CATEGORIES.map(cat => `
        <li>
          <a href="#san-pham-noi-bat" onclick="filterProductsByCategory('${cat.id}')" class="cat-menu-item flex items-center justify-between px-3.5 py-2.5 group">
            <div class="flex items-center gap-3 min-w-0">
              <span class="w-8 h-8 rounded-lg bg-slate-100 group-hover:bg-flatsome-primary text-flatsome-primary group-hover:text-white flex items-center justify-center shrink-0 transition shadow-xs">
                <i class="${cat.icon} text-xs"></i>
              </span>
              <div class="min-w-0">
                <div class="font-bold text-[13px] text-slate-800 group-hover:text-flatsome-primary leading-tight truncate">${cat.shortName}</div>
                <div class="text-[11px] text-slate-400 group-hover:text-slate-600 truncate mt-0.5">${cat.subItems.slice(0, 2).join(' • ')}</div>
              </div>
            </div>
            <i class="fa-solid fa-chevron-right text-[10px] text-slate-300 group-hover:text-flatsome-secondary shrink-0 ml-2"></i>
          </a>
        </li>
      `).join('');

      // 2. Mobile Off-Canvas Category List
      mobileList.innerHTML = CATEGORIES.map(cat => `
        <div class="p-3">
          <a href="#san-pham-noi-bat" onclick="filterProductsByCategory('${cat.id}'); toggleMobileMenu(false);" class="flex items-center justify-between font-bold text-xs text-slate-800 hover:text-flatsome-primary">
            <span class="flex items-center gap-2">
              <i class="${cat.icon} text-flatsome-primary w-5"></i>
              ${cat.name}
            </span>
            <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
          </a>
          <div class="mt-2 pl-7 flex flex-wrap gap-1.5">
            ${cat.subItems.map(sub => `
              <span onclick="filterProductsByCategory('${cat.id}'); toggleMobileMenu(false);" class="text-[11px] bg-slate-100 text-slate-600 px-2 py-0.5 rounded cursor-pointer hover:bg-blue-50 hover:text-flatsome-primary">
                ${sub}
              </span>
            `).join('')}
          </div>
        </div>
      `).join('');

      // 3. Lưới Danh Mục Trực Quan (Visual Category Grid - Hiển thị trọn bộ 10 danh mục: 2 cột trên điện thoại, 5 cột x 2 hàng trên máy tính)
      visualGrid.innerHTML = CATEGORIES.map(cat => `
        <div onclick="filterProductsByCategory('${cat.id}'); document.getElementById('san-pham-noi-bat').scrollIntoView({behavior:'smooth'});" class="group cursor-pointer rounded-xl border border-slate-200 hover:border-flatsome-primary bg-slate-50/70 hover:bg-white p-2.5 sm:p-3.5 transition shadow-sm hover:shadow-md flex flex-col items-center text-center min-w-0 overflow-hidden">
          <div class="relative w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-white shadow mb-2 bg-white shrink-0">
            <img 
              src="${getDriveUrl(cat.driveId, 400)}" 
              data-drive-id="${cat.driveId}"
              alt="${cat.shortName}" 
              class="w-full h-full object-cover group-hover:scale-110 transition duration-300"
              onerror="handleDriveImgError(this)">
          </div>
          <h3 class="text-xs sm:text-[13.5px] font-extrabold text-slate-800 group-hover:text-flatsome-primary leading-snug line-clamp-1 w-full">${cat.shortName}</h3>
          <p class="text-[10.5px] sm:text-[11px] text-slate-500 mt-0.5 line-clamp-1 w-full">${cat.subItems.slice(0, 2).join(' • ')}</p>
        </div>
      `).join('');

      // 4. Filter Pills
      const pillsHTML = [
        `<button type="button" onclick="filterProductsByCategory('all')" data-cat-pill="all" class="cat-pill-btn px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-bold bg-flatsome-primary text-white transition">Tất cả (16)</button>`
      ].concat(CATEGORIES.map(cat => `
        <button type="button" onclick="filterProductsByCategory('${cat.id}')" data-cat-pill="${cat.id}" class="cat-pill-btn px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-flatsome-primary transition">
          ${cat.shortName}
        </button>
      `));
      filterPills.innerHTML = pillsHTML.join('');
    }

    /* ---------------------------------------------------------------------
       Tạo HTML cho 1 Thẻ Sản Phẩm Chuẩn Flatsome (Có % giảm giá + Xem nhanh)
       Không để các nhãn dán dư thừa ở trang chủ
    ---------------------------------------------------------------------- */
    function createFlatsomeProductCard(product) {
      return `
        <div class="product-small group">
          <div class="box-image">
            <!-- Chỉ hiển thị duy nhất vòng tròn % giảm giá chuẩn Flatsome -->
            <div class="flatsome-onsale">-${product.discount}%</div>

            <img 
              src="${getDriveUrl(product.driveId, 600)}" 
              data-drive-id="${product.driveId}"
              alt="${product.name}" 
              loading="lazy"
              onclick="openQuickView(${product.id})"
              class="cursor-pointer"
              onerror="handleDriveImgError(this)">

            <!-- Nút Xem Nhanh (Quick View) giống Flatsome -->
            <button 
              type="button" 
              onclick="openQuickView(${product.id})" 
              class="quick-view-bar">
              <i class="fa-regular fa-eye mr-1"></i> XEM NHANH
            </button>
          </div>

          <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10px] sm:text-[11px] font-semibold text-slate-400 uppercase tracking-wider mb-1 truncate">
                ${product.categoryName}
              </div>
              <h3 
                onclick="openQuickView(${product.id})"
                class="text-xs sm:text-sm font-bold text-slate-800 hover:text-flatsome-primary cursor-pointer line-clamp-2 leading-snug mb-2 min-h-[2.5rem]">
                ${product.name}
              </h3>
            </div>

            <div>
              <!-- Giá gốc gạch ngang & Giá giảm màu đỏ chuẩn Flatsome -->
              <div class="price-wrapper flex flex-wrap items-baseline gap-1.5 sm:gap-2 mb-2.5">
                <del class="text-[11px] sm:text-xs text-slate-400">${formatVND(product.oldPrice)}</del>
                <ins class="text-xs sm:text-base font-extrabold text-flatsome-red no-underline">${formatVND(product.newPrice)}</ins>
              </div>

              <div class="grid grid-cols-2 gap-1.5">
                <button 
                  type="button" 
                  onclick="selectProductForQuote(${product.id})"
                  class="py-1.5 px-2 rounded bg-slate-100 hover:bg-flatsome-primary hover:text-white text-slate-700 font-bold text-[11px] transition text-center truncate">
                  Báo giá
                </button>
                <button 
                  type="button" 
                  onclick="openQuickView(${product.id})"
                  class="py-1.5 px-2 rounded bg-flatsome-secondary hover:bg-orange-700 text-white font-bold text-[11px] transition text-center truncate">
                  Chi tiết
                </button>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    /* ---------------------------------------------------------------------
       Render Danh Sách Sản Phẩm & Lọc Theo Danh Mục / Từ Khóa
    ---------------------------------------------------------------------- */
    function filterProductsByCategory(catId, searchKeyword = '') {
      const grid = document.getElementById('main-product-grid');
      const heading = document.getElementById('current-category-heading');

      // Cập nhật trạng thái nút pill
      document.querySelectorAll('.cat-pill-btn').forEach(btn => {
        if (btn.getAttribute('data-cat-pill') === catId) {
          btn.className = 'cat-pill-btn px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-bold bg-flatsome-primary text-white transition';
        } else {
          btn.className = 'cat-pill-btn px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-flatsome-primary transition';
        }
      });

      let filtered = PRODUCTS;
      if (catId !== 'all') {
        filtered = PRODUCTS.filter(p => p.category === catId);
        const catObj = CATEGORIES.find(c => c.id === catId);
        if (catObj) {
          heading.innerHTML = `<i class="${catObj.icon} text-flatsome-secondary shrink-0"></i> <span class="truncate">${catObj.name.toUpperCase()}</span>`;
        }
      } else {
        heading.innerHTML = `<i class="fa-solid fa-screwdriver-wrench text-flatsome-secondary shrink-0"></i> <span class="truncate">SẢN PHẨM THỰC TẾ TẠI KHO THIÊN QUÝ</span>`;
      }

      if (searchKeyword.trim() !== '') {
        const kw = searchKeyword.trim().toLowerCase();
        filtered = PRODUCTS.filter(p => 
          p.name.toLowerCase().includes(kw) || 
          p.categoryName.toLowerCase().includes(kw) ||
          p.desc.toLowerCase().includes(kw)
        );
        heading.innerHTML = `<i class="fa-solid fa-magnifying-glass text-flatsome-secondary shrink-0"></i> <span class="truncate">KẾT QUẢ TÌM KIẾM: "${searchKeyword}" (${filtered.length})</span>`;
      }
      });

      let filtered = PRODUCTS;
      if (catId !== 'all') {
        filtered = PRODUCTS.filter(p => p.category === catId);
        const catObj = CATEGORIES.find(c => c.id === catId);
        if (catObj) {
          heading.innerHTML = `<i class="${catObj.icon} text-flatsome-secondary"></i> ${catObj.name.toUpperCase()}`;
        }
      } else {
        heading.innerHTML = `<i class="fa-solid fa-screwdriver-wrench text-flatsome-secondary"></i> TẤT CẢ SẢN PHẨM THỰC TẾ TẠI KHO THIÊN QUÝ`;
      }

      if (searchKeyword.trim() !== '') {
        const kw = searchKeyword.trim().toLowerCase();
        filtered = PRODUCTS.filter(p => 
          p.name.toLowerCase().includes(kw) || 
          p.categoryName.toLowerCase().includes(kw) ||
          p.desc.toLowerCase().includes(kw)
        );
        heading.innerHTML = `<i class="fa-solid fa-magnifying-glass text-flatsome-secondary"></i> KẾT QUẢ TÌM KIẾM: "${searchKeyword}" (${filtered.length})`;
      }

      if (filtered.length === 0) {
        grid.innerHTML = `
          <div class="col-span-2 lg:col-span-4 bg-white rounded-xl p-8 text-center border border-slate-200">
            <p class="text-sm text-slate-600 mb-3">Không tìm thấy sản phẩm khớp từ khóa. Quý khách vui lòng gửi yêu cầu báo giá trực tiếp!</p>
            <button onclick="filterProductsByCategory('all')" class="px-4 py-2 bg-flatsome-primary text-white text-xs font-bold rounded-lg">Xem tất cả sản phẩm</button>
          </div>
        `;
        return;
      }

      grid.innerHTML = filtered.map(p => createFlatsomeProductCard(p)).join('');
    }

    /* ---------------------------------------------------------------------
       Render Các Khối Ngành Hàng Theo Mẫu trangtuphuong.com.vn (2 cột Mobile, 4 cột Desktop)
    ---------------------------------------------------------------------- */
    function renderCategorySections() {
      const container = document.getElementById('category-sections-container');
      const sectionGroups = [
        {
          title: 'VÒNG BI CÔNG NGHIỆP & LINH KIỆN BÁN DẪN IGBT',
          subCats: ['Vòng bi SKF', 'Vòng bi Nachi - Koyo - NSK', 'Mô đun công suất IGBT', 'Thiết bị điện công nghiệp'],
          items: PRODUCTS.slice(0, 4)
        },
        {
          title: 'DỤNG CỤ ĐỒ NGHỀ, DỤNG CỤ CẦM TAY & MÁY HÀN CẮT',
          subCats: ['Asaki - Harkcaput', 'Bosch - Makita - Hitachi', 'Máy Cắt Plasma', 'Máy Hàn Điện Tử'],
          items: PRODUCTS.slice(4, 8)
        },
        {
          title: 'TY REN BULONG, ĐÁ CẮT ĐÁ MÀI, MŨI KHOAN & LƯỠI CẮT',
          subCats: ['Bulong - Đai ốc - Ty ren', 'Đá cắt - Đá mài - Que hàn', 'Mũi khoan Nachi - Bê tông', 'Lưỡi cắt bê tông - Đá'],
          items: PRODUCTS.slice(8, 12)
        },
        {
          title: 'NHÁM XẾP ĐÁNH BÓNG, BÁNH XE ĐẨY, COPPHA & NÂNG HẠ',
          subCats: ['Nhám xếp - Chổi đánh rỉ', 'Bánh xe đẩy công nghiệp', 'Phụ kiện Coppha dàn giáo', 'Dây cáp - Xích - Tăng đơ'],
          items: PRODUCTS.slice(12, 16)
        }
      ];

      container.innerHTML = sectionGroups.map(group => `
        <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
          <div class="section-title-container">
            <div class="section-title-main flex-wrap gap-2">
              <h2 class="text-sm sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-tight">
                ${group.title}
              </h2>
              <div class="hidden md:flex items-center gap-2 text-xs text-slate-600">
                ${group.subCats.map(sc => `<span class="px-2.5 py-1 rounded bg-slate-100 font-medium">${sc}</span>`).join('')}
              </div>
            </div>
          </div>
          <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
          <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-5">
            ${group.items.map(item => createFlatsomeProductCard(item)).join('')}
          </div>
        </div>
      `).join('');
    }

    /* ---------------------------------------------------------------------
       Render 16 Ảnh Thực Tế Kho Hàng Từ Google Drive
    ---------------------------------------------------------------------- */
    function renderRealGallery() {
      const gallery = document.getElementById('real-gallery-grid');
      gallery.innerHTML = PRODUCTS.map((prod, idx) => `
        <div onclick="openQuickView(${prod.id})" class="group relative aspect-square rounded-lg overflow-hidden border border-slate-200 bg-slate-100 cursor-pointer">
          <img 
            src="${getDriveUrl(prod.driveId, 400)}" 
            data-drive-id="${prod.driveId}"
            alt="Ảnh thực tế Thiên Quý ${idx + 1}" 
            loading="lazy"
            class="w-full h-full object-cover group-hover:scale-110 transition duration-300"
            onerror="handleDriveImgError(this)">
          <div class="absolute inset-0 bg-black/40 opacity-0 group-hover:opacity-100 transition flex items-center justify-center text-white text-xs font-bold">
            <i class="fa-solid fa-magnifying-glass-plus mr-1"></i> Xem
          </div>
        </div>
      `).join('');
    }

    /* ---------------------------------------------------------------------
       Render Danh Mục Bài Viết Trang Chủ (Chia 2 cột trên điện thoại, 4 cột trên máy tính)
    ---------------------------------------------------------------------- */
    function filterBlogPosts(catId) {
      const grid = document.getElementById('blog-posts-grid');
      document.querySelectorAll('.blog-tab-btn').forEach(btn => {
        if (btn.getAttribute('data-blog-cat') === catId) {
          btn.className = 'blog-tab-btn px-3 py-1.5 rounded-lg text-xs font-bold bg-flatsome-primary text-white transition';
        } else {
          btn.className = 'blog-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition';
        }
      });

      const list = catId === 'all' ? BLOG_POSTS : BLOG_POSTS.filter(b => b.category === catId);
      grid.innerHTML = list.map(post => `
        <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between min-w-0">
          <div>
            <div class="relative h-28 sm:h-44 bg-slate-100 overflow-hidden cursor-pointer" onclick="openBlogModal(${post.id})">
              <img 
                src="${getDriveUrl(post.driveId, 600)}" 
                data-drive-id="${post.driveId}"
                alt="${post.title}" 
                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                onerror="handleDriveImgError(this)">
            </div>
            <div class="p-2.5 sm:p-4">
              <div class="flex items-center justify-between text-[10px] sm:text-[11px] text-slate-500 mb-1 gap-1">
                <span class="font-bold text-flatsome-secondary uppercase truncate">${post.categoryLabel}</span>
                <span class="shrink-0 hidden sm:inline"><i class="fa-regular fa-calendar mr-1"></i>${post.date}</span>
              </div>
              <h3 onclick="openBlogModal(${post.id})" class="text-xs sm:text-sm font-bold text-slate-800 hover:text-flatsome-primary cursor-pointer line-clamp-2 mb-1.5 leading-snug">
                ${post.title}
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-2 sm:line-clamp-3 leading-relaxed">
                ${post.excerpt}
              </p>
            </div>
          </div>
          <div class="px-2.5 pb-2.5 sm:px-4 sm:pb-4">
            <button type="button" onclick="openBlogModal(${post.id})" class="text-[11px] sm:text-xs font-bold text-flatsome-primary hover:text-flatsome-secondary flex items-center gap-1">
              <span>Đọc tiếp</span>
              <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>
      `).join('');
    }

    /* ---------------------------------------------------------------------
       Modal Xem Nhanh Sản Phẩm (Flatsome Quick View)
    ---------------------------------------------------------------------- */
    function openQuickView(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;

      const imgEl = document.getElementById('qv-image');
      imgEl.setAttribute('data-drive-id', product.driveId);
      imgEl.setAttribute('data-fallback-step', '0');
      imgEl.src = getDriveUrl(product.driveId, 800);
      imgEl.onerror = function() { handleDriveImgError(this); };

      document.getElementById('qv-discount-badge').textContent = `-${product.discount}%`;
      document.getElementById('qv-category').textContent = product.categoryName;
      document.getElementById('qv-title').textContent = product.name;
      document.getElementById('qv-old-price').textContent = formatVND(product.oldPrice);
      document.getElementById('qv-new-price').textContent = formatVND(product.newPrice);
      document.getElementById('qv-desc').textContent = product.desc;

      document.getElementById('qv-quote-btn').onclick = function() {
        closeQuickView();
        selectProductForQuote(product.id);
      };

      const modal = document.getElementById('quick-view-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeQuickView() {
      const modal = document.getElementById('quick-view-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    /* ---------------------------------------------------------------------
       Đưa sản phẩm vào Form Yêu Cầu Báo Giá Trang Chủ
    ---------------------------------------------------------------------- */
    function selectProductForQuote(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;
      const msgEl = document.getElementById('quote-message');
      const currentVal = msgEl.value.trim();
      const line = `- Cần báo giá: ${product.name} (Giá web: ${formatVND(product.newPrice)}) - Số lượng: ...`;
      msgEl.value = currentVal ? (currentVal + '\n' + line) : line;
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
      document.getElementById('quote-name').focus();
    }

    /* ---------------------------------------------------------------------
       Xử lý gửi Form Báo Giá Trang Chủ
    ---------------------------------------------------------------------- */
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('quote-name').value.trim();
      const phone = document.getElementById('quote-phone').value.trim();
      const category = document.getElementById('quote-category').value;
      const message = document.getElementById('quote-message').value.trim();

      const feedback = document.getElementById('quote-feedback');
      feedback.classList.remove('hidden');
      feedback.innerHTML = `
        <div class="flex items-start gap-2.5">
          <i class="fa-solid fa-circle-check text-emerald-600 text-lg mt-0.5"></i>
          <div>
            <strong>Đã ghi nhận yêu cầu báo giá của ${name} (${phone})!</strong><br>
            Danh mục: ${category}. Bộ phận Kinh doanh <strong>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ</strong> sẽ liên hệ lại ngay qua SĐT/Zalo <strong>0978.102.434</strong>.
          </div>
        </div>
      `;
    }

    /* ---------------------------------------------------------------------
       Modal Đọc Bài Viết Kỹ Thuật
    ---------------------------------------------------------------------- */
    function openBlogModal(postId) {
      const post = BLOG_POSTS.find(b => b.id === postId);
      if (!post) return;
      document.getElementById('bm-category').textContent = post.categoryLabel;
      document.getElementById('bm-title').textContent = post.title;
      const img = document.getElementById('bm-image');
      img.setAttribute('data-drive-id', post.driveId);
      img.setAttribute('data-fallback-step', '0');
      img.src = getDriveUrl(post.driveId, 800);
      img.onerror = function() { handleDriveImgError(this); };
      document.getElementById('bm-content').innerHTML = post.content;

      const modal = document.getElementById('blog-reader-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeBlogModal() {
      const modal = document.getElementById('blog-reader-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    /* ---------------------------------------------------------------------
       2 Ảnh Banner Tự Trượt (Auto Slider)
    ---------------------------------------------------------------------- */
    let currentBannerIndex = 0;
    let bannerInterval = null;

    function showBannerSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.banner-dot');
      currentBannerIndex = (index + slides.length) % slides.length;

      slides.forEach((slide, i) => {
        if (i === currentBannerIndex) {
          slide.classList.remove('opacity-0', 'z-0');
          slide.classList.add('opacity-100', 'z-10');
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0');
        }
      });

      dots.forEach((dot, i) => {
        if (i === currentBannerIndex) {
          dot.className = 'banner-dot w-7 h-2 rounded-full bg-amber-400 transition-all';
        } else {
          dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
        }
      });
    }

    function startBannerAutoSlide() {
      stopBannerAutoSlide();
      bannerInterval = setInterval(() => {
        showBannerSlide(currentBannerIndex + 1);
      }, 4500);
    }

    function stopBannerAutoSlide() {
      if (bannerInterval) clearInterval(bannerInterval);
    }

    /* ---------------------------------------------------------------------
       Đóng / Mở Menu Danh Mục Điện Thoại
    ---------------------------------------------------------------------- */
    function toggleMobileMenu(show) {
      const drawer = document.getElementById('mobile-drawer');
      const backdrop = document.getElementById('mobile-drawer-backdrop');
      if (show) {
        backdrop.classList.remove('hidden');
        drawer.classList.remove('-translate-x-full');
      } else {
        backdrop.classList.add('hidden');
        drawer.classList.add('-translate-x-full');
      }
    }

    /* ---------------------------------------------------------------------
       Khởi tạo toàn bộ giao diện khi tải trang
    ---------------------------------------------------------------------- */
    window.addEventListener('DOMContentLoaded', () => {
      renderAllCategories();
      filterProductsByCategory('all');
      renderCategorySections();
      renderRealGallery();
      filterBlogPosts('all');
      startBannerAutoSlide();

      // Sự kiện điều khiển 2 banner tự trượt
      document.getElementById('banner-prev').addEventListener('click', () => {
        showBannerSlide(currentBannerIndex - 1);
        startBannerAutoSlide();
      });
      document.getElementById('banner-next').addEventListener('click', () => {
        showBannerSlide(currentBannerIndex + 1);
        startBannerAutoSlide();
      });
      document.querySelectorAll('.banner-dot').forEach(dot => {
        dot.addEventListener('click', () => {
          const idx = parseInt(dot.getAttribute('data-goto'), 10);
          showBannerSlide(idx);
          startBannerAutoSlide();
        });
      });

      const sliderBox = document.getElementById('hero-banner-slider');
      sliderBox.addEventListener('mouseenter', stopBannerAutoSlide);
      sliderBox.addEventListener('mouseleave', startBannerAutoSlide);

      // Sự kiện menu mobile
      document.getElementById('mobile-menu-btn').addEventListener('click', () => toggleMobileMenu(true));
      document.getElementById('close-mobile-menu').addEventListener('click', () => toggleMobileMenu(false));
      document.getElementById('mobile-drawer-backdrop').addEventListener('click', () => toggleMobileMenu(false));

      // Sự kiện tìm kiếm
      const runDesktopSearch = () => {
        const kw = document.getElementById('desktop-search-input').value;
        filterProductsByCategory('all', kw);
        document.getElementById('san-pham-noi-bat').scrollIntoView({ behavior: 'smooth' });
      };
      document.getElementById('desktop-search-btn').addEventListener('click', runDesktopSearch);
      document.getElementById('desktop-search-input').addEventListener('keydown', e => {
        if (e.key === 'Enter') runDesktopSearch();
      });

      const runMobileSearch = () => {
        const kw = document.getElementById('mobile-search-input').value;
        filterProductsByCategory('all', kw);
        document.getElementById('san-pham-noi-bat').scrollIntoView({ behavior: 'smooth' });
      };
      document.getElementById('mobile-search-btn').addEventListener('click', runMobileSearch);
      document.getElementById('mobile-search-input').addEventListener('keydown', e => {
        if (e.key === 'Enter') runMobileSearch();
      });

      // Đóng modal khi click ra ngoài nền tối
      document.getElementById('quick-view-modal').addEventListener('click', e => {
        if (e.target.id === 'quick-view-modal') closeQuickView();
      });
      document.getElementById('blog-reader-modal').addEventListener('click', e => {
        if (e.target.id === 'blog-reader-modal') closeBlogModal();
      });
    });
  </script>
</body>
</html>
