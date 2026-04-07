<!doctype html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Admin — Blowout Galeria</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,opsz,wght@0,6..96,700;1,6..96,400&family=Cormorant+Garamond:wght@300;400;600&display=swap" rel="stylesheet" />
  <!-- Cloudinary Upload Widget -->
  <script src="https://upload-widget.cloudinary.com/global/all.js" type="text/javascript"></script>
  <style>
    :root {
      --bg: #faf9f7;
      --surface: #ffffff;
      --border: rgba(0,0,0,0.09);
      --text: #0f0f0f;
      --text-mid: #555;
      --accent: #c8a87a;
      --danger: #c0392b;
      --T: cubic-bezier(0.16,1,0.3,1);
    }
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { font-family: "Cormorant Garamond", serif; background: var(--bg); color: var(--text); }

    /* ─── LOGIN ─── */
    #loginScreen {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .login-box {
      background: var(--surface);
      border: 1px solid var(--border);
      padding: 56px 48px;
      width: 360px;
      text-align: center;
    }
    .login-box h1 {
      font-family: "Bodoni Moda", serif;
      font-style: italic;
      font-size: 28px;
      font-weight: 400;
      margin-bottom: 8px;
    }
    .login-box p {
      font-size: 12px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--text-mid);
      margin-bottom: 36px;
    }
    .login-box input {
      width: 100%;
      padding: 14px 18px;
      border: 1px solid var(--border);
      background: var(--bg);
      font-family: "Cormorant Garamond", serif;
      font-size: 16px;
      color: var(--text);
      margin-bottom: 14px;
      outline: none;
      transition: border-color 0.2s;
    }
    .login-box input:focus { border-color: var(--accent); }
    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      padding: 13px 28px;
      font-family: "Cormorant Garamond", serif;
      font-size: 11px;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      cursor: pointer;
      transition: all 0.2s;
      border: none;
    }
    .btn-primary {
      background: var(--text);
      color: #fff;
      width: 100%;
    }
    .btn-primary:hover { background: #333; }
    .btn-accent {
      background: var(--accent);
      color: #fff;
    }
    .btn-accent:hover { background: #b8983a; }
    .btn-outline {
      background: none;
      border: 1px solid var(--border);
      color: var(--text);
    }
    .btn-outline:hover { border-color: var(--text); }
    .btn-danger {
      background: none;
      border: 1px solid rgba(192,57,43,0.3);
      color: var(--danger);
      font-size: 10px;
      padding: 5px 10px;
    }
    .btn-danger:hover { background: rgba(192,57,43,0.05); }
    #loginError {
      font-size: 12px;
      color: var(--danger);
      margin-top: 10px;
      min-height: 18px;
    }

    /* ─── APP ─── */
    #app { display: none; }

    header {
      background: var(--surface);
      border-bottom: 1px solid var(--border);
      padding: 16px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0; z-index: 10;
    }
    .header-brand {
      display: flex;
      align-items: center;
      gap: 16px;
    }
    .header-brand h1 {
      font-family: "Bodoni Moda", serif;
      font-size: 18px;
      font-style: italic;
      font-weight: 400;
    }
    .header-brand span {
      font-size: 11px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--text-mid);
      padding: 4px 12px;
      border: 1px solid var(--border);
    }
    .header-actions { display: flex; gap: 10px; }

    main { max-width: 1100px; margin: 0 auto; padding: 48px 40px; }

    /* ─── SETUP BANNER ─── */
    #setupBanner {
      background: #fffbf2;
      border: 1px solid #e8c97a;
      padding: 28px 32px;
      margin-bottom: 40px;
      display: none;
    }
    #setupBanner h3 {
      font-family: "Bodoni Moda", serif;
      font-size: 17px;
      font-weight: 700;
      margin-bottom: 12px;
    }
    #setupBanner p { font-size: 15px; color: var(--text-mid); line-height: 1.7; margin-bottom: 12px; }
    #setupBanner .setup-inputs { display: flex; gap: 12px; align-items: flex-end; flex-wrap: wrap; margin-top: 16px; }
    #setupBanner .setup-field { display: flex; flex-direction: column; gap: 6px; flex: 1; min-width: 200px; }
    #setupBanner label { font-size: 10px; letter-spacing: 0.2em; text-transform: uppercase; color: var(--text-mid); }
    #setupBanner input {
      padding: 11px 14px;
      border: 1px solid #e8c97a;
      background: #fff;
      font-family: "Cormorant Garamond", serif;
      font-size: 15px;
      outline: none;
    }
    #setupBanner input:focus { border-color: var(--accent); }

    /* ─── TABS ─── */
    .tabs {
      display: flex;
      gap: 0;
      border-bottom: 1px solid var(--border);
      margin-bottom: 40px;
    }
    .tab-btn {
      font-family: "Cormorant Garamond", serif;
      font-size: 12px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: rgba(0,0,0,0.35);
      padding: 12px 24px 14px;
      background: none;
      border: none;
      cursor: pointer;
      position: relative;
      transition: color 0.2s;
      white-space: nowrap;
    }
    .tab-btn::after {
      content: "";
      position: absolute;
      bottom: -1px; left: 0;
      width: 0; height: 2px;
      background: var(--text);
      transition: width 0.3s var(--T);
    }
    .tab-btn.active { color: var(--text); }
    .tab-btn.active::after { width: 100%; }

    /* ─── UPLOAD AREA ─── */
    .upload-area {
      border: 2px dashed var(--border);
      padding: 48px;
      text-align: center;
      margin-bottom: 32px;
      transition: border-color 0.2s;
      cursor: pointer;
    }
    .upload-area:hover { border-color: var(--accent); }
    .upload-area .u-icon { font-size: 36px; margin-bottom: 14px; opacity: 0.4; }
    .upload-area h3 {
      font-family: "Bodoni Moda", serif;
      font-size: 18px;
      font-weight: 700;
      margin-bottom: 8px;
    }
    .upload-area p { font-size: 14px; color: var(--text-mid); margin-bottom: 20px; }
    #cloudSetupNote { font-size: 12px; color: #b8983a; margin-top: 12px; display: none; }

    /* ─── IMAGE GRID ─── */
    .img-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 12px;
      margin-bottom: 32px;
    }
    .img-card {
      position: relative;
      aspect-ratio: 3/4;
      overflow: hidden;
      background: var(--surface);
      border: 1px solid var(--border);
    }
    .img-card img {
      width: 100%; height: 100%;
      object-fit: cover;
      display: block;
    }
    .img-card-overlay {
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.55);
      opacity: 0;
      transition: opacity 0.2s;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }
    .img-card:hover .img-card-overlay { opacity: 1; }
    .img-card input {
      position: absolute;
      bottom: 0; left: 0; right: 0;
      background: rgba(0,0,0,0.7);
      border: none;
      color: #fff;
      font-family: "Cormorant Garamond", serif;
      font-size: 12px;
      padding: 6px 8px;
      width: 100%;
      outline: none;
    }
    .img-card input::placeholder { color: rgba(255,255,255,0.4); }
    .empty-state {
      grid-column: 1/-1;
      padding: 60px 0;
      text-align: center;
      font-size: 13px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: rgba(0,0,0,0.2);
    }

    /* ─── EXPORT ─── */
    #exportPanel {
      background: var(--surface);
      border: 1px solid var(--border);
      padding: 32px;
      display: none;
      margin-top: 24px;
    }
    #exportPanel h3 {
      font-family: "Bodoni Moda", serif;
      font-size: 17px;
      font-weight: 700;
      margin-bottom: 14px;
    }
    #exportPanel p { font-size: 14px; color: var(--text-mid); line-height: 1.6; margin-bottom: 16px; }
    #exportCode {
      font-family: monospace;
      font-size: 12px;
      line-height: 1.6;
      background: #f5f5f5;
      border: 1px solid var(--border);
      padding: 20px;
      width: 100%;
      height: 200px;
      resize: vertical;
      outline: none;
      color: var(--text);
    }
    .export-actions { display: flex; gap: 10px; margin-top: 14px; }

    .status-bar {
      position: fixed;
      bottom: 24px; right: 24px;
      background: var(--text);
      color: #fff;
      padding: 12px 20px;
      font-size: 12px;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      opacity: 0;
      transform: translateY(10px);
      transition: all 0.3s;
      pointer-events: none;
    }
    .status-bar.show { opacity: 1; transform: translateY(0); }
  </style>
</head>
<body>

<!-- LOGIN -->
<div id="loginScreen">
  <div class="login-box">
    <h1>Blowout</h1>
    <p>Panel administratora</p>
    <input type="password" id="passInput" placeholder="Hasło…" autocomplete="current-password" />
    <button class="btn btn-primary" onclick="doLogin()">Zaloguj się</button>
    <div id="loginError"></div>
  </div>
</div>

<!-- APP -->
<div id="app">
  <header>
    <div class="header-brand">
      <h1>Blowout Admin</h1>
      <span>Galeria</span>
    </div>
    <div class="header-actions">
      <button class="btn btn-outline" onclick="previewSite()">Podgląd ↗</button>
      <button class="btn btn-accent" onclick="saveGallery()">Zapisz i opublikuj</button>
      <button class="btn btn-outline" onclick="doLogout()">Wyloguj</button>
    </div>
  </header>

  <main>
    <!-- SETUP BANNER -->
    <div id="setupBanner">
      <h3>⚙ Skonfiguruj Cloudinary</h3>
      <p>
        Cloudinary to darmowy serwis do przechowywania zdjęć. Rejestracja jest bezpłatna
        (25 GB miejsca). Wpisz poniżej swoje dane, aby móc wgrywać zdjęcia przez ten panel.
      </p>
      <p>
        <strong>Jak to zrobić:</strong><br/>
        1. Przejdź na <strong>cloudinary.com</strong> i załóż darmowe konto.<br/>
        2. Po zalogowaniu w dashboardzie znajdziesz swój <em>Cloud Name</em> (np. <code>my-blowout</code>).<br/>
        3. Przejdź do <em>Settings → Upload → Upload presets</em>, kliknij „Add upload preset",<br/>
        &nbsp;&nbsp;&nbsp;ustaw <em>Signing Mode</em> na <strong>Unsigned</strong> i zapisz. Skopiuj nazwę presetu.
      </p>
      <div class="setup-inputs">
        <div class="setup-field">
          <label>Cloud Name</label>
          <input type="text" id="cfCloudName" placeholder="np. my-blowout-studio" />
        </div>
        <div class="setup-field">
          <label>Upload Preset (unsigned)</label>
          <input type="text" id="cfUploadPreset" placeholder="np. blowout_gallery" />
        </div>
        <button class="btn btn-primary" style="flex-shrink:0;padding:11px 24px" onclick="saveCloudinaryConfig()">Zapisz konfigurację</button>
      </div>
    </div>

    <!-- TABS -->
    <div class="tabs">
      <button class="tab-btn active" data-tab="blondy">Blondy</button>
      <button class="tab-btn" data-tab="koloryzacje">Koloryzacje</button>
      <button class="tab-btn" data-tab="ciecia">Cięcia</button>
      <button class="tab-btn" data-tab="upiecia">Upięcia</button>
    </div>

    <!-- UPLOAD AREA -->
    <div class="upload-area" id="uploadArea" onclick="openUpload()">
      <div class="u-icon">📷</div>
      <h3>Wgraj zdjęcia</h3>
      <p>Kliknij, aby otworzyć panel przesyłania Cloudinary.<br/>Obsługuje: JPEG, PNG, WebP, HEIC.</p>
      <button class="btn btn-accent" onclick="openUpload(event)">Wybierz pliki</button>
      <div id="cloudSetupNote">⚠ Najpierw skonfiguruj Cloudinary powyżej.</div>
    </div>

    <!-- IMAGE GRID -->
    <div class="img-grid" id="imgGrid"></div>

    <!-- EXPORT -->
    <div id="exportPanel">
      <h3>Gotowy plik gallery-data.js</h3>
      <p>Skopiuj ten kod i zapisz jako <code>gallery-data.js</code> w folderze projektu,
         aby zmiany były trwałe nawet po wyczyszczeniu pamięci przeglądarki.</p>
      <textarea id="exportCode" readonly></textarea>
      <div class="export-actions">
        <button class="btn btn-primary" onclick="downloadFile()">Pobierz gallery-data.js</button>
        <button class="btn btn-outline" onclick="copyCode()">Kopiuj kod</button>
        <button class="btn btn-outline" onclick="document.getElementById('exportPanel').style.display='none'">Zamknij</button>
      </div>
    </div>
  </main>
</div>

<div class="status-bar" id="statusBar"></div>

<script>
// ─── PASSWORD ──────────────────────────────────────────────────────────
// Change this to your desired password:
const ADMIN_PASSWORD = "blowout2025";

function doLogin() {
  const val = document.getElementById("passInput").value;
  if (val === ADMIN_PASSWORD) {
    document.getElementById("loginScreen").style.display = "none";
    document.getElementById("app").style.display = "block";
    initApp();
  } else {
    document.getElementById("loginError").textContent = "Nieprawidłowe hasło.";
    document.getElementById("passInput").value = "";
  }
}
document.getElementById("passInput").addEventListener("keydown", e => {
  if (e.key === "Enter") doLogin();
});
function doLogout() {
  document.getElementById("loginScreen").style.display = "flex";
  document.getElementById("app").style.display = "none";
}

// ─── STATE ─────────────────────────────────────────────────────────────
const TABS = ["blondy", "koloryzacje", "ciecia", "upiecia"];
let gallery = { blondy: [], koloryzacje: [], ciecia: [], upiecia: [] };
let activeTab = "blondy";
let cfCloudName = "", cfUploadPreset = "";

function loadState() {
  try {
    const g = localStorage.getItem("blowout_gallery");
    if (g) gallery = JSON.parse(g);
    const cf = localStorage.getItem("blowout_cloudinary");
    if (cf) { const p = JSON.parse(cf); cfCloudName = p.cloudName || ""; cfUploadPreset = p.uploadPreset || ""; }
  } catch {}
}

function initApp() {
  loadState();

  // Restore cloudinary config inputs
  if (cfCloudName) document.getElementById("cfCloudName").value = cfCloudName;
  if (cfUploadPreset) document.getElementById("cfUploadPreset").value = cfUploadPreset;

  // Show setup banner if not configured
  if (!cfCloudName || !cfUploadPreset) {
    document.getElementById("setupBanner").style.display = "block";
  }

  // Tab clicks
  document.querySelectorAll(".tab-btn").forEach(btn => {
    btn.addEventListener("click", () => {
      activeTab = btn.dataset.tab;
      document.querySelectorAll(".tab-btn").forEach(b => b.classList.remove("active"));
      btn.classList.add("active");
      renderGrid();
    });
  });

  renderGrid();
}

function saveCloudinaryConfig() {
  cfCloudName    = document.getElementById("cfCloudName").value.trim();
  cfUploadPreset = document.getElementById("cfUploadPreset").value.trim();
  if (!cfCloudName || !cfUploadPreset) {
    alert("Wypełnij oba pola: Cloud Name i Upload Preset.");
    return;
  }
  localStorage.setItem("blowout_cloudinary", JSON.stringify({ cloudName: cfCloudName, uploadPreset: cfUploadPreset }));
  document.getElementById("setupBanner").style.display = "none";
  showStatus("Konfiguracja Cloudinary zapisana ✓");
}

// ─── UPLOAD ─────────────────────────────────────────────────────────────
function openUpload(e) {
  if (e) e.stopPropagation();

  // Re-read in case they just saved config
  const freshCf = localStorage.getItem("blowout_cloudinary");
  if (freshCf) { const p = JSON.parse(freshCf); cfCloudName = p.cloudName || ""; cfUploadPreset = p.uploadPreset || ""; }

  if (!cfCloudName || !cfUploadPreset) {
    document.getElementById("setupBanner").style.display = "block";
    document.getElementById("cloudSetupNote").style.display = "block";
    document.getElementById("setupBanner").scrollIntoView({ behavior: "smooth" });
    return;
  }

  const widget = cloudinary.createUploadWidget({
    cloudName:    cfCloudName,
    uploadPreset: cfUploadPreset,
    multiple:     true,
    maxFiles:     20,
    resourceType: "image",
    clientAllowedFormats: ["jpg","jpeg","png","webp","heic"],
    folder:       "blowout/" + activeTab,
    sources: ["local", "url", "camera"],
    styles: {
      palette: { window: "#FFFFFF", sourceBg: "#FAFAF8", windowBorder: "#E0DDDA",
                 tabIcon: "#C8A87A", inactiveTabIcon: "#999", menuIcons: "#555",
                 link: "#C8A87A", action: "#0F0F0F", inProgress: "#C8A87A",
                 complete: "#2ECC71", error: "#C0392B", textDark: "#0F0F0F", textLight: "#FFFFFF" },
      frame: { background: "rgba(0,0,0,0.6)" }
    }
  }, (error, result) => {
    if (error) { console.error(error); return; }
    if (result.event === "success") {
      const info = result.info;
      gallery[activeTab].push({ url: info.secure_url, caption: "" });
      renderGrid();
    }
    if (result.event === "close") {
      saveGallery(true); // silent save after upload session
    }
  });
  widget.open();
}

// ─── GRID RENDER ────────────────────────────────────────────────────────
function renderGrid() {
  const grid   = document.getElementById("imgGrid");
  const images = gallery[activeTab] || [];
  grid.innerHTML = "";

  if (images.length === 0) {
    grid.innerHTML = `<div class="empty-state">Brak zdjęć w tej kategorii.<br/>Kliknij „Wgraj zdjęcia" powyżej.</div>`;
    return;
  }

  images.forEach((img, idx) => {
    const card = document.createElement("div");
    card.className = "img-card";
    card.innerHTML = `
      <img src="${img.url}" alt="${img.caption || ''}" loading="lazy" />
      <div class="img-card-overlay">
        <button class="btn btn-danger" onclick="removeImage(${idx})">✕ Usuń</button>
      </div>
      <input type="text" value="${img.caption || ''}" placeholder="Opis (opcjonalnie)"
             oninput="gallery['${activeTab}'][${idx}].caption = this.value" />`;
    grid.appendChild(card);
  });
}

function removeImage(idx) {
  if (!confirm("Usunąć to zdjęcie?")) return;
  gallery[activeTab].splice(idx, 1);
  renderGrid();
  showStatus("Zdjęcie usunięte");
}

// ─── SAVE ────────────────────────────────────────────────────────────────
function saveGallery(silent = false) {
  localStorage.setItem("blowout_gallery", JSON.stringify(gallery));
  if (!silent) {
    showStatus("Zapisano! Zmiany widoczne na stronie ✓");
    buildExport();
    document.getElementById("exportPanel").style.display = "block";
    document.getElementById("exportPanel").scrollIntoView({ behavior: "smooth" });
  }
}

// ─── EXPORT ──────────────────────────────────────────────────────────────
function buildExport() {
  const lines = ["var GALLERY_DATA = {"];
  TABS.forEach((tab, i) => {
    const imgs = gallery[tab] || [];
    lines.push(`  ${tab}: [`);
    imgs.forEach((img, j) => {
      const comma = j < imgs.length - 1 ? "," : "";
      lines.push(`    { url: "${img.url}", caption: "${img.caption || ''}" }${comma}`);
    });
    lines.push(`  ]${i < TABS.length - 1 ? "," : ""}`);
  });
  lines.push("};");
  document.getElementById("exportCode").value = lines.join("\n");
}

function downloadFile() {
  buildExport();
  const blob = new Blob([document.getElementById("exportCode").value], { type: "text/javascript" });
  const a = document.createElement("a");
  a.href = URL.createObjectURL(blob);
  a.download = "gallery-data.js";
  a.click();
  showStatus("Pobrano gallery-data.js ✓");
}

function copyCode() {
  buildExport();
  navigator.clipboard.writeText(document.getElementById("exportCode").value)
    .then(() => showStatus("Kod skopiowany do schowka ✓"))
    .catch(() => { document.getElementById("exportCode").select(); document.execCommand("copy"); showStatus("Skopiowano ✓"); });
}

function previewSite() {
  window.open("/", "_blank");
}

// ─── STATUS ──────────────────────────────────────────────────────────────
let statusTimer;
function showStatus(msg) {
  const bar = document.getElementById("statusBar");
  bar.textContent = msg;
  bar.classList.add("show");
  clearTimeout(statusTimer);
  statusTimer = setTimeout(() => bar.classList.remove("show"), 3200);
}
</script>
</body>
</html>