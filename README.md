<!-- Enterprise UI Layout Engine & Premium Dark Space Override Framework -->
<style>
  /* Force hide GitHub Pages theme default header components */
  header.page-header, .page-header, .site-header {
    display: none !important;
  }

  /* Global Page Canvas & Premium Typography System */
  html {
    scroll-behavior: smooth !important;
    background-color: #020617 !important;
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "-apple-system-body", "Segoe UI", Roboto, sans-serif !important;
    color: #f8fafc !important;
    letter-spacing: -0.1px;
    overflow-x: hidden;
  }
  
  body {
    max-width: 1140px !important;
    padding: 40px 20px !important;
    margin: 0 auto !important;
    background-color: #020617 !important;
    background-image: 
      radial-gradient(at 0% 0%, rgba(56, 189, 248, 0.08) 0px, transparent 55%),
      radial-gradient(at 100% 0%, rgba(139, 92, 246, 0.06) 0px, transparent 55%),
      radial-gradient(at 50% 100%, rgba(15, 23, 42, 0.98) 0px, transparent 75%) !important;
    background-attachment: fixed !important;
    position: relative;
  }
  
  .main-content {
    max-width: 100% !important;
    padding: 0 !important;
    position: relative;
    z-index: 2;
    box-sizing: border-box !important;
  }

  /* Dense Cosmic Night Sky Canvas Backdrop Layer */
  .space-canvas {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100vw !important;
    height: 100vh !important;
    pointer-events: none !important;
    z-index: -1 !important;
    overflow: hidden !important;
    background-image: 
      radial-gradient(1.2px 1.2px at 15px 25px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 45px 90px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.5px 1.5px at 110px 65px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 210px 140px, #7dd3fc, rgba(0,0,0,0)),
      radial-gradient(1.2px 1.2px at 190px 240px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 310px 380px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.5px 1.5px at 420px 95px, #a5b4fc, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 580px 210px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.2px 1.2px at 690px 130px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 810px 80px, #7dd3fc, rgba(0,0,0,0)),
      radial-gradient(1.8px 1.8px at 890px 320px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.2px 1.2px at 1050px 190px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 35px 280px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.5px 1.5px at 145px 420px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 280px 510px, #a5b4fc, rgba(0,0,0,0)),
      radial-gradient(1.2px 1.2px at 490px 320px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 670px 460px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.5px 1.5px at 830px 240px, #7dd3fc, rgba(0,0,0,0)),
      radial-gradient(1px 1px at 960px 490px, #ffffff, rgba(0,0,0,0)),
      radial-gradient(1.2px 1.2px at 1110px 410px, #ffffff, rgba(0,0,0,0)) !important;
    background-repeat: repeat !important;
    background-size: 400px 400px !important;
    opacity: 0.85;
    animation: celestialShimmer 4s ease-in-out infinite alternate !important;
  }

  @keyframes celestialShimmer {
    0% { opacity: 0.65; }
    100% { opacity: 0.90; }
  }
  
  /* Diagonal High-Velocity Shooting Star Matrix */
  .diagonal-shooting-star {
    position: absolute !important;
    height: 1.5px;
    background: linear-gradient(-45deg, #ffffff, rgba(56, 189, 248, 0));
    filter: drop-shadow(0 0 8px #60a5fa);
    opacity: 0;
  }

  .star-d1 { top: -60px; left: 3%;   width: 130px; animation: diagonalStreak 1.8s linear infinite !important; animation-delay: 0.1s !important; }
  .star-d2 { top: -60px; left: 20%;  width: 160px; animation: diagonalStreak 2.5s linear infinite !important; animation-delay: 1.2s !important; }
  .star-d3 { top: -60px; left: 38%;  width: 115px; animation: diagonalStreak 2.1s linear infinite !important; animation-delay: 0.5s !important; }
  .star-d4 { top: -60px; left: 55%;  width: 150px; animation: diagonalStreak 2.9s linear infinite !important; animation-delay: 1.8s !important; }
  .star-d5 { top: -60px; left: 72%;  width: 135px; animation: diagonalStreak 2.3s linear infinite !important; animation-delay: 0.2s !important; }
  .star-d6 { top: -60px; left: 88%;  width: 145px; animation: diagonalStreak 2.6s linear infinite !important; animation-delay: 0.9s !important; }
  .star-d7 { top: -60px; left: 96%;  width: 120px; animation: diagonalStreak 2.2s linear infinite !important; animation-delay: 1.4s !important; }
  .star-d8  { top: 25vh;  left: 1%;   width: 110px; animation: diagonalStreak 2.4s linear infinite !important; animation-delay: 0.7s !important; }
  .star-d9  { top: 40vh;  left: 84%;  width: 135px; animation: diagonalStreak 2.2s linear infinite !important; animation-delay: 1.3s !important; }
  .star-d10 { top: 60vh;  left: 15%;  width: 125px; animation: diagonalStreak 2.7s linear infinite !important; animation-delay: 0.4s !important; }
  .star-d11 { top: 75vh;  left: 90%;  width: 140px; animation: diagonalStreak 2.5s linear infinite !important; animation-delay: 1.1s !important; }

  @keyframes diagonalStreak {
    0% { transform: translateX(0) translateY(0) rotate(-45deg); opacity: 0; }
    3% { opacity: 1; }
    22% { transform: translateX(-550px) translateY(500px) rotate(-45deg); opacity: 0; }
    100% { transform: translateX(-550px) translateY(500px) rotate(-45deg); opacity: 0; }
  }

  /* Header Hero Card */
  .custom-portfolio-header {
    background: linear-gradient(135deg, rgba(15, 23, 42, 0.4) 0%, rgba(30, 41, 59, 0.15) 100%) !important;
    backdrop-filter: blur(24px) !important;
    -webkit-backdrop-filter: blur(24px) !important;
    padding: 7rem 2rem 5rem 2rem !important;
    text-align: center !important;
    border-radius: 28px !important;
    box-shadow: 0 40px 100px -30px rgba(0, 0, 0, 0.95) !important;
    border: 1px solid rgba(255, 255, 255, 0.04) !important;
    margin-top: 20px !important;
    margin-bottom: 45px !important;
    display: flex !important;
    flex-direction: column !important;
    align-items: center !important;
    justify-content: center !important;
    position: relative;
    z-index: 2;
  }
  
  .name-word-group {
    display: inline-block !important;
    white-space: nowrap !important;
  }

  .typewriter-title {
    color: #ffffff !important;
    font-size: 38px !important;
    font-weight: 800 !important;
    letter-spacing: -0.5px !important;
    margin: 0 !important;
    text-align: center !important;
    line-height: 1.25;
    min-height: 48px;
  }

  .typewriter-tagline {
    color: #94a3b8 !important;
    font-size: 11.5px !important;
    font-weight: 700 !important;
    text-transform: uppercase !important;
    letter-spacing: 3.5px !important;
    margin: 18px 0 0 0 !important;
    text-align: center !important;
    line-height: 1.5;
    width: 100% !important;
    display: block !important;
    min-height: 18px;
  }

  .subtle-walkthrough-btn {
    margin-top: 24px !important;
    display: inline-flex !important;
    align-items: center !important;
    gap: 8px !important;
    background: rgba(255, 255, 255, 0.04) !important;
    color: #38bdf8 !important;
    padding: 8px 18px !important;
    border-radius: 20px !important;
    font-weight: 600 !important;
    font-size: 12px !important;
    letter-spacing: 0.3px !important;
    cursor: pointer !important;
    border: 1px solid rgba(56, 189, 248, 0.2) !important;
    backdrop-filter: blur(10px) !important;
    -webkit-backdrop-filter: blur(10px) !important;
    transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1) !important;
  }

  .subtle-walkthrough-btn:hover {
    background: rgba(56, 189, 248, 0.1) !important;
    color: #ffffff !important;
    border-color: rgba(56, 189, 248, 0.4) !important;
    transform: translateY(-2px) !important;
  }

  .blinking-cursor {
    display: inline-block !important;
    color: #ffffff !important; 
    font-weight: 800 !important;
    font-size: 36px !important;
    animation: pulseCursor 0.8s step-end infinite !important;
    vertical-align: baseline !important;
    margin-left: 2px !important;
    line-height: 1 !important;
  }

  @keyframes pulseCursor {
    from, to { opacity: 0; }
    50% { opacity: 1; }
  }

  /* Navigation Dock */
  .nav-container {
    position: -webkit-sticky;
    position: sticky;
    top: 24px;
    z-index: 999;
    display: flex;
    justify-content: center;
    background-color: rgba(3, 7, 18, 0.75);
    -webkit-backdrop-filter: blur(30px);
    backdrop-filter: blur(30px);
    padding: 6px;
    border-radius: 40px;
    border: 1px solid rgba(255, 255, 255, 0.06);
    box-shadow: 0 30px 60px -15px rgba(0, 0, 0, 0.8), inset 0 1px 0 rgba(255,255,255,0.05);
    margin-bottom: 80px;
  }

  .nav-btn {
    position: relative !important;
    white-space: nowrap !important;
    color: #94a3b8 !important;
    padding: 12px 24px !important;
    border-radius: 30px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 13px !important;
    display: inline-block !important;
    letter-spacing: 0.2px !important;
    transition: all 0.3s cubic-bezier(0.25, 1, 0.5, 1) !important;
  }
  
  .nav-btn:hover {
    color: #ffffff !important;
    background-color: rgba(255, 255, 255, 0.05) !important;
  }
  
  .nav-btn::after {
    content: '' !important;
    position: absolute !important;
    bottom: 4px !important;
    left: 50% !important;
    width: 0 !important;
    height: 2px !important;
    background: linear-gradient(90deg, #38bdf8, #818cf8) !important;
    transition: all 0.3s ease !important;
    transform: translateX(-50%) !important;
  }
  .nav-btn:hover::after { width: 25% !important; }

  /* Frosted Matrix Card Component */
  .premium-card {
    background: linear-gradient(135deg, rgba(15, 23, 42, 0.45) 0%, rgba(30, 41, 59, 0.25) 100%) !important;
    backdrop-filter: blur(20px) !important;
    -webkit-backdrop-filter: blur(20px) !important;
    border: 1px solid rgba(255, 255, 255, 0.04) !important;
    box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.6) !important;
    transition: all 0.45s cubic-bezier(0.16, 1, 0.3, 1) !important;
  }
  
  .premium-card.glow-orange:hover {
    transform: translateY(-4px) !important;
    border-color: rgba(249, 115, 22, 0.3) !important;
    box-shadow: 0 30px 60px -15px rgba(249, 115, 22, 0.25) !important;
  }
  
  .premium-card.glow-blue:hover {
    transform: translateY(-4px) !important;
    border-color: rgba(56, 189, 248, 0.3) !important;
    box-shadow: 0 30px 60px -15px rgba(56, 189, 248, 0.25) !important;
  }

  .premium-card.glow-emerald:hover {
    transform: translateY(-4px) !important;
    border-color: rgba(16, 185, 129, 0.3) !important;
    box-shadow: 0 30px 60px -15px rgba(16, 185, 129, 0.25) !important;
  }
  
  .badge-btn {
    transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1) !important;
    cursor: pointer !important;
  }
  .badge-btn:hover {
    transform: translateY(-2px) !important;
    filter: brightness(1.15);
  }

  .section-title-wrapper {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 36px;
  }
  .section-bar {
    width: 4px;
    height: 28px;
    background: linear-gradient(to bottom, #60a5fa, #3b82f6);
    border-radius: 10px;
  }
  
  .pill-metric {
    font-size: 11px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 6px 14px;
    border-radius: 20px;
    display: inline-block;
  }

  .audit-table-wrapper {
    width: 100% !important;
    overflow-x: auto !important;
    -webkit-overflow-scrolling: touch !important;
    border-radius: 12px !important;
    background: rgba(15, 23, 42, 0.25) !important;
    border: 1px solid rgba(255, 255, 255, 0.06) !important;
    margin-top: 20px !important;
  }

  .audit-table {
    width: 100% !important;
    min-width: 750px !important;
    border-collapse: collapse !important;
    font-size: 13.5px !important;
    color: #cbd5e1 !important;
  }
  .audit-table th {
    text-align: left !important;
    padding: 16px !important;
    background: rgba(255, 255, 255, 0.04) !important;
    color: #ffffff !important;
    font-weight: 600 !important;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1) !important;
  }
  .audit-table td {
    padding: 16px !important;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05) !important;
    line-height: 1.6 !important;
  }

  /* Modals */
  .custom-modal-overlay {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: rgba(3, 7, 18, 0.96) !important;
    backdrop-filter: blur(24px) !important;
    -webkit-backdrop-filter: blur(24px) !important;
    z-index: 10000 !important;
    display: none !important;
    align-items: center !important;
    justify-content: center !important;
    opacity: 0 !important;
    transition: opacity 0.3s cubic-bezier(0.16, 1, 0.3, 1) !important;
  }
  
  .custom-modal-overlay.is-active { display: flex !important; opacity: 1 !important; }
  
  .custom-modal-window {
    position: relative !important;
    width: 90vw !important;
    height: 85vh !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    overflow: hidden !important;
    border-radius: 16px !important;
  }
  .custom-modal-content {
    max-width: 100% !important;
    max-height: 100% !important;
    object-fit: contain !important;
    user-select: none !important;
    -webkit-user-drag: none !important;
    transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1) !important;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.7) !important;
    cursor: zoom-in !important;
  }

  .video-modal-window {
    width: 80vw !important;
    max-width: 960px !important;
    height: 0 !important;
    padding-bottom: 45% !important;
    background-color: #000000 !important;
    border-radius: 20px !important;
    border: 1px solid rgba(255, 255, 255, 0.1) !important;
    box-shadow: 0 30px 90px rgba(0, 0, 0, 0.9) !important;
    overflow: hidden !important;
    position: relative !important;
  }

  .video-frame {
    position: absolute !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    border: none !important;
  }
  
  .report-modal-window {
    width: 85vw !important;
    height: 85vh !important;
    background-color: #111827 !important;
    border-radius: 16px !important;
    border: 1px solid rgba(255, 255, 255, 0.08) !important;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.8) !important;
    overflow: hidden !important;
    display: flex !important;
    flex-direction: column !important;
    align-items: center !important;
    justify-content: center !important;
    position: relative !important;
  }
  .report-frame {
    width: 100% !important;
    height: 100% !important;
    border: none !important;
    background: #111827 !important;
  }

  .mobile-pdf-fallback {
    display: none;
    padding: 20px;
    text-align: center;
  }

  .custom-modal-close-btn {
    position: fixed !important;
    top: 25px !important;
    right: 35px !important;
    background: rgba(15, 23, 42, 0.7) !important;
    border: 1px solid rgba(255,255,255,0.08) !important;
    backdrop-filter: blur(8px) !important;
    -webkit-backdrop-filter: blur(8px) !important;
    color: #94a3b8 !important;
    font-size: 24px !important;
    width: 44px !important;
    height: 44px !important;
    border-radius: 50% !important;
    cursor: pointer !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    transition: all 0.2s ease !important;
    z-index: 10001 !important;
  }

  /* Mobile Media Queries */
  @media (max-width: 768px) {
    html, body, .main-content, .container-lg {
      padding-left: 0px !important;
      padding-right: 0px !important;
      margin-left: 0px !important;
      margin-right: 0px !important;
    }
    
    body {
      padding-top: 10px !important;
      padding-bottom: 20px !important;
    }
    
    .custom-portfolio-header, #who-i-am, #projects-overview, #case-study-laundrify, #case-study-1-ergochef, #case-study-2-elearn-ux-audit, #case-study-ezshop, #personal-challenges, #submission {
      border-radius: 0px !important; 
      padding-left: 16px !important;
      padding-right: 16px !important;
      box-sizing: border-box !important;
      width: 100% !important;
    }

    .video-modal-window {
      width: 92vw !important;
      padding-bottom: 56.25% !important;
    }
    
    .nav-container {
      justify-content: flex-start !important;
      overflow-x: auto !important;
      -webkit-overflow-scrolling: touch !important;
      border-radius: 0px !important;
      padding: 6px !important;
      margin-bottom: 40px;
      top: 0px;
    }
    .nav-container::-webkit-scrollbar { display: none !important; }
    .nav-btn { padding: 12px 16px !important; }

    .case-split-grid {
      display: flex !important;
      flex-direction: column !important;
      gap: 16px !important;
      width: 100% !important;
    }
    .case-split-grid > div {
      width: 100% !important;
      max-width: 100% !important;
      box-sizing: border-box !important;
    }
    
    .badge-btn-container {
      width: 100% !important;
      box-sizing: border-box !important;
      padding: 0px !important;
      display: flex !important;
      justify-content: center !important;
    }
    .badge-btn-container > .badge-btn {
      max-width: 100% !important;
      width: 100% !important;
    }

    .mobile-pdf-fallback {
      display: flex !important;
      flex-direction: column !important;
      align-items: center !important;
      justify-content: center !important;
    }
  }
</style>

<!-- Canvas Backdrop -->
<div class="space-canvas">
  <div class="diagonal-shooting-star star-d1"></div>
  <div class="diagonal-shooting-star star-d2"></div>
  <div class="diagonal-shooting-star star-d3"></div>
  <div class="diagonal-shooting-star star-d4"></div>
  <div class="diagonal-shooting-star star-d5"></div>
  <div class="diagonal-shooting-star star-d6"></div>
  <div class="diagonal-shooting-star star-d7"></div>
  <div class="diagonal-shooting-star star-d8"></div>
  <div class="diagonal-shooting-star star-d9"></div>
  <div class="diagonal-shooting-star star-d10"></div>
  <div class="diagonal-shooting-star star-d11"></div>
</div>

<div class="main-content">

  <!-- Header Area -->
  <div class="custom-portfolio-header">
    <h1 class="typewriter-title">
      <span class="name-word-group" id="js-type-name-1"></span> 
      <span class="name-word-group" id="js-type-name-2"></span> 
      <span class="name-word-group"><span id="js-type-name-3"></span><span id="js-cursor-name" class="blinking-cursor">_</span></span>
    </h1>
    <h2 id="js-type-tagline" class="typewriter-tagline"></h2>

    <button onclick="openVideoModal('walkthrough')" class="subtle-walkthrough-btn">
      <svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor">
        <path d="M8 5v14l11-7z"/>
      </svg>
      Watch Portfolio Walkthrough
    </button>
  </div>

  <!-- Navigation Dock -->
  <div class="nav-container">
    <a href="#who-i-am" class="nav-btn">Profile</a>
    <a href="#projects-overview" class="nav-btn">Projects</a>
    <a href="#case-study-laundrify" class="nav-btn">Laundrify (FYP)</a>
    <a href="#case-study-1-ergochef" class="nav-btn">ErgoChef+</a>
    <a href="#case-study-2-elearn-ux-audit" class="nav-btn">eLearn Audit</a>
    <a href="#case-study-ezshop" class="nav-btn">EZShop</a>
    <a href="#personal-challenges" class="nav-btn">Challenges</a>
    <a href="#submission" class="nav-btn">Submission</a>
  </div>

  <!-- Profile Section -->
  <div id="who-i-am" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: linear-gradient(#38bdf8, #818cf8);"></div>
      <h2 style="color: #ffffff; font-size: 28px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Introduction</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 28px;">
      <div class="premium-card glow-blue" style="flex: 2; min-width: 320px; border-radius: 24px; padding: 40px; display: flex; gap: 35px; align-items: center; flex-wrap: wrap;">
        <div style="position: relative; flex-shrink: 0;">
          <div style="position: absolute; top: -5px; left: -4px; right: -4px; bottom: -4px; background: linear-gradient(135deg, #38bdf8, #818cf8); border-radius: 50%; z-index: 0; opacity: 0.3; filter: blur(4px);"></div>
          <img src="https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/WhatsApp%20Image%202026-07-03%20at%2010.14.22%20PM.jpeg" alt="Malcolm Jeremiah Richard" style="position: relative; width: 110px; height: 110px; border-radius: 50%; object-fit: cover; border: 4px solid #020617; z-index: 1;" />
        </div>
        <div style="flex: 1; min-width: 240px;">
          <p style="font-size: 16px; line-height: 1.8; color: #cbd5e1; margin: 0; font-weight: 400; letter-spacing: 0.2px;">
            I am an <strong>Information Technology</strong> student specializing in software automation, scalable back-end services, and user-centered system workflows. Combining enterprise exposure from Maybank with practical full-stack deployment, my focus centers on building reliable, secure applications that solve operational bottlenecks while delivering clean, low-cognitive-load digital experiences.
          </p>
        </div>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 280px; border-radius: 24px; padding: 35px; display: flex; flex-direction: column; justify-content: center;">
        <h4 style="margin-top: 0; margin-bottom: 16px; color: #475569; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 2px;">Languages & Automation</h4>
        <div style="margin-bottom: 24px; display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #38bdf8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(56, 189, 248, 0.15);">Python</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">PHP</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">JavaScript</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">SQL</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">Power Automate</span>
        </div>
        <h4 style="margin-top: 0; margin-bottom: 16px; color: #475569; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 2px;">Databases & Systems</h4>
        <div style="display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #a5b4fc; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(129, 140, 248, 0.12);">MySQL</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">RESTful APIs</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">Git / GitHub</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.05);">Cisco Packet Tracer</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Projects Matrix Overview -->
  <div id="projects-overview" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: linear-gradient(#10b981, #06b6d4);"></div>
      <h2 style="color: #ffffff; font-size: 28px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Technical Projects Directory</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 28px;">
      
      <!-- Laundrify Card -->
      <div class="premium-card glow-emerald" style="flex: 1; min-width: 280px; border-radius: 24px; padding: 36px; display: flex; flex-direction: column; justify-content: space-between; border-left: 3px solid #10b981 !important;">
        <div>
          <span class="pill-metric" style="background-color: rgba(16, 185, 129, 0.08); color: #6ee7b7; border: 1px solid rgba(16, 185, 129, 0.15);">Final Year Project</span>
          <h3 style="margin: 20px 0 14px 0; font-size: 22px; color: #ffffff; font-weight: 700; letter-spacing: -0.5px;">Laundrify: On-Demand Service Platform</h3>
          <p style="font-size: 14.5px; line-height: 1.7; color: #94a3b8; margin: 0 0 30px 0;">Cloud-deployed full-stack booking system with RESTful API architecture, role-based access control, and dynamic pricing calculations.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 24px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 13px; color: #cbd5e1;"><strong>Stack:</strong> Python, MySQL, Cloud</div>
          <a href="#case-study-laundrify" style="font-size: 14px; font-weight: 700; color: #6ee7b7; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Platform →</a>
        </div>
      </div>

      <!-- ErgoChef+ Card -->
      <div class="premium-card glow-orange" style="flex: 1; min-width: 280px; border-radius: 24px; padding: 36px; display: flex; flex-direction: column; justify-content: space-between; border-left: 3px solid #f97316 !important;">
        <div>
          <span class="pill-metric" style="background-color: rgba(249, 115, 22, 0.08); color: #fdba74; border: 1px solid rgba(249, 115, 22, 0.15);">Interactive Prototype</span>
          <h3 style="margin: 20px 0 14px 0; font-size: 22px; color: #ffffff; font-weight: 700; letter-spacing: -0.5px;">ErgoChef+: AI Ergonomic Assistant</h3>
          <p style="font-size: 14.5px; line-height: 1.7; color: #94a3b8; margin: 0 0 30px 0;">Context-aware kitchen guidance using posture detection models and progressive overlay notifications to reduce physical strain during cooking.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 24px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 13px; color: #cbd5e1;"><strong>Role:</strong> Lead UI/Interaction</div>
          <a href="#case-study-1-ergochef" style="font-size: 14px; font-weight: 700; color: #fdba74; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Case →</a>
        </div>
      </div>
      
      <!-- eLearn Card -->
      <div class="premium-card glow-blue" style="flex: 1; min-width: 280px; border-radius: 24px; padding: 36px; display: flex; flex-direction: column; justify-content: space-between; border-left: 3px solid #38bdf8 !important;">
        <div>
          <span class="pill-metric" style="background-color: rgba(56, 189, 248, 0.08); color: #7dd3fc; border: 1px solid rgba(56, 189, 248, 0.15);">Heuristic Audit</span>
          <h3 style="margin: 20px 0 14px 0; font-size: 22px; color: #ffffff; font-weight: 700; letter-spacing: -0.5px;">Learning Management UX Audit</h3>
          <p style="font-size: 14.5px; line-height: 1.7; color: #94a3b8; margin: 0 0 30px 0;">Empirical usability audit identifying architectural friction, nested navigational loops, and key heuristic violations on university portals.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 24px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 13px; color: #cbd5e1;"><strong>Role:</strong> Lead UX Auditor</div>
          <a href="#case-study-2-elearn-ux-audit" style="font-size: 14px; font-weight: 700; color: #7dd3fc; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Audit →</a>
        </div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 1: Laundrify -->
  <div id="case-study-laundrify" style="padding-top: 40px; margin-bottom: 80px;">
    <div class="premium-card glow-emerald" style="border-radius: 28px; padding: 45px; box-shadow: 0 40px 80px -20px rgba(0,0,0,0.6);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 28px; margin-bottom: 36px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 28px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">Laundrify – On-Demand Service Platform</h2>
          <p style="color: #10b981; font-size: 13px; font-weight: 700; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Individual Final Year Capstone Project</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 20px; border-radius: 30px; border: 1px solid rgba(255, 255, 255, 0.08);">Full-Stack Engineering & Cloud Architecture</span>
      </div>
      
      <div style="background: linear-gradient(135deg, rgba(16, 185, 129, 0.02) 0%, rgba(5, 150, 105, 0.05) 100%); border: 1px solid rgba(16, 185, 129, 0.12); border-radius: 16px; padding: 32px; margin-bottom: 40px;">
        <h4 style="margin-top: 0; color: #6ee7b7; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px; margin-bottom: 16px;">System Scope & Architectural Overview</h4>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 20px;">
          <strong>The Problem:</strong> Traditional residential laundry services lack unified real-time dispatching, transparent pricing, and centralized status tracking. Customers encounter unpredictable turnaround windows, while service providers struggle with fragmented phone and messaging coordination.
        </p>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 0;">
          <strong>The Solution:</strong> Laundrify delivers an end-to-end web platform featuring structured relational schemas, secure RESTful endpoints, role-based access management (Client vs. Administrator), dynamic weight-tier cost calculation, and continuous deployment on modern cloud platforms.
        </p>
      </div>

      <!-- 4-Pillar Engineering Architecture -->
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 45px;">
        <div style="flex: 1; min-width: 200px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #6ee7b7; font-size: 13px; display: block; margin-bottom: 8px; text-transform: uppercase;">1. REST API Architecture</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8;">Modular endpoints handling user authentication, order creation, and status transitions.</span>
        </div>
        <div style="flex: 1; min-width: 200px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #6ee7b7; font-size: 13px; display: block; margin-bottom: 8px; text-transform: uppercase;">2. Database Modeling</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8;">Indexed relational MySQL schemas enforcing strict data validation and transaction integrity.</span>
        </div>
        <div style="flex: 1; min-width: 200px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #6ee7b7; font-size: 13px; display: block; margin-bottom: 8px; text-transform: uppercase;">3. Security & Validation</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8;">Role-based permission gating, password hashing, and parameterized query validation.</span>
        </div>
        <div style="flex: 1; min-width: 200px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #6ee7b7; font-size: 13px; display: block; margin-bottom: 8px; text-transform: uppercase;">4. Cloud CI/CD</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8;">Automated deployment pipelines to ensure high availability and continuous version updates.</span>
        </div>
      </div>

      <!-- Interactive Artefacts Actions -->
      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 40px; margin-bottom: 45px; text-align: center;">
        <h4 style="margin: 0 0 8px 0; color: #ffffff; font-size: 18px; font-weight: 700;">Project Artefacts & Technical Documentation</h4>
        <p style="font-size: 14px; color: #64748b; margin: 0 0 32px 0;">Review the cloud database schemas, operational architecture diagrams, and complete engineering report.</p>
        <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; justify-content: center;">
          <!-- Replace image path with your actual repo link -->
          <div onclick="openUniversalImageModal('https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/assets/laundrify-architecture.png', 'Laundrify System Architecture')" class="badge-btn" style="flex: 1; min-width: 220px; max-width: 280px; background: linear-gradient(135deg, #10b981 0%, #059669 100%); color: white; padding: 16px 24px; border-radius: 10px; font-weight: 700; font-size: 13.5px; text-align: center; box-shadow: 0 10px 25px -5px rgba(16, 185, 129, 0.3);">View Architecture Diagram</div>
          <!-- Replace PDF path with your actual repo link -->
          <div onclick="openUniversalReportModal('22078778_Assignment1.pdf')" class="badge-btn" style="flex: 1; min-width: 220px; max-width: 280px; background-color: #111827; color: #ffffff; padding: 16px 24px; border-radius: 10px; font-weight: 700; font-size: 13.5px; text-align: center; border: 1px solid rgba(255, 255, 255, 0.08);">Read Technical Report</div>
        </div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 2: ErgoChef+ -->
  <div id="case-study-1-ergochef" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="premium-card glow-orange" style="border-radius: 28px; padding: 45px; box-shadow: 0 40px 80px -20px rgba(0,0,0,0.6);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 28px; margin-bottom: 36px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 28px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">ErgoChef+ – AI Ergonomic Assistant</h2>
          <p style="color: #f97316; font-size: 13px; font-weight: 700; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">AI-Powered Kitchen Context Ecosystem</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 20px; border-radius: 30px; border: 1px solid rgba(255, 255, 255, 0.08);">Lead UI & Interaction Designer</span>
      </div>
      
      <div style="background: linear-gradient(135deg, rgba(249, 115, 22, 0.02) 0%, rgba(234, 88, 12, 0.05) 100%); border: 1px solid rgba(249, 115, 22, 0.12); border-radius: 16px; padding: 32px; margin-bottom: 45px;">
        <h4 style="margin-top: 0; color: #fdba74; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px; margin-bottom: 16px;">Project Overview & Context</h4>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 20px;">
          <strong>The Problem:</strong> Cooking involves highly repetitive physical actions like bending, chopping, stirring, and prolonged standing that generate chronic musculoskeletal strain. Traditional smart kitchen appliances automate culinary tasks but completely disregard the user's posture.
        </p>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 0;">
          <strong>The Solution:</strong> ErgoChef+ introduces real-time posture sensing, non-intrusive progressive visual alerts, and contextual ergonomic reporting to correct posture habits without interrupting culinary workflow.
        </p>
      </div>

      <!-- 5-Phase Alignment -->
      <h4 style="color: #ffffff; font-size: 12px; font-weight: 700; margin-bottom: 24px; text-transform: uppercase; letter-spacing: 2px;">Design Process & Iterative Framework</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 45px;">
        <div style="flex: 1; min-width: 180px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #fdba74; font-size: 13px; display: block; margin-bottom: 10px; text-transform: uppercase;">1. User Research</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Conducted user surveys ($n=25$) and structured interviews to identify physical strain zones.</span>
        </div>
        <div style="flex: 1; min-width: 180px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #fdba74; font-size: 13px; display: block; margin-bottom: 10px; text-transform: uppercase;">2. Ideation & Flow</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Mapped camera-to-screen interaction paths for hands-free kitchen environments.</span>
        </div>
        <div style="flex: 1; min-width: 180px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #fdba74; font-size: 13px; display: block; margin-bottom: 10px; text-transform: uppercase;">3. Wireframing</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Positioned glanceable UI overlay alerts to keep peripheral vision uncluttered.</span>
        </div>
        <div style="flex: 1; min-width: 180px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #fdba74; font-size: 13px; display: block; margin-bottom: 10px; text-transform: uppercase;">4. High-Fi Prototype</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Developed interactive prototype evaluating pose-correction HUD responsiveness.</span>
        </div>
        <div style="flex: 1; min-width: 180px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 24px;">
          <strong style="color: #fdba74; font-size: 13px; display: block; margin-bottom: 10px; text-transform: uppercase;">5. Validation</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Measured user correction speed and minimal cognitive friction during testing.</span>
        </div>
      </div>

      <!-- Artefacts -->
      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 40px; margin-bottom: 45px; text-align: center;">
        <h4 style="margin: 0 0 8px 0; color: #ffffff; font-size: 18px; font-weight: 700;">Design Artefacts & Media</h4>
        <p style="font-size: 14px; color: #64748b; margin: 0 0 32px 0;">Explore the live application interface, video walkthrough, and high-resolution design poster.</p>
        <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; justify-content: center;">
          <a href="https://ergo-chef-journey.lovable.app/" target="_blank" class="badge-btn" style="flex: 1; min-width: 220px; max-width: 280px; background: linear-gradient(135deg, #f97316 0%, #ea580c 100%); color: white; padding: 16px 28px; border-radius: 10px; text-decoration: none; font-weight: 700; font-size: 13.5px; text-align: center; box-shadow: 0 10px 25px -5px rgba(234, 88, 12, 0.4);">Launch Live Prototype</a>
          <div onclick="openVideoModal('ergochef')" class="badge-btn" style="flex: 1; min-width: 220px; max-width: 280px; background-color: #111827; color: #ffffff; padding: 16px 28px; border-radius: 10px; font-weight: 700; font-size: 13.5px; text-align: center; border: 1px solid rgba(255, 255, 255, 0.08);">Watch Video Demo</div>
          <div onclick="openUniversalImageModal('https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true', 'ErgoChef+ Project Poster')" class="badge-btn" style="flex: 1; min-width: 220px; max-width: 280px; background-color: #374151; color: #e5e7eb; padding: 16px 28px; border-radius: 10px; font-weight: 700; font-size: 13.5px; text-align: center; border: 1px solid rgba(255, 255, 255, 0.05);">View Design Poster</div>
        </div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 3: eLearn Heuristic Audit -->
  <div id="case-study-2-elearn-ux-audit" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="premium-card glow-blue" style="border-radius: 28px; padding: 45px; box-shadow: 0 40px 80px -20px rgba(0,0,0,0.6);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 28px; margin-bottom: 36px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 26px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">Institutional eLearn UX Audit</h2>
          <p style="color: #38bdf8; font-size: 13px; font-weight: 700; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Academic Management Portal Usability Evaluation</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 20px; border-radius: 30px; border: 1px solid rgba(255, 255, 255, 0.08);">Lead Usability Auditor</span>
      </div>
      
      <div style="background: linear-gradient(135deg, rgba(56, 189, 248, 0.02) 0%, rgba(56, 189, 248, 0.03) 100%); border: 1px solid rgba(56, 189, 248, 0.08); border-radius: 16px; padding: 32px; margin-bottom: 40px;">
        <h4 style="margin-top: 0; color: #7dd3fc; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px; margin-bottom: 16px;">Audit Scope & Empirical Discovery</h4>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 0;">
          Assessed academic portal architecture through rigorous heuristic evaluations and cognitive walkthroughs. Uncovered critical navigation loops, inconsistent status indicators, and cognitive overload points, formulating a centralized card directory layout to streamline student access.
        </p>
      </div>

      <!-- Diagnostic Table -->
      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 35px; margin-bottom: 45px;">
        <div style="border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 16px; margin-bottom: 20px;">
          <h4 style="margin: 0; color: #ffffff; font-size: 17px; font-weight: 700;">Empirical Usability Diagnostic Log</h4>
          <p style="font-size: 13px; color: #64748b; margin: 4px 0 0 0;">Identified defects categorized under Nielsen Norman Heuristics.</p>
        </div>
        
        <div class="audit-table-wrapper">
          <table class="audit-table">
            <thead>
              <tr>
                <th>ID</th>
                <th>Target Heuristic</th>
                <th>Mechanics & Defect Description</th>
                <th>Severity</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V01</td>
                <td>H2: System & Real World</td>
                <td>Internal database keys and cryptic system strings exposed on primary portal headers.</td>
                <td><span style="background: rgba(245, 158, 11, 0.1); color: #f59e0b; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 2</span></td>
              </tr>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V03</td>
                <td>H4: Consistency Standards</td>
                <td>Course directory filtering fails intermittently on upper-tier student accounts, returning blank containers.</td>
                <td><span style="background: rgba(239, 68, 68, 0.1); color: #ef4444; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 3</span></td>
              </tr>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V04</td>
                <td>H7: Flexibility & Efficiency</td>
                <td>Workspace directories cluttered with completed, expired course cards lacking automated archive triggers.</td>
                <td><span style="background: rgba(239, 68, 68, 0.1); color: #ef4444; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 3</span></td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>

      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 35px; text-align: center;">
        <h4 style="margin: 0 0 8px 0; color: #ffffff; font-size: 18px; font-weight: 700;">Full Usability Report</h4>
        <p style="font-size: 14px; color: #64748b; margin: 0 0 24px 0;">Access the comprehensive 24-page analytical report detailing empirical metrics and redesign prototypes.</p>
        <div class="badge-btn-container">
          <div onclick="openUniversalReportModal('22078778_Assignment1.pdf')" class="badge-btn" style="background: linear-gradient(135deg, #38bdf8 0%, #0284c7 100%); color: #020617 !important; padding: 14px 28px; border-radius: 10px; font-weight: 700; font-size: 14px; text-align: center; box-shadow: 0 10px 25px -5px rgba(56, 189, 248, 0.3);">View Complete Report PDF</div>
        </div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 4: EZShop -->
  <div id="case-study-ezshop" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="premium-card glow-blue" style="border-radius: 28px; padding: 45px; box-shadow: 0 40px 80px -20px rgba(0,0,0,0.6);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 28px; margin-bottom: 36px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 26px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">EZShop – E-Commerce Web Application</h2>
          <p style="color: #818cf8; font-size: 13px; font-weight: 700; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Relational Web Platform Architecture</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 20px; border-radius: 30px; border: 1px solid rgba(255, 255, 255, 0.08);">Full-Stack Web Development</span>
      </div>

      <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 24px;">
        Developed a fully responsive online retail store using <strong>PHP, MySQL, HTML5, and CSS3</strong>. Engineered indexed search queries, persistent user session handling, dynamic shopping cart logic, order confirmation pipelines, and reward point accounting.
      </p>

      <div style="display: flex; gap: 16px; flex-wrap: wrap;">
        <!-- Replace with your actual ERD diagram image path -->
        <div onclick="openUniversalImageModal('https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/assets/ezshop-erd.png', 'EZShop Database Schema')" class="badge-btn" style="background-color: #111827; color: #cbd5e1; padding: 12px 24px; border-radius: 8px; border: 1px solid rgba(255,255,255,0.08); font-size: 13px; font-weight: 600;">View Entity Relationship Diagram (ERD)</div>
      </div>

    </div>
  </div>

  <!-- Personal Challenges Section -->
  <div id="personal-challenges" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: linear-gradient(#6366f1, #a855f7);"></div>
      <h2 style="color: #ffffff; font-size: 28px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Engineering Challenges & Solutions</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px; margin-bottom: 24px;">
      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Markdown Styling Restrictions</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Standard GitHub theme parsers stripped out traditional CSS layouts, breaking typography sizes and viewport parameters.
          <br><br>
          <strong>Resolution:</strong> Encapsulated structural layouts inside raw inline HTML wrapper components with explicit style assignments, bypassing markdown parser limitations.
        </p>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Cross-Terminal Git Merge Collisions</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Updating media assets across testing workstations triggered tree conflicts and dropped local file references.
          <br><br>
          <strong>Resolution:</strong> Structured a strict upstream branch rebase workflow with dedicated asset tracking tags to maintain branch integrity.
        </p>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Asset URL Path Standardization</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Relative local paths resulted in missing previews and broken resource links across different viewing devices.
          <br><br>
          <strong>Resolution:</strong> Shifted media deliveries to raw absolute GitHub repository URLs, ensuring permanent, cache-safe visibility.
        </p>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: rgba(255,255,255,0.05); margin: 60px 0;">

  <!-- Submission Verification -->
  <div id="submission" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="premium-card glow-blue" style="border-radius: 20px; padding: 40px; display: flex; align-items: center; gap: 28px; flex-wrap: wrap;">
      <div style="background-color: rgba(255,255,255,0.02); padding: 20px; border-radius: 50%; border: 1px solid rgba(255,255,255,0.05); font-size: 22px;">📋</div>
      <div style="flex: 1; min-width: 260px;">
        <h3 style="color: #ffffff; font-size: 20px; font-weight: 700; margin: 0 0 10px 0;">Academic Integrity & Project Verification</h3>
        <p style="font-size: 14.5px; color: #94a3b8; line-height: 1.7; margin: 0;">
          This web portfolio is documented and maintained in full alignment with university academic standards. All listed architecture models, database schemas, and usability audit matrices represent authentic engineering work conducted by the student. Generative AI development tools were purposefully utilized for front-end interface scripting, styling optimization, and editorial refinement.
        </p>
      </div>
    </div>
  </div>

  <!-- UNIVERSAL MODAL 1: Dynamic Image / Poster Lightbox -->
  <div id="universalImageModal" class="custom-modal-overlay" onclick="closeUniversalImageModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeUniversalImageModal()">&times;</button>
    <div class="custom-modal-window" id="imageModalWindow">
      <img id="universalModalImg" class="custom-modal-content" src="" alt="Project Artefact" />
    </div>
  </div>

  <!-- UNIVERSAL MODAL 2: Video Lightbox -->
  <div id="videoModal" class="custom-modal-overlay" onclick="closeVideoModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeVideoModal()">&times;</button>
    <div class="video-modal-window">
      <iframe id="videoPlayerFrame" class="video-frame" src="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>

  <!-- UNIVERSAL MODAL 3: Dynamic PDF Document Viewer -->
  <div id="universalReportModal" class="custom-modal-overlay" onclick="closeUniversalReportModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeUniversalReportModal()">&times;</button>
    <div class="report-modal-window">
      <iframe id="universalPdfFrame" class="report-frame" src=""></iframe>
      <div class="mobile-pdf-fallback">
        <p style="color: #94a3b8; font-size: 14px; margin-bottom: 16px;">Mobile browsers may require opening documents directly:</p>
        <a id="universalPdfDownloadLink" href="#" target="_blank" style="background: linear-gradient(135deg, #38bdf8 0%, #0284c7 100%); color: #020617; padding: 14px 28px; border-radius: 10px; font-weight: 700; font-size: 14px; text-decoration: none;">Open Document Directly</a>
      </div>
    </div>
  </div>

</div>

<!-- JavaScript Engine: Typewriter & Modal Control -->
<script>
  /* Typewriter Initialization */
  const w1 = "MALCOLM";
  const w2 = "JEREMIAH";
  const w3 = "RICHARD";
  const taglineStr = "BSC (HONS) INFORMATION TECHNOLOGY | ENTERPRISE & SOFTWARE PORTFOLIO";
  
  const c1 = document.getElementById("js-type-name-1");
  const c2 = document.getElementById("js-type-name-2");
  const c3 = document.getElementById("js-type-name-3");
  const tagline = document.getElementById("js-type-tagline");

  let idx = 0;

  function typeSequence() {
    if (idx < w1.length) {
      c1.innerHTML += w1.charAt(idx);
      idx++;
      setTimeout(typeSequence, 50);
    } 
    else if (idx < w1.length + w2.length) {
      if(idx === w1.length) { c1.innerHTML += "&nbsp;"; }
      c2.innerHTML += w2.charAt(idx - w1.length);
      idx++;
      setTimeout(typeSequence, 50);
    } 
    else if (idx < w1.length + w2.length + w3.length) {
      if(idx === w1.length + w2.length) { c2.innerHTML += "&nbsp;"; }
      c3.innerHTML += w3.charAt(idx - (w1.length + w2.length));
      idx++;
      setTimeout(typeSequence, 50);
    } 
    else {
      idx = 0;
      setTimeout(typeTagline, 250);
    }
  }

  function typeTagline() {
    if (idx < taglineStr.length) {
      tagline.innerHTML += taglineStr.charAt(idx);
      idx++;
      setTimeout(typeTagline, 35);
    }
  }

  window.addEventListener("DOMContentLoaded", () => {
    setTimeout(typeSequence, 400);
  });

  /* Modal Mechanics */
  const universalImageModal = document.getElementById('universalImageModal');
  const universalModalImg = document.getElementById('universalModalImg');
  const videoModal = document.getElementById('videoModal');
  const videoPlayerFrame = document.getElementById('videoPlayerFrame');
  const universalReportModal = document.getElementById('universalReportModal');
  const universalPdfFrame = document.getElementById('universalPdfFrame');
  const universalPdfDownloadLink = document.getElementById('universalPdfDownloadLink');

  /* Dynamic Image / Poster Handler */
  function openUniversalImageModal(imgSrc, altText) {
    resetZoom();
    universalModalImg.src = imgSrc;
    universalModalImg.alt = altText || 'Technical Artefact';
    universalImageModal.classList.add('is-active');
    document.body.style.overflow = 'hidden'; 
  }

  function closeUniversalImageModal() {
    universalImageModal.classList.remove('is-active');
    document.body.style.overflow = ''; 
    resetZoom();
  }

  function closeUniversalImageModalFromOverlay(event) {
    if (event.target.id === 'universalImageModal' || event.target.id === 'imageModalWindow') {
      closeUniversalImageModal();
    }
  }

  /* Dynamic Video Handler */
  function openVideoModal(videoType) {
    let embedUrl = "";
    if (videoType === 'walkthrough') {
      embedUrl = "https://www.youtube-nocookie.com/embed/JaEmmGhA464?autoplay=1";
    } else if (videoType === 'ergochef') {
      embedUrl = "https://www.youtube-nocookie.com/embed/-QOms8I-tbM?autoplay=1";
    }
    videoPlayerFrame.src = embedUrl;
    videoModal.classList.add('is-active');
    document.body.style.overflow = 'hidden';
  }

  function closeVideoModal() {
    videoPlayerFrame.src = "";
    videoModal.classList.remove('is-active');
    document.body.style.overflow = '';
  }

  function closeVideoModalFromOverlay(event) {
    if (event.target.id === 'videoModal') {
      closeVideoModal();
    }
  }

  /* Dynamic PDF Report Handler */
  function openUniversalReportModal(pdfPath) {
    universalPdfFrame.src = pdfPath + "#toolbar=1&navpanes=1&scrollbar=1";
    universalPdfDownloadLink.href = pdfPath;
    universalReportModal.classList.add('is-active');
    document.body.style.overflow = 'hidden';
  }

  function closeUniversalReportModal() {
    universalPdfFrame.src = "";
    universalReportModal.classList.remove('is-active');
    document.body.style.overflow = '';
  }

  function closeUniversalReportModalFromOverlay(event) {
    if (event.target.id === 'universalReportModal') {
      closeUniversalReportModal();
    }
  }

  /* Global Keyboard Esc Handler */
  document.addEventListener('keydown', (event) => {
    if (event.key === 'Escape') {
      closeUniversalImageModal();
      closeVideoModal();
      closeUniversalReportModal();
    }
  });

  /* Pan & Zoom Mechanics */
  let isZoomed = false;
  let isDragging = false;
  let startX, startY;
  let translateX = 0, translateY = 0;

  universalModalImg.addEventListener('click', (event) => {
    event.stopPropagation();
    if (!isZoomed) {
      isZoomed = true;
      universalModalImg.style.cursor = 'zoom-out';
      const rect = universalModalImg.getBoundingClientRect();
      const clickX = (event.clientX - rect.left) / rect.width;
      const clickY = (event.clientY - rect.top) / rect.height;
      universalModalImg.style.transformOrigin = `${clickX * 100}% ${clickY * 100}%`;
      universalModalImg.style.transform = 'scale(2.2)';
    } else {
      resetZoom();
    }
  });

  universalModalImg.addEventListener('mousedown', (event) => {
    if (!isZoomed) return;
    isDragging = true;
    startX = event.clientX - translateX;
    startY = event.clientY - translateY;
    universalModalImg.style.cursor = 'grabbing';
  });

  window.addEventListener('mousemove', (event) => {
    if (!isDragging || !isZoomed) return;
    event.preventDefault();
    translateX = event.clientX - startX;
    translateY = event.clientY - startY;
    universalModalImg.style.transform = `scale(2.2) translate(${translateX / 2.2}px, ${translateY / 2.2}px)`;
  });

  window.addEventListener('mouseup', () => { 
    if(isZoomed) universalModalImg.style.cursor = 'zoom-out';
    isDragging = false; 
  });

  function resetZoom() {
    isZoomed = false;
    isDragging = false;
    translateX = 0;
    translateY = 0;
    universalModalImg.style.cursor = 'zoom-in';
    universalModalImg.style.transform = 'scale(1) translate(0px, 0px)';
    universalModalImg.style.transformOrigin = 'center center';
  }
</script>
