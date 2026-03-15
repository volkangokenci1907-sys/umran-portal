<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Şirket Paneli</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0f0f13;
    --surface: #17171d;
    --surface2: #1e1e27;
    --border: #2a2a38;
    --accent: #f5a623;
    --accent2: #e05c5c;
    --accent3: #4ecdc4;
    --text: #e8e8f0;
    --muted: #7a7a95;
    --gold: #d4a853;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--bg);
    color: var(--text);
    min-height: 100vh;
  }

  /* TOP BAR */
  .topbar {
    background: var(--surface);
    border-bottom: 1px solid var(--border);
    padding: 0 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 76px;
    position: sticky;
    top: 0;
    z-index: 100;
  }

  .logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem;
    color: var(--gold);
    letter-spacing: 0.05em;
  }

  .logo span { color: var(--muted); font-size: 0.8rem; font-family: 'DM Sans', sans-serif; font-weight: 300; display: block; }

  .date-badge {
    background: var(--surface2);
    border: 1px solid var(--border);
    padding: 0.4rem 1rem;
    border-radius: 20px;
    font-size: 0.85rem;
    color: var(--muted);
  }

  /* NAV TABS */
  .nav {
    background: var(--surface);
    border-bottom: 1px solid var(--border);
    padding: 0 2rem;
    display: flex;
    gap: 0;
  }

  .nav-btn {
    padding: 1rem 1.5rem;
    background: none;
    border: none;
    color: var(--muted);
    font-family: 'DM Sans', sans-serif;
    font-size: 0.9rem;
    font-weight: 500;
    cursor: pointer;
    border-bottom: 2px solid transparent;
    transition: all 0.2s;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .nav-btn:hover { color: var(--text); }
  .nav-btn.active { color: var(--accent); border-bottom-color: var(--accent); }

  .nav-btn .icon { font-size: 1.1rem; }

  /* MAIN CONTENT */
  .main { padding: 2rem; max-width: 1200px; margin: 0 auto; }

  .section { display: none; }
  .section.active { display: block; }

  /* SECTION HEADER */
  .section-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 1.5rem;
  }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: 1.6rem;
    color: var(--text);
  }

  .section-title span { color: var(--gold); }

  /* CARD */
  .card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
  }

  /* ADD BUTTON */
  .btn-add {
    background: var(--accent);
    color: #000;
    border: none;
    padding: 0.6rem 1.2rem;
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-weight: 600;
    font-size: 0.85rem;
    cursor: pointer;
    transition: opacity 0.2s;
    display: flex;
    align-items: center;
    gap: 0.4rem;
  }
  .btn-add:hover { opacity: 0.85; }

  .btn-danger {
    background: transparent;
    color: var(--accent2);
    border: 1px solid var(--accent2);
    padding: 0.35rem 0.75rem;
    border-radius: 6px;
    font-family: 'DM Sans', sans-serif;
    font-size: 0.78rem;
    cursor: pointer;
    transition: all 0.2s;
  }
  .btn-danger:hover { background: var(--accent2); color: #fff; }

  .btn-edit {
    background: transparent;
    color: var(--accent3);
    border: 1px solid var(--accent3);
    padding: 0.35rem 0.75rem;
    border-radius: 6px;
    font-family: 'DM Sans', sans-serif;
    font-size: 0.78rem;
    cursor: pointer;
    transition: all 0.2s;
  }
  .btn-edit:hover { background: var(--accent3); color: #000; }

  /* ====== YEMEK LİSTESİ ====== */
  .meal-day-selector {
    display: flex;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
    flex-wrap: wrap;
  }

  .day-btn {
    padding: 0.5rem 1rem;
    background: var(--surface2);
    border: 1px solid var(--border);
    color: var(--muted);
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-size: 0.85rem;
    cursor: pointer;
    transition: all 0.2s;
  }

  .day-btn:hover { border-color: var(--accent); color: var(--text); }
  .day-btn.active { background: var(--accent); color: #000; border-color: var(--accent); font-weight: 600; }

  .meal-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1rem;
  }

  .meal-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1.2rem;
    position: relative;
  }

  .meal-type-badge {
    display: inline-block;
    padding: 0.2rem 0.7rem;
    border-radius: 20px;
    font-size: 0.7rem;
    font-weight: 600;
    margin-bottom: 0.6rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .badge-ogle { background: rgba(245,166,35,0.15); color: var(--accent); }
  .badge-aksam { background: rgba(78,205,196,0.15); color: var(--accent3); }
  .badge-kahvalti { background: rgba(224,92,92,0.15); color: var(--accent2); }

  .meal-name {
    font-size: 1rem;
    font-weight: 600;
    color: var(--text);
    margin-bottom: 0.3rem;
  }

  .meal-desc {
    font-size: 0.82rem;
    color: var(--muted);
    line-height: 1.5;
  }

  .meal-actions {
    display: flex;
    gap: 0.4rem;
    margin-top: 0.8rem;
  }

  /* ====== DOĞUM GÜNÜ ====== */
  .birthday-list { display: flex; flex-direction: column; gap: 0; }

  .birthday-item {
    display: flex;
    align-items: center;
    padding: 1rem 1.5rem;
    border-bottom: 1px solid var(--border);
    gap: 1rem;
    transition: background 0.15s;
  }

  .birthday-item:last-child { border-bottom: none; }
  .birthday-item:hover { background: var(--surface2); }

  .avatar {
    width: 44px;
    height: 44px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.1rem;
    font-weight: 700;
    flex-shrink: 0;
  }

  .birthday-info { flex: 1; }
  .birthday-name { font-weight: 600; font-size: 0.95rem; }
  .birthday-dept { font-size: 0.8rem; color: var(--muted); margin-top: 0.1rem; }

  .birthday-date {
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--accent);
    min-width: 80px;
    text-align: right;
  }

  .birthday-today {
    background: rgba(245,166,35,0.06);
    border-left: 3px solid var(--accent);
  }

  .today-tag {
    background: var(--accent);
    color: #000;
    font-size: 0.65rem;
    font-weight: 700;
    padding: 0.15rem 0.5rem;
    border-radius: 20px;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .birthday-actions { display: flex; gap: 0.4rem; align-items: center; }

  /* ====== DUYURULAR ====== */
  .announcement-list { display: flex; flex-direction: column; gap: 1rem; }

  .announcement-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1.5rem;
    position: relative;
  }

  .ann-header { display: flex; align-items: flex-start; justify-content: space-between; margin-bottom: 0.8rem; gap: 1rem; }
  .ann-title { font-size: 1rem; font-weight: 600; color: var(--text); }

  .priority-badge {
    padding: 0.2rem 0.7rem;
    border-radius: 20px;
    font-size: 0.7rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    flex-shrink: 0;
  }

  .priority-yuksek { background: rgba(224,92,92,0.15); color: var(--accent2); }
  .priority-orta { background: rgba(245,166,35,0.15); color: var(--accent); }
  .priority-dusuk { background: rgba(78,205,196,0.15); color: var(--accent3); }

  .ann-body { font-size: 0.88rem; color: var(--muted); line-height: 1.65; }

  .ann-footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 1rem;
    padding-top: 0.8rem;
    border-top: 1px solid var(--border);
  }

  .ann-meta { font-size: 0.78rem; color: var(--muted); }
  .ann-actions { display: flex; gap: 0.4rem; }

  /* ====== MODAL ====== */
  .modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.7);
    z-index: 200;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 1rem;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.2s;
  }

  .modal-overlay.open { opacity: 1; pointer-events: all; }

  .modal {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 2rem;
    width: 100%;
    max-width: 480px;
    transform: translateY(20px);
    transition: transform 0.2s;
  }

  .modal-overlay.open .modal { transform: translateY(0); }

  .modal-title {
    font-family: 'Playfair Display', serif;
    font-size: 1.3rem;
    margin-bottom: 1.5rem;
    color: var(--gold);
  }

  .form-group { margin-bottom: 1rem; }

  .form-label {
    display: block;
    font-size: 0.82rem;
    font-weight: 500;
    color: var(--muted);
    margin-bottom: 0.4rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .form-input, .form-select, .form-textarea {
    width: 100%;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 0.65rem 0.9rem;
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 0.9rem;
    outline: none;
    transition: border-color 0.2s;
  }

  .form-input:focus, .form-select:focus, .form-textarea:focus {
    border-color: var(--accent);
  }

  .form-textarea { resize: vertical; min-height: 80px; }

  .form-select option { background: var(--surface2); }

  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }

  .modal-actions {
    display: flex;
    gap: 0.75rem;
    margin-top: 1.5rem;
    justify-content: flex-end;
  }

  .btn-cancel {
    background: var(--surface2);
    border: 1px solid var(--border);
    color: var(--muted);
    padding: 0.6rem 1.2rem;
    border-radius: 8px;
    cursor: pointer;
    font-family: 'DM Sans', sans-serif;
    font-size: 0.9rem;
    transition: all 0.2s;
  }

  .btn-cancel:hover { color: var(--text); border-color: var(--muted); }

  /* ====== HAFTALIK TOPLU GİRİŞ ====== */
  .weekly-modal .modal { max-width: 860px; max-height: 90vh; overflow-y: auto; }

  .weekly-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 0.75rem;
    margin-bottom: 1rem;
  }

  .weekly-day-col {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }

  .weekly-day-header {
    background: var(--border);
    padding: 0.6rem 0.75rem;
    font-size: 0.8rem;
    font-weight: 700;
    text-align: center;
    color: var(--accent);
    text-transform: uppercase;
    letter-spacing: 0.06em;
  }

  .weekly-day-body { padding: 0.6rem; display: flex; flex-direction: column; gap: 0.5rem; }

  .weekly-meal-row label {
    display: block;
    font-size: 0.68rem;
    font-weight: 600;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.05em;
    margin-bottom: 0.25rem;
  }

  .weekly-meal-row input {
    width: 100%;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 0.4rem 0.6rem;
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 0.8rem;
    outline: none;
    transition: border-color 0.2s;
  }
  .weekly-meal-row input:focus { border-color: var(--accent); }
  .weekly-meal-row input::placeholder { color: var(--muted); font-size: 0.75rem; }

  .weekly-meal-row input.k { border-left: 2px solid var(--accent2); }
  .weekly-meal-row input.o { border-left: 2px solid var(--accent); }
  .weekly-meal-row input.a { border-left: 2px solid var(--accent3); }

  .weekly-legend {
    display: flex;
    gap: 1.2rem;
    margin-bottom: 1rem;
    font-size: 0.78rem;
    color: var(--muted);
  }

  .weekly-legend span { display: flex; align-items: center; gap: 0.4rem; }
  .legend-dot { width: 10px; height: 10px; border-radius: 2px; flex-shrink: 0; }

  .btn-weekly {
    background: var(--surface2);
    color: var(--accent3);
    border: 1px solid var(--accent3);
    padding: 0.6rem 1.2rem;
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-weight: 600;
    font-size: 0.85rem;
    cursor: pointer;
    transition: all 0.2s;
    display: flex;
    align-items: center;
    gap: 0.4rem;
  }
  .btn-weekly:hover { background: var(--accent3); color: #000; }

  .weekly-clear-btn {
    background: transparent;
    color: var(--accent2);
    border: 1px solid var(--border);
    padding: 0.35rem 0.9rem;
    border-radius: 6px;
    font-family: 'DM Sans', sans-serif;
    font-size: 0.78rem;
    cursor: pointer;
    transition: all 0.2s;
  }
  .weekly-clear-btn:hover { border-color: var(--accent2); }

  /* ====== YAKLAŞAN DOĞUM GÜNLERİ ====== */
  .upcoming-banner {
    margin-bottom: 1.2rem;
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
  }

  .upcoming-card {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 0.9rem 1.2rem;
    border-radius: 10px;
    border: 1px solid;
    position: relative;
    overflow: hidden;
  }

  .upcoming-today {
    background: rgba(245,166,35,0.08);
    border-color: rgba(245,166,35,0.4);
  }

  .upcoming-soon {
    background: rgba(78,205,196,0.06);
    border-color: rgba(78,205,196,0.25);
  }

  .upcoming-card::before {
    content: '';
    position: absolute;
    left: 0; top: 0; bottom: 0;
    width: 3px;
  }
  .upcoming-today::before { background: var(--accent); }
  .upcoming-soon::before { background: var(--accent3); }

  .upcoming-avatar {
    width: 40px; height: 40px;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 1rem; font-weight: 700; flex-shrink: 0;
  }

  .upcoming-info { flex: 1; }
  .upcoming-name { font-weight: 600; font-size: 0.92rem; }
  .upcoming-dept { font-size: 0.78rem; color: var(--muted); margin-top: 0.1rem; }

  .upcoming-tag {
    font-size: 0.72rem;
    font-weight: 700;
    padding: 0.25rem 0.7rem;
    border-radius: 20px;
    white-space: nowrap;
  }
  .tag-today { background: var(--accent); color: #000; }
  .tag-tomorrow { background: rgba(245,166,35,0.2); color: var(--accent); }
  .tag-soon { background: rgba(78,205,196,0.15); color: var(--accent3); }

  /* EMPTY STATE */
  .empty-state {
    text-align: center;
    padding: 3rem 2rem;
    color: var(--muted);
  }

  .empty-state .empty-icon { font-size: 2.5rem; margin-bottom: 0.75rem; }
  .empty-state p { font-size: 0.9rem; }

  /* TOAST */
  .toast {
    position: fixed;
    bottom: 2rem;
    right: 2rem;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-left: 3px solid var(--accent3);
    padding: 0.9rem 1.3rem;
    border-radius: 10px;
    font-size: 0.88rem;
    color: var(--text);
    z-index: 300;
    opacity: 0;
    transform: translateY(10px);
    transition: all 0.3s;
    pointer-events: none;
  }

  .toast.show { opacity: 1; transform: translateY(0); }
</style>
<script src="https://cdnjs.cloudflare.com/ajax/libs/mammoth/1.6.0/mammoth.browser.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
</head>
<body>

<div class="topbar">
  <div class="logo" style="display:flex;align-items:center;gap:24px;">
    <img src="data:image/png;base64,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" alt="Ümran" style="height:52px;width:auto;" />
    <div style="display:flex;flex-direction:column;line-height:1.1;">
      <span style="font-family:'Playfair Display',serif;font-size:2rem;font-weight:700;letter-spacing:0.08em;color:#1a9ba1;">ÜMRAN</span>
      <span style="font-family:'DM Sans',sans-serif;font-size:0.82rem;font-weight:600;letter-spacing:0.28em;color:#7a8a99;text-transform:uppercase;">PORTAL</span>
    </div>
  </div>
  </div>
<div style="display:flex;align-items:center;gap:1rem">
    <div class="date-badge" id="currentDate"></div>
    <div style="position:relative;cursor:pointer" onclick="showSection('dogumgunu')" title="Doğum günü bildirimleri">
      <span style="font-size:1.3rem">🔔</span>
      <span id="bdNotifBadge" style="display:none;position:absolute;top:-4px;right:-4px;background:var(--accent2);color:#fff;font-size:0.6rem;font-weight:700;min-width:16px;height:16px;border-radius:8px;display:none;align-items:center;justify-content:center;padding:0 3px;line-height:1"></span>
    </div>
    <button id="btnAdminGiris" onclick="toggleAdminPanel()" style="background:var(--surface2);border:1px solid var(--border);color:var(--muted);padding:0.4rem 1rem;border-radius:20px;font-size:0.82rem;cursor:pointer;font-family:'DM Sans',sans-serif;display:flex;align-items:center;gap:0.4rem;transition:all 0.2s;">
      🔐 Giriş
    </button>
  </div>
</div>

<nav class="nav">
  <button class="nav-btn active" onclick="showSection('yemek')" id="tab-yemek">
    <span class="icon">🍽️</span> Yemek Listesi
  </button>
  <button class="nav-btn" onclick="showSection('dogumgunu')" id="tab-dogumgunu">
    <span class="icon">🎂</span> Doğum Günleri
  </button>
  <button class="nav-btn" onclick="showSection('duyuru')" id="tab-duyuru">
    <span class="icon">📢</span> Duyurular
  </button>
  <button class="nav-btn" onclick="showSection('etkinlik')" id="tab-etkinlik">
    <span class="icon">🎉</span> Etkinlikler
  </button>
  <button class="nav-btn" onclick="showSection('rehber')" id="tab-rehber">
    <span class="icon">📋</span> Dahili Rehber
  </button>
</nav>

<main class="main">

  <!-- ===== YEMEK ===== -->
  <section class="section active" id="section-yemek">
    <div class="section-header">
      <h1 class="section-title">Günlük <span>Yemek Listesi</span></h1>
      <div style="display:flex;gap:0.6rem;align-items:center">
        <label class="btn-weekly" style="cursor:pointer">
          📂 Word Dosyası Yükle
          <input type="file" id="wordFileInput" accept=".docx" style="display:none" onchange="importWordFile(event)">
        </label>
        <button class="btn-add" onclick="openModal('yemek')">+ Tekli Ekle</button>
      </div>
    </div>

    <div class="meal-day-selector" id="daySelector"></div>

    <div id="weekBanner" style="background:rgba(78,205,196,0.08); border:1px solid rgba(78,205,196,0.25); border-radius:10px; padding:0.7rem 1.2rem; margin-bottom:1rem; align-items:center; justify-content:space-between; gap:1rem;">
      <div style="font-size:0.85rem; color:var(--accent3)">
        <strong>📋 Yüklenen Liste:</strong> <span id="weekBannerText"></span>
      </div>
      <button class="btn-danger" onclick="clearImportedMeals()" style="font-size:0.75rem;padding:0.25rem 0.7rem">🗑️ Listeyi Temizle</button>
    </div>

    <div class="card">
      <div class="meal-grid" id="mealGrid" style="padding:1rem;">
        <div class="empty-state">
          <div class="empty-icon">🍽️</div>
          <p>Bu gün için yemek eklenmemiş.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== DOĞUM GÜNÜ ===== -->
  <section class="section" id="section-dogumgunu">
    <div class="section-header">
      <h1 class="section-title">Doğum <span>Günleri</span></h1>
      <button class="btn-add" onclick="openModal('dogumgunu')">+ Çalışan Ekle</button>
    </div>

    <!-- Yaklaşan doğum günleri banner -->
    <div id="upcomingBanner"></div>

    <div class="card">
      <div class="birthday-list" id="birthdayList">
        <div class="empty-state">
          <div class="empty-icon">🎂</div>
          <p>Henüz çalışan eklenmemiş.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== DUYURU ===== -->
  <section class="section" id="section-duyuru">
    <div class="section-header">
      <h1 class="section-title">Duyuru <span>Panosu</span></h1>
      <button class="btn-add" onclick="state.adminLoggedIn?openModal('duyuru'):showAdminLoginForm()">+ Duyuru Ekle</button>
    </div>
    <div class="announcement-list" id="announcementList">
      <div class="empty-state card" style="padding:3rem">
        <div class="empty-icon">📢</div>
        <p>Henüz duyuru eklenmemiş.</p>
      </div>
    </div>
  </section>

  <!-- ===== ETKİNLİK ===== -->
  <section class="section" id="section-etkinlik">
    <div class="section-header">
      <h1 class="section-title">Etkinlik <span>Takvimi</span></h1>
      <button class="btn-add" id="btnEtkinlikEkle" onclick="openModal('etkinlik')" style="display:none;">+ Etkinlik Ekle</button>
    </div>
    <div id="etkinlikGrid" style="display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:1.2rem;"></div>
  </section>

</main>

<!-- ===== MODAL ===== -->
<div class="modal-overlay" id="modalOverlay" onclick="closeModalOnOverlay(event)">
  <div class="modal" id="modal">
    <h2 class="modal-title" id="modalTitle">Ekle</h2>
    <div id="modalBody"></div>
    <div class="modal-actions">
      <button class="btn-cancel" onclick="closeModal()">İptal</button>
      <button class="btn-add" onclick="saveItem()">💾 Kaydet</button>
    </div>
  </div>
</div>

<!-- ===== ADMIN GİRİŞ PANEL ===== -->
<div class="modal-overlay" id="adminPanelOverlay" onclick="closeAdminPanelOnOverlay(event)" style="opacity:0;pointer-events:none;">
  <div class="modal" style="max-width:420px;" id="adminPanelModal">
    <h2 class="modal-title" id="adminPanelTitle">🔐 Admin Girişi</h2>
    <div id="adminPanelBody"></div>
    <div class="modal-actions" id="adminPanelActions"></div>
  </div>
</div>

<!-- ===== IMPORT LOADING ===== -->
<div class="modal-overlay" id="importLoadingOverlay" style="pointer-events:none;opacity:0;transition:opacity 0.2s;">
  <div class="modal" style="max-width:340px;text-align:center;padding:2.5rem 2rem;">
    <div style="font-size:2.5rem;margin-bottom:1rem">⏳</div>
    <div style="font-family:'Playfair Display',serif;font-size:1.1rem;color:var(--gold);margin-bottom:0.5rem">Dosya Okunuyor...</div>
    <div style="font-size:0.85rem;color:var(--muted)" id="importStatus">Lütfen bekleyin.</div>
  </div>
</div>








<script>
// ===== STATE =====
const DAYS = ['Pazartesi','Salı','Çarşamba','Perşembe','Cuma','Cumartesi','Pazar'];
let state = {
  meals: [],        // {id, day, type, name, desc}
  birthdays: [],    // {id, name, dept, date, color}
  announcements:[], // {id, title, body, priority, author, createdAt}
  etkinlikler: [],  // {id, title, date, time, desc, color}
  rehber: [],       // {id, name, dept, unite, dahili}
  rehberTab: 'merkez', // merkez | fabrika | tumu
  activeDay: DAYS[new Date().getDay()-1] || DAYS[0],
  editId: null,
  modalType: null,
  adminLoggedIn: false,
  adminUser: null
};

// ===== SUPABASE =====
const SUPABASE_URL = 'https://jlzfhpoqyufctjqrncuk.supabase.co';
const SUPABASE_KEY = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImpsemZocG9xeXVmY3RqcXJuY3VrIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzM0NDM5NzgsImV4cCI6MjA4OTAxOTk3OH0.xV3pJsnbtVibVD94UzTZDG59b3TXm8ufs0iJl-VdNGc';
const db = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);

// Yükleme göstergesi
function setLoading(show) {
  const sections = document.querySelectorAll('.section.active .section-header');
  // sadece console'a yaz, UI'yi bozmayalım
}

// ===== SUPABASE API FONKSİYONLARI =====

// Duyurular
async function sbGetDuyurular() {
  const { data, error } = await db.from('duyurular').select('*').order('created_at', { ascending: false });
  if (error) { console.error('Duyuru yükleme hatası:', error); return []; }
  return data.map(d => ({ id: String(d.id), title: d.baslik, body: d.detay, priority: d.oncelik, author: d.yayimlayan, createdAt: new Date(d.created_at).getTime() }));
}

async function sbSaveDuyuru(item, editId) {
  const row = { baslik: item.title, detay: item.body, oncelik: item.priority, yayimlayan: item.author };
  if (editId) {
    const { error } = await db.from('duyurular').update(row).eq('id', editId);
    if (error) throw error;
  } else {
    const { error } = await db.from('duyurular').insert(row);
    if (error) throw error;
  }
}

async function sbDeleteDuyuru(id) {
  const { error } = await db.from('duyurular').delete().eq('id', id);
  if (error) throw error;
}

// Etkinlikler
async function sbGetEtkinlikler() {
  const { data, error } = await db.from('etkinlikler').select('*').order('tarih', { ascending: true });
  if (error) { console.error('Etkinlik yükleme hatası:', error); return []; }
  return data.map(e => ({ id: String(e.id), title: e.baslik, date: e.tarih, time: e.saat||'', desc: e.aciklama||'', color: e.renk||'#4ecdc4' }));
}

async function sbSaveEtkinlik(item, editId) {
  const row = { baslik: item.title, tarih: item.date, saat: item.time||null, aciklama: item.desc, renk: item.color };
  if (editId) {
    const { error } = await db.from('etkinlikler').update(row).eq('id', editId);
    if (error) throw error;
  } else {
    const { error } = await db.from('etkinlikler').insert(row);
    if (error) throw error;
  }
}

async function sbDeleteEtkinlik(id) {
  const { error } = await db.from('etkinlikler').delete().eq('id', id);
  if (error) throw error;
}

// Doğum günleri
async function sbGetDogumGunleri() {
  const { data, error } = await db.from('dogum_gunleri').select('*').order('ad_soyad');
  if (error) { console.error('Doğum günü yükleme hatası:', error); return []; }
  return data.map(b => ({ id: String(b.id), name: b.ad_soyad, dept: b.departman||'', date: b.tarih, color: b.renk||'#4ecdc4' }));
}

async function sbSaveDogumGunu(item, editId) {
  const row = { ad_soyad: item.name, departman: item.dept, tarih: item.date, renk: item.color };
  if (editId) {
    const { error } = await db.from('dogum_gunleri').update(row).eq('id', editId);
    if (error) throw error;
  } else {
    const { error } = await db.from('dogum_gunleri').insert(row);
    if (error) throw error;
  }
}

async function sbDeleteDogumGunu(id) {
  const { error } = await db.from('dogum_gunleri').delete().eq('id', id);
  if (error) throw error;
}

// Yemekler
async function sbGetYemekler() {
  const { data, error } = await db.from('yemek_listesi').select('*').order('created_at');
  if (error) { console.error('Yemek yükleme hatası:', error); return []; }
  return data.map(m => ({ id: String(m.id), day: m.gun, type: m.ogun||'ogle', name: m.ad, desc: m.aciklama||'', imported: false }));
}

async function sbSaveYemek(item, editId) {
  const row = { gun: item.day, ogun: item.type, ad: item.name, aciklama: item.desc };
  if (editId) {
    const { error } = await db.from('yemek_listesi').update(row).eq('id', editId);
    if (error) throw error;
  } else {
    const { error } = await db.from('yemek_listesi').insert(row);
    if (error) throw error;
  }
}

async function sbDeleteYemek(id) {
  const { error } = await db.from('yemek_listesi').delete().eq('id', id);
  if (error) throw error;
}

// Dahili Rehber
async function sbGetRehber() {
  const { data, error } = await db.from('kullanicilar').select('*').order('ad_soyad');
  if (error) { console.error('Rehber yükleme hatası:', error); return []; }
  return data.map(k => ({ id: String(k.id), name: k.ad_soyad, dept: k.departman||'', unite: k.unite||'Merkez', dahili: k.merkez_tel||'' }));
}

async function sbSaveRehber(item, editId) {
  const row = { ad_soyad: item.name, departman: item.dept, unite: item.unite, merkez_tel: item.dahili };
  if (editId) {
    const { error } = await db.from('kullanicilar').update(row).eq('id', editId);
    if (error) throw error;
  } else {
    const { error } = await db.from('kullanicilar').insert(row);
    if (error) throw error;
  }
}

async function sbDeleteRehber(id) {
  const { error } = await db.from('kullanicilar').delete().eq('id', id);
  if (error) throw error;
}

// Admin kullanıcıları
async function sbGetAdmins() {
  const { data, error } = await db.from('admin_kullanicilar').select('kullanici_adi, sifre_hash, rol');
  if (error) { console.error('Admin yükleme hatası:', error); return []; }
  return data;
}

async function sbSaveAdmin(username, passwordHash) {
  const { error } = await db.from('admin_kullanicilar').insert({ kullanici_adi: username, sifre_hash: passwordHash });
  if (error) throw error;
}

async function sbDeleteAdmin(username) {
  const { error } = await db.from('admin_kullanicilar').delete().eq('kullanici_adi', username);
  if (error) throw error;
}

// ===== VERİ YÜKLEME =====
async function loadAllData() {
  try {
    const [duyurular, etkinlikler, dogumGunleri, yemekler, rehber] = await Promise.all([
      sbGetDuyurular(),
      sbGetEtkinlikler(),
      sbGetDogumGunleri(),
      sbGetYemekler(),
      sbGetRehber()
    ]);
    state.announcements = duyurular;
    state.etkinlikler = etkinlikler;
    state.birthdays = dogumGunleri;
    state.meals = yemekler;
    state.rehber = rehber;
  } catch(e) {
    console.error('Veri yükleme hatası:', e);
    showToast('⚠️ Veri yüklenirken hata oluştu!');
  }
}

// Load from localStorage
function loadState() {
  const s = localStorage.getItem('sirketPaneli');
  if (s) {
    const saved = JSON.parse(s);
    state.meals = saved.meals || [];
    state.birthdays = saved.birthdays || [];
    state.announcements = saved.announcements || [];
    state.etkinlikler = saved.etkinlikler || [];
    state.importedFileName = saved.importedFileName || null;
    state.importedDayCount = saved.importedDayCount || 0;
    state.importedMealCount = saved.importedMealCount || 0;
  }
}

function saveState() {
  // Sadece word import bilgilerini localStorage'da tut
  localStorage.setItem('sirketPanelImport', JSON.stringify({
    importedFileName: state.importedFileName || null,
    importedDayCount: state.importedDayCount || 0,
    importedMealCount: state.importedMealCount || 0,
  }));
}

// ===== UTILS =====
function uid() { return Date.now().toString(36) + Math.random().toString(36).slice(2); }

function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 2500);
}

function initDate() {
  const d = new Date();
  const opts = { weekday:'long', year:'numeric', month:'long', day:'numeric' };
  document.getElementById('currentDate').textContent = d.toLocaleDateString('tr-TR', opts);
}

// ===== NAVIGATION =====
function showSection(name) {
  document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
  document.getElementById('section-'+name).classList.add('active');
  document.getElementById('tab-'+name).classList.add('active');
  if (name === 'yemek') renderMeals();
  if (name === 'dogumgunu') renderBirthdays();
  if (name === 'duyuru') renderAnnouncements();
  if (name === 'etkinlik') renderEtkinlikler();
  if (name === 'rehber') renderRehber();
}

// ===== MEALS =====
function renderDaySelector() {
  const el = document.getElementById('daySelector');
  el.innerHTML = DAYS.map(d => `
    <button class="day-btn ${d===state.activeDay?'active':''}" onclick="selectDay('${d}')">${d}</button>
  `).join('');
}

function selectDay(day) {
  state.activeDay = day;
  renderDaySelector();
  renderMeals();
}

function renderMeals() {
  renderDaySelector();
  const grid = document.getElementById('mealGrid');
  const items = state.meals.filter(m => m.day === state.activeDay);

  if (!items.length) {
    grid.innerHTML = `<div class="empty-state"><div class="empty-icon">🍽️</div><p>Bu gün için yemek eklenmemiş.</p></div>`;
    return;
  }

  // Import edilenler ve manuel eklenenleri ayır
  const imported = items.filter(m => m.imported).sort((a,b) => (a.order||0)-(b.order||0));
  const manual   = items.filter(m => !m.imported);

  let html = '';

  // Import edilenler varsa liste olarak göster
  if (imported.length) {
    html += `
      <div class="meal-card" style="grid-column: 1 / -1; background:var(--surface2); border-color:rgba(78,205,196,0.2);">
        <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:1rem;">
          <div style="font-size:0.7rem;font-weight:700;text-transform:uppercase;letter-spacing:0.08em;color:var(--accent3)">
            📋 Günlük Menü
          </div>
          <div style="font-size:0.72rem;color:var(--muted)">${state.activeDay}</div>
        </div>
        <div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:0.5rem;">
          ${imported.map((m, i) => `
            <div style="display:flex;align-items:center;gap:0.6rem;padding:0.55rem 0.75rem;background:var(--surface);border:1px solid var(--border);border-radius:8px;">
              <span style="color:var(--accent);font-weight:700;font-size:0.75rem;min-width:18px">${i+1}.</span>
              <span style="font-size:0.87rem;color:var(--text);font-weight:500;flex:1">${m.name}</span>
              <button onclick="deleteItem('yemek','${m.id}')" title="Sil" style="background:none;border:none;color:var(--muted);cursor:pointer;font-size:0.85rem;padding:0;line-height:1;transition:color 0.15s" onmouseover="this.style.color='var(--accent2)'" onmouseout="this.style.color='var(--muted)'">✕</button>
            </div>
          `).join('')}
        </div>
      </div>
    `;
  }

  // Manuel eklenenler
  manual.forEach(m => {
    const badge = m.type ? `<div class="meal-type-badge badge-${m.type}">${mealTypeLabel(m.type)}</div>` : '';
    html += `
      <div class="meal-card">
        ${badge}
        <div class="meal-name">${m.name}</div>
        ${m.desc ? `<div class="meal-desc">${m.desc}</div>` : ''}
        <div class="meal-actions" style="display:flex;gap:0.4rem;margin-top:0.8rem;">
          <button class="btn-edit" onclick="editItem('yemek','${m.id}')">Düzenle</button>
          <button class="btn-danger" onclick="deleteItem('yemek','${m.id}')">Sil</button>
        </div>
      </div>
    `;
  });

  grid.innerHTML = html;
}

function mealTypeLabel(t) {
  return {ogle:'Öğle Yemeği', aksam:'Akşam Yemeği', kahvalti:'Kahvaltı'}[t] || t;
}

// ===== BIRTHDAYS =====
const avatarColors = ['#f5a623','#e05c5c','#4ecdc4','#a78bfa','#34d399','#f472b6'];

function todayStr() {
  const d = new Date();
  return `${String(d.getDate()).padStart(2,'0')}.${String(d.getMonth()+1).padStart(2,'0')}`;
}

function renderBirthdays() {
  renderUpcomingBanner();
  updateNotifBadge();

  const list = document.getElementById('birthdayList');
  if (!state.birthdays.length) {
    list.innerHTML = `<div class="empty-state"><div class="empty-icon">🎂</div><p>Henüz çalışan eklenmemiş.</p></div>`;
    return;
  }
  const today = todayStr();
  const sorted = [...state.birthdays].sort((a,b) => {
    const da = daysUntilBirthday(a.date);
    const db = daysUntilBirthday(b.date);
    return da - db;
  });
  list.innerHTML = sorted.map(b => {
    const isToday = b.date.startsWith(today);
    const daysLeft = daysUntilBirthday(b.date);
    const initials = b.name.split(' ').map(w=>w[0]).join('').toUpperCase().slice(0,2);

    let daysTag = '';
    if (isToday) {
      daysTag = `<span class="today-tag">🎉 Bugün!</span>`;
    } else if (daysLeft <= 7) {
      daysTag = `<span class="today-tag" style="background:rgba(78,205,196,0.2);color:var(--accent3)">${daysLeft} gün sonra</span>`;
    }

    return `
      <div class="birthday-item ${isToday ? 'birthday-today' : ''}">
        <div class="avatar" style="background:${b.color}22;color:${b.color}">${initials}</div>
        <div class="birthday-info">
          <div class="birthday-name">${b.name} ${daysTag}</div>
          <div class="birthday-dept">${b.dept}</div>
        </div>
        <div class="birthday-date">${b.date}</div>
        <div class="birthday-actions">
          <button class="btn-edit" onclick="editItem('dogumgunu','${b.id}')">Düzenle</button>
          <button class="btn-danger" onclick="deleteItem('dogumgunu','${b.id}')">Sil</button>
        </div>
      </div>
    `;
  }).join('');
}

// ===== ANNOUNCEMENTS =====
function renderAnnouncements() {
  const list = document.getElementById('announcementList');
  if (!state.announcements.length) {
    list.innerHTML = `<div class="empty-state card" style="padding:3rem"><div class="empty-icon">📢</div><p>Henüz duyuru eklenmemiş.</p></div>`;
    return;
  }
  const sorted = [...state.announcements].sort((a,b) => b.createdAt - a.createdAt);
  list.innerHTML = sorted.map(a => `
    <div class="announcement-card">
      <div class="ann-header">
        <div class="ann-title">${a.title}</div>
        <span class="priority-badge priority-${a.priority}">${priorityLabel(a.priority)}</span>
      </div>
      <div class="ann-body">${a.body}</div>
      <div class="ann-footer">
        <div class="ann-meta">✍️ ${a.author} &nbsp;·&nbsp; 📅 ${new Date(a.createdAt).toLocaleDateString('tr-TR')}</div>
        <div class="ann-actions">
          <button class="btn-edit" onclick="editItem('duyuru','${a.id}')">Düzenle</button>
          <button class="btn-danger" onclick="deleteItem('duyuru','${a.id}')">Sil</button>
        </div>
      </div>
    </div>
  `).join('');
}

function priorityLabel(p) {
  return {yuksek:'🔴 Yüksek', orta:'🟡 Orta', dusuk:'🟢 Düşük'}[p] || p;
}

// ===== MODAL =====
function openModal(type, editId = null) {
  state.modalType = type;
  state.editId = editId;
  const overlay = document.getElementById('modalOverlay');
  const title = document.getElementById('modalTitle');
  const body = document.getElementById('modalBody');

  if (type === 'yemek') {
    const item = editId ? state.meals.find(m=>m.id===editId) : null;
    title.textContent = editId ? 'Yemeği Düzenle' : 'Yemek Ekle';
    body.innerHTML = `
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Gün</label>
          <select class="form-select" id="f-day">
            ${DAYS.map(d=>`<option value="${d}" ${item?.day===d?'selected':''}>${d}</option>`).join('')}
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Öğün</label>
          <select class="form-select" id="f-type">
            <option value="kahvalti" ${item?.type==='kahvalti'?'selected':''}>Kahvaltı</option>
            <option value="ogle" ${(!item||item?.type==='ogle')?'selected':''}>Öğle Yemeği</option>
            <option value="aksam" ${item?.type==='aksam'?'selected':''}>Akşam Yemeği</option>
          </select>
        </div>
      </div>
      <div class="form-group">
        <label class="form-label">Yemek Adı</label>
        <input class="form-input" id="f-name" placeholder="örn. Mercimek Çorbası" value="${item?.name||''}">
      </div>
      <div class="form-group">
        <label class="form-label">Açıklama (opsiyonel)</label>
        <textarea class="form-textarea" id="f-desc" placeholder="Malzemeler, kalori vb.">${item?.desc||''}</textarea>
      </div>
    `;
  }

  if (type === 'dogumgunu') {
    const item = editId ? state.birthdays.find(b=>b.id===editId) : null;
    title.textContent = editId ? 'Çalışanı Düzenle' : 'Çalışan Ekle';
    body.innerHTML = `
      <div class="form-group">
        <label class="form-label">Ad Soyad</label>
        <input class="form-input" id="f-name" placeholder="örn. Ayşe Kaya" value="${item?.name||''}">
      </div>
      <div class="form-group">
        <label class="form-label">Departman</label>
        <input class="form-input" id="f-dept" placeholder="örn. Yazılım Geliştirme" value="${item?.dept||''}">
      </div>
      <div class="form-group">
        <label class="form-label">Doğum Tarihi (GG.AA)</label>
        <input class="form-input" id="f-date" placeholder="örn. 15.03" value="${item?.date||''}">
      </div>
    `;
  }

  if (type === 'duyuru') {
    const item = editId ? state.announcements.find(a=>a.id===editId) : null;
    title.textContent = editId ? 'Duyuruyu Düzenle' : 'Duyuru Ekle';
    body.innerHTML = `
      <div class="form-group">
        <label class="form-label">Başlık</label>
        <input class="form-input" id="f-title" placeholder="Duyuru başlığı" value="${item?.title||''}">
      </div>
      <div class="form-group">
        <label class="form-label">İçerik</label>
        <textarea class="form-textarea" id="f-body" placeholder="Duyuru detayları...">${item?.body||''}</textarea>
      </div>
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Öncelik</label>
          <select class="form-select" id="f-priority">
            <option value="dusuk" ${item?.priority==='dusuk'?'selected':''}>🟢 Düşük</option>
            <option value="orta" ${(!item||item?.priority==='orta')?'selected':''}>🟡 Orta</option>
            <option value="yuksek" ${item?.priority==='yuksek'?'selected':''}>🔴 Yüksek</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Yayımlayan</label>
          <input class="form-input" id="f-author" placeholder="İsim / Departman" value="${item?.author||''}">
        </div>
      </div>
    `;
  }

  if (type === 'rehber') {
    const item = editId ? state.rehber.find(k=>k.id===editId) : null;
    title.textContent = editId ? 'Kişiyi Düzenle' : 'Kişi Ekle';
    body.innerHTML = `
      <div class="form-group">
        <label class="form-label">Ad Soyad</label>
        <input class="form-input" id="f-rname" placeholder="örn. Ahmet Yılmaz" value="${item?.name||''}">
      </div>
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Ünite</label>
          <select class="form-select" id="f-runite">
            <option value="Merkez" ${(!item||item?.unite==='Merkez')?'selected':''}>🏢 Merkez</option>
            <option value="Fabrika" ${item?.unite==='Fabrika'?'selected':''}>🏭 Fabrika</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Dahili No</label>
          <input class="form-input" id="f-rdahili" placeholder="örn. 1180" value="${item?.dahili||''}">
        </div>
      </div>
      <div class="form-group">
        <label class="form-label">Departman / Görev</label>
        <input class="form-input" id="f-rdept" placeholder="örn. Bilgi İşlem" value="${item?.dept||''}">
      </div>
    `;
  }

  if (type === 'etkinlik') {
    const item = editId ? state.etkinlikler.find(e=>e.id===editId) : null;
    title.textContent = editId ? 'Etkinliği Düzenle' : 'Etkinlik Ekle';
    const renkler = ['#4ecdc4','#f5a623','#e05c5c','#a78bfa','#34d399','#f472b6'];
    const seciliRenk = item?.color || '#4ecdc4';
    body.innerHTML = `
      <div class="form-group">
        <label class="form-label">Etkinlik Adı</label>
        <input class="form-input" id="f-etitle" placeholder="örn. Yıl Sonu Yemeği" value="${item?.title||''}">
      </div>
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Tarih</label>
          <input class="form-input" id="f-edate" type="date" value="${item?.date||''}">
        </div>
        <div class="form-group">
          <label class="form-label">Saat (opsiyonel)</label>
          <input class="form-input" id="f-etime" type="time" value="${item?.time||''}">
        </div>
      </div>
      <div class="form-group">
        <label class="form-label">Açıklama</label>
        <textarea class="form-textarea" id="f-edesc" placeholder="Etkinlik detayları...">${item?.desc||''}</textarea>
      </div>
      <div class="form-group">
        <label class="form-label">Renk</label>
        <div style="display:flex;gap:0.6rem;margin-top:0.3rem;">
          ${renkler.map(c=>`
            <div class="ecolor-opt" data-color="${c}" onclick="selectEColor(this)"
              style="width:28px;height:28px;border-radius:50%;background:${c};cursor:pointer;
                     border:3px solid ${seciliRenk===c?'#fff':'transparent'};
                     box-shadow:${seciliRenk===c?'0 0 0 2px '+c:'none'};
                     transition:all 0.15s;box-sizing:border-box;"></div>
          `).join('')}
        </div>
        <input type="hidden" id="f-ecolor" value="${seciliRenk}">
      </div>
    `;
  }

  overlay.classList.add('open');
}

function selectEColor(el) {
  document.querySelectorAll('.ecolor-opt').forEach(x => {
    x.style.border = '3px solid transparent';
    x.style.boxShadow = 'none';
  });
  el.style.border = '3px solid #fff';
  el.style.boxShadow = `0 0 0 2px ${el.dataset.color}`;
  document.getElementById('f-ecolor').value = el.dataset.color;
}

function closeModal() {
  document.getElementById('modalOverlay').classList.remove('open');
  state.editId = null;
}

function closeModalOnOverlay(e) {
  if (e.target === document.getElementById('modalOverlay')) closeModal();
}

async function saveItem() {
  const type = state.modalType;

  try {
    if (type === 'yemek') {
      const day = document.getElementById('f-day').value;
      const mtype = document.getElementById('f-type').value;
      const name = document.getElementById('f-name').value.trim();
      const desc = document.getElementById('f-desc').value.trim();
      if (!name) { alert('Yemek adı boş olamaz!'); return; }
      await sbSaveYemek({ day, type: mtype, name, desc }, state.editId);
      state.meals = await sbGetYemekler();
      renderMeals();
    }

    if (type === 'dogumgunu') {
      const name = document.getElementById('f-name').value.trim();
      const dept = document.getElementById('f-dept').value.trim();
      const date = document.getElementById('f-date').value.trim();
      if (!name || !date) { alert('Ad ve tarih zorunludur!'); return; }
      if (!/^\d{2}\.\d{2}$/.test(date)) { alert('Tarih GG.AA formatında olmalı (örn: 15.03)'); return; }
      const color = avatarColors[state.birthdays.length % avatarColors.length];
      await sbSaveDogumGunu({ name, dept, date, color }, state.editId);
      state.birthdays = await sbGetDogumGunleri();
      renderBirthdays();
    }

    if (type === 'duyuru') {
      const title = document.getElementById('f-title').value.trim();
      const body = document.getElementById('f-body').value.trim();
      const priority = document.getElementById('f-priority').value;
      const author = document.getElementById('f-author').value.trim() || 'Yönetim';
      if (!title || !body) { alert('Başlık ve içerik zorunludur!'); return; }
      await sbSaveDuyuru({ title, body, priority, author }, state.editId);
      state.announcements = await sbGetDuyurular();
      renderAnnouncements();
    }

    if (type === 'rehber') {
    const item = editId ? state.rehber.find(k=>k.id===editId) : null;
    title.textContent = editId ? 'Kişiyi Düzenle' : 'Kişi Ekle';
    body.innerHTML = `
      <div class="form-group">
        <label class="form-label">Ad Soyad</label>
        <input class="form-input" id="f-rname" placeholder="örn. Ahmet Yılmaz" value="${item?.name||''}">
      </div>
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Ünite</label>
          <select class="form-select" id="f-runite">
            <option value="Merkez" ${(!item||item?.unite==='Merkez')?'selected':''}>🏢 Merkez</option>
            <option value="Fabrika" ${item?.unite==='Fabrika'?'selected':''}>🏭 Fabrika</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Dahili No</label>
          <input class="form-input" id="f-rdahili" placeholder="örn. 1180" value="${item?.dahili||''}">
        </div>
      </div>
      <div class="form-group">
        <label class="form-label">Departman / Görev</label>
        <input class="form-input" id="f-rdept" placeholder="örn. Bilgi İşlem" value="${item?.dept||''}">
      </div>
    `;
  }

  if (type === 'etkinlik') {
      const etitle = document.getElementById('f-etitle').value.trim();
      const edate = document.getElementById('f-edate').value;
      const etime = document.getElementById('f-etime').value;
      const edesc = document.getElementById('f-edesc').value.trim();
      const ecolor = document.getElementById('f-ecolor').value || '#4ecdc4';
      if (!etitle || !edate) { alert('Etkinlik adı ve tarih zorunludur!'); return; }
      await sbSaveEtkinlik({ title:etitle, date:edate, time:etime, desc:edesc, color:ecolor }, state.editId);
      state.etkinlikler = await sbGetEtkinlikler();
      renderEtkinlikler();
    }

    closeModal();
    showToast('✅ Kaydedildi!');
  } catch(e) {
    console.error('Kaydetme hatası:', e);
    showToast('❌ Kaydetme başarısız!');
  }
}

function editItem(type, id) {
  const section = type === 'yemek' ? 'yemek' : type === 'dogumgunu' ? 'dogumgunu' : type === 'etkinlik' ? 'etkinlik' : type === 'rehber' ? 'rehber' : 'duyuru';
  showSection(section);
  openModal(type, id);
}

async function deleteItem(type, id) {
  if (!confirm('Silmek istediğinize emin misiniz?')) return;
  try {
    if (type === 'yemek') { await sbDeleteYemek(id); state.meals = await sbGetYemekler(); renderMeals(); }
    if (type === 'dogumgunu') { await sbDeleteDogumGunu(id); state.birthdays = await sbGetDogumGunleri(); renderBirthdays(); }
    if (type === 'duyuru') { await sbDeleteDuyuru(id); state.announcements = await sbGetDuyurular(); renderAnnouncements(); }
    if (type === 'rehber') {
    const item = editId ? state.rehber.find(k=>k.id===editId) : null;
    title.textContent = editId ? 'Kişiyi Düzenle' : 'Kişi Ekle';
    body.innerHTML = `
      <div class="form-group">
        <label class="form-label">Ad Soyad</label>
        <input class="form-input" id="f-rname" placeholder="örn. Ahmet Yılmaz" value="${item?.name||''}">
      </div>
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Ünite</label>
          <select class="form-select" id="f-runite">
            <option value="Merkez" ${(!item||item?.unite==='Merkez')?'selected':''}>🏢 Merkez</option>
            <option value="Fabrika" ${item?.unite==='Fabrika'?'selected':''}>🏭 Fabrika</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Dahili No</label>
          <input class="form-input" id="f-rdahili" placeholder="örn. 1180" value="${item?.dahili||''}">
        </div>
      </div>
      <div class="form-group">
        <label class="form-label">Departman / Görev</label>
        <input class="form-input" id="f-rdept" placeholder="örn. Bilgi İşlem" value="${item?.dept||''}">
      </div>
    `;
  }

  if (type === 'etkinlik') { await sbDeleteEtkinlik(id); state.etkinlikler = await sbGetEtkinlikler(); renderEtkinlikler(); }
    if (type === 'rehber') { await sbDeleteRehber(id); state.rehber = await sbGetRehber(); renderRehber(); }
    showToast('🗑️ Silindi.');
  } catch(e) {
    console.error('Silme hatası:', e);
    showToast('❌ Silme başarısız!');
  }
}

// ===== WORD IMPORT =====
// Türkçe büyük harf güvenli normalize
function trUpper(str) {
  return str.replace(/ı/g,'I').replace(/i/g,'İ').toUpperCase();
}

const DAY_MAP = {
  'PAZARTESİ': 'Pazartesi', 'SALI': 'Salı', 'ÇARŞAMBA': 'Çarşamba',
  'PERŞEMBE': 'Perşembe', 'CUMA': 'Cuma', 'CUMARTESİ': 'Cumartesi', 'PAZAR': 'Pazar'
};

// Hücre metninden gün adını bul
function findDayKey(text) {
  const upper = trUpper(text.trim());
  return Object.keys(DAY_MAP).find(k => upper.startsWith(k) || upper === k) || null;
}

function importWordFile(event) {
  const file = event.target.files[0];
  if (!file) return;

  // Reset input so same file can be re-imported
  event.target.value = '';

  const overlay = document.getElementById('importLoadingOverlay');
  overlay.style.opacity = '1';
  overlay.style.pointerEvents = 'all';
  document.getElementById('importStatus').textContent = `"${file.name}" okunuyor...`;

  const reader = new FileReader();
  reader.onload = async (e) => {
    try {
      const arrayBuffer = e.target.result;
      const result = await mammoth.convertToHtml({ arrayBuffer });
      const html = result.value;

      // HTML'i parse et
      const parser = new DOMParser();
      const doc = parser.parseFromString(html, 'text/html');
      const tables = doc.querySelectorAll('table');

      if (!tables.length) {
        hideImportLoading();
        showToast('❌ Dosyada tablo bulunamadı!');
        return;
      }

      const parsed = {}; // { 'Pazartesi': ['yemek1', 'yemek2', ...], ... }

      tables.forEach(table => {
        const cells = table.querySelectorAll('td, th');
        cells.forEach(cell => {
          const lines = [];
          cell.querySelectorAll('p, li').forEach(el => {
            const text = el.textContent.trim().replace(/\s+/g, ' ');
            if (text) lines.push(text);
          });

          if (!lines.length) return;

          // İlk satır gün adı mı? (Türkçe güvenli)
          const dayKey = findDayKey(lines[0]);
          if (!dayKey) return;

          const dayName = DAY_MAP[dayKey];
          // Gün adı satırını atla, gerisi yemek
          const meals = lines.slice(1).filter(l => {
            const t = l.trim();
            return t.length > 1 && !t.match(/^[.\s]+$/) && !t.match(/^AFİYET/i) && !t.match(/^RAMAZAN/i) && !t.match(/^İFTAR/i);
          });
          if (meals.length) {
            parsed[dayName] = meals;
          }
        });
      });

      const dayCount = Object.keys(parsed).length;
      if (!dayCount) {
        hideImportLoading();
        showToast('❌ Gün/yemek verisi okunamadı!');
        return;
      }

      // Mevcut import edilmiş yemekleri temizle, manuel eklenenleri koru
      state.meals = state.meals.filter(m => !m.imported);

      // Yeni verileri ekle
      let total = 0;
      Object.entries(parsed).forEach(([day, items]) => {
        items.forEach((name, idx) => {
          state.meals.push({ id: uid(), day, type: 'ogle', name, desc: '', imported: true, order: idx });
          total++;
        });
      });

      // Banner güncelle
      state.importedFileName = file.name;
      state.importedDayCount = dayCount;
      state.importedMealCount = total;

      saveState();
      hideImportLoading();
      updateWeekBanner();

      // Aktif günü ilk bulunan güne ayarla
      const firstDay = Object.keys(parsed)[0];
      if (firstDay) { state.activeDay = firstDay; }

      renderMeals();
      showToast(`✅ ${dayCount} gün, ${total} yemek yüklendi!`);

    } catch (err) {
      hideImportLoading();
      showToast('❌ Dosya okunamadı: ' + err.message);
    }
  };
  reader.readAsArrayBuffer(file);
}

function hideImportLoading() {
  const overlay = document.getElementById('importLoadingOverlay');
  overlay.style.opacity = '0';
  overlay.style.pointerEvents = 'none';
}

function updateWeekBanner() {
  const banner = document.getElementById('weekBanner');
  if (!banner) return;
  if (state.importedFileName) {
    document.getElementById('weekBannerText').textContent =
      `${state.importedFileName}  ·  ${state.importedDayCount} gün  ·  ${state.importedMealCount} yemek`;
    banner.style.display = 'flex';
  } else {
    banner.style.display = 'none';
  }
}

function clearImportedMeals() {
  if (!confirm('İçe aktarılan tüm yemekler silinsin mi?')) return;
  state.meals = state.meals.filter(m => !m.imported);
  state.importedFileName = null;
  state.importedDayCount = 0;
  state.importedMealCount = 0;
  saveState();
  updateWeekBanner();
  renderMeals();
  showToast('🗑️ İçe aktarılan yemekler temizlendi.');
}

// ===== DOĞUM GÜNÜ BİLDİRİMLERİ =====

// Bir doğum gününün bugünden kaç gün sonra olduğunu hesapla (0=bugün, -1=geçti, max 365)
function daysUntilBirthday(dateStr) {
  const [dd, mm] = dateStr.split('.').map(Number);
  const today = new Date();
  const thisYear = today.getFullYear();

  let bday = new Date(thisYear, mm - 1, dd);
  const todayMidnight = new Date(today.getFullYear(), today.getMonth(), today.getDate());

  let diff = Math.round((bday - todayMidnight) / (1000 * 60 * 60 * 24));
  if (diff < 0) {
    // Bu yıl geçtiyse gelecek yıla bak
    bday = new Date(thisYear + 1, mm - 1, dd);
    diff = Math.round((bday - todayMidnight) / (1000 * 60 * 60 * 24));
  }
  return diff;
}

function getUpcoming(days = 7) {
  return state.birthdays
    .map(b => ({ ...b, daysLeft: daysUntilBirthday(b.date) }))
    .filter(b => b.daysLeft >= 0 && b.daysLeft <= days)
    .sort((a, b) => a.daysLeft - b.daysLeft);
}

function renderUpcomingBanner() {
  const container = document.getElementById('upcomingBanner');
  if (!container) return;

  const upcoming = getUpcoming(7);
  if (!upcoming.length) {
    container.innerHTML = '';
    return;
  }

  const cards = upcoming.map(b => {
    const initials = b.name.split(' ').map(w => w[0]).join('').toUpperCase().slice(0, 2);
    let tagHtml, cardClass;
    if (b.daysLeft === 0) {
      tagHtml = `<span class="upcoming-tag tag-today">🎉 Bugün!</span>`;
      cardClass = 'upcoming-today';
    } else if (b.daysLeft === 1) {
      tagHtml = `<span class="upcoming-tag tag-tomorrow">⏰ Yarın</span>`;
      cardClass = 'upcoming-soon';
    } else {
      tagHtml = `<span class="upcoming-tag tag-soon">📅 ${b.daysLeft} gün sonra</span>`;
      cardClass = 'upcoming-soon';
    }
    return `
      <div class="upcoming-card ${cardClass}">
        <div class="upcoming-avatar" style="background:${b.color}22;color:${b.color}">${initials}</div>
        <div class="upcoming-info">
          <div class="upcoming-name">${b.name}</div>
          <div class="upcoming-dept">${b.dept} &nbsp;·&nbsp; 🎂 ${b.date}</div>
        </div>
        ${tagHtml}
      </div>
    `;
  }).join('');

  container.innerHTML = `<div class="upcoming-banner">${cards}</div>`;
}

function updateNotifBadge() {
  const badge = document.getElementById('bdNotifBadge');
  if (!badge) return;
  const upcoming = getUpcoming(7);
  if (upcoming.length) {
    badge.textContent = upcoming.length;
    badge.style.display = 'flex';
  } else {
    badge.style.display = 'none';
  }
}

// ===== ETKİNLİKLER =====
const ETKINLIK_COLORS = ['#4ecdc4','#f5a623','#e05c5c','#a78bfa','#34d399','#f472b6'];

// ===== ADMIN SİSTEMİ =====
// Süper admin (HTML'de sabit) - kullanıcı yönetimi yapabilir
const SUPER_ADMIN = { username: 'superadmin', password: 'Umran2024!' };

// SHA-256 hash fonksiyonu
async function sha256(str) {
  const buf = await crypto.subtle.digest('SHA-256', new TextEncoder().encode(str));
  return Array.from(new Uint8Array(buf)).map(b=>b.toString(16).padStart(2,'0')).join('');
}

// Admin kullanıcılarını Supabase'den yükle
async function loadAdmins() {
  return await sbGetAdmins();
}

// Admin giriş panelini aç/kapat
function toggleAdminPanel() {
  if (state.adminLoggedIn) {
    showAdminDashboard();
  } else {
    showAdminLoginForm();
  }
}

function closeAdminPanelOnOverlay(e) {
  if (e.target === document.getElementById('adminPanelOverlay')) closeAdminPanel();
}

function closeAdminPanel() {
  const ov = document.getElementById('adminPanelOverlay');
  ov.style.opacity = '0';
  ov.style.pointerEvents = 'none';
}

function openAdminPanel() {
  const ov = document.getElementById('adminPanelOverlay');
  ov.style.opacity = '1';
  ov.style.pointerEvents = 'all';
}

function showAdminLoginForm() {
  document.getElementById('adminPanelTitle').textContent = '🔐 Admin Girişi';
  document.getElementById('adminPanelBody').innerHTML = `
    <div class="form-group">
      <label class="form-label">Kullanıcı Adı</label>
      <input class="form-input" id="ap-user" placeholder="Kullanıcı adı" autocomplete="off">
    </div>
    <div class="form-group">
      <label class="form-label">Şifre</label>
      <input class="form-input" id="ap-pass" type="password" placeholder="Şifre" onkeydown="if(event.key==='Enter')doAdminLogin()">
    </div>
    <div id="ap-error" style="color:var(--accent2);font-size:0.82rem;margin-top:0.3rem;display:none;">Hatalı kullanıcı adı veya şifre!</div>
  `;
  document.getElementById('adminPanelActions').innerHTML = `
    <button class="btn-cancel" onclick="closeAdminPanel()">İptal</button>
    <button class="btn-add" onclick="doAdminLogin()">🔐 Giriş Yap</button>
  `;
  openAdminPanel();
  setTimeout(() => document.getElementById('ap-user')?.focus(), 100);
}

async function doAdminLogin() {
  const user = document.getElementById('ap-user').value.trim();
  const pass = document.getElementById('ap-pass').value;
  if (!user || !pass) return;

  const hash = await sha256(pass);

  // Süper admin kontrolü
  const superHash = await sha256(SUPER_ADMIN.password);
  if (user === SUPER_ADMIN.username && hash === superHash) {
    state.adminLoggedIn = true;
    state.adminUser = { username: user, role: 'super' };
    updateAdminBtn();
    renderEtkinlikler();
    showAdminDashboard();
    return;
  }

  // Normal admin kontrolü - Supabase'den
  const admins = await loadAdmins();
  const found = admins.find(a => a.kullanici_adi === user && a.sifre_hash === hash);
  if (found) {
    state.adminLoggedIn = true;
    state.adminUser = { username: user, role: found.rol || 'admin' };
    updateAdminBtn();
    renderEtkinlikler();
    showAdminDashboard();
  } else {
    document.getElementById('ap-error').style.display = 'block';
  }
}

async function showAdminDashboard() {
  const isSuperAdmin = state.adminUser?.role === 'super';
  document.getElementById('adminPanelTitle').textContent = `👤 ${state.adminUser?.username || 'Admin'}`;
  const userListHTML = isSuperAdmin ? await renderUserListHTML() : '';
  document.getElementById('adminPanelBody').innerHTML = `
    <div style="margin-bottom:1rem;padding:0.8rem 1rem;background:var(--surface2);border-radius:8px;border:1px solid var(--border);font-size:0.85rem;color:var(--muted);">
      <span style="color:var(--accent3);font-weight:600;">●</span> Giriş yapıldı
      ${isSuperAdmin ? '<span style="margin-left:0.5rem;background:rgba(245,166,35,0.15);color:var(--accent);font-size:0.72rem;font-weight:700;padding:0.15rem 0.5rem;border-radius:10px;letter-spacing:0.05em;">SÜPER ADMİN</span>' : ''}
    </div>
    ${userListHTML}
  `;
  document.getElementById('adminPanelActions').innerHTML = `
    ${isSuperAdmin ? '<button class="btn-add" onclick="showAddUserForm()" style="margin-right:auto">+ Kullanıcı Ekle</button>' : ''}
    <button class="btn-cancel" onclick="doAdminLogout()">🚪 Çıkış</button>
    <button class="btn-add" onclick="closeAdminPanel()">Kapat</button>
  `;
  openAdminPanel();
}

async function renderUserListHTML() {
  const admins = await loadAdmins();
  if (!admins.length) return '<div style="font-size:0.84rem;color:var(--muted);text-align:center;padding:1rem 0;">Henüz admin kullanıcısı eklenmemiş.</div>';
  return `
    <div style="font-size:0.72rem;font-weight:700;text-transform:uppercase;letter-spacing:0.08em;color:var(--muted);margin-bottom:0.6rem;">Kullanıcılar</div>
    <div style="display:flex;flex-direction:column;gap:0.4rem;">
      ${admins.map(a => `
        <div style="display:flex;align-items:center;justify-content:space-between;padding:0.6rem 0.8rem;background:var(--surface2);border:1px solid var(--border);border-radius:8px;">
          <span style="font-size:0.87rem;color:var(--text);font-weight:500;">👤 ${a.kullanici_adi}</span>
          <button onclick="deleteAdmin('${a.kullanici_adi}')" style="background:none;border:none;color:var(--muted);cursor:pointer;font-size:0.85rem;padding:0;transition:color 0.15s" onmouseover="this.style.color='var(--accent2)'" onmouseout="this.style.color='var(--muted)'">✕</button>
        </div>
      `).join('')}
    </div>
  `;
}

function showAddUserForm() {
  document.getElementById('adminPanelTitle').textContent = '➕ Yeni Kullanıcı';
  document.getElementById('adminPanelBody').innerHTML = `
    <div class="form-group">
      <label class="form-label">Kullanıcı Adı</label>
      <input class="form-input" id="nu-user" placeholder="örn. ahmet.yilmaz" autocomplete="off">
    </div>
    <div class="form-group">
      <label class="form-label">Şifre</label>
      <input class="form-input" id="nu-pass" type="password" placeholder="En az 4 karakter">
    </div>
    <div class="form-group">
      <label class="form-label">Şifre Tekrar</label>
      <input class="form-input" id="nu-pass2" type="password" placeholder="Şifreyi tekrar girin">
    </div>
    <div id="nu-error" style="color:var(--accent2);font-size:0.82rem;margin-top:0.3rem;display:none;"></div>
  `;
  document.getElementById('adminPanelActions').innerHTML = `
    <button class="btn-cancel" onclick="showAdminDashboard()">← Geri</button>
    <button class="btn-add" onclick="doAddUser()">Kaydet</button>
  `;
}

async function doAddUser() {
  const username = document.getElementById('nu-user').value.trim();
  const pass = document.getElementById('nu-pass').value;
  const pass2 = document.getElementById('nu-pass2').value;
  const errEl = document.getElementById('nu-error');

  if (!username || !pass) { errEl.textContent='Kullanıcı adı ve şifre zorunludur!'; errEl.style.display='block'; return; }
  if (pass.length < 4) { errEl.textContent='Şifre en az 4 karakter olmalıdır!'; errEl.style.display='block'; return; }
  if (pass !== pass2) { errEl.textContent='Şifreler eşleşmiyor!'; errEl.style.display='block'; return; }
  if (username === SUPER_ADMIN.username) { errEl.textContent='Bu kullanıcı adı kullanılamaz!'; errEl.style.display='block'; return; }

  try {
    const passwordHash = await sha256(pass);
    await sbSaveAdmin(username, passwordHash);
    showToast('✅ Kullanıcı eklendi!');
    showAdminDashboard();
  } catch(e) {
    errEl.textContent = e.message?.includes('duplicate') ? 'Bu kullanıcı adı zaten kullanımda!' : 'Hata oluştu!';
    errEl.style.display = 'block';
  }
}

async function deleteAdmin(username) {
  if (!confirm(`"${username}" kullanıcısını silmek istediğinize emin misiniz?`)) return;
  try {
    await sbDeleteAdmin(username);
    showToast('🗑️ Kullanıcı silindi.');
    showAdminDashboard();
  } catch(e) {
    showToast('❌ Silme başarısız!');
  }
}

function doAdminLogout() {
  state.adminLoggedIn = false;
  state.adminUser = null;
  updateAdminBtn();
  renderEtkinlikler();
  closeAdminPanel();
  showToast('👋 Çıkış yapıldı.');
}

function updateAdminBtn() {
  const btn = document.getElementById('btnAdminGiris');
  if (btn) {
    if (state.adminLoggedIn) {
      btn.innerHTML = `👤 ${state.adminUser?.username || 'Admin'}`;
      btn.style.borderColor = 'var(--accent3)';
      btn.style.color = 'var(--accent3)';
    } else {
      btn.innerHTML = '🔐 Giriş';
      btn.style.borderColor = 'var(--border)';
      btn.style.color = 'var(--muted)';
    }
  }
  const etkinlikBtn = document.getElementById('btnEtkinlikEkle');
  if (etkinlikBtn) etkinlikBtn.style.display = state.adminLoggedIn ? 'inline-flex' : 'none';
  const rehberBtn = document.getElementById('btnRehberEkle');
  if (rehberBtn) rehberBtn.style.display = state.adminLoggedIn ? 'inline-flex' : 'none';
}

function adminGiris() {
  if (state.adminLoggedIn) {
    openModal('etkinlik');
  } else {
    showAdminLoginForm();
  }
}

function formatEtkinlikTarih(dateStr) {
  if (!dateStr) return '';
  const d = new Date(dateStr + 'T00:00:00');
  return d.toLocaleDateString('tr-TR', { day:'numeric', month:'long', year:'numeric', weekday:'long' });
}

function etkinlikGunFarki(dateStr) {
  if (!dateStr) return null;
  const today = new Date(); today.setHours(0,0,0,0);
  const ev = new Date(dateStr + 'T00:00:00');
  const diff = Math.round((ev - today) / 86400000);
  return diff;
}

function renderEtkinlikler() {
  const grid = document.getElementById('etkinlikGrid');
  if (!grid) return;

  // Etkinlik ekle butonunu admin durumuna göre güncelle
  const btn = document.getElementById('btnEtkinlikEkle');
  if (btn) btn.style.display = state.adminLoggedIn ? 'inline-flex' : 'none';

  if (!state.etkinlikler.length) {
    grid.innerHTML = `<div class="empty-state" style="grid-column:1/-1;padding:3rem;background:var(--surface2);border-radius:12px;border:1px solid var(--border);text-align:center"><div class="empty-icon">🎉</div><p>Henüz etkinlik eklenmemiş.</p></div>`;
    return;
  }

  // Tarihe göre sırala
  const sorted = [...state.etkinlikler].sort((a,b) => new Date(a.date) - new Date(b.date));
  const today = new Date(); today.setHours(0,0,0,0);

  // Yaklaşan ve geçmiş ayır
  const upcoming = sorted.filter(e => new Date(e.date+'T00:00:00') >= today);
  const past = sorted.filter(e => new Date(e.date+'T00:00:00') < today);

  let html = '';

  if (upcoming.length) {
    html += upcoming.map(e => etkinlikKart(e, false)).join('');
  }

  if (past.length) {
    html += `<div style="grid-column:1/-1;margin-top:0.5rem;padding-top:1rem;border-top:1px solid var(--border)">
      <div style="font-size:0.72rem;font-weight:700;text-transform:uppercase;letter-spacing:0.1em;color:var(--muted);margin-bottom:1rem">Geçmiş Etkinlikler</div>
    </div>`;
    html += past.reverse().map(e => etkinlikKart(e, true)).join('');
  }

  grid.innerHTML = html;
}

function etkinlikKart(e, gecmis) {
  const diff = etkinlikGunFarki(e.date);
  let etiket = '';
  if (diff === 0) etiket = `<span style="background:${e.color}22;color:${e.color};font-size:0.68rem;font-weight:700;padding:0.2rem 0.6rem;border-radius:20px;letter-spacing:0.05em;">🔥 BUGÜN</span>`;
  else if (diff === 1) etiket = `<span style="background:${e.color}22;color:${e.color};font-size:0.68rem;font-weight:700;padding:0.2rem 0.6rem;border-radius:20px;letter-spacing:0.05em;">⏰ YARIN</span>`;
  else if (diff > 1 && diff <= 7) etiket = `<span style="background:${e.color}22;color:${e.color};font-size:0.68rem;font-weight:700;padding:0.2rem 0.6rem;border-radius:20px;letter-spacing:0.05em;">${diff} gün sonra</span>`;
  else if (gecmis) etiket = `<span style="background:var(--surface);color:var(--muted);font-size:0.68rem;font-weight:600;padding:0.2rem 0.6rem;border-radius:20px;">Geçti</span>`;

  const adminBtns = state.adminLoggedIn ? `
    <div style="display:flex;gap:0.4rem;margin-top:1rem;">
      <button class="btn-edit" onclick="editItem('etkinlik','${e.id}')">Düzenle</button>
      <button class="btn-danger" onclick="deleteItem('etkinlik','${e.id}')">Sil</button>
    </div>` : '';

  return `
    <div style="background:var(--surface2);border:1px solid var(--border);border-top:4px solid ${e.color};border-radius:12px;padding:1.4rem;opacity:${gecmis?'0.6':'1'};transition:opacity 0.2s;">
      <div style="display:flex;align-items:flex-start;justify-content:space-between;gap:0.5rem;margin-bottom:0.8rem;">
        <div style="font-size:1.05rem;font-weight:700;color:var(--text);line-height:1.3;">${e.title}</div>
        ${etiket}
      </div>
      <div style="display:flex;align-items:center;gap:0.4rem;font-size:0.82rem;color:${e.color};font-weight:600;margin-bottom:${e.desc?'0.7rem':'0'}">
        📅 ${formatEtkinlikTarih(e.date)}${e.time ? ' · ⏰ ' + e.time : ''}
      </div>
      ${e.desc ? `<div style="font-size:0.84rem;color:var(--muted);line-height:1.6;">${e.desc}</div>` : ''}
      ${adminBtns}
    </div>
  `;
}

// ===== DAHİLİ REHBER =====
let rehberTabState = 'merkez';

function selectRehberTab(tab) {
  rehberTabState = tab;
  // Tab butonlarını güncelle
  ['merkez','fabrika','tumu'].forEach(t => {
    const btn = document.getElementById('rtab-' + (t === 'tumu' ? 'tumü' : t));
    if (!btn) return;
    if (t === tab) {
      btn.style.borderBottom = '3px solid var(--accent3)';
      btn.style.color = 'var(--accent3)';
    } else {
      btn.style.borderBottom = '3px solid transparent';
      btn.style.color = 'var(--muted)';
    }
  });
  filterRehber();
}

function filterRehber() {
  const q = (document.getElementById('rehberSearch')?.value || '').toLowerCase().trim();
  let liste = state.rehber;

  // Tab filtresi
  if (rehberTabState === 'merkez') liste = liste.filter(k => k.unite === 'Merkez');
  else if (rehberTabState === 'fabrika') liste = liste.filter(k => k.unite === 'Fabrika');

  // Arama filtresi
  if (q) liste = liste.filter(k =>
    k.name.toLowerCase().includes(q) ||
    (k.dept||'').toLowerCase().includes(q) ||
    (k.dahili||'').includes(q)
  );

  renderRehberList(liste);
}

function renderRehber() {
  // Admin butonunu güncelle
  const btn = document.getElementById('btnRehberEkle');
  if (btn) btn.style.display = state.adminLoggedIn ? 'inline-flex' : 'none';
  filterRehber();
}

function renderRehberList(liste) {
  const grid = document.getElementById('rehberGrid');
  if (!grid) return;

  if (!liste.length) {
    grid.innerHTML = `<div class="empty-state" style="grid-column:1/-1;padding:3rem;background:var(--surface2);border-radius:12px;border:1px solid var(--border);text-align:center">
      <div class="empty-icon">📋</div><p>Kayıt bulunamadı.</p></div>`;
    return;
  }

  grid.innerHTML = liste.map(k => {
    const renk = k.unite === 'Merkez' ? 'var(--accent3)' : 'var(--accent)';
    const uniteBadge = k.unite === 'Merkez' ? '🏢' : '🏭';
    const adminBtns = state.adminLoggedIn ? `
      <div style="display:flex;gap:0.4rem;margin-top:0.8rem;padding-top:0.6rem;border-top:1px solid var(--border);">
        <button class="btn-edit" onclick="editItem('rehber','${k.id}')" style="font-size:0.75rem;padding:0.25rem 0.6rem;">Düzenle</button>
        <button class="btn-danger" onclick="deleteItem('rehber','${k.id}')" style="font-size:0.75rem;padding:0.25rem 0.6rem;">Sil</button>
      </div>` : '';

    return `
      <div style="background:var(--surface2);border:1px solid var(--border);border-left:4px solid ${renk};border-radius:10px;padding:1rem 1.1rem;display:flex;flex-direction:column;gap:0.3rem;">
        <div style="display:flex;align-items:center;justify-content:space-between;gap:0.5rem;">
          <div style="font-size:0.92rem;font-weight:700;color:var(--text);">${k.name}</div>
          <span style="font-size:0.7rem;font-weight:600;color:${renk};background:${renk}22;padding:0.15rem 0.5rem;border-radius:10px;white-space:nowrap;">${uniteBadge} ${k.unite}</span>
        </div>
        ${k.dept ? `<div style="font-size:0.8rem;color:var(--muted);">${k.dept}</div>` : ''}
        <div style="display:flex;align-items:center;gap:0.4rem;margin-top:0.3rem;">
          <span style="font-size:1rem;">📞</span>
          <span style="font-size:1rem;font-weight:700;color:${renk};letter-spacing:0.05em;">${k.dahili}</span>
        </div>
        ${adminBtns}
      </div>`;
  }).join('');
}

// ===== INIT =====
loadState(); // localStorage'dan importedFileName gibi local state'leri yükle
initDate();
updateWeekBanner();

// Supabase'den tüm verileri yükle, sonra render et
(async () => {
  await loadAllData();
  renderMeals();
  updateNotifBadge();
})();
</script>
</body>
</html>
