---
layout: single
title: "Stufe A2: Grundstufe II – Kasuskomplex, Relationen & Satzverbindungen"
permalink: /deutsch/grammatik/a2/
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
        <span class="hero-badge">CEFR A2 Grundstufe II</span>
        <h1 class="hero-title">Stufe A2: Grundstufe II – Kasuskomplex, Relationen & Satzverbindungen</h1>
        <p class="hero-summary">Erweiterte Grundstufe: Dativ-Systematik & Dativ-Verben, Wechselpräpositionen (Wohin vs. Wo), Positions- & Aktionsverbpaare, Reflexive Verben (Akk vs. Dat), vollständige Adjektivdeklination (Typ 1, 2, 3), Komparativ & Superlativ, Nebensätze mit Konjunktionen (weil, dass, wenn, ob, als), Präteritum von Hilfs- & Modalverben und indirekte Fragesätze.</p>
        <div class="hero-actions">
            <a href="/deutsch/grammatik/" class="action-btn">📚 Grammatik-Hub</a>
            <a href="/files/Deutsch_Grammatik_A2.md" class="action-btn" download>📥 Download Markdown</a>
            <a href="/deutsch/" class="action-btn">🇩🇪 Deutsch Portal</a>
        </div>
    </div>

    <nav class="toc-bar" aria-label="Kapitel-Navigation">
        <div class="toc-bar-title">⚡ Schnellnavigation durch alle 10 Kapitel (A2):</div>
        <div class="toc-grid">
            <a href="#a2-ch01-dativ" class="toc-pill">Kapitel 1</a><a href="#a2-ch02-dativ-verbs-prep" class="toc-pill">Kapitel 2</a><a href="#a2-ch03-two-way-prepositions" class="toc-pill">Kapitel 3</a><a href="#a2-ch04-reflexive" class="toc-pill">Kapitel 4</a><a href="#a2-ch05-adjective-declension" class="toc-pill">Kapitel 5</a><a href="#a2-ch06-comparative-superlative" class="toc-pill">Kapitel 6</a><a href="#a2-ch07-subordinate-clauses" class="toc-pill">Kapitel 7</a><a href="#a2-ch08-temporalsatz" class="toc-pill">Kapitel 8</a><a href="#a2-ch09-praeteritum" class="toc-pill">Kapitel 9</a><a href="#a2-ch10-indirect-questions" class="toc-pill">Kapitel 10</a>
        </div>
    </nav>

    <div class="chapters-wrapper">
        
        <article id="a2-ch01-dativ" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 01</div>
                <h2 class="ch-heading">Kapitel 1: Der Dativ (Wem-Fall) &amp; Wortstellung bei doppelten Objekten</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Artikelformen im Dativ:**</li><li class="rule-item">  - *Maskulin:* **dem / einem / keinem / meinem**</li><li class="rule-item">  - *Feminin:* **der / einer / keiner / meiner**</li><li class="rule-item">  - *Neutrum:* **dem / einem / keinem / meinem**</li><li class="rule-item">  - *Plural:* **den / — / keinen / meinen + -(e)n am Nomen** (*den Kindern, den Experimenten, den Professoren*; Ausnahme: Nomen auf -s erhalten kein -n: *den Autos*).</li><li class="rule-item">**2. Personalpronomen im Dativ:**</li><li class="rule-item">  - *mir (ich), dir (du), ihm (er/es), ihr (sie sg.), uns (wir), euch (ihr), ihnen (sie pl.), Ihnen (Höflichkeit)*.</li><li class="rule-item">**3. Gesetz der doppelten Objekte (Dativ- und Akkusativobjekt im selben Satz):**</li><li class="rule-item">  - **Regel A (Beide sind Nomen):** Dativ-Nomen steht VOR Akkusativ-Nomen (*Ich gebe [dem Professor: Dat] [das Protokoll: Akk]*).</li><li class="rule-item">  - **Regel B (Eines ist Pronomen, eines Nomen):** Das Pronomen steht IMMER vor dem Nomen, egal welcher Fall (*Ich gebe [es: Akk-Pron] [dem Professor: Dat-Nomen]*; *Ich gebe [ihm: Dat-Pron] [das Protokoll: Akk-Nomen]*).</li><li class="rule-item">  - **Regel C (Beide sind Pronomen):** Akkusativ-Pronomen steht VOR Dativ-Pronomen (*Ich gebe [es: Akk] [ihm: Dat]*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Objekt-Reihenfolge Matrix im Deutschen Hauptsatz</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Objekt-Kombination</th><th>Regel-Formel</th><th>Beispielsatz</th><th>Bedeutung</th></tr></thead>
                        <tbody><tr><td>Nomen + Nomen</td><td>Dativ-Nomen VOR Akkusativ-Nomen</td><td>Der Dozent erklärt dem Studenten die Methode.</td><td>dem Studenten (Dat) vor die Methode (Akk)</td></tr><tr><td>Pronomen + Nomen</td><td>Pronomen VOR Nomen</td><td>Der Dozent erklärt sie dem Studenten.</td><td>sie (Akk-Pron) vor dem Studenten (Dat-Nomen)</td></tr><tr><td>Pronomen + Pronomen</td><td>Akkusativ-Pronomen VOR Dativ-Pronomen</td><td>Der Dozent erklärt sie ihm.</td><td>sie (Akk) vor ihm (Dat)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Laborleiterin überreicht dem Gastwissenschaftler (Dat-Nomen) die Auszeichnung (Akk-Nomen).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The lab director presents the award to the guest scientist.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Sie überreicht sie (Akk-Pron) ihm (Dat-Pron) feierlich.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> She presents it to him ceremoniously.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch02-dativ-verbs-prep" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 02</div>
                <h2 class="ch-heading">Kapitel 2: Die wichtigsten Dativ-Verben &amp; Feste Dativ-Präpositionen</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Die wichtigsten Verben mit Dativergänzung:**</li><li class="rule-item">  - *helfen (+ Dat):* Können Sie mir helfen?</li><li class="rule-item">  - *danken (+ Dat):* Wir danken Ihnen für die Kooperation.</li><li class="rule-item">  - *antworten (+ Dat):* Der Betreuer antwortet dem Doktoranden.</li><li class="rule-item">  - *gratulieren (+ Dat):* Wir gratulieren dir zur bestandenen Prüfung.</li><li class="rule-item">  - *gehören (+ Dat):* Das Mikroskop gehört unserem Institut.</li><li class="rule-item">  - *gefallen (+ Dat):* Das neue Laborkonzept gefällt den Forschern.</li><li class="rule-item">  - *schmecken (+ Dat):* Der Kaffee schmeckt mir gut.</li><li class="rule-item">  - *passen (+ Dat):* Der Termin passt mir ausgezeichnet.</li><li class="rule-item">  - *fehlen (+ Dat):* Den Zellen fehlt wichtiger Sauerstoff.</li><li class="rule-item">  - *schaden (+ Dat):* Hoher Druck schadet der Membran.</li><li class="rule-item">  - *vertrauen (+ Dat):* Wir vertrauen den Messergebnissen.</li><li class="rule-item">  - *zuhören (+ Dat):* Die Studenten hören der Vorlesung aufmerksam zu.</li><li class="rule-item">**2. Dativ-Präpositionen (Merksatz: Aus-Bei-Mit-Nach-Seit-Von-Zu + gegenüber &amp; außer):**</li><li class="rule-item">  - **aus:** Herkunft (*aus Deutschland*), Material (*aus Silikon*), Heraustreten (*aus dem Kanal*).</li><li class="rule-item">  - **bei:** Aufenthalt/Firma (*bei der Universität*), Gleichzeitigkeit (*beim Experiment*).</li><li class="rule-item">  - **mit:** Werkzeug/Mittel (*mit der Pipette*), Begleitung (*mit dem Team*).</li><li class="rule-item">  - **nach:** Zeitlich danach (*nach der Zentrifugation*), Ortsrichtung Länder/Städte (*nach Berlin*).</li><li class="rule-item">  - **seit:** Beginn in Vergangenheit, dauert an (*seit zwei Jahren* -&gt; Verlangt Präsens!).</li><li class="rule-item">  - **von:** Ausgangspunkt (*vom Labor*), Urheber (*von Professor Bauer*).</li><li class="rule-item">  - **zu:** Zielperson/Ort (*zum Seminar*), Anlass (*zur Feier*).</li><li class="rule-item">  - **gegenüber:** Lage gegenüber (*dem Institutsgebäude gegenüber*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Übersicht der reinen Dativ-Präpositionen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Präposition</th><th>Kasus</th><th>Hauptfunktion</th><th>Beispiel</th></tr></thead>
                        <tbody><tr><td>aus</td><td>Dativ</td><td>Herkunft / Material</td><td>Die mikrofluidischen Chips bestehen aus PDMS.</td></tr><tr><td>bei</td><td>Dativ</td><td>Ort / Bedingung</td><td>Bei steigender Temperatur erhöht sich die Diffusionsrate.</td></tr><tr><td>mit</td><td>Dativ</td><td>Instrument / Begleitung</td><td>Wir steuern die Pumpe mit einem Mikrocontroller.</td></tr><tr><td>nach</td><td>Dativ</td><td>Zeitfolge / Richtung</td><td>Nach der Inkubation messen wir das Fluoreszenzsignal.</td></tr><tr><td>seit</td><td>Dativ</td><td>Dauer seit Beginn</td><td>Seit einem Monat führen wir die Versuchsreihe durch.</td></tr><tr><td>von</td><td>Dativ</td><td>Urheber / Ausgangsort</td><td>Die Publikation stammt von unserer Arbeitsgruppe.</td></tr><tr><td>zu</td><td>Dativ</td><td>Richtung / Zweck</td><td>Wir gehen zur wöchentlichen Arbeitsgruppenbesprechung.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Ich forsche seit einem Jahr (Dat) bei einem renommierten Institut (Dat).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> I have been researching for a year at a renowned institute.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Der plötzliche Temperaturabfall schadet den lebenden Zellen (Dat).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The sudden temperature drop harms the living cells.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch03-two-way-prepositions" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 03</div>
                <h2 class="ch-heading">Kapitel 3: Wechselpräpositionen (Wohin Akk vs. Wo Dat) &amp; Positionsverben</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Die goldene Regel der 9 Wechselpräpositionen:**</li><li class="rule-item">  - **Wohin? (Richtung / Dynamik / Aktion):** -&gt; **AKKUSATIV** (*Ich stelle die Flasche auf den Tisch*).</li><li class="rule-item">  - **Wo? (Ort / Statik / Zustand):** -&gt; **DATIV** (*Die Flasche steht auf dem Tisch*).</li><li class="rule-item">**2. Die 4 klassischen Verbpaare (Transitiv vs. Intransitiv):**</li><li class="rule-item">  - *stellen (regelm., wohin? -&gt; Akk)* vs. *stehen (stark: stand/gestanden, wo? -&gt; Dat)*.</li><li class="rule-item">  - *legen (regelm., wohin? -&gt; Akk)* vs. *liegen (stark: lag/gelegen, wo? -&gt; Dat)*.</li><li class="rule-item">  - *setzen (regelm., wohin? -&gt; Akk)* vs. *sitzen (stark: saß/gesessen, wo? -&gt; Dat)*.</li><li class="rule-item">  - *hängen (regelm., wohin? -&gt; Akk)* vs. *hängen (stark: hing/gehangen, wo? -&gt; Dat)*.</li><li class="rule-item">  - *stecken (wohin? -&gt; Akk)* vs. *stecken (wo? -&gt; Dat)*.</li><li class="rule-item">**3. Temporale Verwendung der Wechselpräpositionen (Immer Dativ!):**</li><li class="rule-item">  - *an:* Tage, Tageszeiten (*am Montag, am Morgen, am Wochenende*).</li><li class="rule-item">  - *in:* Monate, Jahreszeiten, Jahre, Zeitspannen (*im Mai, im Sommer, in zwei Wochen*).</li><li class="rule-item">  - *vor / nach:* Vorher / Nachher (*vor dem Versuch, nach der Konferenz*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Positions- und Aktionsverbpaare im systematischen Vergleich</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Aktionsverb (Wohin? -&gt; Akkusativ)</th><th>Positionsverb (Wo? -&gt; Dativ)</th><th>Beispielsatz Akkusativ</th><th>Beispielsatz Dativ</th></tr></thead>
                        <tbody><tr><td>stellen (regelm.)</td><td>stehen (stand, gestanden)</td><td>Ich stelle das Becherglas auf die Heizplatte (Akk).</td><td>Das Becherglas steht auf der Heizplatte (Dat).</td></tr><tr><td>legen (regelm.)</td><td>liegen (lag, gelegen)</td><td>Er legt die Probe unter das Mikroskop (Akk).</td><td>Die Probe liegt unter dem Mikroskop (Dat).</td></tr><tr><td>setzen (regelm.)</td><td>sitzen (saß, gesessen)</td><td>Sie setzt sich an den Schreibtisch (Akk).</td><td>Sie sitzt am (an dem) Schreibtisch (Dat).</td></tr><tr><td>hängen (regelm.)</td><td>hängen (hing, gehangen)</td><td>Wir hängen das Poster an die Stellwand (Akk).</td><td>Das Poster hängt an der Stellwand (Dat).</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir füllen das Nährmedium in die obere Kammer (f, Akk: Wohin?).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We fill the nutrient medium into the upper chamber.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Endothelzellen wachsen in der oberen Kammer (f, Dat: Wo?).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The endothelial cells grow in the upper chamber.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch04-reflexive" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 04</div>
                <h2 class="ch-heading">Kapitel 4: Reflexive &amp; Reziproke Verben (Akkusativ vs. Dativ)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Echte vs. Unechte Reflexivverben:**</li><li class="rule-item">  - *Echte Reflexivverben:* Können nur mit Reflexivpronomen existieren (*sich konzentrieren auf, sich erkundigen nach, sich weigern, sich schämen, sich ereignen*).</li><li class="rule-item">  - *Unechte Reflexivverben:* Können reflexiv oder transitiv auf andere Objekte angewendet werden (*Ich wasche mich* vs. *Ich wasche das Auto*).</li><li class="rule-item">**2. Reflexivpronomen im Akkusativ vs. Dativ:**</li><li class="rule-item">  - Nur in der 1. und 2. Person Singular (*ich, du*) unterscheiden sich Akkusativ (*mich, dich*) und Dativ (*mir, dir*). Alle anderen Personen verwenden *sich, uns, euch, sich*.</li><li class="rule-item">  - *Wann Dativ?* Wenn im Satz bereits ein separates Akkusativobjekt vorhanden ist (*Ich ziehe mich (Akk) an* vs. *Ich ziehe mir (Dat) den Kittel (Akk) an*).</li><li class="rule-item">**3. Reziproke Verben (Wechselseitige Handlung):**</li><li class="rule-item">  - Subjekt steht im Plural; die Handlung ist gegenseitig (*sich treffen, sich einigen, sich austauschen, sich widersprechen*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Reflexivpronomen Übersicht Akkusativ vs. Dativ</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Person</th><th>Reflexiv Akkusativ</th><th>Reflexiv Dativ</th><th>Musterbeispiel</th></tr></thead>
                        <tbody><tr><td>ich</td><td>mich</td><td>mir</td><td>Ich konzentriere mich (Akk) / Ich merke mir die Formel (Dat).</td></tr><tr><td>du</td><td>dich</td><td>dir</td><td>Du freust dich (Akk) / Du wäschst dir die Hände (Dat).</td></tr><tr><td>er/sie/es</td><td>sich</td><td>sich</td><td>Er interessiert sich für Biomedizin.</td></tr><tr><td>wir</td><td>uns</td><td>uns</td><td>Wir einigen uns auf ein einheitliches Protokoll.</td></tr><tr><td>ihr</td><td>euch</td><td>euch</td><td>Ihr bereitet euch auf die Präsentation vor.</td></tr><tr><td>sie / Sie</td><td>sich</td><td>sich</td><td>Sie haben sich schnell in das Thema eingearbeitet.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Vor dem Betreten des Labors ziehen wir uns die Schutzbrille (Akk) an (Reflexiv im Dativ: uns).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Before entering the lab we put on the safety goggles.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Forscher tauschen sich (reziprok) regelmäßig über ihre Versuchsergebnisse aus.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The researchers exchange views regularly about their experimental results.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch05-adjective-declension" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 05</div>
                <h2 class="ch-heading">Kapitel 5: Die vollständige Adjektivdeklination (Typ 1, Typ 2, Typ 3)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**Grundprinzip:** Ein Adjektiv vor einem Nomen (attributiv) MUSS dekliniert werden. Es zeigt Genus, Numerus und Kasus an.</li><li class="rule-item">**Typ 1: Schwache Deklination (nach bestimmtem Artikel: der, die, das, dieser, jener, jeder, welcher):**</li><li class="rule-item">  - *Regel:* Nur zwei mögliche Endungen: **-e** oder **-en**!</li><li class="rule-item">  - **-e:** Nur in 5 Positionen: Nominativ Singular aller drei Geschlechter (*der neue Chip, die neue Pumpe, das neue Labor*) und Akkusativ Feminin &amp; Neutrum (*die neue Pumpe, das neue Labor*).</li><li class="rule-item">  - **-en:** In allen anderen Fällen (Akkusativ Maskulin, kompletter Dativ, kompletter Genitiv und kompletter Plural!).</li><li class="rule-item">**Typ 2: Gemischte Deklination (nach unbestimmtem Artikel: ein, kein, mein, dein, sein...):**</li><li class="rule-item">  - *Regel:* Adjektiv übernimmt dort die Signalendung des bestimmten Artikels, wo das Artikelwort keine eindeutige Endung hat (Nom. Mask: *ein neu-er Chip*; Nom/Akk Neutrum: *ein neu-es Labor*).</li><li class="rule-item">  - In allen Dativ-, Genitiv-, Akkusativ-Maskulin- und Pluralformen lautet die Endung **-en**.</li><li class="rule-item">**Typ 3: Starke Deklination (Nullartikel / ohne Artikelwort):**</li><li class="rule-item">  - *Regel:* Das Adjektiv muss die vollen Signalendungen des bestimmten Artikels tragen (*neu-er Sensor, neu-e Pumpe, neu-es Medium, neu-e Methoden*; Ausnahme: Genitiv Maskulin/Neutrum endet auf **-en**, weil das Nomen bereits das -s trägt: *kalt-en Wassers*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Master-Matrix der Adjektivendungen (Alle 3 Typen im Vergleich)</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Kasus &amp; Genus</th><th>Typ 1 (nach &#x27;der/die/das&#x27;)</th><th>Typ 2 (nach &#x27;ein/mein/kein&#x27;)</th><th>Typ 3 (Nullartikel / Ohne)</th></tr></thead>
                        <tbody><tr><td>Nom. Maskulin</td><td>der neu-e Chip</td><td>ein neu-er Chip</td><td>neu-er Chip</td></tr><tr><td>Akk. Maskulin</td><td>den neu-en Chip</td><td>einen neu-en Chip</td><td>neu-en Chip</td></tr><tr><td>Dat. Maskulin</td><td>dem neu-en Chip</td><td>einem neu-en Chip</td><td>neu-em Chip</td></tr><tr><td>Nom. Feminin</td><td>die neu-e Pumpe</td><td>eine neu-e Pumpe</td><td>neu-e Pumpe</td></tr><tr><td>Akk. Feminin</td><td>die neu-e Pumpe</td><td>eine neu-e Pumpe</td><td>neu-e Pumpe</td></tr><tr><td>Dat. Feminin</td><td>der neu-en Pumpe</td><td>einer neu-en Pumpe</td><td>neu-er Pumpe</td></tr><tr><td>Nom/Akk Neutrum</td><td>das neu-e Labor</td><td>ein neu-es Labor</td><td>neu-es Labor</td></tr><tr><td>Dat. Neutrum</td><td>dem neu-en Labor</td><td>einem neu-en Labor</td><td>neu-em Labor</td></tr><tr><td>Nom/Akk Plural</td><td>die neu-en Daten</td><td>keine neu-en Daten</td><td>neu-e Daten</td></tr><tr><td>Dat. Plural</td><td>den neu-en Daten</td><td>keinen neu-en Daten</td><td>neu-en Daten</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir nutzen ein hochauflösendes Mikroskop (Typ 2, n, Akk) für die präzise Zellanalyse (Typ 1, f, Akk).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We use a high-resolution microscope for precise cell analysis.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Frisches steriles Nährmedium (Typ 3, n, Nom) ist für das Zellwachstum unerlässlich.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Fresh sterile nutrient medium is essential for cell growth.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch06-comparative-superlative" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 06</div>
                <h2 class="ch-heading">Kapitel 6: Komparativ &amp; Superlativ (Steigerung &amp; attributive Endungen)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Die drei Steigerungsstufen:**</li><li class="rule-item">  - *Positiv (Grundstufe):* Gleichheit mit **so / genauso + Adjektiv + wie** (*Das Modell ist genauso präzise wie die Referenz*).</li><li class="rule-item">  - *Komparativ (Vergleichsstufe):* Ungleichheit mit **Adjektiv + -er + als** (*Dieses System ist stabiler als das vorherige*).</li><li class="rule-item">  - *Superlativ (Höchststufe):* Prädikativ mit **am + Adjektiv + -(e)sten** (*Dieses Design ist am effektivsten*); Attributiv mit bestimmtem Artikel und Adjektivendung (*das effektivste Design*).</li><li class="rule-item">**2. Umlautregeln &amp; Phonetische Besonderheiten:**</li><li class="rule-item">  - Einsilbige Adjektive mit *a, o, u* erhalten meist einen Umlaut (*alt/älter, warm/wärmer, groß/größer, kurz/kürzer, jung/jünger*).</li><li class="rule-item">  - Adjektive auf *-d, -t, -s, -ß, -z, -x, -los* erhalten im Superlativ ein **-e-** (*breit -&gt; am breitesten, heiß -&gt; am heißesten*).</li><li class="rule-item">  - Adjektive auf *-el / -er* verlieren im Komparativ das Stamm-e (*dunkel -&gt; dunkler; teuer -&gt; teurer*).</li><li class="rule-item">**3. Deklinierte Komparative &amp; Superlative vor Nomen:**</li><li class="rule-item">  - Erst steigern, dann nach normaler Adjektivdeklination beugen: *ein besser-er (Komparativ) + -er (Typ 2 Maskulin) = ein besserer Sensor*; *die schnell-st-e Pumpe*.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Unregelmäßige und hochfrequente Steigerungsformen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Positiv</th><th>Komparativ</th><th>Superlativ (Prädikativ)</th><th>Superlativ (Attributiv mit Nomen)</th><th>Bedeutung / Typ</th></tr></thead>
                        <tbody><tr><td>gut</td><td>besser als</td><td>am besten</td><td>das beste Ergebnis</td><td>Völlig unregelmäßig</td></tr><tr><td>viel</td><td>mehr als</td><td>am meisten</td><td>die meisten Publikationen</td><td>Völlig unregelmäßig</td></tr><tr><td>gern</td><td>lieber als</td><td>am liebsten</td><td>das liebste Forschungsfeld</td><td>Völlig unregelmäßig</td></tr><tr><td>hoch</td><td>höher als</td><td>am höchsten</td><td>der höchste Druck</td><td>c entfällt im Komparativ</td></tr><tr><td>nah</td><td>näher als</td><td>am nächsten</td><td>der nächste Messpunkt</td><td>h -&gt; ch im Superlativ</td></tr><tr><td>groß</td><td>größer als</td><td>am größten</td><td>der größte Vorteil</td><td>Umlaut, Superlativ nur -ten</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Organ-on-a-Chip-Modelle bieten eine deutlich höhere (attributiver Komparativ) physiologische Relevanz als statische Zellkulturen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Organ-on-a-Chip models offer a significantly higher physiological relevance than static cell cultures.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die höchste Überlebensrate (attributiver Superlativ) wurde bei 37°C gemessen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The highest survival rate was measured at 37°C.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch07-subordinate-clauses" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 07</div>
                <h2 class="ch-heading">Kapitel 7: Nebensätze I: Kausal (weil/da), Objekt (dass), Konditional (wenn/falls) &amp; ob</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Die fundamentale Nebensatz-Regel (Verbletztstellung):**</li><li class="rule-item">  - Das konjugierte Verb wandert ans **absolute Ende** des Nebensatzes.</li><li class="rule-item">  - Nebensätze werden im Deutschen IMMER durch ein Komma vom Hauptsatz getrennt.</li><li class="rule-item">**2. Die wichtigsten Subjunktionen im A2-Bereich:**</li><li class="rule-item">  - **weil / da (Kausal):** Begründung (*Wir wiederholen den Versuch, weil die Flussrate schwankte*). *da* steht bevorzugt am Satzanfang für bekannte Gründe (*Da das Labor renoviert wird, arbeiten wir im Nachbargebäude*).</li><li class="rule-item">  - **dass (Objekt-/Inhaltssatz):** Ergänzung nach Verben des Wissens, Meinens, Sagens (*Ich weiß, dass die Daten verlässlich sind*).</li><li class="rule-item">  - **wenn / falls (Konditional):** Bedingung (*Wenn der Druck steigt, schlägt der Alarm an*).</li><li class="rule-item">  - **ob (Indirekte Ja/Nein-Frage):** Ungewissheit (*Wir prüfen, ob die Membran dicht ist*).</li><li class="rule-item">**3. Satzstellung bei vorangestelltem Nebensatz (Verb-Verb-Regel):**</li><li class="rule-item">  - Beginnt der Satz mit dem Nebensatz (Nebensatz = Position 1 des Gesamtsatzes), beginnt der folgende Hauptsatz SOFORT mit dem finiten Verb (*Wenn die Messung beendet ist [Verb 1], starten [Verb 2] wir die Auswertung*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Nebensatz-Typen und Konjunktionen im Überblick</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Konjunktion</th><th>Typ</th><th>Funktion</th><th>Satzbeispiel (Hauptsatz + Nebensatz)</th></tr></thead>
                        <tbody><tr><td>weil</td><td>Kausal</td><td>Ursache / Grund</td><td>Das Experiment glückte, weil alle Parameter exakt kalibriert waren.</td></tr><tr><td>da</td><td>Kausal</td><td>Bekannter Grund (oft vorne)</td><td>Da die Reagenzien neu sind, erwarten wir hohe Reinheit.</td></tr><tr><td>dass</td><td>Subjekt/Objekt</td><td>Sachverhalt / Aussage</td><td>Der Gutachter bestätigte, dass die Methodik innovativ ist.</td></tr><tr><td>wenn</td><td>Konditional</td><td>Bedingung / Voraussetzung</td><td>Wenn die Zellen konfluent sind, beginnen wir mit der Perfusion.</td></tr><tr><td>ob</td><td>Interrogativ</td><td>Indirekte Entscheidungsfrage</td><td>Niemand weiß genau, ob der Versuch heute gelingt.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Weil die Scherbelastung die Differenzierung fördert, perfundieren wir das Endothel kontinuierlich.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Because shear stress promotes differentiation, we perfuse the endothelium continuously.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Ich bin mir sicher, dass wir bis Freitag alle Messreihen abschließen werden.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> I am certain that we will conclude all measurement series by Friday.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch08-temporalsatz" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 08</div>
                <h2 class="ch-heading">Kapitel 8: Temporale Nebensätze: Die genaue Unterscheidung von &#x27;wenn&#x27; und &#x27;als&#x27;</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Die Gretchenfrage: &#x27;wenn&#x27; oder &#x27;als&#x27;?**</li><li class="rule-item">  - **als:** Wird NUR verwendet bei einem **einmaligen Ereignis in der Vergangenheit** (*Als ich 2024 nach Deutschland kam...*; *Als der Sensor ausfiel, stoppten wir die Pumpe*).</li><li class="rule-item">  - **wenn:** Wird verwendet bei:</li><li class="rule-item">    1. Handlungen in Gegenwart und Zukunft (*Wenn ich Zeit habe, lese ich Fachartikel*).</li><li class="rule-item">    2. **Wiederholten Ereignissen in der Vergangenheit** (Signalwörter: *immer wenn, jedes Mal wenn*: *Immer wenn die Temperatur anstieg, öffnete sich das Ventil*).</li><li class="rule-item">**2. Weitere temporale Konjunktionen:**</li><li class="rule-item">  - **während:** Gleichzeitigkeit (*Während die Zellen inkubieren, werten wir die Daten aus*).</li><li class="rule-item">  - **bevor / ehe:** Vorzeitigkeit des Hauptsatzes (*Bevor wir beginnen, sterilisieren wir die Werkzeuge*).</li><li class="rule-item">  - **nachdem:** Nachzeitigkeit (erfordert Zeitenfolge: Plusquamperfekt bei Präteritum-Hauptsatz).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Entscheidungsbaum: &#x27;als&#x27; vs. &#x27;wenn&#x27;</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Zeitstufe</th><th>Häufigkeit</th><th>Konjunktion</th><th>Beispielsatz</th></tr></thead>
                        <tbody><tr><td>Vergangenheit</td><td>Einmalig in der Vergangenheit</td><td>als</td><td>Als wir das erste Experiment durchführten, gab es Probleme.</td></tr><tr><td>Vergangenheit</td><td>Wiederholt in der Vergangenheit</td><td>(immer) wenn</td><td>Immer wenn der Druck abfiel, überprüften wir die Dichtungen.</td></tr><tr><td>Gegenwart</td><td>Einmalig oder wiederholt</td><td>wenn</td><td>Wenn ich im Labor bin, trage ich immer Schutzkleidung.</td></tr><tr><td>Zukunft</td><td>Einmalig oder wiederholt</td><td>wenn</td><td>Wenn die Ergebnisse vorliegen, schreiben wir das Paper.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Als ich mein Studium in München begann (einmalig, Vergangenheit), lernte ich Deutsch.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> When I began my studies in Munich, I learned German.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Jedes Mal wenn wir die Nährlösung wechselten (wiederholt, Vergangenheit), stieg die Zellaktivität.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Every time we changed the nutrient solution, cell activity increased.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch09-praeteritum" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 09</div>
                <h2 class="ch-heading">Kapitel 9: Das Präteritum (Die schriftliche Vergangenheitsform)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Verwendung des Präteritums:** Hauptsächlich in schriftlichen Berichten, wissenschaftlichen Artikeln, Protokollen, Zeitungsberichten und literarischen Erzählungen. Im Alltag werden *sein, haben* und Modalverben auch mündlich im Präteritum gebraucht.</li><li class="rule-item">**2. Regelmäßige (schwache) Verben:**</li><li class="rule-item">  - Verbstamm + **-te, -test, -te, -ten, -tet, -ten** (*lernen -&gt; ich lernte, du lerntest, er lernte, wir lernten, ihr lerntet, sie lernten*).</li><li class="rule-item">  - Bei Stamm auf -d/-t: **-ete, -etest, -ete, -eten, -etet, -eten** (*arbeiten -&gt; arbeitete*).</li><li class="rule-item">**3. Unregelmäßige (starke) Verben:**</li><li class="rule-item">  - Stammvokal ändert sich (Ablaut!). 1. und 3. Person Singular haben KEINE Endung!</li><li class="rule-item">  - Endungen: **—, -st, —, -en, -t, -en** (*gehen -&gt; ging, gingst, ging, gingen, gingt, gingen; sprechen -&gt; sprach; sehen -&gt; sah; finden -&gt; fand*).</li><li class="rule-item">**4. Gemischte Verben (Ablaut + -te Endung):**</li><li class="rule-item">  - *denken -&gt; dachte, bringen -&gt; brachte, kennen -&gt; kannte, wissen -&gt; wusste*.</li><li class="rule-item">**5. Modalverben im Präteritum (Verlieren alle Umlaute!):**</li><li class="rule-item">  - *konnte, musste, durfte, sollte, wollte, mochte*.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Wichtige Präteritum-Stammformen im Überblick</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Infinitiv</th><th>3. Person Präsens</th><th>3. Person Präteritum</th><th>Partizip II (Perfekt)</th><th>Bedeutung</th></tr></thead>
                        <tbody><tr><td>sein</td><td>ist</td><td>war</td><td>ist gewesen</td><td>to be</td></tr><tr><td>haben</td><td>hat</td><td>hatte</td><td>hat gehabt</td><td>to have</td></tr><tr><td>werden</td><td>wird</td><td>wurde</td><td>ist geworden</td><td>to become</td></tr><tr><td>können</td><td>kann</td><td>konnte</td><td>hat gekonnt</td><td>can / to be able</td></tr><tr><td>müssen</td><td>muss</td><td>musste</td><td>hat gemusst</td><td>must / to have to</td></tr><tr><td>geben</td><td>gibt</td><td>gab</td><td>hat gegeben</td><td>to give / there was</td></tr><tr><td>gehen</td><td>geht</td><td>ging</td><td>ist gegangen</td><td>to go</td></tr><tr><td>finden</td><td>findet</td><td>fand</td><td>hat gefunden</td><td>to find</td></tr><tr><td>schreiben</td><td>schreibt</td><td>schrieb</td><td>hat geschrieben</td><td>to write</td></tr><tr><td>schließen</td><td>schließt</td><td>schloss</td><td>hat geschlossen</td><td>to close / conclude</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Forscher beobachteten (schwach) eine signifikante Zunahme der Barrieredichte und schrieben (stark) einen Zwischenbericht.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The researchers observed a significant increase in barrier density and wrote an interim report.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Das Labor war (Hilfsverb) gestern bis spät in die Nacht geöffnet, weil wir die Messreihe abschließen mussten (Modalverb).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The lab was open until late at night yesterday because we had to conclude the measurement series.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a2-ch10-indirect-questions" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 10</div>
                <h2 class="ch-heading">Kapitel 10: Indirekte Fragesätze &amp; Höfliche Bitten mit Konjunktiv II</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Indirekte W-Fragen:**</li><li class="rule-item">  - Direkt: *Wann beginnt die Konferenz?*</li><li class="rule-item">  - Indirekt: *Können Sie mir sagen, **wann die Konferenz beginnt**?* (Fragewort wird zur Subjunktion -&gt; Verb am Satzende!).</li><li class="rule-item">**2. Indirekte Ja/Nein-Fragen:**</li><li class="rule-item">  - Direkt: *Funktioniert das Spektrometer?*</li><li class="rule-item">  - Indirekt: *Ich möchte wissen, **ob das Spektrometer funktioniert**.* (Einleitung mit *ob* -&gt; Verb am Satzende!).</li><li class="rule-item">**3. Höfliche Bitten im universitären und professionellen Alltag:**</li><li class="rule-item">  - *Könnten Sie bitte... + Infinitiv* (*Könnten Sie mir bitte die Rohdaten zusenden?*).</li><li class="rule-item">  - *Würden Sie bitte... + Infinitiv* (*Würden Sie bitte die Kammer desinfizieren?*).</li><li class="rule-item">  - *Ich hätte gerne...* (*Ich hätte gerne Auskunft über das Promotionsprogramm*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Transformation Direkte Frage -&gt; Indirekte Frage</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Direkte Frage (Hauptsatz)</th><th>Einleitungsformel</th><th>Indirekte Frage (Nebensatz mit Verbletzt)</th></tr></thead>
                        <tbody><tr><td>Wo ist das Chemikalienlager?</td><td>Wissen Sie,</td><td>... wo das Chemikalienlager ist?</td></tr><tr><td>Wie viel Nährmedium brauchen wir?</td><td>Können Sie mir sagen,</td><td>... wie viel Nährmedium wir brauchen?</td></tr><tr><td>Ist der Autoklav noch frei?</td><td>Darf ich fragen,</td><td>... ob der Autoklav noch frei ist?</td></tr><tr><td>Wann liefert die Firma den Chip?</td><td>Ich möchte gern wissen,</td><td>... wann die Firma den Chip liefert.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Könnten Sie mir bitte mitteilen, wo ich die Sicherheitsdatenblätter für diese Reagenzien finde?</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Could you please inform me where I can find the material safety data sheets for these reagents?</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir würden gerne erfahren, ob eine Kooperation mit Ihrer Arbeitsgruppe möglich wäre.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We would like to find out whether a collaboration with your research group would be possible.</div>
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
        <a href="/deutsch/grammatik/a1/" class="nav-btn">← Stufe A1</a>
        <a href="/deutsch/grammatik/" class="nav-btn" style="background: #ffffff; color: #0284c7; border: 1px solid #0284c7;">📖 Zurück zum 40-Kapitel-Hub</a>
        <a href="/deutsch/grammatik/b1/" class="nav-btn">Stufe B1 →</a>
    </div>
</div>
