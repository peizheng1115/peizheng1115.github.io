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
    padding: 16px 20px;
    margin-bottom: 24px;
}
.rule-box-header {
    font-size: 0.95rem;
    font-weight: 700;
    color: #0369a1;
    margin-bottom: 10px;
    display: flex;
    align-items: center;
    gap: 6px;
}
.rule-list {
    margin: 0;
    padding-left: 20px;
}
.rule-item {
    font-size: 0.96rem;
    line-height: 1.6;
    color: #334155;
    margin-bottom: 8px;
}
.rule-item:last-child {
    margin-bottom: 0;
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
        <h1 class="hero-title">Stufe B1: Mittelstufe I – Komplexe Syntax, Passiv & Irrealis</h1>
        <p class="hero-summary">Mittelstufen-Standard für selbstständige akademische und professionelle Sprachverwendung: Konjunktiv II in Gegenwart & Vergangenheit, irreale Konditionalsätze, Vorgangspassiv in allen 6 Zeitformen, unpersönliches Passiv, Zustandspassiv, Relativsätze (Nom, Akk, Dat, Gen & Präpositionen), Genitiv-Systematik, N-Deklination (Schwache Maskulina), Verben mit festen Präpositionen & Pronominaladverbien, Infinitiv mit zu, Finalsätze (um...zu / damit) und Futur I / II.</p>
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Funktionen des Konjunktiv II:**</li><li class="rule-item">  - *Höfliche Bitten &amp; Diplomatie:* Könnten Sie mir die Daten senden? Ich würde gerne etwas fragen.</li><li class="rule-item">  - *Irreale Wünsche &amp; Träume:* Wenn ich doch bloß mehr Zeit hätte! / Hätte ich doch mehr Zeit!</li><li class="rule-item">  - *Irreale Bedingungen (Konditionalsätze):* Wenn die Flussrate höher wäre, würden die Zellen stärker differenzieren.</li><li class="rule-item">  - *Irreale Vergleiche mit als ob / als wenn:* Er spricht, als ob er der Projektleiter wäre.</li><li class="rule-item">  - *Ratschläge &amp; Empfehlungen:* Du solltest vor der Messung den Sensor kalibrieren.</li><li class="rule-item">**2. Bildung Konjunktiv II der Gegenwart:**</li><li class="rule-item">  - *Allgemeine Form (fast alle Vollverben):* **würde + Infinitiv am Satzende** (*ich würde forschen, du würdest testen, wir würden publizieren*).</li><li class="rule-item">  - *Echte Konjunktiv II Formen (OHNE &#x27;würde&#x27;!):*</li><li class="rule-item">    - **sein:** *wäre, wärest, wäre, wären, wärt, wären*</li><li class="rule-item">    - **haben:** *hätte, hättest, hätte, hätten, hättet, hätten*</li><li class="rule-item">    - **werden:** *würde, würdest, würde, würden, würdet, würden*</li><li class="rule-item">    - **wissen:** *wüsste, wüsstest, wüsste, wüssten, wüsstet, wüssten*</li><li class="rule-item">    - **Starke Verben (Stamm Präteritum + Umlaut + -e):** *kommen -&gt; käme, gehen -&gt; ginge, finden -&gt; fände, bleiben -&gt; bliebe, geben -&gt; gäbe, lassen -&gt; ließe, tun -&gt; täte*.</li><li class="rule-item">**3. Modalverben im Konjunktiv II:**</li><li class="rule-item">  - *können -&gt; könnte, müssen -&gt; müsste, dürfen -&gt; dürfte, sollen -&gt; sollte (kein Umlaut!), wollen -&gt; wollte (kein Umlaut!)*.</li><li class="rule-item">**4. Konjunktiv II der Vergangenheit (Irreale Vergangenheit):**</li><li class="rule-item">  - **hätte / wäre + Partizip II** (*Wenn wir gestern schneller gewesen wären, hätten wir die Messung beendet*).</li><li class="rule-item">  - *Mit Modalverb in der Vergangenheit:* **hätte + Doppelinfinitiv** (*Wir hätten die Probe kühlen müssen*).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Das Grundprinzip:** Im Passiv steht die Handlung (der Vorgang) im Mittelpunkt; der Handelnde ist unwichtig, unbekannt oder allgemein.</li><li class="rule-item">**2. Transformation Aktiv -&gt; Passiv:**</li><li class="rule-item">  - *Aktiv-Akkusativobjekt* wird zum *Passiv-Subjekt im Nominativ*.</li><li class="rule-item">  - *Aktiv-Subjekt* wird optional zur *Präpositionalphrase:* **von + Dativ** (handelnde Person, Urheber) oder **durch + Akkusativ** (Mittel, Ursache, Instrument).</li><li class="rule-item">**3. Die 6 Zeitformen des Vorgangspassivs:**</li><li class="rule-item">  - *Präsens:* **wird + Partizip II** (*Die Probe wird zentrifugiert*).</li><li class="rule-item">  - *Präteritum:* **wurde + Partizip II** (*Die Probe wurde zentrifugiert*).</li><li class="rule-item">  - *Perfekt:* **ist + Partizip II + worden** (Beachte: *worden*, NICHT *geworden*!).</li><li class="rule-item">  - *Plusquamperfekt:* **war + Partizip II + worden** (*Die Probe war zentrifugiert worden*).</li><li class="rule-item">  - *Futur I:* **wird + Partizip II + werden** (*Die Probe wird zentrifugiert werden*).</li><li class="rule-item">  - *Futur II:* **wird + Partizip II + worden sein** (*Die Probe wird zentrifugiert worden sein*).</li><li class="rule-item">**4. Passiv mit Modalverben:**</li><li class="rule-item">  - *Präsens:* **Modalverb (konjugiert) + ... + Partizip II + werden (Infinitiv)** (*Die Durchflussrate muss kontrolliert werden*).</li><li class="rule-item">  - *Präteritum:* **Modalverb Präteritum + ... + Partizip II + werden** (*Die Durchflussrate musste kontrolliert werden*).</li><li class="rule-item">**5. Unpersönliches Passiv (Passiv ohne Subjekt):**</li><li class="rule-item">  - Intransitive Verben können ein Passiv ohne Subjekt bilden (*Im Labor wird nicht geraucht; Es wurde lange über das Ergebnis diskutiert*).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Vorgangspassiv vs. Zustandspassiv:**</li><li class="rule-item">  - *Vorgangspassiv (werden + P.II):* Betont den dynamischen Ablauf, die Aktion oder Veränderung (*Das Labor wird um 18:00 Uhr geschlossen* = Jemand schließt die Tür).</li><li class="rule-item">  - *Zustandspassiv (sein + P.II):* Betont den statischen Zustand nach Abschluss der Handlung (*Das Labor ist geschlossen* = Die Tür ist zu).</li><li class="rule-item">**2. Bildung des Zustandspassivs in den Zeitformen:**</li><li class="rule-item">  - *Präsens:* **sein (konjugiert) + Partizip II** (*Die Proben sind sterilisiert*).</li><li class="rule-item">  - *Präteritum:* **war + Partizip II** (*Die Proben waren bereits sterilisiert*).</li><li class="rule-item">  - *Perfekt:* **ist + Partizip II + gewesen** (*Die Proben sind sterilisiert gewesen*).</li><li class="rule-item">  - *Futur I:* **wird + Partizip II + sein** (*Morgen um 8 Uhr wird alles vorbereitet sein*).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Kongruenz und Kasus des Relativpronomens:**</li><li class="rule-item">  - **Genus &amp; Numerus** richten sich nach dem Bezugswort im Hauptsatz (*der Forscher -&gt; Maskulin Singular*).</li><li class="rule-item">  - **Kasus** richtet sich nach der syntaktischen Funktion im Relativsatz (*Subjekt -&gt; Nominativ; Objekt -&gt; Akkusativ/Dativ/Genitiv*).</li><li class="rule-item">**2. Die Formen des Relativpronomens:** Entsprechen dem bestimmten Artikel bis auf zwei Ausnahmen:</li><li class="rule-item">  - *Dativ Plural:* **denen** (nicht &#x27;den&#x27;).</li><li class="rule-item">  - *Genitiv:* **dessen** (Mask./Neutr.) / **deren** (Fem./Plur.).</li><li class="rule-item">**3. Relativsätze mit Präpositionen:**</li><li class="rule-item">  - Die Präposition steht DIREKT vor dem Relativpronomen und bestimmt dessen Kasus (*das Modell, [auf dem: Dat] wir die Versuche basieren; der Kollege, [ohne den: Akk] das Projekt nicht möglich gewesen wäre*).</li><li class="rule-item">**4. Freie / Indefinite Relativsätze mit &#x27;was&#x27;, &#x27;wo&#x27;, &#x27;wohin&#x27;, &#x27;woher&#x27;:**</li><li class="rule-item">  - Eingeleitet durch *was* nach neutralen Indefinitpronomen (*alles, nichts, vieles, einiges, das Beste*): *Das ist alles, was wir wissen*.</li><li class="rule-item">  - Eingeleitet durch *was* bei Bezug auf den gesamten vorangehenden Satz (*Wir gewannen den Preis, was uns alle sehr freute*).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Formen des Genitivs:**</li><li class="rule-item">  - *Maskulin &amp; Neutrum:* **des / eines / meines / keines + Nomenendung (-s / -es)**.</li><li class="rule-item">  - *Feminin &amp; Plural:* **der / einer / meiner / keiner (OHNE Nomenendung!)**.</li><li class="rule-item">**2. Wann -s und wann -es bei Maskulina &amp; Neutra?**</li><li class="rule-item">  - **-es (Zwingend):** Bei einsilbigen Wörtern (*des Mannes, des Tages, des Jahres, des Glases*) und nach Zischlauten *-s, -ß, -z, -x, -sch, -tz* (*des Flusses, des Gesetzes, des Reflexes*).</li><li class="rule-item">  - **-s:** Bei mehrsilbigen Wörtern auf unbetonte Endungen *-el, -er, -en, -chen, -lein, -ment, -ling, -or* (*des Computers, des Experiments, des Lehrlings*).</li><li class="rule-item">**3. Die N-Deklination (Schwache maskuline Substantive):**</li><li class="rule-item">  - Diese Maskulina erhalten in ALLEN Kasus außer dem Nominativ Singular die Endung **-(e)n**!</li><li class="rule-item">  - *Gruppe A (Endung auf -e):* *der Kollege (des Kollegen), der Biologe, der Kunde, der Zeuge, der Experte, der Junge, der Nachbar*.</li><li class="rule-item">  - *Gruppe B (Fremdwörter mit betonter Endung):* *-ant, -ent, -ist, -at, -et, -oge, -nom, -soph, -graf* (*der Student, der Doktorand, der Assistent, der Spezialist, der Philosoph, der Fotograf*).</li><li class="rule-item">  - *Sonderform mit -ns im Genitiv:* *der Name (des Namens), der Gedanke (des Gedankens), der Buchstabe (des Buchstabens), der Wille (des Willens)* sowie *das Herz (des Herzens, dem Herzen, das Herz)*.</li><li class="rule-item">**4. Genitiv-Präpositionen im B1/B2-Bereich:**</li><li class="rule-item">  - *während* (während des Versuchs), *wegen* (wegen des Ausfalls), *trotz* (trotz der hohen Kosten), *(an)statt* (anstatt des Standardverfahrens), *innerhalb* (innerhalb eines Tages), *außerhalb* (außerhalb der Sprechzeiten), *aufgrund* (aufgrund neuer Daten), *infolge* (infolge der Reaktion).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Präpositionalobjekte:** Viele Verben sind fest an eine bestimmte Präposition gekoppelt, die ihren Kasus bestimmt.</li><li class="rule-item">**2. Pronominaladverbien (NUR bei Sachen / Konzepten):**</li><li class="rule-item">  - **Aussage / Pronomen:** *da + Präposition* (Beginnt die Präposition mit Vokal -&gt; Einschub von *-r-*: *dar-auf, dar-an, dar-über, dar-unter, dar-in, da-mit, da-für, da-von, da-zu*).</li><li class="rule-item">  - **Frageform:** *wo + Präposition* (Beginnt die Präposition mit Vokal -&gt; Einschub von *-r-*: *wor-auf, wor-an, wor-über, wor-unter, wo-mit, wo-für, wo-von, wo-zu*).</li><li class="rule-item">**3. Personenreferenz (NIEMALS da-/wo- bei Personen!):**</li><li class="rule-item">  - Bei Personen wird die reguläre Präposition mit dem Personalpronomen kombiniert (*Ich warte auf meinen Professor -&gt; Auf wen wartest du? -&gt; Ich warte auf ihn!*).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Der Infinitiv mit &#x27;zu&#x27;:**</li><li class="rule-item">  - Steht nach bestimmten Verben (*planen, versuchen, beabsichtigen, hoffen, vergessen, vorschlagen, empfehlen, beschließen, aufhören, anfangen*).</li><li class="rule-item">  - Steht nach unpersönlichen Ausdrücken mit Adjektiven (*Es ist wichtig/notwendig/möglich/schwierig, die Parameter zu überwachen*).</li><li class="rule-item">  - Steht nach Nomen mit festem Bezug (*keine Zeit/Lust/Möglichkeit/Absicht haben, das Experiment zu wiederholen*).</li><li class="rule-item">  - *Position:* Das &#x27;zu&#x27; steht direkt vor dem Infinitiv am Satzende; bei trennbaren Verben wird es eingeschoben (*ein-zu-schalten, vor-zu-bereiten*).</li><li class="rule-item">**2. Finalsätze: &#x27;um... zu&#x27; vs. &#x27;damit&#x27;:**</li><li class="rule-item">  - **um ... zu + Infinitiv:** DARF NUR verwendet werden, wenn das Subjekt im Haupt- und Nebensatz **100% IDENTISCH** ist (*Ich kalibriere den Sensor [Subjekt: Ich], um präzise Daten zu erhalten [Subjekt: Ich]*).</li><li class="rule-item">  - **damit + Nebensatz (mit finitem Verb am Ende):** MUSS verwendet werden bei **VERSCHIEDENEN Subjekten** (*Ich kalibriere den Sensor [Subjekt 1: Ich], damit der Algorithmus [Subjekt 2] fehlerfrei rechnet*). Kann auch bei gleichen Subjekten stehen.</li><li class="rule-item">**3. Modale Infinitivkonstruktionen:**</li><li class="rule-item">  - **ohne ... zu + Infinitiv:** Negation einer Begleithandlung (*Er startete die Pumpe, ohne den Fluss zu prüfen = without checking*).</li><li class="rule-item">  - **(an)statt ... zu + Infinitiv:** Unerwartete Alternative (*Wir nutzen humane Zellen, anstatt Tiermodelle einzusetzen = instead of using*).</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Konzessivsätze (Gegengrund / Einräumung):**</li><li class="rule-item">  - **obwohl / obgleich (Subjunktion -&gt; Verbletzt):** *Obwohl die Flussrate schwankte, blieben die Zellen intakt.*</li><li class="rule-item">  - **trotzdem / dennoch (Konjunktionaladverb -&gt; Inversion Pos 1/2):** *Die Flussrate schwankte, trotzdem blieben die Zellen intakt.*</li><li class="rule-item">**2. Temporale Zeitenfolge bei &#x27;nachdem&#x27;:**</li><li class="rule-item">  - Die Handlung des *nachdem*-Satzes ist VORZEITIG zur Handlung des Hauptsatzes!</li><li class="rule-item">  - *Hauptsatz im Präsens/Futur:* nachdem-Satz im **Perfekt** (*Nachdem wir die Lösung gemischt haben, starten wir die Messung*).</li><li class="rule-item">  - *Hauptsatz im Präteritum/Perfekt:* nachdem-Satz im **Plusquamperfekt** (*Nachdem wir die Lösung gemischt hatten, starteten wir die Messung*).</li><li class="rule-item">**3. Konsekutivsätze (Folge):**</li><li class="rule-item">  - **sodass (Subjunktion -&gt; Verbletzt):** *Der Druck stieg zu stark an, sodass die Membran riss.*</li><li class="rule-item">  - **so ... dass (getrennt):** *Der Druck war so hoch, dass die Membran riss.*</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Futur I (werden + Infinitiv am Satzende):**</li><li class="rule-item">  - *Zukunftsbezug:* Feste Pläne, Prognosen (*Nächstes Jahr werden wir die klinische Phase starten*). Hinweis: Im Deutschen wird Zukunft im Alltag meist mit Präsens + Zeitangabe ausgedrückt (*Morgen fliege ich nach Berlin*).</li><li class="rule-item">  - *Vermutung über die Gegenwart:* Kombiniert mit Modalpartikeln (*wohl, vermutlich, wahrscheinlich*): *Er wird wohl im Labor sein = Ich vermute, dass er im Labor ist*.</li><li class="rule-item">  - *Aufforderung / Befehl:* *Du wirst jetzt sofort das Protokoll schreiben!*</li><li class="rule-item">**2. Futur II (werden + Partizip II + haben / sein):**</li><li class="rule-item">  - *Abgeschlossene Handlung in der Zukunft:* *Bis morgen Abend werde ich die Analyse abgeschlossen haben.*</li><li class="rule-item">  - *Vermutung über die Vergangenheit:* *Er wird den Sensor wohl falsch kalibriert haben = Ich vermute, dass er ihn falsch kalibriert hat.*</li></ul></div>
                
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
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Komposition (Zusammensetzung):**</li><li class="rule-item">  - Nomen + Nomen (*die Zelle + die Kultur = die Zellkultur*).</li><li class="rule-item">  - Verb + Nomen (*messen + das Gerät = das Messgerät*).</li><li class="rule-item">  - Adjektiv + Nomen (*hoch + die Auflösung = die Hochauflösung*).</li><li class="rule-item">  - *Fugenelemente:* Oft wird ein **-s-** (*das Forschungs-labor*), **-en-** (*die Studenten-arbeit*) oder **-er-** (*die Bilder-galerie*) eingefügt.</li><li class="rule-item">**2. Derivation (Ableitung mit Suffixen):**</li><li class="rule-item">  - *Verben zu Nomen:* *-ung* (untersuchen -&gt; die Untersuchung), *-ion* (reagieren -&gt; die Reaktion).</li><li class="rule-item">  - *Adjektive zu Nomen:* *-heit/-keit* (sauber -&gt; die Sauberkeit, stabil -&gt; die Stabilität).</li><li class="rule-item">  - *Nomen zu Adjektiven:* *-isch* (Biologie -&gt; biologisch), *-lich* (Tag -&gt; täglich), *-los* (Fehler -&gt; fehlerlos), *-voll* (Erfolg -&gt; erfolgreich).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Wichtige Wortbildungsmuster im wissenschaftlichen Deutsch</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Suffix / Muster</th><th>Basiswortart</th><th>Zielwortart</th><th>Beispiel 1</th><th>Beispiel 2</th></tr></thead>
                        <tbody><tr><td>-ung</td><td>Verb</td><td>Nomen (feminin)</td><td>trennen -&gt; die Trennung</td><td>entwickeln -&gt; die Entwicklung</td></tr><tr><td>-bar</td><td>Verb</td><td>Adjektiv (Möglichkeit)</td><td>reproduzieren -&gt; reproduzierbar</td><td>messen -&gt; messbar</td></tr><tr><td>-fähig</td><td>Nomen/Verb</td><td>Adjektiv (Fähigkeit)</td><td>die Differenzierung -&gt; differenzierungsfähig</td><td>anpassen -&gt; anpassungsfähig</td></tr><tr><td>-arm / -frei</td><td>Nomen</td><td>Adjektiv (Mangel/Freiheit)</td><td>die Keime -&gt; keimfrei</td><td>der Sauerstoff -&gt; sauerstoffarm</td></tr></tbody>
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
