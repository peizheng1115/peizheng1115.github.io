---
layout: single
title: "Stufe B1: Mittelstufe I – Komplexe Syntax, Passiv & Irrealis"
permalink: /deutsch/grammatik/b1/
sidebar:
  nav: "deutsch"
toc: false
---

<style>
/* Light Blue Modern Aesthetic for German Grammar System */
.grammar-container {
    max-width: 1080px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    color: #0f172a;
}

/* Hero Section */
.hero-box {
    background: linear-gradient(135deg, #e0f2fe 0%, #f0f9ff 50%, #ffffff 100%);
    border: 1px solid #bae6fd;
    border-radius: 16px;
    padding: 32px 28px;
    margin-bottom: 28px;
    box-shadow: 0 4px 20px -2px rgba(2, 132, 199, 0.08);
}
.hero-badge {
    display: inline-block;
    background-color: #0284c7;
    color: #ffffff;
    font-weight: 700;
    font-size: 0.82rem;
    padding: 4px 12px;
    border-radius: 9999px;
    letter-spacing: 0.5px;
    text-transform: uppercase;
    margin-bottom: 12px;
}
.hero-title {
    font-size: 2rem;
    font-weight: 800;
    color: #0369a1;
    margin: 0 0 12px 0;
    line-height: 1.25;
}
.hero-summary {
    font-size: 1.05rem;
    line-height: 1.6;
    color: #334155;
    margin: 0 0 20px 0;
}
.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    align-items: center;
}
.action-btn {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: #ffffff;
    color: #0284c7;
    border: 1px solid #7dd3fc;
    padding: 8px 16px;
    border-radius: 8px;
    font-weight: 600;
    font-size: 0.92rem;
    text-decoration: none;
    transition: all 0.2s ease;
}
.action-btn:hover {
    background: #0284c7;
    color: #ffffff;
    border-color: #0284c7;
    box-shadow: 0 4px 12px rgba(2, 132, 199, 0.25);
}

/* Quick TOC Navigation Bar */
.toc-bar {
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    padding: 16px 20px;
    margin-bottom: 36px;
}
.toc-bar-title {
    font-size: 0.9rem;
    font-weight: 700;
    color: #64748b;
    text-transform: uppercase;
    letter-spacing: 0.6px;
    margin-bottom: 10px;
}
.toc-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
}
.toc-pill {
    background: #ffffff;
    color: #0369a1;
    border: 1px solid #bae6fd;
    padding: 5px 12px;
    border-radius: 6px;
    font-size: 0.88rem;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.15s ease;
}
.toc-pill:hover {
    background: #0284c7;
    color: #ffffff;
    border-color: #0284c7;
}

/* Chapter Cards */
.chapter-card {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-left: 6px solid #0284c7;
    border-radius: 14px;
    margin-bottom: 36px;
    padding: 28px;
    box-shadow: 0 4px 16px -2px rgba(15, 23, 42, 0.05);
    scroll-margin-top: 80px;
}
.chapter-card-header {
    margin-bottom: 20px;
    padding-bottom: 16px;
    border-bottom: 1px solid #f1f5f9;
}
.ch-badge-num {
    font-size: 0.8rem;
    font-weight: 800;
    color: #0284c7;
    text-transform: uppercase;
    letter-spacing: 0.8px;
    margin-bottom: 4px;
}
.ch-heading {
    font-size: 1.45rem;
    font-weight: 700;
    color: #0f172a;
    margin: 0;
    line-height: 1.35;
}

/* Formula Chips */
.formula-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 20px;
}
.formula-chip {
    background: #f0fdf4;
    border: 1px solid #bbf7d0;
    padding: 6px 14px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    gap: 8px;
}
.formula-badge {
    background: #16a34a;
    color: #ffffff;
    font-size: 0.72rem;
    font-weight: 700;
    padding: 2px 6px;
    border-radius: 4px;
    text-transform: uppercase;
}
.formula-chip code {
    color: #166534;
    font-weight: 700;
    font-size: 0.92rem;
    background: transparent;
    padding: 0;
}

/* Rule Boxes */
.rule-box {
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 10px;
    padding: 18px 22px;
    margin-bottom: 24px;
}
.rule-box-header {
    font-size: 0.95rem;
    font-weight: 700;
    color: #0369a1;
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 6px;
}
.rule-list {
    margin: 0;
    padding-left: 0;
    list-style: none;
}
.rule-header-item {
    font-size: 1rem;
    font-weight: 700;
    color: #0369a1;
    margin-top: 14px;
    margin-bottom: 6px;
    list-style: none;
}
.rule-header-item:first-child {
    margin-top: 0;
}
.rule-item {
    font-size: 0.96rem;
    line-height: 1.6;
    color: #334155;
    margin-bottom: 8px;
    position: relative;
    padding-left: 18px;
}
.rule-item::before {
    content: "•";
    position: absolute;
    left: 4px;
    color: #0284c7;
    font-weight: bold;
}
.rule-sub-item {
    font-size: 0.94rem;
    line-height: 1.55;
    color: #475569;
    margin-bottom: 6px;
    padding-left: 32px;
    position: relative;
}
.rule-sub-item::before {
    content: "–";
    position: absolute;
    left: 18px;
    color: #94a3b8;
}

.inline-code {
    background: #e0f2fe;
    color: #0369a1;
    padding: 2px 6px;
    border-radius: 4px;
    font-size: 0.9em;
    font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
}

/* Tables */
.grammar-table-wrapper {
    margin-bottom: 24px;
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-radius: 10px;
    overflow: hidden;
}
.table-title {
    background: #f1f5f9;
    padding: 10px 16px;
    font-weight: 700;
    font-size: 0.94rem;
    color: #1e293b;
    border-bottom: 1px solid #e2e8f0;
}
.table-responsive {
    overflow-x: auto;
}
.grammar-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.92rem;
    text-align: left;
    margin: 0;
}
.grammar-table th {
    background: #f8fafc;
    color: #0369a1;
    font-weight: 700;
    padding: 10px 14px;
    border-bottom: 2px solid #e2e8f0;
    border-right: 1px solid #f1f5f9;
}
.grammar-table td {
    padding: 10px 14px;
    border-bottom: 1px solid #f1f5f9;
    border-right: 1px solid #f8fafc;
    color: #334155;
    line-height: 1.5;
}
.grammar-table tr:hover td {
    background-color: #f0f9ff;
}

/* Examples Grid */
.examples-section {
    margin-top: 24px;
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 10px;
    padding: 16px 20px;
}
.examples-header {
    font-size: 0.95rem;
    font-weight: 700;
    color: #047857;
    margin-bottom: 14px;
}
.examples-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(360px, 1fr));
    gap: 12px;
}
.example-card {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-left: 3px solid #10b981;
    border-radius: 8px;
    padding: 10px 14px;
}
.ex-de {
    font-size: 0.94rem;
    font-weight: 600;
    color: #0f172a;
    margin-bottom: 4px;
    line-height: 1.45;
}
.ex-en {
    font-size: 0.88rem;
    color: #64748b;
    line-height: 1.4;
}
.ex-flag {
    font-size: 0.9rem;
    margin-right: 4px;
}

/* Card Footer */
.chapter-card-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 24px;
    padding-top: 14px;
    border-top: 1px dashed #e2e8f0;
    font-size: 0.88rem;
}
.back-to-top, .hub-link {
    color: #0284c7;
    text-decoration: none;
    font-weight: 600;
}
.back-to-top:hover, .hub-link:hover {
    text-decoration: underline;
}

/* Level Bottom Nav */
.level-nav-bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #f0f9ff;
    border: 1px solid #bae6fd;
    border-radius: 12px;
    padding: 18px 24px;
    margin-top: 40px;
}
.nav-btn {
    display: inline-block;
    background: #0284c7;
    color: #ffffff;
    font-weight: 700;
    font-size: 0.95rem;
    padding: 10px 20px;
    border-radius: 8px;
    text-decoration: none;
    transition: background 0.2s;
}
.nav-btn:hover {
    background: #0369a1;
    color: #ffffff;
}
.nav-btn.disabled {
    background: #cbd5e1;
    color: #64748b;
    pointer-events: none;
}
</style>

<div class="grammar-container">
    <div id="toc-top" class="hero-box">
        <span class="hero-badge">CEFR B1 Mittelstufe I</span>
        <h1 class="hero-title">Stufe B1: Mittelstufe I – Komplexe Syntax, Passiv &amp; Irrealis</h1>
        <p class="hero-summary">Mittelstufen-Standard für selbstständige akademische und professionelle Sprachverwendung: Konjunktiv II in Gegenwart &amp; Vergangenheit, irreale Konditionalsätze, Vorgangspassiv in allen 6 Zeitformen, unpersönliches Passiv, Zustandspassiv, Relativsätze (Nom, Akk, Dat, Gen &amp; Präpositionen), Genitiv-Systematik, N-Deklination (Schwache Maskulina), Verben mit festen Präpositionen &amp; Pronominaladverbien, Infinitiv mit zu, Finalsätze (um...zu / damit) und Futur I / II.</p>
        <div class="hero-actions">
            <a href="/deutsch/grammatik/" class="action-btn">📚 Grammatik-Hub</a>
            <a href="/files/Deutsch_Grammatik_B1.md" class="action-btn" download>📥 Download Markdown</a>
            <a href="/deutsch/" class="action-btn">🇩🇪 Deutsch Portal</a>
        </div>
    </div>

    <nav class="toc-bar" aria-label="Kapitel-Navigation">
        <div class="toc-bar-title">⚡ Schnellnavigation durch alle 10 Kapitel (B1):</div>
        <div class="toc-grid">
            <a href="#b1-ch01-konjunktiv2" class="toc-pill">Kapitel 1</a><a href="#b1-ch02-vorgangspassiv" class="toc-pill">Kapitel 2</a><a href="#b1-ch03-zustandspassiv" class="toc-pill">Kapitel 3</a><a href="#b1-ch04-relativsaetze" class="toc-pill">Kapitel 4</a><a href="#b1-ch05-genitive" class="toc-pill">Kapitel 5</a><a href="#b1-ch06-verbs-prepositions-dawo" class="toc-pill">Kapitel 6</a><a href="#b1-ch07-infinitive-clauses" class="toc-pill">Kapitel 7</a><a href="#b1-ch08-adverbial-clauses" class="toc-pill">Kapitel 8</a><a href="#b1-ch09-future-tenses" class="toc-pill">Kapitel 9</a><a href="#b1-ch10-word-formation" class="toc-pill">Kapitel 10</a>
        </div>
    </nav>

    <div class="chapters-wrapper">
        
        <article id="b1-ch01-konjunktiv2" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 01</div>
                <h2 class="ch-heading">Kapitel 1: Der Konjunktiv II (Gegenwart, Vergangenheit &amp; Irreale Konditionalsätze)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Funktionen des Konjunktiv II:</strong></li><li class="rule-sub-item"><em>Höfliche Bitten &amp; Diplomatie:</em> Könnten Sie mir die Daten senden? Ich würde gerne etwas fragen.</li><li class="rule-sub-item"><em>Irreale Wünsche &amp; Träume:</em> Wenn ich doch bloß mehr Zeit hätte! / Hätte ich doch mehr Zeit!</li><li class="rule-sub-item"><em>Irreale Bedingungen (Konditionalsätze):</em> Wenn die Flussrate höher wäre, würden die Zellen stärker differenzieren.</li><li class="rule-sub-item"><em>Irreale Vergleiche mit als ob / als wenn:</em> Er spricht, als ob er der Projektleiter wäre.</li><li class="rule-sub-item"><em>Ratschläge &amp; Empfehlungen:</em> Du solltest vor der Messung den Sensor kalibrieren.</li><li class="rule-header-item"><strong>2. Bildung Konjunktiv II der Gegenwart:</strong></li><li class="rule-sub-item"><em>Allgemeine Form (fast alle Vollverben):</em> <strong>würde + Infinitiv am Satzende</strong> (<em>ich würde forschen, du würdest testen, wir würden publizieren</em>).</li><li class="rule-sub-item"><em>Echte Konjunktiv II Formen (OHNE &#x27;würde&#x27;!):</em></li><li class="rule-sub-item"><strong>sein:</strong> <em>wäre, wärest, wäre, wären, wärt, wären</em></li><li class="rule-sub-item"><strong>haben:</strong> <em>hätte, hättest, hätte, hätten, hättet, hätten</em></li><li class="rule-sub-item"><strong>werden:</strong> <em>würde, würdest, würde, würden, würdet, würden</em></li><li class="rule-sub-item"><strong>wissen:</strong> <em>wüsste, wüsstest, wüsste, wüssten, wüsstet, wüssten</em></li><li class="rule-sub-item"><strong>Starke Verben (Stamm Präteritum + Umlaut + -e):</strong> <em>kommen → käme, gehen → ginge, finden → fände, bleiben → bliebe, geben → gäbe, lassen → ließe, tun → täte</em>.</li><li class="rule-header-item"><strong>3. Modalverben im Konjunktiv II:</strong></li><li class="rule-sub-item"><em>können → könnte, müssen → müsste, dürfen → dürfte, sollen → sollte (kein Umlaut!), wollen → wollte (kein Umlaut!)</em>.</li><li class="rule-header-item"><strong>4. Konjunktiv II der Vergangenheit (Irreale Vergangenheit):</strong></li><li class="rule-sub-item"><strong>hätte / wäre + Partizip II</strong> (<em>Wenn wir gestern schneller gewesen wären, hätten wir die Messung beendet</em>).</li><li class="rule-sub-item"><em>Mit Modalverb in der Vergangenheit:</em> <strong>hätte + Doppelinfinitiv</strong> (<em>Wir hätten die Probe kühlen müssen</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Übersicht: Konjunktiv II Formen Gegenwart und Vergangenheit</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Verbtyp</th><th>Präsens Konjunktiv II</th><th>Vergangenheit Konjunktiv II</th><th>Anwendungsbeispiel</th></tr></thead>
                        <tbody><tr><td>Hilfsverb sein</td><td>ich wäre (if I were)</td><td>ich wäre gewesen (if I had been)</td><td>Wenn das System steril gewesen wäre, ...</td></tr><tr><td>Hilfsverb haben</td><td>ich hätte (if I had)</td><td>ich hätte gehabt (if I had had)</td><td>Hätten wir mehr Daten gehabt, ...</td></tr><tr><td>Modalverb können</td><td>ich könnte (could)</td><td>ich hätte ... können (could have)</td><td>Wir hätten den Versuch wiederholen können.</td></tr><tr><td>Modalverb müssen</td><td>ich müsste (would have to)</td><td>ich hätte ... müssen (should/must have)</td><td>Sie hätte das Protokoll prüfen müssen.</td></tr><tr><td>Vollverb forschen</td><td>ich würde forschen</td><td>ich hätte geforscht</td><td>Ich hätte länger an diesem Thema geforscht.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Hätte das Labor über modernere Geräte verfügt (Vergangenheit KII), hätten wir die Publikation früher eingereicht.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Had the lab possessed more modern equipment, we would have submitted the publication earlier.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> An Ihrer Stelle würde ich die Konzentrationsreihe um zwei weitere Verdünnungsstufen erweitern.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> In your place I would expand the concentration series by two additional dilution levels.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch02-vorgangspassiv" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 02</div>
                <h2 class="ch-heading">Kapitel 2: Das Vorgangspassiv in allen 6 Zeitformen &amp; Passiv mit Modalverben</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-item"><strong>1. Das Grundprinzip:</strong> Im Passiv steht die Handlung (der Vorgang) im Mittelpunkt; der Handelnde ist unwichtig, unbekannt oder allgemein.</li><li class="rule-header-item"><strong>2. Transformation Aktiv → Passiv:</strong></li><li class="rule-sub-item"><em>Aktiv-Akkusativobjekt</em> wird zum <em>Passiv-Subjekt im Nominativ</em>.</li><li class="rule-sub-item"><em>Aktiv-Subjekt</em> wird optional zur <em>Präpositionalphrase:</em> <strong>von + Dativ</strong> (handelnde Person, Urheber) oder <strong>durch + Akkusativ</strong> (Mittel, Ursache, Instrument).</li><li class="rule-header-item"><strong>3. Die 6 Zeitformen des Vorgangspassivs:</strong></li><li class="rule-sub-item"><em>Präsens:</em> <strong>wird + Partizip II</strong> (<em>Die Probe wird zentrifugiert</em>).</li><li class="rule-sub-item"><em>Präteritum:</em> <strong>wurde + Partizip II</strong> (<em>Die Probe wurde zentrifugiert</em>).</li><li class="rule-sub-item"><em>Perfekt:</em> <strong>ist + Partizip II + worden</strong> (Beachte: <em>worden</em>, NICHT <em>geworden</em>!).</li><li class="rule-sub-item"><em>Plusquamperfekt:</em> <strong>war + Partizip II + worden</strong> (<em>Die Probe war zentrifugiert worden</em>).</li><li class="rule-sub-item"><em>Futur I:</em> <strong>wird + Partizip II + werden</strong> (<em>Die Probe wird zentrifugiert werden</em>).</li><li class="rule-sub-item"><em>Futur II:</em> <strong>wird + Partizip II + worden sein</strong> (<em>Die Probe wird zentrifugiert worden sein</em>).</li><li class="rule-header-item"><strong>4. Passiv mit Modalverben:</strong></li><li class="rule-sub-item"><em>Präsens:</em> <strong>Modalverb (konjugiert) + ... + Partizip II + werden (Infinitiv)</strong> (<em>Die Durchflussrate muss kontrolliert werden</em>).</li><li class="rule-sub-item"><em>Präteritum:</em> <strong>Modalverb Präteritum + ... + Partizip II + werden</strong> (<em>Die Durchflussrate musste kontrolliert werden</em>).</li><li class="rule-header-item"><strong>5. Unpersönliches Passiv (Passiv ohne Subjekt):</strong></li><li class="rule-sub-item">Intransitive Verben können ein Passiv ohne Subjekt bilden (<em>Im Labor wird nicht geraucht; Es wurde lange über das Ergebnis diskutiert</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Die 6 Zeitformen des Vorgangspassivs im tabellarischen Vergleich</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Zeitform</th><th>Aktiv-Satz</th><th>Passiv-Satz (Formel)</th><th>Wissenschaftlicher Kontext</th></tr></thead>
                        <tbody><tr><td>Präsens</td><td>Der Forscher reinigt den Chip.</td><td>Der Chip wird gereinigt. (wird + P.II)</td><td>Tägliche Laborroutine</td></tr><tr><td>Präteritum</td><td>Der Forscher reinigte den Chip.</td><td>Der Chip wurde gereinigt. (wurde + P.II)</td><td>Schriftlicher Versuchsbericht</td></tr><tr><td>Perfekt</td><td>Der Forscher hat den Chip gereinigt.</td><td>Der Chip ist gereinigt worden. (ist + P.II + worden)</td><td>Mündlicher Statusbericht</td></tr><tr><td>Plusquamperfekt</td><td>Der Forscher hatte den Chip gereinigt.</td><td>Der Chip war gereinigt worden. (war + P.II + worden)</td><td>Vorzeitigkeit in der Vergangenheit</td></tr><tr><td>Futur I</td><td>Der Forscher wird den Chip reinigen.</td><td>Der Chip wird gereinigt werden. (wird + P.II + werden)</td><td>Geplante Versuche</td></tr><tr><td>Mit Modalverb</td><td>Man muss den Chip reinigen.</td><td>Der Chip muss gereinigt werden. (Modal + P.II + werden)</td><td>Vorschrift / Arbeitsanweisung</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Zellsuspension wurde vor dem Einsäen dreimal mit sterilem Puffer gewaschen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The cell suspension was washed three times with sterile buffer before seeding.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Durch die kontinuierliche Zufuhr von Nährstoffen (durch + Akk) wird das Zellwachstum stimuliert.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Through the continuous supply of nutrients, cell growth is stimulated.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch03-zustandspassiv" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 03</div>
                <h2 class="ch-heading">Kapitel 3: Das Zustandspassiv (Stative Passive) &amp; Abgrenzung zum Vorgangspassiv</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Vorgangspassiv vs. Zustandspassiv:</strong></li><li class="rule-sub-item"><em>Vorgangspassiv (werden + P.II):</em> Betont den dynamischen Ablauf, die Aktion oder Veränderung (<em>Das Labor wird um 18:00 Uhr geschlossen</em> = Jemand schließt die Tür).</li><li class="rule-sub-item"><em>Zustandspassiv (sein + P.II):</em> Betont den statischen Zustand nach Abschluss der Handlung (<em>Das Labor ist geschlossen</em> = Die Tür ist zu).</li><li class="rule-header-item"><strong>2. Bildung des Zustandspassivs in den Zeitformen:</strong></li><li class="rule-sub-item"><em>Präsens:</em> <strong>sein (konjugiert) + Partizip II</strong> (<em>Die Proben sind sterilisiert</em>).</li><li class="rule-sub-item"><em>Präteritum:</em> <strong>war + Partizip II</strong> (<em>Die Proben waren bereits sterilisiert</em>).</li><li class="rule-sub-item"><em>Perfekt:</em> <strong>ist + Partizip II + gewesen</strong> (<em>Die Proben sind sterilisiert gewesen</em>).</li><li class="rule-sub-item"><em>Futur I:</em> <strong>wird + Partizip II + sein</strong> (<em>Morgen um 8 Uhr wird alles vorbereitet sein</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Vorgangspassiv vs. Zustandspassiv im direkten Vergleich</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Kategorie</th><th>Vorgangspassiv (Prozess)</th><th>Zustandspassiv (Zustand/Ergebnis)</th><th>Semantischer Unterschied</th></tr></thead>
                        <tbody><tr><td>Präsens</td><td>Die Membran wird beschichtet.</td><td>Die Membran ist beschichtet.</td><td>Vorgang läuft vs. Schicht ist vorhanden</td></tr><tr><td>Präteritum</td><td>Die Membran wurde beschichtet.</td><td>Die Membran war beschichtet.</td><td>Handlung fand statt vs. Zustand lag vor</td></tr><tr><td>Perfekt</td><td>Die Membran ist beschichtet worden.</td><td>Die Membran ist beschichtet gewesen.</td><td>Abschluss der Aktion vs. Früherer Zustand</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Als wir den Versuch starteten, waren alle Sensoren bereits exakt kalibriert (Zustandspassiv Präteritum).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> When we started the experiment, all sensors were already calibrated exactly.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Ventile sind für den Hochdruckbetrieb ausgelegt.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The valves are designed for high-pressure operation.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch04-relativsaetze" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 04</div>
                <h2 class="ch-heading">Kapitel 4: Relativsätze (Komplettes 4-Fälle-System, Präpositionen &amp; Indefinite Relativsätze)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Kongruenz und Kasus des Relativpronomens:</strong></li><li class="rule-sub-item"><strong>Genus &amp; Numerus</strong> richten sich nach dem Bezugswort im Hauptsatz (<em>der Forscher → Maskulin Singular</em>).</li><li class="rule-sub-item"><strong>Kasus</strong> richtet sich nach der syntaktischen Funktion im Relativsatz (<em>Subjekt → Nominativ; Objekt → Akkusativ/Dativ/Genitiv</em>).</li><li class="rule-item"><strong>2. Die Formen des Relativpronomens:</strong> Entsprechen dem bestimmten Artikel bis auf zwei Ausnahmen:</li><li class="rule-sub-item"><em>Dativ Plural:</em> <strong>denen</strong> (nicht &#x27;den&#x27;).</li><li class="rule-sub-item"><em>Genitiv:</em> <strong>dessen</strong> (Mask./Neutr.) / <strong>deren</strong> (Fem./Plur.).</li><li class="rule-header-item"><strong>3. Relativsätze mit Präpositionen:</strong></li><li class="rule-sub-item">Die Präposition steht DIREKT vor dem Relativpronomen und bestimmt dessen Kasus (<em>das Modell, [auf dem: Dat] wir die Versuche basieren; der Kollege, [ohne den: Akk] das Projekt nicht möglich gewesen wäre</em>).</li><li class="rule-header-item"><strong>4. Freie / Indefinite Relativsätze mit &#x27;was&#x27;, &#x27;wo&#x27;, &#x27;wohin&#x27;, &#x27;woher&#x27;:</strong></li><li class="rule-sub-item">Eingeleitet durch <em>was</em> nach neutralen Indefinitpronomen (<em>alles, nichts, vieles, einiges, das Beste</em>): <em>Das ist alles, was wir wissen</em>.</li><li class="rule-sub-item">Eingeleitet durch <em>was</em> bei Bezug auf den gesamten vorangehenden Satz (<em>Wir gewannen den Preis, was uns alle sehr freute</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Vollständige Deklinationstabelle der deutschen Relativpronomen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Kasus im Relativsatz</th><th>Maskulin (m)</th><th>Feminin (f)</th><th>Neutrum (n)</th><th>Plural (pl)</th></tr></thead>
                        <tbody><tr><td>Nominativ (Subjekt)</td><td>der Mann, der forscht</td><td>die Zelle, die wächst</td><td>das Labor, das neu ist</td><td>die Geräte, die laufen</td></tr><tr><td>Akkusativ (Objekt)</td><td>der Chip, den ich baue</td><td>die Pumpe, die ich steuere</td><td>das Mikroskop, das ich nutze</td><td>die Daten, die wir erheben</td></tr><tr><td>Dativ (indirekt)</td><td>der Betreuer, dem ich danke</td><td>die Forscherin, der ich helfe</td><td>das Institut, dem wir angehören</td><td>die Partner, denen wir vertrauen (+n)</td></tr><tr><td>Genitiv (Besitz/Zugehör.)</td><td>der Autor, dessen Paper...</td><td>die Universität, deren Ruf...</td><td>das Team, dessen Erfolg...</td><td>die Studenten, deren Arbeiten...</td></tr><tr><td>Mit Präposition (Beispiel)</td><td>der Sensor, mit dem wir...</td><td>die Kammer, in der das Fluid...</td><td>das Feld, an dem wir...</td><td>die Firmen, mit denen wir...</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Wissenschaftlerin, deren Veröffentlichung (Genitiv) weltweit zitiert wurde, leitet das neue Institut.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The scientist whose publication was cited worldwide leads the new institute.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Das ist das Trägermaterial, auf dem (Präposition + Dativ) die Stammzellen differenziert wurden.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> That is the substrate material on which the stem cells were differentiated.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch05-genitive" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 05</div>
                <h2 class="ch-heading">Kapitel 5: Der Genitiv (Wessen-Fall), N-Deklination &amp; Genitiv-Präpositionen</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Formen des Genitivs:</strong></li><li class="rule-sub-item"><em>Maskulin &amp; Neutrum:</em> <strong>des / eines / meines / keines + Nomenendung (-s / -es)</strong>.</li><li class="rule-sub-item"><em>Feminin &amp; Plural:</em> <strong>der / einer / meiner / keiner (OHNE Nomenendung!)</strong>.</li><li class="rule-header-item"><strong>2. Wann -s und wann -es bei Maskulina &amp; Neutra?</strong></li><li class="rule-sub-item"><strong>-es (Zwingend):</strong> Bei einsilbigen Wörtern (<em>des Mannes, des Tages, des Jahres, des Glases</em>) und nach Zischlauten <em>-s, -ß, -z, -x, -sch, -tz</em> (<em>des Flusses, des Gesetzes, des Reflexes</em>).</li><li class="rule-sub-item"><strong>-s:</strong> Bei mehrsilbigen Wörtern auf unbetonte Endungen <em>-el, -er, -en, -chen, -lein, -ment, -ling, -or</em> (<em>des Computers, des Experiments, des Lehrlings</em>).</li><li class="rule-header-item"><strong>3. Die N-Deklination (Schwache maskuline Substantive):</strong></li><li class="rule-sub-item">Diese Maskulina erhalten in ALLEN Kasus außer dem Nominativ Singular die Endung <strong>-(e)n</strong>!</li><li class="rule-sub-item"><em>Gruppe A (Endung auf -e):</em> <em>der Kollege (des Kollegen), der Biologe, der Kunde, der Zeuge, der Experte, der Junge, der Nachbar</em>.</li><li class="rule-sub-item"><em>Gruppe B (Fremdwörter mit betonter Endung):</em> <em>-ant, -ent, -ist, -at, -et, -oge, -nom, -soph, -graf</em> (<em>der Student, der Doktorand, der Assistent, der Spezialist, der Philosoph, der Fotograf</em>).</li><li class="rule-sub-item"><em>Sonderform mit -ns im Genitiv:</em> <em>der Name (des Namens), der Gedanke (des Gedankens), der Buchstabe (des Buchstabens), der Wille (des Willens)</em> sowie <em>das Herz (des Herzens, dem Herzen, das Herz)</em>.</li><li class="rule-header-item"><strong>4. Genitiv-Präpositionen im B1/B2-Bereich:</strong></li><li class="rule-sub-item"><em>während</em> (während des Versuchs), <em>wegen</em> (wegen des Ausfalls), <em>trotz</em> (trotz der hohen Kosten), <em>(an)statt</em> (anstatt des Standardverfahrens), <em>innerhalb</em> (innerhalb eines Tages), <em>außerhalb</em> (außerhalb der Sprechzeiten), <em>aufgrund</em> (aufgrund neuer Daten), <em>infolge</em> (infolge der Reaktion).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Das vollständige 4-Fälle-Deklinationssystem der deutschen Nomen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Kasus</th><th>Maskulin (m)</th><th>Feminin (f)</th><th>Neutrum (n)</th><th>Plural (pl)</th></tr></thead>
                        <tbody><tr><td>Nominativ</td><td>der / ein / kein Forscher</td><td>die / eine / keine Probe</td><td>das / ein / kein Institut</td><td>die / — / keine Resultate</td></tr><tr><td>Akkusativ</td><td>den / einen / keinen Forscher</td><td>die / eine / keine Probe</td><td>das / ein / kein Institut</td><td>die / — / keine Resultate</td></tr><tr><td>Dativ</td><td>dem / einem / keinem Forscher</td><td>der / einer / keiner Probe</td><td>dem / einem / keinem Institut</td><td>den / — / keinen Resultaten (+n)</td></tr><tr><td>Genitiv</td><td>des / eines / keines Forschers</td><td>der / einer / keiner Probe</td><td>des / eines / keines Instituts</td><td>der / — / keiner Resultate</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Trotz des unerwarteten Ausfalls (Genitiv) der Mikropumpe konnten wir die Daten des Doktoranden (N-Deklination) retten.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Despite the unexpected failure of the micropump, we were able to save the doctoral student&#x27;s data.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Innerhalb der nächsten zwei Wochen (Genitiv) reichen wir den Förderantrag ein.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Within the next two weeks we will submit the grant application.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch06-verbs-prepositions-dawo" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 06</div>
                <h2 class="ch-heading">Kapitel 6: Verben mit festen Präpositionen &amp; Pronominaladverbien (da-/wo-)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-item"><strong>1. Präpositionalobjekte:</strong> Viele Verben sind fest an eine bestimmte Präposition gekoppelt, die ihren Kasus bestimmt.</li><li class="rule-header-item"><strong>2. Pronominaladverbien (NUR bei Sachen / Konzepten):</strong></li><li class="rule-sub-item"><strong>Aussage / Pronomen:</strong> <em>da + Präposition</em> (Beginnt die Präposition mit Vokal → Einschub von <em>-r-</em>: <em>dar-auf, dar-an, dar-über, dar-unter, dar-in, da-mit, da-für, da-von, da-zu</em>).</li><li class="rule-sub-item"><strong>Frageform:</strong> <em>wo + Präposition</em> (Beginnt die Präposition mit Vokal → Einschub von <em>-r-</em>: <em>wor-auf, wor-an, wor-über, wor-unter, wo-mit, wo-für, wo-von, wo-zu</em>).</li><li class="rule-header-item"><strong>3. Personenreferenz (NIEMALS da-/wo- bei Personen!):</strong></li><li class="rule-sub-item">Bei Personen wird die reguläre Präposition mit dem Personalpronomen kombiniert (<em>Ich warte auf meinen Professor → Auf wen wartest du? → Ich warte auf ihn!</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Katalog der wichtigsten Verben mit festen Präpositionen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Verb + feste Präposition</th><th>Kasus</th><th>Frage / Pronomen (Sache)</th><th>Frage / Pronomen (Person)</th><th>Bedeutung / Beispielsatz</th></tr></thead>
                        <tbody><tr><td>warten auf</td><td>Akkusativ</td><td>Worauf? – Darauf.</td><td>Auf wen? – Auf ihn.</td><td>Wir warten auf die Genehmigung.</td></tr><tr><td>sich konzentrieren auf</td><td>Akkusativ</td><td>Worauf? – Darauf.</td><td>Auf wen? – Auf sie.</td><td>Die Studie konzentriert sich auf Barrieredichte.</td></tr><tr><td>denken an</td><td>Akkusativ</td><td>Woran? – Daran.</td><td>An wen? – An ihn.</td><td>Denken Sie an die Kontrollmessung!</td></tr><tr><td>sich freuen auf (Zukunft)</td><td>Akkusativ</td><td>Worauf? – Darauf.</td><td>Auf wen? – Auf sie.</td><td>Ich freue mich auf die Zusammenarbeit.</td></tr><tr><td>sich freuen über (Gegenwart/Verg.)</td><td>Akkusativ</td><td>Worüber? – Darüber.</td><td>Über wen? – Über ihn.</td><td>Wir freuen uns über die Publikation.</td></tr><tr><td>forschen / arbeiten an</td><td>Dativ</td><td>Woran? – Daran.</td><td>An wem? – An ihr.</td><td>Unsere Gruppe forscht an Organ-on-a-Chip.</td></tr><tr><td>sich befassen mit</td><td>Dativ</td><td>Womit? – Damit.</td><td>Mit wem? – Mit ihnen.</td><td>Das Team befasst sich mit Toxikologie.</td></tr><tr><td>abhängen von</td><td>Dativ</td><td>Wovon? – Davon.</td><td>Von wem? – Von ihr.</td><td>Die Validität hängt von der Kalibrierung ab.</td></tr><tr><td>beitragen zu</td><td>Dativ</td><td>Wozu? – Dazu.</td><td>Zu wem? – Zu ihnen.</td><td>Dies trägt zur Vermeidung von Tierversuchen bei.</td></tr><tr><td>zweifeln an</td><td>Dativ</td><td>Woran? – Daran.</td><td>An wem? – An ihm.</td><td>Niemand zweifelt an der Reproduzierbarkeit.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Womit beschäftigen Sie sich in Ihrer Dissertation? – Ich beschäftige mich mit mikrofluidischer Zellstimulation.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> What are you dealing with in your dissertation? – I deal with microfluidic cell stimulation.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Auf wen warten Sie vor dem Hörsaal? – Ich warte auf den Gastdozenten (Person: auf wen).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Who are you waiting for in front of the lecture hall? – I am waiting for the guest lecturer.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch07-infinitive-clauses" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 07</div>
                <h2 class="ch-heading">Kapitel 7: Infinitivkonstruktionen: Infinitiv mit &#x27;zu&#x27; &amp; Finalsätze (&#x27;um... zu&#x27; vs. &#x27;damit&#x27;)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Der Infinitiv mit &#x27;zu&#x27;:</strong></li><li class="rule-sub-item">Steht nach bestimmten Verben (<em>planen, versuchen, beabsichtigen, hoffen, vergessen, vorschlagen, empfehlen, beschließen, aufhören, anfangen</em>).</li><li class="rule-sub-item">Steht nach unpersönlichen Ausdrücken mit Adjektiven (<em>Es ist wichtig/notwendig/möglich/schwierig, die Parameter zu überwachen</em>).</li><li class="rule-sub-item">Steht nach Nomen mit festem Bezug (<em>keine Zeit/Lust/Möglichkeit/Absicht haben, das Experiment zu wiederholen</em>).</li><li class="rule-sub-item"><em>Position:</em> Das &#x27;zu&#x27; steht direkt vor dem Infinitiv am Satzende; bei trennbaren Verben wird es eingeschoben (<em>ein-zu-schalten, vor-zu-bereiten</em>).</li><li class="rule-header-item"><strong>2. Finalsätze: &#x27;um... zu&#x27; vs. &#x27;damit&#x27;:</strong></li><li class="rule-sub-item"><strong>um ... zu + Infinitiv:</strong> DARF NUR verwendet werden, wenn das Subjekt im Haupt- und Nebensatz <strong>100% IDENTISCH</strong> ist (<em>Ich kalibriere den Sensor [Subjekt: Ich], um präzise Daten zu erhalten [Subjekt: Ich]</em>).</li><li class="rule-sub-item"><strong>damit + Nebensatz (mit finitem Verb am Ende):</strong> MUSS verwendet werden bei <strong>VERSCHIEDENEN Subjekten</strong> (<em>Ich kalibriere den Sensor [Subjekt 1: Ich], damit der Algorithmus [Subjekt 2] fehlerfrei rechnet</em>). Kann auch bei gleichen Subjekten stehen.</li><li class="rule-header-item"><strong>3. Modale Infinitivkonstruktionen:</strong></li><li class="rule-sub-item"><strong>ohne ... zu + Infinitiv:</strong> Negation einer Begleithandlung (<em>Er startete die Pumpe, ohne den Fluss zu prüfen = without checking</em>).</li><li class="rule-sub-item"><strong>(an)statt ... zu + Infinitiv:</strong> Unerwartete Alternative (<em>Wir nutzen humane Zellen, anstatt Tiermodelle einzusetzen = instead of using</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Infinitivkonstruktionen und Subjekt-Bedingungen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Konstruktion</th><th>Subjekt-Bezug</th><th>Syntaktische Struktur</th><th>Musterbeispiel</th></tr></thead>
                        <tbody><tr><td>um ... zu + Infinitiv</td><td>Gleiches Subjekt zwingend</td><td>Hauptsatz + , um ... zu + Inf.</td><td>Wir kühlen die Kammer, um Proteine zu stabilisieren.</td></tr><tr><td>damit + Nebensatz</td><td>Gleiches oder verschiedenes Subj.</td><td>Hauptsatz + , damit Subjekt ... finites Verb.</td><td>Wir kühlen die Kammer, damit die Probe stabil bleibt.</td></tr><tr><td>ohne ... zu + Infinitiv</td><td>Gleiches Subjekt zwingend</td><td>Hauptsatz + , ohne ... zu + Inf.</td><td>Er publizierte die Daten, ohne das Team zu informieren.</td></tr><tr><td>(an)statt ... zu + Inf.</td><td>Gleiches Subjekt zwingend</td><td>Hauptsatz + , anstatt ... zu + Inf.</td><td>Wir nutzen Organchips, anstatt Tierversuche zu machen.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Es ist zwingend erforderlich, die Drucksensoren vor jedem Durchlauf neu zu eichen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> It is imperative to recalibrate the pressure sensors before each run.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir regulieren den pH-Wert automatisch, damit das Gewebe unter physiologischen Bedingungen wächst.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We regulate the pH value automatically so that the tissue grows under physiological conditions.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch08-adverbial-clauses" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 08</div>
                <h2 class="ch-heading">Kapitel 8: Konzessiv-, Temporal-, Kausal- &amp; Konsekutivsätze im B1-Niveau</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Konzessivsätze (Gegengrund / Einräumung):</strong></li><li class="rule-sub-item"><strong>obwohl / obgleich (Subjunktion → Verbletzt):</strong> <em>Obwohl die Flussrate schwankte, blieben die Zellen intakt.</em></li><li class="rule-sub-item"><strong>trotzdem / dennoch (Konjunktionaladverb → Inversion Pos 1/2):</strong> <em>Die Flussrate schwankte, trotzdem blieben die Zellen intakt.</em></li><li class="rule-header-item"><strong>2. Temporale Zeitenfolge bei &#x27;nachdem&#x27;:</strong></li><li class="rule-sub-item">Die Handlung des <em>nachdem</em>-Satzes ist VORZEITIG zur Handlung des Hauptsatzes!</li><li class="rule-sub-item"><em>Hauptsatz im Präsens/Futur:</em> nachdem-Satz im <strong>Perfekt</strong> (<em>Nachdem wir die Lösung gemischt haben, starten wir die Messung</em>).</li><li class="rule-sub-item"><em>Hauptsatz im Präteritum/Perfekt:</em> nachdem-Satz im <strong>Plusquamperfekt</strong> (<em>Nachdem wir die Lösung gemischt hatten, starteten wir die Messung</em>).</li><li class="rule-header-item"><strong>3. Konsekutivsätze (Folge):</strong></li><li class="rule-sub-item"><strong>sodass (Subjunktion → Verbletzt):</strong> <em>Der Druck stieg zu stark an, sodass die Membran riss.</em></li><li class="rule-sub-item"><strong>so ... dass (getrennt):</strong> <em>Der Druck war so hoch, dass die Membran riss.</em></li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Übersicht komplexer Satzverbindungen im B1-Bereich</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Logische Relation</th><th>Subjunktion (Verbletzt)</th><th>Konnektor (Position 1 + Inversion)</th><th>Präposition (Nominalstil)</th></tr></thead>
                        <tbody><tr><td>Konzessiv (Gegengrund)</td><td>obwohl / obgleich</td><td>trotzdem / dennoch</td><td>trotz (+ Genitiv)</td></tr><tr><td>Kausal (Ursache)</td><td>weil / da</td><td>deshalb / darum / daher</td><td>wegen / aufgrund (+ Genitiv)</td></tr><tr><td>Temporal (Vorzeitigkeit)</td><td>nachdem (+ Perfekt/Plusquamperfekt)</td><td>danach / anschließend</td><td>nach (+ Dativ)</td></tr><tr><td>Temporal (Gleichzeitigkeit)</td><td>während / solange</td><td>währenddessen / gleichzeitig</td><td>während (+ Genitiv)</td></tr><tr><td>Konsekutiv (Folge)</td><td>sodass / so ... dass</td><td>infolgedessen / folglich</td><td>infolge (+ Genitiv)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Nachdem die Daten vollständig erhoben worden waren (Plusquamperfekt Passiv), begann das Team mit der statistischen Signifikanzanalyse.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> After the data had been fully collected, the team began the statistical significance analysis.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Obwohl die Synthese sehr komplex ist, liefert sie hochgradig reproduzierbare Polymere.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Although the synthesis is very complex, it yields highly reproducible polymers.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch09-future-tenses" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 09</div>
                <h2 class="ch-heading">Kapitel 9: Futur I &amp; Futur II: Zukunftspläne, Versprechen &amp; Vermutungen</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Futur I (werden + Infinitiv am Satzende):</strong></li><li class="rule-sub-item"><em>Zukunftsbezug:</em> Feste Pläne, Prognosen (<em>Nächstes Jahr werden wir die klinische Phase starten</em>). Hinweis: Im Deutschen wird Zukunft im Alltag meist mit Präsens + Zeitangabe ausgedrückt (<em>Morgen fliege ich nach Berlin</em>).</li><li class="rule-sub-item"><em>Vermutung über die Gegenwart:</em> Kombiniert mit Modalpartikeln (<em>wohl, vermutlich, wahrscheinlich</em>): <em>Er wird wohl im Labor sein = Ich vermute, dass er im Labor ist</em>.</li><li class="rule-sub-item"><em>Aufforderung / Befehl:</em> <em>Du wirst jetzt sofort das Protokoll schreiben!</em></li><li class="rule-header-item"><strong>2. Futur II (werden + Partizip II + haben / sein):</strong></li><li class="rule-sub-item"><em>Abgeschlossene Handlung in der Zukunft:</em> <em>Bis morgen Abend werde ich die Analyse abgeschlossen haben.</em></li><li class="rule-sub-item"><em>Vermutung über die Vergangenheit:</em> <em>Er wird den Sensor wohl falsch kalibriert haben = Ich vermute, dass er ihn falsch kalibriert hat.</em></li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Futur I und Futur II Formen und Funktionen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Zeitform</th><th>Bildungsformel</th><th>Funktion 1 (Zukunft)</th><th>Funktion 2 (Vermutung)</th></tr></thead>
                        <tbody><tr><td>Futur I</td><td>werden (konjugiert) + Infinitiv</td><td>Wir werden das Projekt im Mai beenden.</td><td>Er wird wohl gerade messen. (Gegenwartsvermutung)</td></tr><tr><td>Futur II</td><td>werden + Partizip II + haben/sein</td><td>Bis Freitag werde ich alles erledigt haben.</td><td>Er wird den Fehler übersehen haben. (Vergangenheitsvermutung)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Bis Ende des Quartals werden wir alle toxikologischen Screening-Tests abgeschlossen haben (Futur II).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> By the end of the quarter we will have completed all toxicological screening tests.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Professor Weber ist nicht in seinem Büro; er wird vermutlich bei der Fakultätsratssitzung sein (Vermutung Futur I).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Professor Weber is not in his office; he is probably at the faculty council meeting.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b1-ch10-word-formation" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 10</div>
                <h2 class="ch-heading">Kapitel 10: Wortbildung &amp; Wortschatzerweiterung: Derivation &amp; Komposition</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Komposition (Zusammensetzung):</strong></li><li class="rule-sub-item">Nomen + Nomen (<em>die Zelle + die Kultur = die Zellkultur</em>).</li><li class="rule-sub-item">Verb + Nomen (<em>messen + das Gerät = das Messgerät</em>).</li><li class="rule-sub-item">Adjektiv + Nomen (<em>hoch + die Auflösung = die Hochauflösung</em>).</li><li class="rule-sub-item"><em>Fugenelemente:</em> Oft wird ein <strong>-s-</strong> (<em>das Forschungs-labor</em>), <strong>-en-</strong> (<em>die Studenten-arbeit</em>) oder <strong>-er-</strong> (<em>die Bilder-galerie</em>) eingefügt.</li><li class="rule-header-item"><strong>2. Derivation (Ableitung mit Suffixen):</strong></li><li class="rule-sub-item"><em>Verben zu Nomen:</em> <em>-ung</em> (untersuchen → die Untersuchung), <em>-ion</em> (reagieren → die Reaktion).</li><li class="rule-sub-item"><em>Adjektive zu Nomen:</em> <em>-heit/-keit</em> (sauber → die Sauberkeit, stabil → die Stabilität).</li><li class="rule-sub-item"><em>Nomen zu Adjektiven:</em> <em>-isch</em> (Biologie → biologisch), <em>-lich</em> (Tag → täglich), <em>-los</em> (Fehler → fehlerlos), <em>-voll</em> (Erfolg → erfolgreich).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Wichtige Wortbildungsmuster im wissenschaftlichen Deutsch</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Suffix / Muster</th><th>Basiswortart</th><th>Zielwortart</th><th>Beispiel 1</th><th>Beispiel 2</th></tr></thead>
                        <tbody><tr><td>-ung</td><td>Verb</td><td>Nomen (feminin)</td><td>trennen → die Trennung</td><td>entwickeln → die Entwicklung</td></tr><tr><td>-bar</td><td>Verb</td><td>Adjektiv (Möglichkeit)</td><td>reproduzieren → reproduzierbar</td><td>messen → messbar</td></tr><tr><td>-fähig</td><td>Nomen/Verb</td><td>Adjektiv (Fähigkeit)</td><td>die Differenzierung → differenzierungsfähig</td><td>anpassen → anpassungsfähig</td></tr><tr><td>-arm / -frei</td><td>Nomen</td><td>Adjektiv (Mangel/Freiheit)</td><td>die Keime → keimfrei</td><td>der Sauerstoff → sauerstoffarm</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Differenzierungsfähigkeit (f) der induzierten pluripotenten Stammzellen ist bemerkenswert hoch.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The differentiation capacity of the induced pluripotent stem cells is remarkably high.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir verwenden ausschließlich keimfreie (steril) und endotoxinarme Reagenzien.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We use exclusively sterile and low-endotoxin reagents.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
    </div>

    <div class="level-nav-bar">
        <a href="/deutsch/grammatik/a2/" class="nav-btn">← Stufe A2</a>
        <a href="/deutsch/grammatik/" class="nav-btn" style="background: #ffffff; color: #0284c7; border: 1px solid #0284c7;">📖 Zurück zum 40-Kapitel-Hub</a>
        <a href="/deutsch/grammatik/b2/" class="nav-btn">Stufe B2 →</a>
    </div>
</div>
