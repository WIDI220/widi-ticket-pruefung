<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WIDI – Ticket-Prüfung</title>
<style>
:root {
  --bg: #F5F4F1;
  --surface: #FFFFFF;
  --border: #E2DFD8;
  --border-strong: #C8C4BC;
  --text: #1C1B19;
  --text-muted: #7A7570;
  --text-faint: #A8A49E;
  --red: #D04040;
  --red-bg: #FDF2F2;
  --red-border: #F0C0C0;
  --green: #2A8A5A;
  --green-bg: #F0F8F4;
  --green-border: #AADDC4;
  --blue: #2060A8;
  --blue-bg: #EFF4FC;
  --blue-border: #B0C8E8;
  --radius: 8px;
  --radius-lg: 12px;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
  background: var(--bg);
  color: var(--text);
  min-height: 100vh;
  font-size: 14px;
  line-height: 1.5;
}

/* ── TOPBAR ── */
.topbar {
  background: var(--surface);
  border-bottom: 1px solid var(--border);
  padding: 0 1.5rem;
  height: 52px;
  display: flex;
  align-items: center;
  gap: 10px;
  position: sticky;
  top: 0;
  z-index: 50;
}
.logo { font-weight: 700; font-size: 17px; letter-spacing: -0.3px; color: var(--text); }
.logo-dot { color: var(--red); }
.topbar-divider { width: 1px; height: 18px; background: var(--border); }
.topbar-title { font-size: 13px; color: var(--text-muted); }
.topbar-right { margin-left: auto; display: flex; align-items: center; gap: 8px; }
#topbar-badge {
  display: none;
  font-size: 11px;
  font-weight: 600;
  padding: 3px 9px;
  border-radius: 20px;
  background: var(--red-bg);
  color: var(--red);
  border: 1px solid var(--red-border);
}

/* ── LAYOUT ── */
.page { max-width: 800px; margin: 0 auto; padding: 2rem 1.5rem 4rem; }

/* ── BUTTONS ── */
.btn {
  display: inline-flex; align-items: center; gap: 6px;
  padding: 8px 16px; border-radius: var(--radius);
  border: 1px solid var(--border-strong);
  background: var(--surface); color: var(--text);
  font-size: 13px; font-weight: 500; cursor: pointer;
  font-family: inherit; transition: background 0.1s, border-color 0.1s;
  white-space: nowrap;
}
.btn:hover { background: var(--bg); }
.btn-primary { background: var(--text); color: #fff; border-color: var(--text); }
.btn-primary:hover { background: #333; }
.btn-danger { background: var(--red); color: #fff; border-color: var(--red); }
.btn-danger:hover { background: #b83535; }
.btn-sm { padding: 6px 12px; font-size: 12px; }
.btn svg { flex-shrink: 0; }

/* ── UPLOAD SCREEN ── */
#view-upload { display: block; }
.upload-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius-lg);
  padding: 2.5rem 2rem;
  text-align: center;
}
.upload-card h2 { font-size: 16px; font-weight: 600; margin-bottom: 6px; }
.upload-card > p { font-size: 13px; color: var(--text-muted); margin-bottom: 1.5rem; }

.drop-zone {
  border: 2px dashed var(--border-strong);
  border-radius: var(--radius-lg);
  padding: 3rem 2rem;
  cursor: pointer;
  transition: border-color 0.15s, background 0.15s;
  background: var(--bg);
}
.drop-zone:hover, .drop-zone.drag {
  border-color: var(--red);
  background: var(--red-bg);
}
.drop-icon { font-size: 36px; margin-bottom: 10px; }
.drop-zone p { font-size: 14px; color: var(--text-muted); }
.drop-zone p strong { color: var(--text); }
.drop-zone small { display: block; margin-top: 6px; font-size: 12px; color: var(--text-faint); }

.upload-or { display: flex; align-items: center; gap: 12px; margin: 1.25rem 0; }
.upload-or::before, .upload-or::after { content: ''; flex: 1; height: 1px; background: var(--border); }
.upload-or span { font-size: 12px; color: var(--text-faint); }

/* ── ANALYZING SCREEN ── */
#view-analyzing { display: none; }
.analyzing-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius-lg);
  padding: 3rem 2rem;
  text-align: center;
}
.spinner {
  width: 36px; height: 36px;
  border: 3px solid var(--border);
  border-top-color: var(--red);
  border-radius: 50%;
  animation: spin 0.75s linear infinite;
  margin: 0 auto 1rem;
}
@keyframes spin { to { transform: rotate(360deg); } }
.analyzing-card h3 { font-size: 15px; font-weight: 600; margin-bottom: 6px; }
.analyzing-card p { font-size: 13px; color: var(--text-muted); }
.progress-bar { background: var(--border); border-radius: 4px; height: 3px; margin-top: 1.25rem; overflow: hidden; }
.progress-fill { height: 100%; background: var(--red); border-radius: 4px; transition: width 0.6s ease; }

/* ── RESULTS SCREEN ── */
#view-results { display: none; }

.stats-row {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 10px;
  margin-bottom: 1.25rem;
}
.stat {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 14px 16px;
}
.stat .n { font-size: 24px; font-weight: 700; line-height: 1; }
.stat .l { font-size: 11px; color: var(--text-muted); margin-top: 4px; text-transform: uppercase; letter-spacing: 0.04em; }
.n-total { color: var(--text); }
.n-ok { color: var(--green); }
.n-err { color: var(--red); }
.n-fix { color: var(--blue); }

.results-toolbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 12px;
}
.results-toolbar h3 {
  font-size: 11px;
  font-weight: 700;
  color: var(--text-muted);
  text-transform: uppercase;
  letter-spacing: 0.06em;
}
.toolbar-actions { display: flex; gap: 8px; }

/* ── TICKET ── */
.ticket {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius-lg);
  margin-bottom: 8px;
  overflow: hidden;
  border-left: 3px solid var(--border);
}
.ticket.t-ok    { border-left-color: var(--green); }
.ticket.t-error { border-left-color: var(--red); }
.ticket.t-fixed { border-left-color: var(--blue); }

.ticket-header {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 12px 16px;
  cursor: pointer;
  user-select: none;
}
.ticket-header:hover { background: var(--bg); }

.t-nr {
  font-size: 11px;
  font-weight: 700;
  color: var(--text-muted);
  font-family: monospace;
  min-width: 100px;
}
.t-meta { flex: 1; min-width: 0; }
.t-name { font-size: 13px; font-weight: 600; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
.t-sub { font-size: 12px; color: var(--text-muted); margin-top: 1px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }

.badge {
  font-size: 11px; font-weight: 600;
  padding: 3px 9px; border-radius: 20px;
  white-space: nowrap; flex-shrink: 0;
}
.badge-ok  { background: var(--green-bg); color: var(--green); border: 1px solid var(--green-border); }
.badge-err { background: var(--red-bg);   color: var(--red);   border: 1px solid var(--red-border); }
.badge-fix { background: var(--blue-bg);  color: var(--blue);  border: 1px solid var(--blue-border); }

.chevron { color: var(--text-faint); font-size: 16px; transition: transform 0.2s; flex-shrink: 0; }
.chevron.open { transform: rotate(180deg); }

/* ── TICKET BODY ── */
.ticket-body {
  display: none;
  padding: 0 16px 16px;
  border-top: 1px solid var(--border);
}
.ticket-body.open { display: block; padding-top: 14px; }

.info-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
  margin-bottom: 14px;
}
.info-cell .ic-label {
  font-size: 10px; font-weight: 700; color: var(--text-faint);
  text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 3px;
}
.info-cell .ic-val { font-size: 13px; font-weight: 500; }

.section-label {
  font-size: 10px; font-weight: 700; color: var(--text-faint);
  text-transform: uppercase; letter-spacing: 0.06em;
  margin: 14px 0 6px;
}

.remark {
  background: var(--bg);
  border-radius: var(--radius);
  padding: 9px 12px;
  font-size: 13px;
  color: var(--text-muted);
  line-height: 1.6;
}

.times { display: flex; flex-direction: column; gap: 4px; }
.time-row {
  display: flex; align-items: flex-start; gap: 10px;
  padding: 7px 10px; border-radius: 6px; font-size: 12px;
}
.time-row.ok  { background: var(--green-bg); color: var(--green); }
.time-row.err { background: var(--red-bg);   color: var(--red); }
.time-row .tr-entry { flex: 1; font-family: monospace; }
.time-row .tr-note  { font-size: 11px; font-weight: 600; }

.error-block {
  background: var(--red-bg);
  border: 1px solid var(--red-border);
  border-radius: var(--radius);
  padding: 10px 14px;
  margin: 12px 0 0;
}
.error-block-title {
  font-size: 11px; font-weight: 700; color: var(--red);
  text-transform: uppercase; letter-spacing: 0.04em;
  margin-bottom: 6px;
}
.error-block ul { list-style: none; display: flex; flex-direction: column; gap: 5px; }
.error-block li {
  font-size: 13px; color: var(--red);
  display: flex; gap: 8px; line-height: 1.4;
}
.error-block li::before { content: '→'; flex-shrink: 0; }

/* correction */
.correction-wrap { margin-top: 14px; }
.correction-wrap label {
  display: block; font-size: 12px; font-weight: 600;
  color: var(--text-muted); margin-bottom: 6px;
}
.correction-wrap textarea {
  width: 100%;
  border: 1.5px solid var(--red);
  border-radius: var(--radius);
  padding: 9px 12px;
  font-size: 13px; font-family: inherit;
  color: var(--red); background: var(--red-bg);
  resize: vertical; min-height: 76px;
  outline: none; line-height: 1.5;
}
.correction-wrap textarea:focus {
  box-shadow: 0 0 0 3px rgba(208,64,64,0.12);
}
.ticket-actions { display: flex; gap: 8px; margin-top: 10px; flex-wrap: wrap; }

.fixed-block {
  background: var(--blue-bg);
  border: 1px solid var(--blue-border);
  border-radius: var(--radius);
  padding: 10px 14px;
  margin-top: 14px;
}
.fixed-block-title {
  font-size: 10px; font-weight: 700; color: var(--blue);
  text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 5px;
}
.fixed-block-text { font-size: 13px; color: var(--blue); line-height: 1.5; }
.fixed-block-actions { margin-top: 8px; }

/* ── BOTTOM BAR ── */
.bottom-bar {
  display: flex; align-items: center; gap: 10px;
  margin-top: 1.5rem; padding-top: 1.25rem;
  border-top: 1px solid var(--border);
}
.bottom-bar .status { flex: 1; font-size: 13px; color: var(--text-muted); }

/* ── PRINT ── */
@media print {
  .topbar, .topbar-right, .no-print { display: none !important; }
  body { background: #fff; }
  .ticket-body { display: block !important; }
  .chevron { display: none; }
  .ticket { break-inside: avoid; }
}
</style>
</head>
<body>

<header class="topbar">
  <span class="logo">widi<span class="logo-dot">.</span></span>
  <span class="topbar-divider"></span>
  <span class="topbar-title">Ticket-Prüfung</span>
  <div class="topbar-right">
    <span id="topbar-badge"></span>
  </div>
</header>

<main class="page">

  <!-- UPLOAD -->
  <div id="view-upload">
    <div class="upload-card">
      <h2>Auftragsscheine prüfen</h2>
      <p>PDF hochladen – Arbeitszeiten und Mitarbeiter werden automatisch geprüft.</p>
      <div class="drop-zone" id="drop-zone" onclick="document.getElementById('file-in').click()">
        <div class="drop-icon">📋</div>
        <p><strong>PDF hier ablegen</strong> oder klicken zum Auswählen</p>
        <small>Auftragsscheine · Arbeitsaufträge · KW-Sammlungen</small>
      </div>
      <input type="file" id="file-in" accept="application/pdf" style="display:none">
      <div class="upload-or"><span>oder</span></div>
      <button class="btn btn-sm" onclick="loadDemo()">Demo mit Beispieldaten testen</button>
    </div>
  </div>

  <!-- ANALYZING -->
  <div id="view-analyzing">
    <div class="analyzing-card">
      <div class="spinner"></div>
      <h3 id="a-title">PDF wird analysiert…</h3>
      <p id="a-msg">Tickets werden extrahiert und geprüft</p>
      <div class="progress-bar"><div class="progress-fill" id="a-progress" style="width:8%"></div></div>
    </div>
  </div>

  <!-- RESULTS -->
  <div id="view-results">
    <div class="stats-row" id="stats-row"></div>
    <div class="results-toolbar">
      <h3>Tickets</h3>
      <div class="toolbar-actions no-print">
        <button class="btn btn-sm" onclick="window.print()">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="6 9 6 2 18 2 18 9"/><path d="M6 18H4a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2"/><rect x="6" y="14" width="12" height="8"/></svg>
          Drucken
        </button>
        <button class="btn btn-sm" onclick="resetAll()">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="1 4 1 10 7 10"/><path d="M3.51 15a9 9 0 1 0 .49-4.87"/></svg>
          Neue PDF
        </button>
      </div>
    </div>
    <div id="ticket-list"></div>
    <div class="bottom-bar no-print">
      <span class="status" id="bottom-status"></span>
      <button class="btn btn-primary" onclick="window.print()">Prüfbericht drucken</button>
    </div>
  </div>

</main>

<script>
let tickets = [];

// ── DRAG & DROP ──────────────────────────────────────
const dz = document.getElementById('drop-zone');
const fi = document.getElementById('file-in');
dz.addEventListener('dragover',  e => { e.preventDefault(); dz.classList.add('drag'); });
dz.addEventListener('dragleave', ()  => dz.classList.remove('drag'));
dz.addEventListener('drop', e => {
  e.preventDefault(); dz.classList.remove('drag');
  handleFile(e.dataTransfer.files[0]);
});
fi.addEventListener('change', e => handleFile(e.target.files[0]));

function handleFile(file) {
  if (!file || file.type !== 'application/pdf') { alert('Bitte eine PDF-Datei auswählen.'); return; }
  const reader = new FileReader();
  reader.onload = e => analyzeWithClaude(e.target.result.split(',')[1]);
  reader.readAsDataURL(file);
}

// ── VIEW SWITCHING ───────────────────────────────────
function show(id) {
  ['view-upload', 'view-analyzing', 'view-results'].forEach(v =>
    document.getElementById(v).style.display = (v === id) ? 'block' : 'none'
  );
}

// ── CLAUDE ANALYSIS ──────────────────────────────────
async function analyzeWithClaude(pdfBase64) {
  show('view-analyzing');
  const fill  = document.getElementById('a-progress');
  const title = document.getElementById('a-title');
  const msg   = document.getElementById('a-msg');

  const steps = [
    [20, 'Tickets werden extrahiert…',        'Seiten werden gelesen'],
    [40, 'Arbeitszeiten werden berechnet…',   'Start- und Endzeiten vergleichen'],
    [60, 'Mitarbeiter werden abgeglichen…',   'Bemerkungen auf Zusatzmitarbeiter prüfen'],
    [80, 'Fehler werden klassifiziert…',      'Abweichungen werden markiert'],
    [92, 'Fast fertig…',                      'Ergebnis wird aufbereitet'],
  ];
  let si = 0;
  const iv = setInterval(() => {
    if (si < steps.length) {
      fill.style.width  = steps[si][0] + '%';
      title.textContent = steps[si][1];
      msg.textContent   = steps[si][2];
      si++;
    }
  }, 1800);

  const SYSTEM = `Du bist ein Prüfsystem für Arbeitsaufträge von WIDI Hellersen GmbH.
Analysiere das PDF und extrahiere ALLE Tickets/Auftragsscheine.

Prüfe zwei Fehlertypen:

1. ZEITFEHLER
   - Berechne Endzeit − Startzeit für jede Zeile.
   - Wenn Endzeit < Startzeit (ohne klaren Nachtschicht-Kontext) → Fehler.
   - Wenn berechnete Dauer ≥ 5 Minuten von angegebener Dauer abweicht → Fehler.

2. MITARBEITERFEHLER
   - Wenn in der Bemerkung ein weiterer Mitarbeiter genannt wird (z.B. "Weiterer Mitarbeiter: W. Dwining"), der NICHT im Ticket-Kopf als Mitarbeiter steht → Fehler.

Antworte NUR mit einem JSON-Array. Kein Text, keine Backticks.

Schema pro Ticket:
{
  "ticketNr": "A26-08200",
  "mitarbeiter": "Timur van der Werf",
  "datum": "08.05.2026",
  "auftrag": "Kurzbeschreibung max 80 Zeichen",
  "bemerkung": "Volltext oder null",
  "gesamtstunden": "24:30",
  "arbeitszeiten": [
    {
      "eintrag": "07.05.2026 10:12 - 11:02 Uhr (00:49 Std.)",
      "angegeben": "00:49",
      "berechnet": "00:50",
      "ok": true,
      "problem": null
    }
  ],
  "fehler": ["Beschreibung…"],
  "hat_fehler": true
}

Wenn keine Fehler: fehler = [], hat_fehler = false.`;

  try {
    const resp = await fetch('/api/analyze', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        model: 'claude-sonnet-4-20250514',
        max_tokens: 4096,
        system: SYSTEM,
        messages: [{
          role: 'user',
          content: [
            { type: 'document', source: { type: 'base64', media_type: 'application/pdf', data: pdfBase64 } },
            { type: 'text', text: 'Analysiere alle Tickets und gib das JSON zurück.' }
          ]
        }]
      })
    });

    clearInterval(iv);
    fill.style.width = '100%';

    if (!resp.ok) {
      const err = await resp.json().catch(() => ({}));
      throw new Error(err.error?.message || `Server-Fehler ${resp.status}`);
    }

    const data = await resp.json();
    const raw  = (data.content || []).filter(b => b.type === 'text').map(b => b.text).join('');
    const json = raw.replace(/```json|```/g, '').trim();
    const parsed = JSON.parse(json);

    tickets = parsed.map((t, i) => ({
      ...t, id: i, correctionText: '', userFixed: false, userConfirmed: false
    }));

    setTimeout(() => { show('view-results'); renderAll(); }, 300);

  } catch (err) {
    clearInterval(iv);
    show('view-upload');
    alert('Fehler bei der Analyse:\n' + err.message);
  }
}

// ── DEMO DATA ────────────────────────────────────────
function loadDemo() {
  tickets = [
    {
      id: 0, ticketNr: 'A26-08200', mitarbeiter: 'Timur van der Werf / Kalovljevic',
      datum: '07.–08.05.2026',
      auftrag: 'Fernseher und Wandhalterungen in Gästezimmern montieren',
      bemerkung: 'Begutachtet, 10m Verlängerungskabel von Bachmann. Fernseher und Wandhalterungen bei IT abgeholt und angebracht.',
      gesamtstunden: '24:30',
      arbeitszeiten: [
        { eintrag: '07.05.2026 10:12 - 11:02 Uhr (00:49 Std.)', angegeben: '00:49', berechnet: '00:50', ok: true, problem: null },
        { eintrag: '07.05.2026 13:24 - 06:28 Uhr (17:03 Std.)', angegeben: '17:03', berechnet: '17:04', ok: false, problem: 'Endzeit 06:28 liegt vor Startzeit 13:24 – möglicher Tippfehler' },
        { eintrag: '08.05.2026 07:24 - 14:02 Uhr (06:38 Std.)', angegeben: '06:38', berechnet: '06:38', ok: true, problem: null }
      ],
      fehler: ['Zeile 2: Endzeit 06:28 liegt vor Startzeit 13:24 – möglicher Tippfehler (evtl. 17:03 Uhr gemeint)'],
      hat_fehler: true, correctionText: '', userFixed: false, userConfirmed: false
    },
    {
      id: 1, ticketNr: 'A26-08853', mitarbeiter: 'Timur van der Werf / Aksoy',
      datum: '11.05.2026',
      auftrag: 'Diverse Möbelstücke entsorgen (Kastenwagen)',
      bemerkung: 'Weiterer Mitarbeiter: W. Dwining\nMüll eingeladen.',
      gesamtstunden: '01:00',
      arbeitszeiten: [
        { eintrag: '11.05.2026 06:13 - 07:13 Uhr (01:00 Std.)', angegeben: '01:00', berechnet: '01:00', ok: true, problem: null }
      ],
      fehler: ['Mitarbeiter W. Dwining in Bemerkung erwähnt, aber nicht im Ticket-Kopf eingetragen'],
      hat_fehler: true, correctionText: '', userFixed: false, userConfirmed: false
    },
    {
      id: 2, ticketNr: '10707 (#10498)', mitarbeiter: 'Stefan Giesmann / Kalovljevic',
      datum: '08.05.2026',
      auftrag: 'Haustechnik Instandhaltung – Split aus Ticket 10498',
      bemerkung: 'Auftrag nach Wunsch ausgeführt. Details siehe Haupt-Ticket.',
      gesamtstunden: '06:45',
      arbeitszeiten: [
        { eintrag: '08.05.2026 07:24 - 14:10 Uhr (06:45 Std.)', angegeben: '06:45', berechnet: '06:46', ok: true, problem: null }
      ],
      fehler: [],
      hat_fehler: false, correctionText: '', userFixed: false, userConfirmed: false
    }
  ];
  show('view-results');
  renderAll();
}

// ── RENDER ───────────────────────────────────────────
function renderAll() {
  renderStats();
  renderTickets();
  renderBottomStatus();
}

function renderStats() {
  const total = tickets.length;
  const ok    = tickets.filter(t => !t.hat_fehler || t.userConfirmed).length;
  const err   = tickets.filter(t => t.hat_fehler  && !t.userConfirmed).length;
  const fix   = tickets.filter(t => t.userFixed).length;

  document.getElementById('stats-row').innerHTML = `
    <div class="stat"><div class="n n-total">${total}</div><div class="l">Gesamt</div></div>
    <div class="stat"><div class="n n-ok">${ok}</div><div class="l">In Ordnung</div></div>
    <div class="stat"><div class="n n-err">${err}</div><div class="l">Fehlerhaft</div></div>
    <div class="stat"><div class="n n-fix">${fix}</div><div class="l">Korrigiert</div></div>
  `;

  const badge = document.getElementById('topbar-badge');
  if (err > 0) {
    badge.textContent = `${err} offen`;
    badge.style.display = 'inline-block';
  } else {
    badge.style.display = 'none';
  }
}

function renderBottomStatus() {
  const open = tickets.filter(t => t.hat_fehler && !t.userConfirmed && !t.userFixed).length;
  document.getElementById('bottom-status').textContent = open > 0
    ? `${open} Ticket${open > 1 ? 's' : ''} noch offen`
    : '✓ Alle Tickets geprüft';
}

function renderTickets() {
  const list = document.getElementById('ticket-list');
  list.innerHTML = '';

  tickets.forEach(t => {
    const isOk   = !t.hat_fehler || t.userConfirmed;
    const cls    = isOk ? 't-ok' : t.userFixed ? 't-fixed' : 't-error';
    const bCls   = isOk ? 'badge-ok' : t.userFixed ? 'badge-fix' : 'badge-err';
    const bTxt   = isOk ? '✓ In Ordnung' : t.userFixed ? '✎ Korrigiert' : '✗ Fehler';

    // Arbeitszeiten
    const zeitenHtml = (t.arbeitszeiten || []).map(z => `
      <div class="time-row ${z.ok ? 'ok' : 'err'}">
        <span class="tr-entry">${z.eintrag}</span>
        <span class="tr-note">${z.ok ? '✓ korrekt' : '⚠ ' + (z.problem || 'Abweichung')}</span>
      </div>`).join('');

    // Fehlerblock
    const errHtml = (t.hat_fehler && t.fehler?.length && !t.userConfirmed) ? `
      <div class="error-block">
        <div class="error-block-title">Erkannte Probleme</div>
        <ul>${t.fehler.map(f => `<li>${f}</li>`).join('')}</ul>
      </div>` : '';

    // Korrekturfeld
    const corrHtml = (t.hat_fehler && !t.userConfirmed && !t.userFixed) ? `
      <div class="correction-wrap">
        <label>Korrektur / Notiz eintragen:</label>
        <textarea id="corr-${t.id}" placeholder="z.B. Mitarbeiter W. Dwining wurde nachträglich eingetragen. Korrekte Endzeit: 17:03 Uhr.">${t.correctionText}</textarea>
      </div>
      <div class="ticket-actions">
        <button class="btn btn-danger btn-sm" onclick="saveCorr(${t.id})">Korrektur speichern</button>
        <button class="btn btn-sm" onclick="markOk(${t.id})">Als korrekt abhaken</button>
      </div>` : '';

    // Gespeicherte Korrektur
    const fixHtml = (t.userFixed && t.correctionText) ? `
      <div class="fixed-block">
        <div class="fixed-block-title">Eingetragene Korrektur</div>
        <div class="fixed-block-text">${t.correctionText.replace(/\n/g, '<br>')}</div>
        <div class="fixed-block-actions">
          <button class="btn btn-sm" onclick="editCorr(${t.id})">Ändern</button>
        </div>
      </div>` : '';

    const div = document.createElement('div');
    div.className = `ticket ${cls}`;
    div.id = `ticket-${t.id}`;
    div.innerHTML = `
      <div class="ticket-header" onclick="toggle(${t.id})">
        <span class="t-nr">${t.ticketNr || '—'}</span>
        <div class="t-meta">
          <div class="t-name">${t.mitarbeiter || '—'}</div>
          <div class="t-sub">${t.datum || '—'}${t.auftrag ? ' · ' + t.auftrag : ''}</div>
        </div>
        <span class="badge ${bCls}">${bTxt}</span>
        <span class="chevron" id="chev-${t.id}">▾</span>
      </div>
      <div class="ticket-body" id="body-${t.id}">
        <div class="info-grid">
          <div class="info-cell"><div class="ic-label">Mitarbeiter</div><div class="ic-val">${t.mitarbeiter || '—'}</div></div>
          <div class="info-cell"><div class="ic-label">Datum</div><div class="ic-val">${t.datum || '—'}</div></div>
          <div class="info-cell"><div class="ic-label">Gesamtstunden</div><div class="ic-val">${t.gesamtstunden || '—'}</div></div>
        </div>
        ${t.bemerkung ? `<div class="section-label">Bemerkung</div><div class="remark">${t.bemerkung.replace(/\n/g,'<br>')}</div>` : ''}
        ${t.arbeitszeiten?.length ? `<div class="section-label">Arbeitszeiten</div><div class="times">${zeitenHtml}</div>` : ''}
        ${errHtml}
        ${fixHtml}
        ${corrHtml}
      </div>`;
    list.appendChild(div);

    // Fehlerhafte Tickets automatisch aufklappen
    if (t.hat_fehler && !t.userConfirmed && !t.userFixed) toggle(t.id);
  });
}

// ── ACTIONS ──────────────────────────────────────────
function toggle(id) {
  const body = document.getElementById(`body-${id}`);
  const chev = document.getElementById(`chev-${id}`);
  const open = body.classList.toggle('open');
  chev.classList.toggle('open', open);
}

function saveCorr(id) {
  const el = document.getElementById(`corr-${id}`);
  const text = el?.value.trim();
  if (!text) { alert('Bitte eine Korrektur eingeben.'); return; }
  tickets[id].correctionText = text;
  tickets[id].userFixed = true;
  renderAll();
}

function editCorr(id) {
  tickets[id].userFixed = false;
  renderAll();
  setTimeout(() => document.getElementById(`corr-${id}`)?.focus(), 50);
}

function markOk(id) {
  tickets[id].userConfirmed = true;
  renderAll();
}

function resetAll() {
  tickets = [];
  document.getElementById('file-in').value = '';
  document.getElementById('topbar-badge').style.display = 'none';
  show('view-upload');
}
</script>
</body>
</html>
