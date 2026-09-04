<!-- Enterprise Modern Light Theme Layout Engine -->
<style>
  /* Force hide GitHub Pages theme defaults */
  header.page-header, .page-header, .site-header {
    display: none !important;
  }

  html {
    scroll-behavior: smooth !important;
    background-color: #f8fafc !important;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    color: #0f172a !important;
    letter-spacing: -0.1px;
    overflow-x: hidden;
  }
  
  body {
    max-width: 1140px !important;
    padding: 30px 20px !important;
    margin: 0 auto !important;
    background-color: #f8fafc !important;
    position: relative;
  }
  
  .main-content {
    max-width: 100% !important;
    padding: 0 !important;
    box-sizing: border-box !important;
  }

  /* Clean Minimalist Hero Card */
  .custom-portfolio-header {
    background: #ffffff !important;
    padding: 4.5rem 2rem 4rem 2rem !important;
    text-align: center !important;
    border-radius: 20px !important;
    box-shadow: 0 10px 30px -10px rgba(15, 23, 42, 0.08) !important;
    border: 1px solid #e2e8f0 !important;
    margin-top: 10px !important;
    margin-bottom: 35px !important;
    display: flex !important;
    flex-direction: column !important;
    align-items: center !important;
    justify-content: center !important;
  }
  
  .name-word-group {
    display: inline-block !important;
    white-space: nowrap !important;
  }

  .typewriter-title {
    color: #0f172a !important;
    font-size: 38px !important;
    font-weight: 800 !important;
    letter-spacing: -0.8px !important;
    margin: 0 !important;
    text-align: center !important;
    line-height: 1.25;
    min-height: 48px;
  }

  .typewriter-tagline {
    color: #64748b !important;
    font-size: 12px !important;
    font-weight: 700 !important;
    text-transform: uppercase !important;
    letter-spacing: 2px !important;
    margin: 14px 0 0 0 !important;
    text-align: center !important;
    line-height: 1.5;
    width: 100% !important;
    display: block !important;
  }

  .blinking-cursor {
    display: inline-block !important;
    color: #2563eb !important; 
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

  /* Minimalist Clean Navigation Dock */
  .nav-container {
    position: -webkit-sticky;
    position: sticky;
    top: 20px;
    z-index: 999;
    display: flex;
    justify-content: center;
    background-color: rgba(255, 255, 255, 0.92);
    -webkit-backdrop-filter: blur(16px);
    backdrop-filter: blur(16px);
    padding: 6px;
    border-radius: 40px;
    border: 1px solid #cbd5e1;
    box-shadow: 0 10px 25px -5px rgba(15, 23, 42, 0.06);
    margin-bottom: 60px;
  }

  .nav-btn {
    position: relative !important;
    white-space: nowrap !important;
    color: #475569 !important;
    padding: 10px 20px !important;
    border-radius: 30px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 13px !important;
    display: inline-block !important;
    transition: all 0.25s ease !important;
  }
  
  .nav-btn:hover {
    color: #0f172a !important;
    background-color: #f1f5f9 !important;
  }

  /* Modern Solid Clean Surface Cards */
  .premium-card {
    background: #ffffff !important;
    border: 1px solid #e2e8f0 !important;
    box-shadow: 0 8px 24px -6px rgba(15, 23, 42, 0.05) !important;
    transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1) !important;
  }
  
  .premium-card:hover {
    box-shadow: 0 16px 36px -8px rgba(15, 23, 42, 0.09) !important;
    border-color: #cbd5e1 !important;
  }
  
  .badge-btn {
    transition: all 0.25s ease !important;
    cursor: pointer !important;
    display: inline-block;
  }
  .badge-btn:hover {
    transform: translateY(-2px) !important;
    filter: brightness(0.96);
  }

  .section-title-wrapper {
    display: flex;
    align-items: center;
    gap: 14px;
    margin-bottom: 28px;
  }
  .section-bar {
    width: 4px;
    height: 26px;
    border-radius: 4px;
  }
  
  .pill-metric {
    font-size: 11px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.8px;
    padding: 5px 12px;
    border-radius: 16px;
    display: inline-block;
  }

  /* Fixed Clean High-Contrast Usability Table */
  .audit-table-wrapper {
    width: 100% !important;
    overflow-x: auto !important;
    -webkit-overflow-scrolling: touch !important;
    border-radius: 12px !important;
    background: #ffffff !important;
    border: 1px solid #e2e8f0 !important;
    margin-top: 20px !important;
  }

  .audit-table {
    width: 100% !important;
    min-width: 700px !important;
    border-collapse: collapse !important;
    font-size: 13.5px !important;
    color: #334155 !important;
    background: #ffffff !important;
  }
  .audit-table th {
    text-align: left !important;
    padding: 14px 18px !important;
    background: #f8fafc !important;
    color: #0f172a !important;
    font-weight: 700 !important;
    border-bottom: 1px solid #e2e8f0 !important;
  }
  .audit-table td {
    padding: 14px 18px !important;
    border-bottom: 1px solid #f1f5f9 !important;
    line-height: 1.6 !important;
  }

  /* Modals */
  .custom-modal-overlay {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: rgba(15, 23, 42, 0.75) !important;
    backdrop-filter: blur(12px) !important;
    -webkit-backdrop-filter: blur(12px) !important;
    z-index: 10000 !important;
    display: none !important;
    align-items: center !important;
    justify-content: center !important;
    opacity: 0 !important;
    transition: opacity 0.25s ease !important;
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
    transition: transform 0.25s ease !important;
    box-shadow: 0 20px 50px rgba(0, 0, 0, 0.3) !important;
    cursor: zoom-in !important;
  }

  .video-modal-window {
    width: 80vw !important;
    max-width: 960px !important;
    height: 0 !important;
    padding-bottom: 45% !important;
    background-color: #000000 !important;
    border-radius: 16px !important;
    border: 1px solid #334155 !important;
    box-shadow: 0 20px 50px rgba(0, 0, 0, 0.4) !important;
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
    background-color: #ffffff !important;
    border-radius: 16px !important;
    border: 1px solid #cbd5e1 !important;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.25) !important;
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
    background: #ffffff !important;
  }

  .custom-modal-close-btn {
    position: fixed !important;
    top: 25px !important;
    right: 35px !important;
    background: #ffffff !important;
    border: 1px solid #cbd5e1 !important;
    color: #0f172a !important;
    font-size: 22px !important;
    width: 40px !important;
    height: 40px !important;
    border-radius: 50% !important;
    cursor: pointer !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1) !important;
    z-index: 10001 !important;
  }

  /* Responsive Adjustments */
  @media (max-width: 768px) {
    body { padding-top: 10px !important; padding-bottom: 20px !important; }
    .custom-portfolio-header, #who-i-am, #projects-overview, #case-study-laundrify, #case-study-1-ergochef, #case-study-2-elearn-ux-audit, #case-study-ezshop {
      border-radius: 14px !important; 
      padding: 24px 16px !important;
      width: 100% !important;
    }
    .nav-container {
      justify-content: flex-start !important;
      overflow-x: auto !important;
      -webkit-overflow-scrolling: touch !important;
      border-radius: 0px !important;
      padding: 6px !important;
      margin-bottom: 30px;
    }
    .nav-container::-webkit-scrollbar { display: none !important; }
    .nav-btn { padding: 8px 14px !important; font-size: 12px !important; }
  }
</style>

<div class="main-content">

  <!-- Minimalist Hero Header (No Repo Title / No Awkward Lines / No Walkthrough Button) -->
  <div class="custom-portfolio-header">
    <h1 class="typewriter-title">
      <span class="name-word-group" id="js-type-name-1"></span> 
      <span class="name-word-group" id="js-type-name-2"></span> 
      <span class="name-word-group"><span id="js-type-name-3"></span><span id="js-cursor-name" class="blinking-cursor">_</span></span>
    </h1>
    <h2 id="js-type-tagline" class="typewriter-tagline"></h2>
  </div>

  <!-- Clean Navigation Dock (Challenges & Submission Removed) -->
  <div class="nav-container">
    <a href="#who-i-am" class="nav-btn">Profile</a>
    <a href="#projects-overview" class="nav-btn">Projects</a>
    <a href="#case-study-laundrify" class="nav-btn">Laundrify (FYP)</a>
    <a href="#case-study-1-ergochef" class="nav-btn">ErgoChef+</a>
    <a href="#case-study-2-elearn-ux-audit" class="nav-btn">eLearn Audit</a>
    <a href="#case-study-ezshop" class="nav-btn">EZShop</a>
  </div>

  <!-- Profile Section -->
  <div id="who-i-am" style="padding-top: 10px; margin-bottom: 60px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: #2563eb;"></div>
      <h2 style="color: #0f172a; font-size: 24px; font-weight: 700; margin: 0;">Profile Overview</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px;">
      <div class="premium-card" style="flex: 2; min-width: 320px; border-radius: 16px; padding: 36px; display: flex; gap: 30px; align-items: center; flex-wrap: wrap;">
        <div style="flex-shrink: 0;">
          <img src="https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/WhatsApp%20Image%202026-07-03%20at%2010.14.22%20PM.jpeg" alt="Malcolm Jeremiah Richard" style="width: 105px; height: 105px; border-radius: 50%; object-fit: cover; border: 3px solid #e2e8f0;" />
        </div>
        <div style="flex: 1; min-width: 240px;">
          <p style="font-size: 15.5px; line-height: 1.8; color: #334155; margin: 0; font-weight: 400;">
            Recent <strong>Information Technology</strong> graduate with hands-on experience in full-stack web development, enterprise automation, and systems architecture gained through corporate internship work at Maybank. Practical background in designing scalable databases, scripting operational automation tools, and applying foundational networking and cybersecurity practices.
          </p>
        </div>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 280px; border-radius: 16px; padding: 30px; display: flex; flex-direction: column; justify-content: center;">
        <h4 style="margin-top: 0; margin-bottom: 14px; color: #64748b; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px;">Core Stack & Scripting</h4>
        <div style="margin-bottom: 20px; display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #2563eb; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">Python</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">PHP</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">JavaScript</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">SQL</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">Power Automate</span>
        </div>
        <h4 style="margin-top: 0; margin-bottom: 14px; color: #64748b; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px;">Databases & Tools</h4>
        <div style="display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #0284c7; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">MySQL</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">RESTful APIs</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">Git / GitHub</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 5px 12px; border-radius: 16px; border: 1px solid #e2e8f0;">Cisco Packet Tracer</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Projects Directory Overview -->
  <div id="projects-overview" style="padding-top: 10px; margin-bottom: 60px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: #0284c7;"></div>
      <h2 style="color: #0f172a; font-size: 24px; font-weight: 700; margin: 0;">Featured Projects</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px;">
      
      <!-- Laundrify Card -->
      <div class="premium-card" style="flex: 1; min-width: 260px; border-radius: 16px; padding: 28px; display: flex; flex-direction: column; justify-content: space-between; border-top: 4px solid #10b981 !important;">
        <div>
          <span class="pill-metric" style="background-color: #ecfdf5; color: #059669; border: 1px solid #a7f3d0;">Final Year Project</span>
          <h3 style="margin: 16px 0 10px 0; font-size: 19px; color: #0f172a; font-weight: 700;">Laundrify Platform</h3>
          <p style="font-size: 14px; line-height: 1.6; color: #64748b; margin: 0 0 24px 0;">Cloud-deployed booking ecosystem with RESTful APIs, role-based auth, and automated operational pipelines.</p>
        </div>
        <div style="border-top: 1px solid #f1f5f9; padding-top: 16px;">
          <a href="#case-study-laundrify" style="font-size: 13.5px; font-weight: 700; color: #059669; text-decoration: none;">View Details →</a>
        </div>
      </div>

      <!-- ErgoChef+ Card -->
      <div class="premium-card" style="flex: 1; min-width: 260px; border-radius: 16px; padding: 28px; display: flex; flex-direction: column; justify-content: space-between; border-top: 4px solid #ea580c !important;">
        <div>
          <span class="pill-metric" style="background-color: #fff7ed; color: #ea580c; border: 1px solid #fed7aa;">Interactive Prototype</span>
          <h3 style="margin: 16px 0 10px 0; font-size: 19px; color: #0f172a; font-weight: 700;">ErgoChef+ Assistant</h3>
          <p style="font-size: 14px; line-height: 1.6; color: #64748b; margin: 0 0 24px 0;">Context-aware kitchen guidance using posture detection models and progressive overlay UI notifications.</p>
        </div>
        <div style="border-top: 1px solid #f1f5f9; padding-top: 16px;">
          <a href="#case-study-1-ergochef" style="font-size: 13.5px; font-weight: 700; color: #ea580c; text-decoration: none;">View Details →</a>
        </div>
      </div>
      
      <!-- eLearn Card -->
      <div class="premium-card" style="flex: 1; min-width: 260px; border-radius: 16px; padding: 28px; display: flex; flex-direction: column; justify-content: space-between; border-top: 4px solid #0284c7 !important;">
        <div>
          <span class="pill-metric" style="background-color: #f0f9ff; color: #0284c7; border: 1px solid #bae6fd;">Heuristic Audit</span>
          <h3 style="margin: 16px 0 10px 0; font-size: 19px; color: #0f172a; font-weight: 700;">eLearn UX Audit</h3>
          <p style="font-size: 14px; line-height: 1.6; color: #64748b; margin: 0 0 24px 0;">Empirical usability audit identifying architectural friction and navigation loops on university portals.</p>
        </div>
        <div style="border-top: 1px solid #f1f5f9; padding-top: 16px;">
          <a href="#case-study-2-elearn-ux-audit" style="font-size: 13.5px; font-weight: 700; color: #0284c7; text-decoration: none;">View Details →</a>
        </div>
      </div>

      <!-- EZShop Card -->
      <div class="premium-card" style="flex: 1; min-width: 260px; border-radius: 16px; padding: 28px; display: flex; flex-direction: column; justify-content: space-between; border-top: 4px solid #6366f1 !important;">
        <div>
          <span class="pill-metric" style="background-color: #eef2ff; color: #4f46e5; border: 1px solid #c7d2fe;">Full-Stack Store</span>
          <h3 style="margin: 16px 0 10px 0; font-size: 19px; color: #0f172a; font-weight: 700;">EZShop Platform</h3>
          <p style="font-size: 14px; line-height: 1.6; color: #64748b; margin: 0 0 24px 0;">Relational e-commerce web platform engineered with session security, live inventory, and checkout logic.</p>
        </div>
        <div style="border-top: 1px solid #f1f5f9; padding-top: 16px;">
          <a href="#case-study-ezshop" style="font-size: 13.5px; font-weight: 700; color: #4f46e5; text-decoration: none;">View Details →</a>
        </div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 1: Laundrify -->
  <div id="case-study-laundrify" style="padding-top: 10px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 18px; padding: 36px;">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid #e2e8f0; padding-bottom: 20px; margin-bottom: 24px; gap: 14px;">
        <div>
          <h2 style="color: #0f172a; font-size: 24px; font-weight: 800; margin: 0;">Laundrify – On-Demand Service Platform</h2>
          <p style="color: #059669; font-size: 12px; font-weight: 700; margin: 6px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Individual Final Year Project (FYP)</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 16px; border-radius: 20px; border: 1px solid #e2e8f0;">Full-Stack & Cloud Architecture</span>
      </div>
      
      <p style="font-size: 15px; line-height: 1.75; color: #334155; margin-bottom: 24px;">
        Laundrify is an end-to-end on-demand service ecosystem designed to eliminate logistical bottlenecks in residential laundry workflows. Built from the ground up with modular <strong>RESTful APIs</strong>, relational data schemas, and role-based access control (RBAC), the platform ensures consistent state synchronizations across customer booking interfaces and administrative fulfillment dashboards.
      </p>

      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 14px; margin-bottom: 30px;">
        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 18px;">
          <strong style="color: #059669; font-size: 13px; display: block; margin-bottom: 6px;">RESTful Core</strong>
          <span style="font-size: 13px; color: #64748b; line-height: 1.5; display: block;">Modular JSON endpoints enforcing sanitized payload structures and automated status updates.</span>
        </div>
        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 18px;">
          <strong style="color: #059669; font-size: 13px; display: block; margin-bottom: 6px;">Database Integrity</strong>
          <span style="font-size: 13px; color: #64748b; line-height: 1.5; display: block;">Indexed relational MySQL schemas with transactional integrity checks preventing race conditions.</span>
        </div>
        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 18px;">
          <strong style="color: #059669; font-size: 13px; display: block; margin-bottom: 6px;">Role Gating & Auth</strong>
          <span style="font-size: 13px; color: #64748b; line-height: 1.5; display: block;">Role-based permission gating to segregate customer booking views from administrative fulfillment.</span>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 12px;">
        <div onclick="openUniversalImageModal('https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/assets/laundrify-architecture.png', 'Laundrify System Architecture')" class="badge-btn" style="background: #059669; color: white; padding: 12px 22px; border-radius: 8px; font-weight: 600; font-size: 13px;">View Architecture Diagram</div>
        <div onclick="openUniversalReportModal('22078778_Assignment1.pdf')" class="badge-btn" style="background: #ffffff; color: #0f172a; padding: 12px 22px; border-radius: 8px; font-weight: 600; font-size: 13px; border: 1px solid #cbd5e1;">Read Technical Report</div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 2: ErgoChef+ -->
  <div id="case-study-1-ergochef" style="padding-top: 10px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 18px; padding: 36px;">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid #e2e8f0; padding-bottom: 20px; margin-bottom: 24px; gap: 14px;">
        <div>
          <h2 style="color: #0f172a; font-size: 24px; font-weight: 800; margin: 0;">ErgoChef+ – AI Ergonomic Assistant</h2>
          <p style="color: #ea580c; font-size: 12px; font-weight: 700; margin: 6px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">AI-Powered Kitchen Context Ecosystem</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 16px; border-radius: 20px; border: 1px solid #e2e8f0;">Lead UI & Interaction Designer</span>
      </div>
      
      <p style="font-size: 15px; line-height: 1.75; color: #334155; margin-bottom: 24px;">
        An AI-assisted ergonomic interface designed to mitigate chronic physical fatigue and musculoskeletal strain during extended culinary prep. ErgoChef+ integrates posture detection frameworks, non-intrusive alert HUDs, and telemetry reporting to build sustainable kitchen ergonomics.
      </p>

      <div style="display: flex; flex-wrap: wrap; gap: 12px;">
        <a href="https://ergo-chef-journey.lovable.app/" target="_blank" class="badge-btn" style="background: #ea580c; color: white; padding: 12px 22px; border-radius: 8px; text-decoration: none; font-weight: 600; font-size: 13px;">Launch Live Prototype</a>
        <div onclick="openVideoModal('ergochef')" class="badge-btn" style="background: #ffffff; color: #0f172a; padding: 12px 22px; border-radius: 8px; font-weight: 600; font-size: 13px; border: 1px solid #cbd5e1;">Watch Video Demo</div>
        <div onclick="openUniversalImageModal('https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true', 'ErgoChef+ Project Poster')" class="badge-btn" style="background: #ffffff; color: #0f172a; padding: 12px 22px; border-radius: 8px; font-weight: 600; font-size: 13px; border: 1px solid #cbd5e1;">View Project Poster</div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 3: eLearn Heuristic Audit -->
  <div id="case-study-2-elearn-ux-audit" style="padding-top: 10px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 18px; padding: 36px;">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid #e2e8f0; padding-bottom: 20px; margin-bottom: 24px; gap: 14px;">
        <div>
          <h2 style="color: #0f172a; font-size: 24px; font-weight: 800; margin: 0;">Institutional eLearn UX Audit</h2>
          <p style="color: #0284c7; font-size: 12px; font-weight: 700; margin: 6px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Academic Management Portal Usability Evaluation</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 16px; border-radius: 20px; border: 1px solid #e2e8f0;">Lead Usability Auditor</span>
      </div>
      
      <p style="font-size: 15px; line-height: 1.75; color: #334155; margin-bottom: 20px;">
        Conducted an empirical usability evaluation on the institutional academic portal utilizing Nielsen Norman heuristics and cognitive walkthroughs to isolate structural navigation bottlenecks and multi-click journey loops.
      </p>

      <!-- Clean High-Contrast Diagnostic Table -->
      <div class="audit-table-wrapper">
        <table class="audit-table">
          <thead>
            <tr>
              <th>Violation ID</th>
              <th>Heuristic Target</th>
              <th>Failure Description</th>
              <th>Severity</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td style="color: #0284c7; font-weight: 700;">V01</td>
              <td>H2: System & Real World</td>
              <td>Raw internal database keys and obscure system parameters exposed on main portal headings.</td>
              <td><span style="background: #fef3c7; color: #b45309; padding: 3px 8px; border-radius: 4px; font-weight: 700; font-size: 11px;">Severity 2</span></td>
            </tr>
            <tr>
              <td style="color: #0284c7; font-weight: 700;">V03</td>
              <td>H4: Consistency Standards</td>
              <td>Course catalog filtering consistently drops active enrollment modules on upper-tier student accounts.</td>
              <td><span style="background: #fee2e2; color: #b91c1c; padding: 3px 8px; border-radius: 4px; font-weight: 700; font-size: 11px;">Severity 3</span></td>
            </tr>
            <tr>
              <td style="color: #0284c7; font-weight: 700;">V04</td>
              <td>H7: Flexibility & Efficiency</td>
              <td>Primary dashboards cluttered with archived, static modules lacking automated seasonal archival triggers.</td>
              <td><span style="background: #fee2e2; color: #b91c1c; padding: 3px 8px; border-radius: 4px; font-weight: 700; font-size: 11px;">Severity 3</span></td>
            </tr>
          </tbody>
        </table>
      </div>

      <div style="margin-top: 24px;">
        <div onclick="openUniversalReportModal('22078778_Assignment1.pdf')" class="badge-btn" style="background: #0284c7; color: white; padding: 12px 22px; border-radius: 8px; font-weight: 600; font-size: 13px;">View Complete Audit Report PDF</div>
      </div>

    </div>
  </div>

  <!-- Detailed Project 4: EZShop (Expanded Architecture & DB Specs) -->
  <div id="case-study-ezshop" style="padding-top: 10px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 18px; padding: 36px;">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid #e2e8f0; padding-bottom: 20px; margin-bottom: 24px; gap: 14px;">
        <div>
          <h2 style="color: #0f172a; font-size: 24px; font-weight: 800; margin: 0;">EZShop – E-Commerce Web Application</h2>
          <p style="color: #4f46e5; font-size: 12px; font-weight: 700; margin: 6px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Relational E-Commerce Platform Architecture</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 16px; border-radius: 20px; border: 1px solid #e2e8f0;">Full-Stack PHP / MySQL</span>
      </div>

      <p style="font-size: 15px; line-height: 1.75; color: #334155; margin-bottom: 20px;">
        EZShop is a transactional online retail web platform built natively using <strong>PHP, MySQL, HTML5, and CSS3</strong>. The system architecture emphasizes data normalization, authenticated transaction flows, and responsive UI components.
      </p>

      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 14px; margin-bottom: 28px;">
        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 18px;">
          <strong style="color: #4f46e5; font-size: 13px; display: block; margin-bottom: 6px;">Catalog Indexing & Search</strong>
          <span style="font-size: 13px; color: #64748b; line-height: 1.5; display: block;">Structured SQL index modeling enabling rapid real-time product filtering, category isolation, and price range sorting.</span>
        </div>
        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 18px;">
          <strong style="color: #4f46e5; font-size: 13px; display: block; margin-bottom: 6px;">Session & Cart State</strong>
          <span style="font-size: 13px; color: #64748b; line-height: 1.5; display: block;">Encrypted PHP session handling maintaining cart state persistence across page navigation and authenticated checkout transitions.</span>
        </div>
        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 18px;">
          <strong style="color: #4f46e5; font-size: 13px; display: block; margin-bottom: 6px;">Inventory & Points Engine</strong>
          <span style="font-size: 13px; color: #64748b; line-height: 1.5; display: block;">Automated stock deduction routines and reward loyalty balance accounting triggered concurrently upon order confirmation.</span>
        </div>
      </div>

      <div style="display: flex; gap: 12px;">
        <div onclick="openUniversalImageModal('https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/assets/ezshop-erd.png', 'EZShop Database Schema')" class="badge-btn" style="background: #ffffff; color: #0f172a; padding: 12px 22px; border-radius: 8px; font-weight: 600; font-size: 13px; border: 1px solid #cbd5e1;">View Database ERD Schema</div>
      </div>

    </div>
  </div>

  <!-- Dynamic Image Lightbox Modal -->
  <div id="universalImageModal" class="custom-modal-overlay" onclick="closeUniversalImageModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeUniversalImageModal()">&times;</button>
    <div class="custom-modal-window" id="imageModalWindow">
      <img id="universalModalImg" class="custom-modal-content" src="" alt="Project Artefact" />
    </div>
  </div>

  <!-- Dynamic Video Lightbox Modal -->
  <div id="videoModal" class="custom-modal-overlay" onclick="closeVideoModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeVideoModal()">&times;</button>
    <div class="video-modal-window">
      <iframe id="videoPlayerFrame" class="video-frame" src="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>

  <!-- Dynamic PDF Document Lightbox Modal -->
  <div id="universalReportModal" class="custom-modal-overlay" onclick="closeUniversalReportModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeUniversalReportModal()">&times;</button>
    <div class="report-modal-window">
      <iframe id="universalPdfFrame" class="report-frame" src=""></iframe>
    </div>
  </div>

</div>

<!-- JavaScript Core: Sequence & Lightbox Controls -->
<script>
  /* Header Sequential Typewriter */
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
      setTimeout(typeSequence, 45);
    } 
    else if (idx < w1.length + w2.length) {
      if(idx === w1.length) { c1.innerHTML += "&nbsp;"; }
      c2.innerHTML += w2.charAt(idx - w1.length);
      idx++;
      setTimeout(typeSequence, 45);
    } 
    else if (idx < w1.length + w2.length + w3.length) {
      if(idx === w1.length + w2.length) { c2.innerHTML += "&nbsp;"; }
      c3.innerHTML += w3.charAt(idx - (w1.length + w2.length));
      idx++;
      setTimeout(typeSequence, 45);
    } 
    else {
      idx = 0;
      setTimeout(typeTagline, 200);
    }
  }

  function typeTagline() {
    if (idx < taglineStr.length) {
      tagline.innerHTML += taglineStr.charAt(idx);
      idx++;
      setTimeout(typeTagline, 30);
    }
  }

  window.addEventListener("DOMContentLoaded", () => {
    setTimeout(typeSequence, 300);
  });

  /* Lightbox Mechanics */
  const universalImageModal = document.getElementById('universalImageModal');
  const universalModalImg = document.getElementById('universalModalImg');
  const videoModal = document.getElementById('videoModal');
  const videoPlayerFrame = document.getElementById('videoPlayerFrame');
  const universalReportModal = document.getElementById('universalReportModal');
  const universalPdfFrame = document.getElementById('universalPdfFrame');

  function openUniversalImageModal(imgSrc, altText) {
    resetZoom();
    universalModalImg.src = imgSrc;
    universalModalImg.alt = altText || 'Artefact';
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

  function openVideoModal(videoType) {
    let embedUrl = "";
    if (videoType === 'ergochef') {
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

  function openUniversalReportModal(pdfPath) {
    universalPdfFrame.src = pdfPath + "#toolbar=1&navpanes=0";
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
