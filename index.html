<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Beetle KI – Majestic RP Regelwerk</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@2.44.0/tabler-icons.min.css" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg:      #0d1117;
      --bg2:     #161b27;
      --bg3:     #1e2535;
      --bg4:     #252d42;
      --border:  rgba(255,255,255,0.07);
      --border2: rgba(255,255,255,0.13);
      --text:    #e2e8f0;
      --text2:   #8892aa;
      --text3:   #55607a;
      --green:   #1D9E75;
      --green-d: #15795a;
      --accent:  #3b82f6;
      --red:     #e24b4a;
      --amber:   #f59e0b;
      --radius:  14px;
      --radius-sm: 8px;
    }

    body {
      font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    /* ── HEADER ── */
    header {
      background: var(--bg2);
      border-bottom: 1px solid var(--border);
      padding: 0 24px;
      height: 64px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(12px);
    }
    .header-left { display: flex; align-items: center; gap: 12px; }
    .beetle-logo {
      width: 38px; height: 38px;
      border-radius: 10px;
      background: linear-gradient(135deg, var(--green), #0d7a57);
      display: flex; align-items: center; justify-content: center;
      box-shadow: 0 0 18px rgba(29,158,117,0.35);
    }
    .beetle-logo i { font-size: 20px; color: #fff; }
    .header-title { font-size: 17px; font-weight: 600; color: var(--text); }
    .header-sub   { font-size: 12px; color: var(--text2); margin-top: 1px; }
    .header-badge {
      font-size: 11px; padding: 3px 10px;
      background: rgba(29,158,117,0.15);
      color: var(--green);
      border: 1px solid rgba(29,158,117,0.3);
      border-radius: 20px;
    }

    /* ── LAYOUT ── */
    .layout {
      display: flex;
      flex: 1;
      height: calc(100vh - 64px);
      overflow: hidden;
    }

    /* ── SIDEBAR ── */
    .sidebar {
      width: 260px;
      flex-shrink: 0;
      background: var(--bg2);
      border-right: 1px solid var(--border);
      display: flex;
      flex-direction: column;
      overflow-y: auto;
      padding: 16px 12px;
    }
    .sidebar-label {
      font-size: 10px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: .08em;
      color: var(--text3);
      padding: 0 8px;
      margin-bottom: 8px;
    }
    .sidebar-btn {
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 9px 10px;
      border-radius: var(--radius-sm);
      border: none;
      background: transparent;
      color: var(--text2);
      font-size: 13px;
      cursor: pointer;
      width: 100%;
      text-align: left;
      transition: background .15s, color .15s;
      margin-bottom: 2px;
    }
    .sidebar-btn:hover { background: var(--bg3); color: var(--text); }
    .sidebar-btn.active { background: rgba(29,158,117,0.12); color: var(--green); }
    .sidebar-btn i { font-size: 16px; flex-shrink: 0; width: 18px; text-align: center; }
    .sidebar-divider {
      border: none;
      border-top: 1px solid var(--border);
      margin: 12px 0;
    }
    .sidebar-section { margin-bottom: 4px; }

    /* ── CHAT AREA ── */
    .chat-area {
      flex: 1;
      display: flex;
      flex-direction: column;
      overflow: hidden;
    }

    #chat-box {
      flex: 1;
      overflow-y: auto;
      padding: 28px 0;
      display: flex;
      flex-direction: column;
      gap: 0;
    }
    #chat-box::-webkit-scrollbar { width: 6px; }
    #chat-box::-webkit-scrollbar-thumb { background: var(--bg4); border-radius: 3px; }

    .msg-row {
      display: flex;
      gap: 14px;
      padding: 12px 32px;
      transition: background .1s;
    }
    .msg-row:hover { background: rgba(255,255,255,0.015); }
    .msg-row.user-row { flex-direction: row-reverse; }

    .avatar {
      width: 32px; height: 32px;
      border-radius: 8px;
      flex-shrink: 0;
      display: flex; align-items: center; justify-content: center;
      font-size: 15px;
      margin-top: 2px;
    }
    .avatar.bot-av { background: linear-gradient(135deg, var(--green), #0d7a57); color: #fff; }
    .avatar.user-av { background: var(--bg4); color: var(--text2); }

    .bubble {
      max-width: 72%;
      padding: 12px 16px;
      border-radius: var(--radius);
      font-size: 14px;
      line-height: 1.7;
      white-space: pre-wrap;
    }
    .bubble.bot-bub {
      background: var(--bg2);
      border: 1px solid var(--border);
      color: var(--text);
      border-radius: 4px var(--radius) var(--radius) var(--radius);
    }
    .bubble.user-bub {
      background: var(--green);
      color: #fff;
      border-radius: var(--radius) 4px var(--radius) var(--radius);
    }
    .bubble strong { font-weight: 600; }
    .bubble .tag {
      display: inline-block;
      font-size: 11px;
      padding: 2px 8px;
      border-radius: 20px;
      font-weight: 600;
      margin-bottom: 6px;
    }
    .tag-red    { background: rgba(226,75,74,0.15); color: var(--red); border: 1px solid rgba(226,75,74,0.25); }
    .tag-amber  { background: rgba(245,158,11,0.15); color: var(--amber); border: 1px solid rgba(245,158,11,0.25); }
    .tag-green  { background: rgba(29,158,117,0.15); color: var(--green); border: 1px solid rgba(29,158,117,0.25); }

    .empty-state {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 12px;
      padding: 40px;
      text-align: center;
    }
    .empty-icon {
      width: 64px; height: 64px;
      border-radius: 16px;
      background: rgba(29,158,117,0.1);
      border: 1px solid rgba(29,158,117,0.2);
      display: flex; align-items: center; justify-content: center;
      margin-bottom: 4px;
    }
    .empty-icon i { font-size: 30px; color: var(--green); }
    .empty-state h2 { font-size: 18px; font-weight: 600; }
    .empty-state p  { font-size: 14px; color: var(--text2); max-width: 380px; line-height: 1.6; }

    .chip-row {
      display: flex; flex-wrap: wrap; gap: 8px;
      justify-content: center;
      margin-top: 16px;
    }
    .chip {
      padding: 7px 14px;
      border-radius: 20px;
      border: 1px solid var(--border2);
      background: var(--bg2);
      color: var(--text2);
      font-size: 13px;
      cursor: pointer;
      transition: all .15s;
    }
    .chip:hover { border-color: var(--green); color: var(--green); background: rgba(29,158,117,0.07); }

    /* ── INPUT BAR ── */
    .input-bar {
      border-top: 1px solid var(--border);
      background: var(--bg2);
      padding: 16px 24px;
    }
    .input-wrap {
      display: flex;
      gap: 10px;
      align-items: flex-end;
      max-width: 900px;
      margin: 0 auto;
    }
    textarea#msg-input {
      flex: 1;
      background: var(--bg3);
      border: 1px solid var(--border2);
      border-radius: var(--radius-sm);
      color: var(--text);
      font-size: 14px;
      font-family: inherit;
      padding: 11px 14px;
      resize: none;
      line-height: 1.5;
      max-height: 120px;
      transition: border-color .15s;
    }
    textarea#msg-input::placeholder { color: var(--text3); }
    textarea#msg-input:focus { outline: none; border-color: var(--green); }

    .send-btn {
      height: 44px; width: 44px;
      border-radius: var(--radius-sm);
      background: var(--green);
      border: none;
      cursor: pointer;
      display: flex; align-items: center; justify-content: center;
      flex-shrink: 0;
      transition: background .15s, transform .1s;
    }
    .send-btn:hover { background: var(--green-d); }
    .send-btn:active { transform: scale(0.95); }
    .send-btn i { font-size: 18px; color: #fff; }

    .input-hint {
      text-align: center;
      font-size: 11px;
      color: var(--text3);
      margin-top: 8px;
    }

    /* ── SCROLLBAR ── */
    .sidebar::-webkit-scrollbar { width: 4px; }
    .sidebar::-webkit-scrollbar-thumb { background: var(--bg4); border-radius: 2px; }

    /* ── RESPONSIVE ── */
    @media (max-width: 680px) {
      .sidebar { display: none; }
      .msg-row { padding: 10px 16px; }
      .bubble { max-width: 90%; }
      header { padding: 0 16px; }
    }
  </style>
</head>
<body>

<!-- HEADER -->
<header>
  <div class="header-left">
    <div class="beetle-logo"><i class="ti ti-bug"></i></div>
    <div>
      <div class="header-title">Beetle KI</div>
      <div class="header-sub">Majestic RP · Regelwerk-Assistent</div>
    </div>
  </div>
  <div class="header-badge">Stand: 08.05.2026</div>
</header>

<!-- LAYOUT -->
<div class="layout">

  <!-- SIDEBAR -->
  <nav class="sidebar" aria-label="Regelkategorien">
    <div class="sidebar-label">Kategorien</div>

    <div class="sidebar-section">
      <button class="sidebar-btn" onclick="askQ('Was ist RDM?')"><i class="ti ti-skull"></i> RDM</button>
      <button class="sidebar-btn" onclick="askQ('Was ist VDM?')"><i class="ti ti-car-crash"></i> VDM</button>
      <button class="sidebar-btn" onclick="askQ('Was ist NLR?')"><i class="ti ti-heartbeat"></i> NLR</button>
      <button class="sidebar-btn" onclick="askQ('Was ist Power Gaming?')"><i class="ti ti-bolt"></i> Power Gaming</button>
      <button class="sidebar-btn" onclick="askQ('Was ist Meta Gaming?')"><i class="ti ti-wifi"></i> Meta Gaming</button>
      <button class="sidebar-btn" onclick="askQ('Was ist Combat Logging?')"><i class="ti ti-plug-off"></i> Combat Logging</button>
    </div>

    <hr class="sidebar-divider" />
    <div class="sidebar-label">Orte & Zonen</div>

    <div class="sidebar-section">
      <button class="sidebar-btn" onclick="askQ('Was sind die Greenzone-Regeln?')"><i class="ti ti-map-pin"></i> Greenzones</button>
      <button class="sidebar-btn" onclick="askQ('Was ist die rote Zone im Ghetto?')"><i class="ti ti-alert-triangle"></i> Rote Zone</button>
      <button class="sidebar-btn" onclick="askQ('Regeln für Fort Zancudo?')"><i class="ti ti-building-fortress"></i> Fort Zancudo</button>
      <button class="sidebar-btn" onclick="askQ('Regeln für Cayo Perico?')"><i class="ti ti-island"></i> Cayo Perico</button>
    </div>

    <hr class="sidebar-divider" />
    <div class="sidebar-label">Aktivitäten</div>

    <div class="sidebar-section">
      <button class="sidebar-btn" onclick="askQ('Regeln für Bankraub und Ladenraub?')"><i class="ti ti-building-bank"></i> Bank- & Ladenraub</button>
      <button class="sidebar-btn" onclick="askQ('Regeln für Geiselnahme?')"><i class="ti ti-user-exclamation"></i> Geiselnahme</button>
      <button class="sidebar-btn" onclick="askQ('Regeln für Ausrauben?')"><i class="ti ti-spy"></i> Ausrauben</button>
      <button class="sidebar-btn" onclick="askQ('Wann findet der AirDrop statt?')"><i class="ti ti-parachute"></i> AirDrop</button>
      <button class="sidebar-btn" onclick="askQ('Regeln für Gang Turf?')"><i class="ti ti-flag"></i> Gang Turf</button>
    </div>

    <hr class="sidebar-divider" />
    <div class="sidebar-label">Fraktionen</div>

    <div class="sidebar-section">
      <button class="sidebar-btn" onclick="askQ('Regeln für staatliche Fraktionen?')"><i class="ti ti-badge"></i> Staatliche Fraktionen</button>
      <button class="sidebar-btn" onclick="askQ('Was sind die Leader-Regeln?')"><i class="ti ti-crown"></i> Leader-Regeln</button>
      <button class="sidebar-btn" onclick="askQ('Kriminelle Organisations-Regeln?')"><i class="ti ti-shield-off"></i> Kriminelle Orgs</button>
    </div>

    <hr class="sidebar-divider" />
    <div class="sidebar-label">Sonstiges</div>

    <div class="sidebar-section">
      <button class="sidebar-btn" onclick="askQ('Was sind die Account-Regeln?')"><i class="ti ti-user-circle"></i> Account-Regeln</button>
      <button class="sidebar-btn" onclick="askQ('Was passiert wenn man cheatet?')"><i class="ti ti-ban"></i> Cheats & Bans</button>
    </div>
  </nav>

  <!-- CHAT AREA -->
  <main class="chat-area">
    <div id="chat-box">
      <div class="empty-state" id="empty">
        <div class="empty-icon"><i class="ti ti-bug"></i></div>
        <h2>Beetle KI</h2>
        <p>Dein Regelwerk-Assistent für Majestic RP. Stelle eine Frage oder wähle eine Kategorie aus der linken Seitenleiste.</p>
        <div class="chip-row">
          <button class="chip" onclick="askQ('Darf ich jemanden ohne Grund erschießen?')">Jemanden erschießen?</button>
          <button class="chip" onclick="askQ('Was passiert nach dem Tod?')">Nach dem Tod?</button>
          <button class="chip" onclick="askQ('Darf ich in der Greenzone kämpfen?')">Greenzone kämpfen?</button>
          <button class="chip" onclick="askQ('Wie viele Geiseln beim Bankraub?')">Geiseln beim Bankraub?</button>
          <button class="chip" onclick="askQ('Wie lange darf man jemanden inhaftieren?')">Maximale Haftzeit?</button>
          <button class="chip" onclick="askQ('Was darf ein Cop nicht tun?')">Cop-Verbote?</button>
        </div>
      </div>
    </div>

    <div class="input-bar">
      <div class="input-wrap">
        <textarea id="msg-input" rows="1" placeholder="Frage zum Regelwerk stellen…" aria-label="Frage eingeben"></textarea>
        <button class="send-btn" onclick="handleSend()" aria-label="Frage absenden">
          <i class="ti ti-send"></i>
        </button>
      </div>
      <p class="input-hint">Beetle KI · Majestic RP Regelwerk Stand 08.05.2026 · Keine Daten werden gespeichert</p>
    </div>
  </main>
</div>

<script>
const RULES = [
  {
    keys: ['rdm','erschießen','töten','angreifen','grund','random','deathmatch','schießen ohne','anschießen'],
    title: 'RDM',
    tag: 'red',
    answer: `<span class="tag tag-red">RDM – Random Deathmatch</span>\n\n<strong>Nein</strong>, das wäre RDM und ist verboten.\n\n<strong>Regel:</strong> Angreifen, Verwunden oder Töten von Spielern ohne IC-Grund oder vorangehenden Dialog ist verboten.\n\n<strong>Strafe:</strong> Waffensperre 5 Stunden / Konto Ban 3–7 Tage\n\n<strong>Ausnahmen – kein Dialog nötig bei:</strong>\n• Bedrohung des eigenen Lebens (Waffe gerichtet, geschlagen, gerammt)\n• Grobe Beleidigung (Familie / Nation / Ethnie)\n• Diebstahl des eigenen Fahrzeugs\n• Geschäftsraub (Beteiligte dürfen getötet werden, nicht vorbeigehende Arbeiter)\n• Verstecken in der Gefahrenzone oder auf Cayo Perico beim Stash\n\n<strong>Hinweis:</strong> Nach Wiederbelebung ist ein neuer Grund nötig. Ausnahme: Selbstwiederbelebungskit.`
  },
  {
    keys: ['vdm','fahrzeug rammen','auto rammen','überfahren','vehicle deathmatch','rammen'],
    title: 'VDM',
    tag: 'red',
    answer: `<span class="tag tag-red">VDM – Vehicle Deathmatch</span>\n\n<strong>Nein</strong>, das wäre VDM und ist verboten.\n\n<strong>Regel:</strong> Spieler mit Fahrzeugen absichtlich angreifen, verletzen oder töten ohne wichtigen IC-Grund ist verboten.\n\n<strong>Strafe:</strong> Jail 40–90 Minuten / Ban 3–7 Tage\n\n<strong>Ausnahme:</strong> Pitten (Fahrzeug aus der Bahn drängen) während einer Verfolgungsjagd ist erlaubt.`
  },
  {
    keys: ['nlr','new life','nach dem tod','rache tod','krankenhaus','sterben','tod','wiederbelebung','location zurück','ort zurück'],
    title: 'NLR',
    tag: 'amber',
    answer: `<span class="tag tag-amber">NLR – New Life Rule</span>\n\n<strong>Regel:</strong> Nach dem Tod im Krankenhaus vergisst dein Charakter alle Ereignisse, die zu seinem Tod geführt haben. Rache-Aktionen nach Wiederbelebung sind verboten.\n\n<strong>Strafe:</strong> Jail 30–90 Minuten / WARN / Ban 3–30 Tage\n\n<strong>Hinweis:</strong> Rückkehr zum Todesort ist erst nach <strong>10 Minuten</strong> erlaubt.`
  },
  {
    keys: ['pg','power gaming','powergaming','aufzwingen','unrealistisch','keine angst','waffe angst','1vs3','2vs5','provozieren bande'],
    title: 'PG',
    tag: 'amber',
    answer: `<span class="tag tag-amber">PG – Power Gaming</span>\n\n<strong>Regel:</strong> Anderen RP aufzwingen ohne faire Chance, unrealistische Aktionen durchführen oder keine Angst vor Waffen/Gefahren zeigen ist verboten.\n\n<strong>Verhältnis-Regel:</strong>\n• 1vs1, 1vs2, 2vs4 = <strong>kein PG</strong>\n• 1vs3 = <strong>PG</strong>\n• 2vs5 = <strong>PG</strong>\n\n<strong>Strafe:</strong> Jail 30–60 Minuten / WARN / Ban 3–30 Tage`
  },
  {
    keys: ['mg','meta gaming','metagaming','discord information','extern','außerhalb spielen','info außerhalb'],
    title: 'MG',
    tag: 'amber',
    answer: `<span class="tag tag-amber">MG – Meta Gaming</span>\n\n<strong>Regel:</strong> Es ist verboten, Ingame-Situationen mit Informationen zu nutzen, die außerhalb des Spiels erhalten wurden (z. B. Discord während des Spiels). Ingame- und externe Kommunikation müssen strikt getrennt bleiben.\n\n<strong>Strafe:</strong> Jail 60 Minuten`
  },
  {
    keys: ['cl','combat log','ausloggen','verlassen spiel','afk rp','disconnect','raus während'],
    title: 'CL',
    tag: 'red',
    answer: `<span class="tag tag-red">CL – Combat Logging</span>\n\n<strong>Regel:</strong> Das Verlassen des Spiels oder AFK-Bleiben während eines aktiven RP-Prozesses ist verboten. Auch in Wasser oder Interieur flüchten während einer Verfolgung ist verboten.\n\n<strong>Strafe:</strong> Ban 4–8 Tage / Konto Ban 4 Tage`
  },
  {
    keys: ['tk','teamkill','eigene töten','fraktion töten','verbündete töten','mitglieder töten'],
    title: 'TK',
    tag: 'red',
    answer: `<span class="tag tag-red">TK – Teamkill</span>\n\n<strong>Regel:</strong> Absichtliches Töten von Mitgliedern der eigenen Fraktion oder Familie ist verboten.\n\n<strong>Strafe:</strong> Waffensperre 5 Stunden / Jail 50–100 Minuten / Konto Ban 3–7 Tage\n\n<strong>Ausnahme:</strong> Selbstverteidigung`
  },
  {
    keys: ['baiting','provoz','absichtlich nervig','reizen','reaktion provoz'],
    title: 'Baiting',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Baiting</span>\n\n<strong>Regel:</strong> Absichtlich nervig oder irritierend sein, um eine Reaktion von anderen Spielern zu provozieren, ist verboten.\n\n<strong>Strafe:</strong> Jail 20–60 Minuten / Ban 3–7 Tage / Konto Ban 15 Tage`
  },
  {
    keys: ['sk','spawn kill','spawnkill','hq töten','hauptquartier töten'],
    title: 'SK',
    tag: 'red',
    answer: `<span class="tag tag-red">SK – Spawn Kill</span>\n\n<strong>Regel:</strong> Einen Spieler auf dem HQ seiner eigenen Fraktion töten ist verboten.\n\n<strong>Strafe:</strong> WARN / Ban 3–7 Tage`
  },
  {
    keys: ['nrp','unrealistisch fahren','gegenfahrbahn','gebäude fahrzeug','nicht rp fahren'],
    title: 'NRP',
    tag: 'amber',
    answer: `<span class="tag tag-amber">NRP – Non-RP Fahren</span>\n\n<strong>Regel:</strong> Unrealistisches Fahren oder Fliegen das der RP-Logik widerspricht ist verboten.\n\n<strong>Beispiele:</strong>\n• Gebäude mit Fahrzeug betreten\n• Gegenfahrbahn über 750 m oder 15 Sekunden\n• Tiefes schnelles Fliegen am Boden\n• Landen auf ungeeigneten Flächen\n\n<strong>Strafe:</strong> Jail 30–90 Minuten / WARN / Ban 3–30 Tage`
  },
  {
    keys: ['greenzone','grüne zone','green zone','tankstelle','bank greenzone','friseur','lsc','casino','krankenhaus','schutzzone'],
    title: 'Greenzone',
    tag: 'green',
    answer: `<span class="tag tag-green">Greenzone – Schutzbereich</span>\n\nIn Greenzones sind <strong>alle kriminellen Aktivitäten verboten</strong>:\n• Keine Schusswaffen (außer Staatsbedienstete/Selbstverteidigung)\n• Keine Entführungen oder Raubüberfälle\n• Kein Flüchten vor Verfolgungen in die Greenzone\n\n<strong>Strafe:</strong> Jail 30–60 Minuten / Ban 3–7 Tage / WARN\n\n<strong>Greenzones sind u. a.:</strong> Rathaus, LSPD, EMS, Banken, Tankstellen, Friseure, LSC, Waffengeschäfte, Krankenhäuser, Geldautomaten, Casinos, Clubs, Angelplätze, Kirchen\n\n<strong>Hinweis:</strong> Würfelpark ist Greenzone von <strong>06:00–22:00 Uhr</strong>.`
  },
  {
    keys: ['rote zone','rot','ghetto','gefahr','ohne vorwarnung schießen'],
    title: 'Rote Zone',
    tag: 'red',
    answer: `<span class="tag tag-red">Rote Zone – Gefahrenbereich (Ghetto)</span>\n\nIn der roten Zone darf <strong>ohne Vorwarnung</strong> auf bewaffnete Personen geschossen werden – also auf Personen, die eine Waffe in der Hand oder auf dem Rücken tragen.\n\n<strong>Strafe bei Verstoß:</strong> RDM-Strafe`
  },
  {
    keys: ['maske','maskierung','vollmaske','bart','gesicht'],
    title: 'Maskierungspflicht',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Maskierungspflicht</span>\n\nAlle kriminellen Aktivitäten, die das staatliche Gesetz brechen, müssen mit <strong>Vollmaskierung</strong> durchgeführt werden.\n\n<strong>Strafe:</strong> Jail 35 Minuten\n\n<strong>Hinweis:</strong> Bart, Schnurrbart und andere Kleidungsstücke die das Gesicht nicht vollständig bedecken zählen <strong>nicht</strong> als Vollmaskierung.`
  },
  {
    keys: ['bankraub','bank','ladenraub','laden','überfall','uhrzeit raub','wann raub'],
    title: 'Bank- & Ladenraub',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Bank- & Ladenraub – Regeln</span>\n\n<strong>Uhrzeiten:</strong>\n• Ladenraub: 12:00 – 00:59 Uhr\n• Bankraub: 12:00 – 22:59 Uhr\n\n<strong>Wichtige Regeln:</strong>\n• Zugang/Ausgang darf nicht blockiert werden (Jail 35 Min)\n• Bankraub: mind. <strong>1 Geisel</strong> erforderlich (gilt nicht beim Ladenraub)\n• Splittergranaten verboten (Jail 60 Min)\n• Ladenraub: 2–35 Personen / Bankraub: mind. 4 Personen\n• Max. <strong>3 Geiseln</strong> erlaubt\n• Raub endet sobald Staat alle Forderungen erfüllt\n\n<strong>Für die Polizei:</strong> Mind. 3 Beamte zur Reaktion, kein Schussgefecht ohne Verhandlungen.`
  },
  {
    keys: ['geisel','geiseln','lösegeld','entführung','kidnap','geiselnahme'],
    title: 'Geiselnahme',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Geiselnahme – Regeln</span>\n\n• EMS (im Dienst) darf <strong>nicht</strong> entführt werden (Jail 35 Min)\n• Max. <strong>3 Geiselnahmen pro Tag</strong> pro Organisation\n• Pro Forderung muss eine Geisel freigelassen werden (Geld ausgenommen)\n\n<strong>Lösegelder – Maximum:</strong>\n• (Co-)Leader kriminelle Org: <strong>200.000 $</strong>\n• (Co-)Leader staatliche Org: <strong>400.000 $</strong>\n• Einfache Geisel: <strong>50.000 $</strong>\n\n<strong>Strafe bei Verstoß:</strong> Jail 35–60 Minuten / Verwarnung des Leaders`
  },
  {
    keys: ['ausrauben','berauben','g-taste','skript raub','weste klauen','opfer raub','mitarbeiter'],
    title: 'Ausrauben',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Ausrauben – Regeln</span>\n\n• Raub nur per <strong>Skript (G-Taste)</strong>, kein RP-Zwang (Jail 35–70 Min)\n• Kein Zwang zur Übergabe von Wohnungen, Fahrzeugen, Bankgeld oder Kleidung\n• Person darf nur <strong>einmal</strong> ausgeraubt werden (WARN)\n• Mind. <strong>doppelt so viele Räuber wie Opfer</strong> + 2 Autos um Fahrzeug zu stoppen\n• Max. <strong>5 Personen</strong> gleichzeitig ausrauben/entführen\n\n<strong>Mitarbeiter-Schutz:</strong> Postboten, LKW-Fahrer, Müllmänner, Elektriker, Feuerwehrleute und Busfahrer dürfen zwischen <strong>12:00–23:00 Uhr NICHT</strong> beraubt werden (Jail 35 Min)`
  },
  {
    keys: ['heilen','heilung','weste anlegen','rüstung','schussgefecht heilen','medkit gefecht','deckung heilen'],
    title: 'Heilung im Gefecht',
    tag: 'red',
    answer: `<span class="tag tag-red">Heilung während Schussgefecht</span>\n\n<strong>Verboten:</strong> Gegenstände zur Heilung oder Rüstungswiederherstellung während eines aktiven Schussgefechts benutzen.\n\n<strong>Ausnahme:</strong> Heilung, neue Weste anlegen oder Reanimation ist nur in <strong>vollständiger Deckung</strong> erlaubt.\n\n<strong>Strafe:</strong> Jail 30 Minuten\n\n<strong>Ebenfalls verboten:</strong> Gegenstände während eines Feuergefechts aufheben → Jail 30 Min / WARN`
  },
  {
    keys: ['airdrop','air drop','kiste','event zeiten','wann event'],
    title: 'AirDrop',
    tag: 'green',
    answer: `<span class="tag tag-green">AirDrop – Regeln</span>\n\n<strong>Uhrzeiten:</strong> 0, 3, 8, 12, 14, 16, 17, 20, 22 Uhr\n(Kann bis zum Öffnen der Kiste mehrmals betreten werden)\n\n<strong>Regeln:</strong>\n• Max. <strong>15 Personen</strong> pro Fraktion/Familie\n• Begegnen sich Fraktionen → Feuer eröffnen, Allianzen verboten\n• Verboten: Sniper, Drohnen, Taser, Wärmebild, Nachtsicht, Handschellen, Luft-Horns\n• Nur <strong>leichte kugelsichere Westen (50%)</strong>\n• Nach Event keine weiteren Überfälle/Schießereien\n\n<strong>Strafe:</strong> Jail 30–100 Minuten / Verwarnung je nach Verstoß`
  },
  {
    keys: ['fort zancudo','fort','militär','sang','zancudo'],
    title: 'Fort Zancudo',
    tag: 'red',
    answer: `<span class="tag tag-red">Fort Zancudo – Regeln</span>\n\n<strong>Angriffszeiten:</strong> Montag, Mittwoch, Freitag, Samstag <strong>15:00–23:00 Uhr</strong>\n\n<strong>Regeln:</strong>\n• Max. <strong>60</strong>, mind. <strong>10 Teilnehmer</strong> (inkl. Allianz)\n• Max. <strong>1 Angriff pro Tag</strong> pro Organisation\n• Zugang nur über Kontrollpunkte\n• Verboten: Sniper, Taser, Drohnen, alle Fahrzeuge außer Speedo\n• Verboten: in das/aus dem Fort schießen\n\n<strong>Strafe:</strong> Jail 30–90 Minuten / Verwarnung je nach Verstoß`
  },
  {
    keys: ['cayo','cayo perico','insel angriff'],
    title: 'Cayo Perico',
    tag: 'red',
    answer: `<span class="tag tag-red">Cayo Perico – Regeln</span>\n\n<strong>Angriffszeiten:</strong> Dienstag, Donnerstag, Sonntag <strong>15:00–23:00 Uhr</strong>\n\n<strong>Regeln:</strong>\n• Max. <strong>60</strong>, mind. <strong>10 Teilnehmer</strong> (inkl. Allianz)\n• Max. <strong>3 Punkte pro Tag</strong> angreifbar\n• Punkt max. <strong>30 Minuten</strong> halten (außer aktives Feuergefecht)\n• Max. <strong>1 Angriff</strong> pro Fraktion/Familie pro Tag\n• Verboten: Sniper, Drohnen, Taser, Privatfahrzeuge (außer Helikopter & Boote)\n\n<strong>Strafe:</strong> Jail 30–60 Minuten / Verwarnung je nach Verstoß`
  },
  {
    keys: ['gang turf','turf','gebiet','capt zeiten','conquista'],
    title: 'Gang Turf',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Gang Turf – Regeln</span>\n\n<strong>Zeiten:</strong> Dienstag, Donnerstag, Sonntag <strong>15:00–21:00 Uhr</strong>\n\n<strong>Teilnehmer:</strong> 8–15 Personen\n\n<strong>Verboten:</strong>\n• Waffen außerhalb des Crafting-Menüs\n• Sniper, MGs, schwere Schrotflinten, Stungewehre\n• Highground (Dächer, Hügel, Container)\n• Spiel während Eroberung verlassen (WARN)\n\n<strong>POV-Pflicht:</strong> 720p, ungeschnitten, Originalton, 48 Stunden aufbewahren\n\n<strong>Strafe fehlende POV:</strong> Konto Ban 15 Tage`
  },
  {
    keys: ['cop','polizei','staatlich','beamter','lspd','fib','lscsd','bad cop','kleiderordnung cop'],
    title: 'Staatliche Fraktionen',
    tag: 'green',
    answer: `<span class="tag tag-green">Staatliche Fraktionen – Regeln</span>\n\n• Mitgliedschaft verboten bei bestehendem <strong>Strafregister</strong> (außer Tat ist >7 Tage alt)\n• <strong>Bad-Cop</strong> verboten: grundlose tödliche Gewalt, Beleidigungen, ungerechtfertigtes Abschleppen\n• Gepanzerte Fahrzeuge in der Stadt verboten (außer bei Überfällen, Paraden)\n• Max. <strong>Haftzeit: 50 Minuten</strong> (mit Gerichtsurteil: 100 Minuten)\n• Im Dienst <strong>keine Maskierung</strong> (Ausnahme: Leader, Co-Leader, Spezialeinheit)\n• Kleiderordnung einhalten (keine Grellfarben, keine Gesichts-/Hals-Tattoos)\n• Verhaftungsprozess nicht absichtlich verzögern\n\n<strong>Strafe:</strong> WARN / Jail 15–90 Minuten je nach Verstoß`
  },
  {
    keys: ['haftzeit','verhaften','festnehmen','einbuchten','max haft','gefängnis'],
    title: 'Haftzeit',
    tag: 'green',
    answer: `<span class="tag tag-green">Maximale Haftzeit</span>\n\n• Normale Verhaftung (LSPD/LSCSD/FIB): max. <strong>50 Minuten</strong>\n• Nach Gerichtsverhandlung oder -anordnung: max. <strong>100 Minuten</strong>\n\n<strong>Strafe bei Verstoß:</strong> WARN`
  },
  {
    keys: ['leader','anführer','amtszeit','strike','leader regeln','leader pflicht','leaderpflicht'],
    title: 'Leader-Regeln',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Leader-Regeln</span>\n\n<strong>Amtszeiten:</strong>\n• Standard: <strong>30 Tage</strong> / GOV: <strong>45 Tage</strong>\n• Max. <strong>3 Amtszeiten</strong> in Folge\n• Max. <strong>4 Strikes</strong> vor Entlassung\n\n<strong>Pflichten:</strong>\n• Mind. <strong>3 Stunden täglich online</strong>, kein AFK\n• Mind. <strong>10 Personen</strong> täglich online\n• Max. 3 Stellvertreter (GOV: nur 1)\n\n<strong>Mindestbestand am Ende:</strong> 600.000 $ / 5.000 Waffenmat. / 4.000 Technikmat. / 3.000 Medizinmat.\n\n<strong>Rücktritt vor 14 Tagen:</strong> 7 Tage Sperre + Leader-Blacklist\n\n<strong>Verboten:</strong> Andere Charaktere spielen, andere GTA-RP Server, toxisches Verhalten`
  },
  {
    keys: ['kriminell','organisation','kriminelle org','fraktionskleidung','hq betreten','kriminell regeln'],
    title: 'Kriminelle Organisationen',
    tag: 'red',
    answer: `<span class="tag tag-red">Kriminelle Organisationen – Regeln</span>\n\n• Kriminelle Handlungen nur als <strong>Mitglied</strong> einer kriminellen Organisation (Jail 35–90 Min)\n• <strong>Fraktionskleidung</strong> (mind. Oberteil) + Fraktionsfahrzeug/-farbe bei Aktivitäten (Jail 35 Min)\n• <strong>Vollmaskierung</strong> bei allen Straftaten (Bart zählt nicht!)\n• HQ betreten ohne IC-Grund verboten (Jail 35–70 Min)\n  Ausnahmen: HQ-Raid, Gespräch mit Leader, Einladung\n• Vor Verfolgungen auf das eigene Gebiet flüchten verboten (Jail 35 Min)`
  },
  {
    keys: ['account','multi account','mehrere accounts','charakter','name','spielername'],
    title: 'Account-Regeln',
    tag: 'green',
    answer: `<span class="tag tag-green">Account & Charakter – Regeln</span>\n\n• Max. <strong>1 Account</strong> pro Spieler → Zweit-Account: Ban 30 Tage / Perm Ban\n• Account <strong>nicht verkaufen/tauschen/teilen</strong> → Perm Ban\n• Mehrere Charaktere gleichzeitig in einer Fraktion → WARN\n• <strong>Realistischer Vor- und Nachname</strong> erforderlich (Jail bis Namensänderung)\n• Akademische Titel (Dr., Prof. etc.) nur mit Government-Erlaubnis und als Staatsbediensteter`
  },
  {
    keys: ['cheat','hack','software','vorteil','mod','textur','dritte software'],
    title: 'Cheats & Software',
    tag: 'red',
    answer: `<span class="tag tag-red">Cheats & illegale Software</span>\n\n<strong>Regel:</strong> Die Verwendung von Software oder Modifikationen, die einen Vorteil verschaffen (Cheats, vorteilhafte Texturen/Mods) ist absolut verboten.\n\n<strong>Strafe:</strong> Konto Ban 15–30 Tage / <strong>Permanenter Bann</strong>`
  },
  {
    keys: ['doxxing','daten','persönlich verbreiten','privat daten'],
    title: 'Doxxing',
    tag: 'red',
    answer: `<span class="tag tag-red">Doxxing</span>\n\n<strong>Regel:</strong> Das Verbreiten von persönlichkeitsbezogenen Daten anderer Spieler ist absolut verboten.\n\n<strong>Strafe:</strong> Konto Ban 30 Tage / <strong>Permanenter Bann</strong>`
  },
  {
    keys: ['ems','sanitäter','arzt','helfen','retten'],
    title: 'EMS-Regeln',
    tag: 'green',
    answer: `<span class="tag tag-green">EMS – Regeln</span>\n\n• EMS-Mitarbeiter dürfen während ihrer Arbeit <strong>nicht angegriffen</strong> werden (Jail 30 Min / WARN)\n• EMS darf einer bewusstlosen Person während eines <strong>aktiven Schussgefechts nicht helfen</strong> – Gebiet muss zuerst sicher sein\n• EMS-Mitglieder sind verpflichtet, <strong>ausnahmslos jedem</strong> Spieler zu helfen (Strafe: WARN)`
  },
  {
    keys: ['konvoi','material lieferung','crafting','lieferung','transport'],
    title: 'Konvoi / Materialtransport',
    tag: 'amber',
    answer: `<span class="tag tag-amber">Konvoi / Materialtransport – Regeln</span>\n\n<strong>Angreifbar:</strong> 15:00–22:30 Uhr\n<strong>Schutzzeit:</strong> 16:00–17:00 Uhr (kein Angriff auf staatliche Lieferungen)\n\n<strong>Regeln:</strong>\n• Max. <strong>30.000 Materialien</strong> pro Lieferung\n• Angriff nur per vollständiger <strong>Straßenblockade</strong> (mind. 4 Autos)\n• Scharfschützengewehre verboten\n• Max. <strong>1 Angriff pro Tag</strong> pro kriminelle Organisation\n\n<strong>Strafe:</strong> Jail 30–60 Min / Verwarnung je nach Verstoß`
  },
  {
    keys: ['bug','exploit','fehler nutzen','missbrauch','grauzone'],
    title: 'Bug / Exploit',
    tag: 'red',
    answer: `<span class="tag tag-red">Bug / Exploit (Regel 7.8)</span>\n\n<strong>Regel:</strong> Die Nutzung oder der Versuch, Fehler, Regelmissbrauch (inkl. Grauzone) und Serverfunktionen auszunutzen, ist verboten.\n\n<strong>Strafe:</strong> WARN / Ban 3–15 Tage / Konto Ban 3–7 Tage`
  },
];

let chatHistory = [];
let hasMessages = false;

function findAnswer(q) {
  const lq = q.toLowerCase();
  let best = null, bestScore = 0;
  for (const r of RULES) {
    let score = 0;
    for (const k of r.keys) {
      if (lq.includes(k)) score += k.length;
    }
    if (score > bestScore) { bestScore = score; best = r; }
  }
  if (best && bestScore > 2) return best.answer;
  return `Zu deiner Frage <strong>"${q}"</strong> habe ich keine direkte Regel gefunden.\n\nVersuche konkretere Begriffe wie:\n• "Was ist RDM?"\n• "Greenzone Regeln?"\n• "Haftzeit Cops?"\n\nOder nutze die Kategorien in der Seitenleiste.`;
}

function addMessage(role, html) {
  const box = document.getElementById('chat-box');
  const empty = document.getElementById('empty');
  if (empty && !hasMessages) { empty.remove(); hasMessages = true; }

  const row = document.createElement('div');
  row.className = 'msg-row ' + (role === 'user' ? 'user-row' : '');

  const av = document.createElement('div');
  av.className = 'avatar ' + (role === 'user' ? 'user-av' : 'bot-av');
  av.innerHTML = role === 'user'
    ? '<i class="ti ti-user"></i>'
    : '<i class="ti ti-bug"></i>';

  const bub = document.createElement('div');
  bub.className = 'bubble ' + (role === 'user' ? 'user-bub' : 'bot-bub');
  bub.innerHTML = html;

  row.appendChild(av);
  row.appendChild(bub);
  box.appendChild(row);
  box.scrollTop = box.scrollHeight;
}

function handleSend() {
  const inp = document.getElementById('msg-input');
  const q = inp.value.trim();
  if (!q) return;
  inp.value = '';
  inp.style.height = 'auto';

  addMessage('user', q);
  const answer = findAnswer(q);
  setTimeout(() => addMessage('bot', answer), 180);
}

function askQ(q) {
  document.getElementById('msg-input').value = q;
  handleSend();
}

document.getElementById('msg-input').addEventListener('keydown', e => {
  if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); handleSend(); }
});

document.getElementById('msg-input').addEventListener('input', function() {
  this.style.height = 'auto';
  this.style.height = Math.min(this.scrollHeight, 120) + 'px';
});
</script>
</body>
</html>
