---
layout: single
title: "Stufe B2: Mittelstufe II – Gehobene Wissenschafts- & Fachsprache"
permalink: /deutsch/grammatik/b2/
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
        <span class="hero-badge">CEFR B2 Fortgeschritten</span>
        <h1 class="hero-title">Stufe B2: Mittelstufe II – Gehobene Wissenschafts- &amp; Fachsprache</h1>
        <p class="hero-summary">Die Meisterschaft des akademischen und publizistischen Ausdrucks: 30+ Nomen-Verb-Verbindungen (Funktionsverbgefüge / FVG), Passiv-Ersatzformen (sein+zu, sich lassen, -bar/-lich), erweiterte Partizipialattribute &amp; Gerundivum, zweiteilige Konnektoren (Doppelkonjunktionen), epistemische / subjektive Modalverben (Gewissheit, Gerüchte, Distanzierung), systematischer Nominalstil vs. Verbalstil, Konjunktiv I (Indirekte Rede), Modalpartikeln und wissenschaftliche Textkohärenz.</p>
        <div class="hero-actions">
            <a href="/deutsch/grammatik/" class="action-btn">📚 Grammatik-Hub</a>
            <a href="/files/Deutsch_Grammatik_B2.md" class="action-btn" download>📥 Download Markdown</a>
            <a href="/deutsch/" class="action-btn">🇩🇪 Deutsch Portal</a>
        </div>
    </div>

    <nav class="toc-bar" aria-label="Kapitel-Navigation">
        <div class="toc-bar-title">⚡ Schnellnavigation durch alle 10 Kapitel (B2):</div>
        <div class="toc-grid">
            <a href="#b2-ch01-fvg" class="toc-pill">Kapitel 1</a><a href="#b2-ch02-passiv-alternatives" class="toc-pill">Kapitel 2</a><a href="#b2-ch03-participles" class="toc-pill">Kapitel 3</a><a href="#b2-ch04-connectors" class="toc-pill">Kapitel 4</a><a href="#b2-ch05-subjective-modals" class="toc-pill">Kapitel 5</a><a href="#b2-ch06-nominalstil" class="toc-pill">Kapitel 6</a><a href="#b2-ch07-konjunktiv1" class="toc-pill">Kapitel 7</a><a href="#b2-ch08-modalpartikeln" class="toc-pill">Kapitel 8</a><a href="#b2-ch09-noun-preposition" class="toc-pill">Kapitel 9</a><a href="#b2-ch10-text-coherence" class="toc-pill">Kapitel 10</a>
        </div>
    </nav>

    <div class="chapters-wrapper">
        
        <article id="b2-ch01-fvg" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 01</div>
                <h2 class="ch-heading">Kapitel 1: Nomen-Verb-Verbindungen (Funktionsverbgefüge / FVG)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Was ist ein Funktionsverbgefüge (FVG)?</strong></li><li class="rule-sub-item">Eine feste Verbindung aus einem Nomen (oft mit Präposition) und einem Funktionsverb (<em>ein Urteil fällen = urteilen; zur Verfügung stellen = bereitstellen</em>).</li><li class="rule-sub-item">Das Nomen trägt die eigentliche semantische Bedeutung; das Verb verblasst und dient primär als grammatikalischer Träger von Person, Tempus und Modus.</li><li class="rule-header-item"><strong>2. Warum FVG in der Wissenschaft?</strong></li><li class="rule-sub-item">Ermöglicht präzise <strong>Aktionsarten</strong> (Beginn, Dauer, Verursachung), die ein einfaches Verb nicht abbilden kann.</li><li class="rule-sub-item">Erlaubt elegante Aktiv-/Passiv-Differenzierungen (<em>zur Verfügung stellen [aktiv]</em> vs. <em>zur Verfügung stehen [passiv/Zustand]</em>).</li><li class="rule-sub-item">Verleiht Fachtexten einen hochgradig sachlichen, prägnanten und professionellen Ton.</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Die 30 wichtigsten wissenschaftlichen und professionellen FVG-Ausdrücke</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Funktionsverbgefüge</th><th>Präp. &amp; Kasus</th><th>Einfaches Verb / Synonym</th><th>Aktionsart / Modus</th><th>Wissenschaftlicher Beispielsatz</th></tr></thead>
                        <tbody><tr><td>zur Verfügung stehen</td><td>Dativ</td><td>verfügbar sein</td><td>Passivisch / Zustand</td><td>Die Rohdaten stehen der Forschungsgemeinschaft zur Verfügung.</td></tr><tr><td>zur Verfügung stellen</td><td>Dativ</td><td>bereitstellen</td><td>Aktiv / Kausativ</td><td>Das Institut stellt uns die Rechenkapazitäten zur Verfügung.</td></tr><tr><td>in Betracht / Erwägung ziehen</td><td>—</td><td>berücksichtigen</td><td>Kausativ (überlegen)</td><td>Wir müssen alternative Zelllinien in Betracht ziehen.</td></tr><tr><td>in Kraft treten</td><td>—</td><td>wirksam werden</td><td>Inchoativ (Beginn)</td><td>Die neue Laborordnung tritt ab 1. Oktober in Kraft.</td></tr><tr><td>zur Anwendung kommen / bringen</td><td>—</td><td>angewendet werden / anwenden</td><td>Passiv / Aktiv</td><td>Diese Methode kommt bei toxikologischen Tests zur Anwendung.</td></tr><tr><td>eine Entscheidung treffen</td><td>—</td><td>sich entscheiden</td><td>Kausativ</td><td>Das Review-Board muss über den Förderantrag eine Entscheidung treffen.</td></tr><tr><td>Kritik üben an</td><td>Dativ</td><td>kritisieren</td><td>Aktiv</td><td>Die Fachgutachter übten konstruktive Kritik an der Kontrollgruppe.</td></tr><tr><td>unter Beweis stellen</td><td>—</td><td>beweisen</td><td>Kausativ</td><td>Der Sensor hat seine Zuverlässigkeit unter Beweis gestellt.</td></tr><tr><td>zur Folge haben</td><td>—</td><td>verursachen / bewirken</td><td>Kausal</td><td>Ein osmotischer Schock hat das Platzen der Zellen zur Folge.</td></tr><tr><td>in Frage kommen</td><td>—</td><td>möglich / relevant sein</td><td>Möglichkeit</td><td>Für dieses Modell kommen primäre Hepatozyten in Frage.</td></tr><tr><td>Bezug nehmen auf</td><td>Akkusativ</td><td>sich beziehen auf</td><td>Verweisend</td><td>In der Diskussion nehmen wir Bezug auf frühere Veröffentlichungen.</td></tr><tr><td>in Anspruch nehmen</td><td>—</td><td>beanspruchen / nutzen</td><td>Durativ</td><td>Die FEM-Simulation nimmt erhebliche Rechenzeit in Anspruch.</td></tr><tr><td>einen Beitrag leisten zu</td><td>Dativ</td><td>beitragen zu</td><td>Kausativ</td><td>Organ-on-a-Chip leistet einen wesentlichen Beitrag zur 3R-Strategie.</td></tr><tr><td>zum Abschluss bringen</td><td>—</td><td>abschließen</td><td>Kausativ (Beenden)</td><td>Wir bringen das Teilprojekt im vierten Quartal zum Abschluss.</td></tr><tr><td>im Vordergrund stehen</td><td>—</td><td>am wichtigsten sein</td><td>Fokussierend</td><td>Die biologische Relevanz der Messdaten steht im Vordergrund.</td></tr><tr><td>Einfluss ausüben auf</td><td>Akkusativ</td><td>beeinflussen</td><td>Kausal</td><td>Scherkräfte üben einen starken Einfluss auf die Zellmorphologie aus.</td></tr><tr><td>in Gang setzen</td><td>—</td><td>starten / initiieren</td><td>Inchoativ (Start)</td><td>Der Wachstumsfaktor setzt eine komplexe Signalkaskade in Gang.</td></tr><tr><td>in Kauf nehmen</td><td>—</td><td>akzeptieren (Nachteil)</td><td>Konzessiv</td><td>Wir müssen einen leichten Signalverlust in Kauf nehmen.</td></tr><tr><td>Stellung nehmen zu</td><td>Dativ</td><td>seine Meinung äußern</td><td>Diskursiv</td><td>Die Autoren nehmen zu den Einwänden der Gutachter Stellung.</td></tr><tr><td>im Widerspruch stehen zu</td><td>Dativ</td><td>widersprechen</td><td>Kontrastiv</td><td>Dieser Befund steht im Widerspruch zu publizierten Daten.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Das Forschungsteam zog mehrere biokompatible Hydrogele in Betracht (berücksichtigte), um die Zelladhäsion zu optimieren.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The research team took several biocompatible hydrogels into account in order to optimize cell adhesion.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die neu entwickelte Methode stellte ihre Überlegenheit gegenüber konventionellen Assays eindrucksvoll unter Beweis (bewies).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The newly developed method impressively proved its superiority over conventional assays.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch02-passiv-alternatives" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 02</div>
                <h2 class="ch-heading">Kapitel 2: Passiv-Ersatzformen &amp; Modale Passivumschreibungen</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-item"><strong>1. Warum Passiv-Ersatzformen?</strong> Häufungen des Vorgangspassivs mit <em>werden</em> wirken monoton. Ersatzformen bringen Abwechslung und drücken gleichzeitig modale Nuancen (Können / Müssen) aus.</li><li class="rule-header-item"><strong>2. Die wichtigsten Konstruktionen im Überblick:</strong></li><li class="rule-header-item"><strong>sein + zu + Infinitiv:</strong></li><li class="rule-sub-item"><em>Bedeutung A (Pflicht/Notwendigkeit = muss/soll getan werden):</em> <em>Das Protokoll ist strikt einzuhalten = Das Protokoll muss eingehalten werden.</em></li><li class="rule-sub-item"><em>Bedeutung B (Möglichkeit = kann getan werden):</em> <em>Der Fehler ist leicht zu beheben = Der Fehler kann leicht behoben werden.</em></li><li class="rule-header-item"><strong>sich lassen + Infinitiv (Immer Möglichkeit = kann getan werden):</strong></li><li class="rule-sub-item"><em>Die Hypothese lässt sich experimentell verifizieren = Die Hypothese kann verifiziert werden.</em></li><li class="rule-header-item"><strong>Adjektive auf -bar / -lich / -abel / -ibel (Möglichkeit = kann getan werden):</strong></li><li class="rule-sub-item"><em>reproduzierbar (kann reproduziert werden), messbar (kann gemessen werden), erklärlich (kann erklärt werden), filtrierbar, praktikabel</em>.</li><li class="rule-header-item"><strong>es gilt + zu + Infinitiv (Drängende Notwendigkeit = man muss):</strong></li><li class="rule-sub-item"><em>Es gilt, die Fehlerquellen systematisch zu eliminieren.</em></li><li class="rule-header-item"><strong>bleiben / stehen + zu + Infinitiv:</strong></li><li class="rule-sub-item"><em>Es bleibt abzuwarten, wie das Gewebe reagiert (= Man muss abwarten).</em></li><li class="rule-header-item"><strong>gehören + Partizip II (Umgangssprachlich für müssen):</strong></li><li class="rule-sub-item"><em>Das gehört gründlich überprüft (= Das muss überprüft werden).</em></li><li class="rule-sub-item"><strong>man + Aktiv-Verb:</strong> <em>Man beobachtet eine Zunahme = Eine Zunahme wird beobachtet.</em></li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Passiv-Ersatzformen Transformations-Matrix</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Passiv-Ersatzform</th><th>Modale Grundbedeutung</th><th>Vorgangspassiv-Äquivalent</th><th>Fachsprachliches Beispiel</th></tr></thead>
                        <tbody><tr><td>sein + zu + Infinitiv</td><td>müssen / sollen</td><td>muss getan werden</td><td>Die Proben sind bei -80°C zu lagern.</td></tr><tr><td>sein + zu + Infinitiv</td><td>können</td><td>kann getan werden</td><td>Die Ergebnisse sind leicht zu reproduzieren.</td></tr><tr><td>sich lassen + Infinitiv</td><td>können (Möglichkeit)</td><td>kann getan werden</td><td>Das Transmembranpotential lässt sich in Echtzeit messen.</td></tr><tr><td>Adjektiv auf -bar</td><td>können</td><td>kann getan werden</td><td>Die Zellviabilität ist optisch quantifizierbar.</td></tr><tr><td>es gilt + zu + Infinitiv</td><td>müssen / höchste Priorität</td><td>muss getan werden</td><td>Im nächsten Schritt gilt es, die Flussstabilität zu sichern.</td></tr><tr><td>Zustandspassiv (sein + P.II)</td><td>Zustand nach Abschluss</td><td>ist getan worden</td><td>Die Flusskammer ist vollständig entlüftet.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die ermittelten Scherspannungswerte lassen sich durch eine feinere Kanalgeometrie weiter präzisieren (= können präzisiert werden).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The determined shear stress values can be further refined through a finer channel geometry.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Alle Sicherheitsvorschriften sind ausnahmslos zu befolgen (= müssen befolgt werden).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> All safety regulations are to be followed without exception.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch03-participles" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 03</div>
                <h2 class="ch-heading">Kapitel 3: Erweiterte Partizipialattribute (Partizip I, II &amp; Gerundivum)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Partizip I als Adjektiv (Partizip Präsens: Verbstamm + -end):</strong></li><li class="rule-sub-item"><em>Semantik:</em> Aktivisch und <strong>gleichzeitig</strong> zum Hauptsatzgeschehen (<em>das strömende Fluid = das Fluid, das strömt</em>).</li><li class="rule-sub-item">Wird wie ein reguläres Adjektiv nach Kasus, Genus und Numerus dekliniert (<em>des strömend-en Fluids, mit strömend-em Fluid</em>).</li><li class="rule-header-item"><strong>2. Partizip II als Adjektiv (Partizip Perfekt: ge-...-t / ge-...-en):</strong></li><li class="rule-sub-item"><em>Semantik bei transitiven Verben:</em> Passivisch und <strong>vorzeitig/abgeschlossen</strong> (<em>die publizierten Daten = Daten, die publiziert wurden</em>).</li><li class="rule-sub-item"><em>Semantik bei intransitiven Verben mit sein:</em> Aktivisch und abgeschlossen (<em>die eingetroffenen Gutachter = Gutachter, die eingetroffen sind</em>).</li><li class="rule-header-item"><strong>3. Das Gerundivum (zu + Partizip I als Adjektiv):</strong></li><li class="rule-sub-item"><em>Bildung:</em> <strong>zu + Verbstamm + -end + Adjektivendung</strong> (<em>die zu lösende Aufgabe</em>).</li><li class="rule-sub-item"><em>Semantik:</em> Drückt eine <strong>passivische Notwendigkeit (müssen)</strong> oder <strong>Möglichkeit (können)</strong> aus (<em>die zu berücksichtigenden Parameter = Parameter, die berücksichtigt werden müssen</em>).</li><li class="rule-header-item"><strong>4. Erweiterte Partizipialattribute (Schachtelsatz / Linksverzweigung):</strong></li><li class="rule-sub-item"><em>Struktur:</em> [Artikel] ... [Adverbiale Bestimmungen + Partizip] ... [Nomen].</li><li class="rule-sub-item"><em>Beispiel:</em> Die [von der Forschungsgruppe im vergangenen Jahr unter Reinraumbedingungen <strong>synthetisierten</strong>] Nanopartikel zeigen hohe Stabilität.</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Partizipialkonstruktionen und ihre Rückverwandlung in Relativsätze</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Partizip-Typ</th><th>Erweitertes Partizipialattribut</th><th>Auflösung in vollständigen Relativsatz</th><th>Semantischer Gehalt</th></tr></thead>
                        <tbody><tr><td>Partizip I (aktiv, gleichzeitig)</td><td>das kontinuierlich durch den Mikrokanal fließende Medium</td><td>das Medium, das kontinuierlich durch den Mikrokanal fließt</td><td>Prozess läuft parallel zur Haupthandlung</td></tr><tr><td>Partizip II (passiv, vorzeitig)</td><td>die im Vorfeld sorgfältig kalibrierten Drucksensoren</td><td>die Drucksensoren, die im Vorfeld sorgfältig kalibriert wurden</td><td>Vorgang ist vor der Haupthandlung abgeschlossen</td></tr><tr><td>Gerundivum (zu + Partizip I)</td><td>die bei der nächsten Sitzung zu diskutierenden Resultate</td><td>die Resultate, die bei der nächsten Sitzung diskutiert werden müssen</td><td>Passivische Notwendigkeit / Pflicht (müssen)</td></tr><tr><td>Partizip II (intransitiv, sein)</td><td>die im Inkubator schnell gewachsenen Zellen</td><td>die Zellen, die im Inkubator schnell gewachsen sind</td><td>Abgeschlossene Zustandsänderung (aktiv)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die in der Fachzeitschrift &#x27;Nature Biomedical Engineering&#x27; publizierten Ergebnisse stießen auf weltweite Beachtung.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The results published in the journal &#x27;Nature Biomedical Engineering&#x27; met with worldwide attention.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die bei der Auswertung einzuhaltenden statistischen Schwellenwerte (Gerundivum) sind im Protokoll definiert.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The statistical threshold values to be complied with during evaluation are defined in the protocol.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch04-connectors" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 04</div>
                <h2 class="ch-heading">Kapitel 4: Zweiteilige Konnektoren (Doppelkonjunktionen)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Kopulativ (Aufzählend / Verbindend):</strong></li><li class="rule-sub-item"><strong>sowohl ... als auch (Gleichwertig positiv = und):</strong> <em>Das Modell ist sowohl kostengünstig als auch präzise.</em> (KEIN Komma!).</li><li class="rule-sub-item"><strong>nicht nur ... sondern auch (Steigernd positiv):</strong> <em>Wir analysierten nicht nur die Zellmorphologie, sondern auch die Genexpression.</em> (Komma vor <em>sondern</em>!).</li><li class="rule-header-item"><strong>2. Negativ (Aufzählend verneinend):</strong></li><li class="rule-sub-item"><strong>weder ... noch (Doppelte Verneinung = weder A noch B):</strong> <em>Das System zeigte weder Rauschen noch Signalverlust.</em> (KEIN Komma!).</li><li class="rule-header-item"><strong>3. Disjunktiv (Alternative):</strong></li><li class="rule-sub-item"><strong>entweder ... oder (Ausschließendes Oder):</strong> <em>Wir müssen entweder den Druck senken oder die Membran verstärken.</em></li><li class="rule-header-item"><strong>4. Konzessiv / Adversativ (Einschränkung / Gegensatz):</strong></li><li class="rule-sub-item"><strong>zwar ... aber / jedoch (Einräumung):</strong> <em>Die Methode ist zwar rechenintensiv, aber hochgradig verlässlich.</em> (Komma vor <em>aber</em>!).</li><li class="rule-sub-item"><strong>einerseits ... andererseits:</strong> <em>Einerseits sinken die Kosten, andererseits steigt der Entwicklungsaufwand.</em></li><li class="rule-header-item"><strong>5. Proportional (Vergleich von Steigerungen):</strong></li><li class="rule-header-item"><strong>je + Komparativ (Nebensatz → Verbletzt) ... desto / umso + Komparativ (Hauptsatz → finite Verb direkt danach!):</strong></li><li class="rule-sub-item"><em>Formel:</em> Je [Komparativ] ... [Verb am Ende], desto [Komparativ] [finites Verb] [Subjekt]...</li><li class="rule-sub-item"><em>Beispiel:</em> <strong>Je höher</strong> der angelegte Scherstress <strong>ist</strong>, <strong>desto stärker richten</strong> sich die Endothelzellen in Flussrichtung <strong>aus</strong>.</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Zweiteilige Konnektoren Übersicht: Syntax, Komma &amp; Funktion</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Konnektor-Paar</th><th>Logische Beziehung</th><th>Kommaregel</th><th>Musterbeispiel mit korrekter Wortstellung</th></tr></thead>
                        <tbody><tr><td>sowohl ... als auch</td><td>Reihend positiv (A + B)</td><td>Kein Komma</td><td>Die Biochips sind sowohl biokompatibel als auch optisch hochtransparent.</td></tr><tr><td>nicht nur ... sondern auch</td><td>Steigernd positiv</td><td>Komma vor sondern</td><td>Die Therapie hemmt nicht nur die Entzündung, sondern regt auch die Gewebeneubildung an.</td></tr><tr><td>weder ... noch</td><td>Reihend negativ (weder A noch B)</td><td>Kein Komma</td><td>Das Experiment zeigte weder Abweichungen noch toxische Begleiterscheinungen.</td></tr><tr><td>entweder ... oder</td><td>Alternative (A oder B)</td><td>Meist kein Komma</td><td>Wir kultivieren entweder primäre Endothelzellen oder iPSC-differenzierte Linien.</td></tr><tr><td>zwar ... aber</td><td>Konzessiv einschränkend</td><td>Komma vor aber</td><td>Die Anschaffung ist zwar kostspielig, aber die Amortisation erfolgt binnen eines Jahres.</td></tr><tr><td>je ... desto / umso</td><td>Proportionale Steigerung</td><td>Komma nach je-Satz</td><td>Je dichter die Zellschicht wird, umso höher steigt der elektrische Widerstand (TEER).</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Je früher toxische Effekte in mikrofluidischen Modellen erkannt werden, desto geringer sind die Entwicklungskosten neuer Medikamente.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The earlier toxic effects are detected in microfluidic models, the lower are the development costs of new drugs.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Ergebnisse sind sowohl für akademische Arbeitsgruppen als auch für die pharmazeutische Industrie von herausragender Bedeutung.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The results are of outstanding significance both for academic research groups and for the pharmaceutical industry.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch05-subjective-modals" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 05</div>
                <h2 class="ch-heading">Kapitel 5: Subjektive Bedeutung der Modalverben (Epistemische Modalität)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Was bedeutet &#x27;subjektiver Gebrauch&#x27;?</strong></li><li class="rule-sub-item">Das Modalverb drückt keine objektive Pflicht oder Fähigkeit des Subjekts aus, sondern die <strong>subjektive Einschätzung / Gewissheit des Sprechers</strong> über einen Sachverhalt.</li><li class="rule-header-item"><strong>2. Die Grade der Gewissheit bei Vermutungen:</strong></li><li class="rule-sub-item"><strong>müssen (95–100% Sicherheit):</strong> Logischer Zwangsschluss (<em>Bei diesen Werten muss ein Membranbruch vorliegen = Es ist zweifellos so</em>).</li><li class="rule-sub-item"><strong>müsste / dürfte (75–80% Wahrscheinlichkeit):</strong> Hohe Wahrscheinlichkeit, begründete Vermutung (<em>Die Probe dürfte bis morgen früh inkubiert sein = Es ist sehr wahrscheinlich</em>).</li><li class="rule-sub-item"><strong>kann / könnte (40–50% Möglichkeit):</strong> Ungewissheit, vorsichtige Hypothese (<em>Eine Verstopfung könnte den Druckabfall erklären = Es ist möglich</em>).</li><li class="rule-header-item"><strong>3. Distanzierung von Aussagen (Hörensagen &amp; Behauptung):</strong></li><li class="rule-sub-item"><strong>sollen (Gerücht / Aussage Dritter):</strong> Der Sprecher gibt eine fremde Information wieder, ohne dafür zu bürgen (<em>Der neue Wirkstoff soll hochwirksam sein = Man behauptet / Die Studie besagt, dass er hochwirksam ist</em>).</li><li class="rule-sub-item"><strong>wollen (Behauptung des Subjekts über sich selbst):</strong> Das Subjekt behauptet etwas über sich, was von anderen bezweifelt wird (<em>Er will die Formel als Erster entdeckt haben = Er behauptet es von sich, aber es ist umstritten</em>).</li><li class="rule-header-item"><strong>4. Subjektive Modalverben in der Vergangenheit:</strong></li><li class="rule-sub-item"><em>Bildungsformel:</em> <strong>Modalverb im Präsens + Partizip II + haben / sein am Satzende</strong>.</li><li class="rule-sub-item"><em>Beispiel:</em> <em>Der Forscher <strong>muss</strong> die Probe <strong>überhitzt haben</strong> (= Ich bin mir sicher, dass er sie überhitzt hat).</em></li><li class="rule-sub-item"><em>Beispiel:</em> <em>Er <strong>soll</strong> gestern in Berlin <strong>angekommen sein</strong> (= Man sagt, dass er gestern angekommen ist).</em></li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Subjektive Modalverben Matrix nach Sprechereinstellung &amp; Gewissheit</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Modalverb</th><th>Gewissheitsgrad / Funktion</th><th>Paraphrase (Gleichbedeutend mit)</th><th>Wissenschaftlicher Beispielsatz</th></tr></thead>
                        <tbody><tr><td>müssen</td><td>Fast 100% sicher (Zwangsschluss)</td><td>Zweifellos / Sicherlich</td><td>Das plötzliche Signalrauschen muss von einer Luftblase herrühren.</td></tr><tr><td>dürfte</td><td>Ca. 75% wahrscheinlich</td><td>Vermutlich / Höchstwahrscheinlich</td><td>Die Konzentration dürfte für eine vollständige Rezeptorblockade ausreichen.</td></tr><tr><td>könnte</td><td>Ca. 40–50% möglich</td><td>Möglicherweise / Eventuell</td><td>Ein osmotischer Gradient könnte die наблюдаete Zellschrumpfung bewirken.</td></tr><tr><td>sollen</td><td>Fremde Behauptung (Distanz)</td><td>Laut Bericht / Es heißt, dass</td><td>Das Konkurrenzlabor soll ähnliche Durchflussraten publiziert haben.</td></tr><tr><td>wollen</td><td>Subjektive Eigenbehauptung</td><td>Das Subjekt behauptet von sich</td><td>Der Autor will den Effekt bereits vor drei Jahren nachgewiesen haben.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Zellen müssen während des Transports kontaminiert worden sein (Vergangenheitsvermutung: 100% sicher).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The cells must have been contaminated during transport.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die neue mikrofluidische Geometrie soll laut Hersteller den Scherstress um 40% reduzieren (Fremdaussage: sollen).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The new microfluidic geometry is said by the manufacturer to reduce shear stress by 40%.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch06-nominalstil" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 06</div>
                <h2 class="ch-heading">Kapitel 6: Wissenschaftlicher Nominalstil vs. Verbalstil (Systematische Transformation)</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Verbalstil vs. Nominalstil:</strong></li><li class="rule-sub-item"><em>Verbalstil (leicht verständlich, dialogisch):</em> Verwendet Nebensätze mit finiten Verben (<em>Weil die Temperatur anstieg, veränderten sich die Zellen</em>).</li><li class="rule-sub-item"><em>Nominalstil (akademisch, hoch verdichtet):</em> Verwendet Substantivierungen und Präpositionalphrasen (<em>Infolge des Temperaturanstiegs erfolgte eine Zellveränderung</em>).</li><li class="rule-header-item"><strong>2. Das Transformations-Schema:</strong></li><li class="rule-sub-item">Verb wird zum Nomen (<em>expandieren → die Expansion, messen → die Messung</em>).</li><li class="rule-sub-item">Subjekt des Nebensatzes wird zum <strong>Genitivattribut</strong> (<em>die Zellen teilen sich → die Teilung der Zellen</em>).</li><li class="rule-sub-item">Adverbien werden zu <strong>attributiven Adjektiven</strong> (<em>schnell wachsen → schnelles Wachstum</em>).</li><li class="rule-sub-item">Konjunktion wird zur entsprechenden <strong>Präposition</strong> (<em>weil → aufgrund/infolge; obwohl → trotz; wenn → bei; nachdem → nach</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Systematische Transformations-Tabelle: Verbalstil → Nominalstil</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Nebensatz-Typ (Verbalstil)</th><th>Subjunktion</th><th>Präposition (Nominalstil)</th><th>Verbaler Beispielsatz</th><th>Nominaler Beispielsatz (Fachsprache)</th></tr></thead>
                        <tbody><tr><td>Kausal (Grund)</td><td>weil / da</td><td>aufgrund / infolge (+ Gen)</td><td>Weil die Flussrate zunimmt, ...</td><td>Infolge der Zunahme der Flussrate ...</td></tr><tr><td>Konzessiv (Gegengrund)</td><td>obwohl / obgleich</td><td>trotz / ungeachtet (+ Gen)</td><td>Obwohl der Druck schwankte, ...</td><td>Trotz der Druckschwankungen ...</td></tr><tr><td>Konditional (Bedingung)</td><td>wenn / falls</td><td>bei (+ Dat) / im Falle (+ Gen)</td><td>Wenn der Sensor ausfällt, ...</td><td>Bei Ausfall des Sensors ...</td></tr><tr><td>Temporal (Vorzeitigkeit)</td><td>nachdem</td><td>nach (+ Dat)</td><td>Nachdem wir zentrifugiert hatten, ...</td><td>Nach der Zentrifugation ...</td></tr><tr><td>Temporal (Gleichzeitigkeit)</td><td>während / solange</td><td>während (+ Gen)</td><td>Während die Zellen inkubieren, ...</td><td>Während der Zellinkubation ...</td></tr><tr><td>Final (Zweck)</td><td>damit / um zu</td><td>zur / zwecks (+ Gen)</td><td>Um Kontaminationen zu vermeiden, ...</td><td>Zur Vermeidung von Kontaminationen ...</td></tr><tr><td>Modal (Mittel)</td><td>indem / dadurch dass</td><td>durch (+ Akk) / mittels (+ Gen)</td><td>Indem man den Kanal verengt, ...</td><td>Durch eine Verengung des Kanals ...</td></tr><tr><td>Konsekutiv (Folge)</td><td>sodass</td><td>mit der Folge (+ Gen)</td><td>..., sodass das Protein denaturierte.</td><td>..., mit der Folge einer Proteindenaturierung.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Verbalstil: Weil das Hydrogel abgebaut wird, können die Endothelzellen tiefer in die Matrix einwandern.
Nominalstil: Infolge des Hydrogelabbaus erfolgt eine tiefere Einwanderung der Endothelzellen in die Matrix.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Verbal: Because the hydrogel degrades, endothelial cells can migrate deeper into the matrix.
Nominal: As a result of hydrogel degradation, deeper endothelial cell migration into the matrix occurs.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Zur Vermeidung von Artefakten (Final im Nominalstil) ist vor der Messung eine Nullpunktkalibrierung durchzuführen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> In order to avoid artifacts, a zero-point calibration is to be performed before the measurement.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch07-konjunktiv1" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 07</div>
                <h2 class="ch-heading">Kapitel 7: Der Konjunktiv I &amp; Die Indirekte Rede in Wissenschaft und Medien</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Funktion des Konjunktiv I:</strong></li><li class="rule-sub-item">Dient in der gehobenen Schriftsprache, im Wissenschaftsjournalismus und in Nachrichten zur <strong>neutralen Wiedergabe von Fremdaussagen</strong> (Indirekte Rede), ohne dass der Sprecher sich die Aussage zu eigen macht.</li><li class="rule-header-item"><strong>2. Bildung des Konjunktiv I (Präsensstamm + Endungen):</strong></li><li class="rule-sub-item">Endungen: <strong>-e, -est, -e, -en, -et, -en</strong> (<em>ich habe, du habest, er habe, wir haben, ihr habet, sie haben</em>).</li><li class="rule-sub-item"><em>Das Hilfsverb sein (Ausnahme):</em> <strong>sei, seiest/seist, sei, seien, seiet, seien</strong> (<em>Er sei der beste Forscher</em>).</li><li class="rule-header-item"><strong>3. Die fundamentale Ersatzregel:</strong></li><li class="rule-sub-item">Ist die Konjunktiv I Form identisch mit dem Indikativ (was bei <em>ich, wir, sie pl.</em> fast immer der Fall ist: <em>wir haben = wir haben</em>), MUSS auf den <strong>Konjunktiv II</strong> ausgewichen werden (<em>wir hätten</em>).</li><li class="rule-sub-item">Ist auch der Konjunktiv II missverständlich oder veraltet, verwendet man die <strong>würde-Form</strong> (<em>sie würden forschen</em>).</li><li class="rule-header-item"><strong>4. Zeitenfolge in der indirekten Rede:</strong></li><li class="rule-sub-item"><em>Gegenwart / Zukünftiges:</em> Konjunktiv I Präsens (<em>Er sagt, er forsche an Biochips</em>).</li><li class="rule-sub-item"><em>Vergangenheit (egal ob Perfekt, Präteritum oder Plusquamperfekt):</em> <strong>sei / habe + Partizip II</strong> (<em>Er sagte, er habe die Daten gestern publiziert</em>).</li><li class="rule-sub-item"><em>Zukunft:</em> <strong>werde + Infinitiv</strong> (<em>Er erklärte, er werde die Versuchsreihe morgen abschließen</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Konjunktiv I Stammformen und die Konjunktiv II Ersatzregel</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Person</th><th>Indikativ Präsens</th><th>Konjunktiv I (Regulär)</th><th>Identisch mit Indikativ?</th><th>Konjunktiv II Ersatzform</th></tr></thead>
                        <tbody><tr><td>ich</td><td>habe</td><td>habe</td><td>Ja (Identisch)</td><td>hätte</td></tr><tr><td>du</td><td>hast</td><td>habest</td><td>Nein (Eindeutig K.I)</td><td>— (habest)</td></tr><tr><td>er/sie/es</td><td>hat</td><td>habe</td><td>Nein (Eindeutig K.I)</td><td>— (habe)</td></tr><tr><td>wir</td><td>haben</td><td>haben</td><td>Ja (Identisch)</td><td>hätten</td></tr><tr><td>ihr</td><td>habt</td><td>habet</td><td>Nein (Eindeutig K.I)</td><td>— (habet)</td></tr><tr><td>sie / Sie</td><td>haben</td><td>haben</td><td>Ja (Identisch)</td><td>hätten</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Der Hauptautor berichtete, die gemessene Barriereintegrität sei (Konjunktiv I) signifikant höher gewesen als in 2D-Kontrollen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The lead author reported that the measured barrier integrity had been significantly higher than in 2D controls.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Gutachter erklärten, sie hätten (K.II Ersatz für K.I &#x27;haben&#x27;) keine methodischen Mängel feststellen können.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The reviewers stated that they had not been able to detect any methodological flaws.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch08-modalpartikeln" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 08</div>
                <h2 class="ch-heading">Kapitel 8: Modalpartikeln &amp; Nuancen der mündlichen Fachkommunikation</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Was sind Modalpartikeln?</strong></li><li class="rule-sub-item">Unveränderliche Wörter, die keine eigene Satzgliedfunktion haben, aber die Einstellung, Erwartung oder emotionale Färbung des Sprechers ausdrücken.</li><li class="rule-header-item"><strong>2. Die wichtigsten Partikeln im akademischen Diskurs:</strong></li><li class="rule-sub-item"><strong>ja:</strong> Drückt aus, dass der Sachverhalt beiden Gesprächspartnern bereits bekannt ist (<em>Das wissen Sie ja bereits = wie Ihnen bekannt ist</em>).</li><li class="rule-sub-item"><strong>doch:</strong> Widerspruch, nachdrückliche Erinnerung oder Aufforderung (<em>Überprüfen Sie doch nochmals die Flussrate!</em>; <em>Das ist doch logisch!</em>).</li><li class="rule-sub-item"><strong>denn:</strong> Macht Fragen freundlicher oder drückt echtes Erstaunen aus (<em>Wie funktioniert denn dieser neue Chip?</em>).</li><li class="rule-sub-item"><strong>eben / halt:</strong> Akzeptanz einer unumstößlichen Tatsache (<em>Zellen sind eben empfindlich = Das ist eine Tatsache, die man nicht ändern kann</em>).</li><li class="rule-sub-item"><strong>eigentlich:</strong> Höfliche Einschränkung oder Themenwechsel (<em>Eigentlich wollten wir heute messen, aber der Laser ist defekt</em>).</li><li class="rule-sub-item"><strong>wohl:</strong> Vermutung (<em>Das wird wohl stimmen = vermutlich</em>).</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Bedeutung und Wirkung deutscher Modalpartikeln</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Partikel</th><th>Sprechereinstellung / Funktion</th><th>Musterbeispiel im Fachgespräch</th><th>Englische sinngemäße Entsprechung</th></tr></thead>
                        <tbody><tr><td>ja</td><td>Gemeinsames Vorwissen (bekanntlich)</td><td>Die PDMS-Membran ist ja gasdurchlässig.</td><td>as you know / obviously</td></tr><tr><td>doch</td><td>Appell / Widerspruch / Erinnerung</td><td>Schauen Sie doch mal in das Laborjournal!</td><td>why don&#x27;t you / after all</td></tr><tr><td>denn</td><td>Interesse / Erstaunen in Fragen</td><td>Welche Zelllinie verwenden Sie denn hier?</td><td>actually / by the way</td></tr><tr><td>eben / halt</td><td>Unveränderliche Gegebenheit</td><td>Biologische Systeme zeigen halt Schwankungen.</td><td>simply / just the way it is</td></tr><tr><td>eigentlich</td><td>Einschränkung / Relativierung</td><td>Das Protokoll ist eigentlich sehr unkompliziert.</td><td>actually / strictly speaking</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Sie kennen ja (Vorwissen) die Richtlinien für die Entsorgung von biohazardösen Abfällen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> You know the guidelines for the disposal of biohazardous waste, of course.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Kommen Sie doch (freundlicher Appell) morgen um 10 Uhr in mein Büro zur Vorbesprechung.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Why don&#x27;t you come to my office tomorrow at 10 AM for a preliminary discussion.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch09-noun-preposition" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 09</div>
                <h2 class="ch-heading">Kapitel 9: Feste Nomen-Präposition-Verbindungen in der Wissenschaftssprache</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Warum Nomen-Präposition-Verbindungen?</strong></li><li class="rule-sub-item">Bilden das Rückgrat des wissenschaftlichen Nominalstils (<em>Die Reaktion der Zellen auf den Wirkstoff; Das Interesse der Industrie an dieser Technologie</em>).</li><li class="rule-header-item"><strong>2. Systematische Gruppen nach Präpositionen:</strong></li><li class="rule-sub-item"><strong>an (+ Dativ):</strong> <em>das Interesse an, der Bedarf an, der Zweifel an, die Kritik an, die Teilnahme an, der Mangel an, die Forschung an</em>.</li><li class="rule-sub-item"><strong>auf (+ Akkusativ):</strong> <em>die Reaktion auf, die Antwort auf, der Hinweis auf, die Auswirkung auf, der Einfluss auf, der Verzicht auf, die Hoffnung auf</em>.</li><li class="rule-sub-item"><strong>für (+ Akkusativ):</strong> <em>das Verständnis für, die Verantwortung für, die Voraussetzung für, das Kriterium für, der Nachweis für</em>.</li><li class="rule-sub-item"><strong>zu (+ Dativ):</strong> <em>der Beitrag zu, die Beziehung zu, der Übergang zu, die Bereitschaft zu, im Vergleich zu</em>.</li><li class="rule-sub-item"><strong>von (+ Dativ):</strong> <em>die Abhängigkeit von, der Unterschied von/zu, die Trennung von</em>.</li><li class="rule-sub-item"><strong>nach (+ Dativ):</strong> <em>die Frage nach, die Suche nach, der Wunsch nach</em>.</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Katalog fester Nomen-Präposition-Verbindungen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Nomen + feste Präposition</th><th>Kasus</th><th>Verwandtes Verb</th><th>Wissenschaftlicher Beispielsatz</th></tr></thead>
                        <tbody><tr><td>das Interesse an</td><td>Dativ</td><td>sich interessieren für (Akk)</td><td>Das weltweite Interesse an mikrofluidischen Modellen wächst stetig.</td></tr><tr><td>die Auswirkung auf</td><td>Akkusativ</td><td>sich auswirken auf (Akk)</td><td>Die Scherspannung hat eine direkte Auswirkung auf das Endothel.</td></tr><tr><td>der Zweifel an</td><td>Dativ</td><td>zweifeln an (Dat)</td><td>Es bestehen keine Zweifel an der Validität der experimentellen Daten.</td></tr><tr><td>die Voraussetzung für</td><td>Akkusativ</td><td>voraussetzen (Akk)</td><td>Sterilität ist die Grundvoraussetzung für erfolgreiche Langzeitkulturen.</td></tr><tr><td>der Beitrag zu</td><td>Dativ</td><td>beitragen zu (Dat)</td><td>Diese Dissertation leistet einen wertvollen Beitrag zur Wirkstoffforschung.</td></tr><tr><td>die Abhängigkeit von</td><td>Dativ</td><td>abhängen von (Dat)</td><td>Wir untersuchten die Abhängigkeit der Zellviabilität von der Flussrate.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Suche nach alternativen Testmethoden (nach + Dat) führte zur Entwicklung mikrofluidischer Organchips.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The search for alternative testing methods led to the development of microfluidic organ chips.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Reaktion der Krebszellen auf die Chemotherapie (auf + Akk) wurde photometrisch quantifiziert.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The response of the cancer cells to the chemotherapy was quantified photometrically.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="b2-ch10-text-coherence" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 10</div>
                <h2 class="ch-heading">Kapitel 10: Textkohärenz, Satzverknüpfung &amp; Konnektoren im akademischen Diskurs</h2>
            </div>
            <div class="chapter-card-body">
                
                
    <div class="rule-box">
        <div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div>
        <ul class="rule-list">
            <li class="rule-header-item"><strong>1. Die 4 syntaktischen Konnektoren-Klassen im Deutschen:</strong></li><li class="rule-header-item"><strong>Klasse 1: Nebenordnende Konjunktionen (Position 0):</strong></li><li class="rule-sub-item"><em>und, aber, oder, denn, sondern</em> → Verändern die normale Satzstellung NICHT (<em>Ich messe [Pos 1] die Probe [Pos 2], <strong>denn</strong> die Pumpe <strong>läuft</strong> [Pos 2] stabil</em>).</li><li class="rule-header-item"><strong>Klasse 2: Konjunktionaladverbien (Position 1 im Vorfeld → Inversion):</strong></li><li class="rule-sub-item"><em>deshalb, folglich, demnach, infolgedessen, trotzdem, dennoch, stattdessen, darüber hinaus, schließlich, allerdings</em> → Das finite Verb folgt direkt an Position 2 (<em>Folglich <strong>müssen</strong> wir die Parameter anpassen</em>).</li><li class="rule-header-item"><strong>Klasse 3: Adverbien im Mittelfeld (Position 3 / Schaltsatz):</strong></li><li class="rule-sub-item"><em>nämlich, jedoch, allerdings, indessen</em> (<em>Wir müssen <strong>jedoch</strong> die Kontrollgruppe beachten</em>).</li><li class="rule-header-item"><strong>Klasse 4: Unterordnende Subjunktionen (Verbletztstellung):</strong></li><li class="rule-sub-item"><em>weil, da, obwohl, sodass, während, indem, damit</em> → Finites Verb am Ende des Nebensatzes.</li>
        </ul>
    </div>
    
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Logische Konnektoren-Matrix für wissenschaftliche Argumentation</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Logische Funktion</th><th>Position 0 (Konjunktion)</th><th>Position 1 (Adverb + Inversion)</th><th>Nebensatz (Subjunktion)</th></tr></thead>
                        <tbody><tr><td>Kausal (Begründung)</td><td>denn</td><td>deshalb / daher / aus diesem Grund</td><td>weil / da</td></tr><tr><td>Konzessiv (Widerspruch)</td><td>aber</td><td>trotzdem / dennoch / gleichwohl</td><td>obwohl / obgleich</td></tr><tr><td>Konsekutiv (Folge/Schluss)</td><td>—</td><td>folglich / infolgedessen / demnach</td><td>sodass</td></tr><tr><td>Additiv (Erweiterung)</td><td>und</td><td>darüber hinaus / ferner / zudem</td><td>sowie</td></tr><tr><td>Adversativ (Gegensatz)</td><td>sondern (nach Negation)</td><td>dagegen / hingegen / im Gegensatz dazu</td><td>während</td></tr><tr><td>Modal (Mittel/Methode)</td><td>—</td><td>dadurch / auf diese Weise / mittels</td><td>indem / dadurch dass</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Membran zeigte minimale Leckagen; infolgedessen (Pos 1 + Inversion) mussten wir die Dichtungsringe austauschen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The membrane showed minimal leakage; consequently we had to replace the sealing rings.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Organ-on-a-Chip-Modelle reduzieren Tierversuche; darüber hinaus ermöglichen sie präzisere mechanistische Einblicke.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Organ-on-a-Chip models reduce animal testing; furthermore they enable more precise mechanistic insights.</div>
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
        <a href="/deutsch/grammatik/b1/" class="nav-btn">← Stufe B1</a>
        <a href="/deutsch/grammatik/" class="nav-btn" style="background: #ffffff; color: #0284c7; border: 1px solid #0284c7;">📖 Zurück zum 40-Kapitel-Hub</a>
        <span class="nav-btn disabled">Stufe B2 (Meister) →</span>
    </div>
</div>
