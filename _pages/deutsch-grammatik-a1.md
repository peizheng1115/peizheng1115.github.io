---
layout: single
title: "Stufe A1: Grundstufe I – Fundamentale Grammatik & Satzbau"
permalink: /deutsch/grammatik/a1/
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
        <span class="hero-badge">CEFR A1 Anfänger</span>
        <h1 class="hero-title">Stufe A1: Grundstufe I – Fundamentale Grammatik & Satzbau</h1>
        <p class="hero-summary">Vollständiges Grundstufen-Kompendium: Genus-Systematik & Endungsregeln, die 5 Pluralbildungsklassen, Artikel- & Possessivgefüge, Konjugation der schwachen/starken Verben im Präsens, Hauptsatz-Syntax mit Satzklammer & Inversion, Akkusativ-System, trennbare/untrennbare Präfixe, Modalverben, Imperativ und Perfekt-Systematik mit haben/sein.</p>
        <div class="hero-actions">
            <a href="/deutsch/grammatik/" class="action-btn">📚 Grammatik-Hub</a>
            <a href="/files/Deutsch_Grammatik_A1.md" class="action-btn" download>📥 Download Markdown</a>
            <a href="/deutsch/" class="action-btn">🇩🇪 Deutsch Portal</a>
        </div>
    </div>

    <nav class="toc-bar" aria-label="Kapitel-Navigation">
        <div class="toc-bar-title">⚡ Schnellnavigation durch alle 10 Kapitel (A1):</div>
        <div class="toc-grid">
            <a href="#a1-ch01-genus" class="toc-pill">Kapitel 1</a><a href="#a1-ch02-plural" class="toc-pill">Kapitel 2</a><a href="#a1-ch03-articles-pronouns" class="toc-pill">Kapitel 3</a><a href="#a1-ch04-verbs-present" class="toc-pill">Kapitel 4</a><a href="#a1-ch05-syntax-fields" class="toc-pill">Kapitel 5</a><a href="#a1-ch06-akkusativ-prepositions" class="toc-pill">Kapitel 6</a><a href="#a1-ch07-prefixes" class="toc-pill">Kapitel 7</a><a href="#a1-ch08-modal-verbs" class="toc-pill">Kapitel 8</a><a href="#a1-ch09-imperativ" class="toc-pill">Kapitel 9</a><a href="#a1-ch10-perfekt" class="toc-pill">Kapitel 10</a>
        </div>
    </nav>

    <div class="chapters-wrapper">
        
        <article id="a1-ch01-genus" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 01</div>
                <h2 class="ch-heading">Kapitel 1: Nomen, Genus-Systematik &amp; Morphologische Erkennung</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Maskuline Nomen (der):**</li><li class="rule-item">  - *Morphologische Suffixe:* **-ling** (Lehrling, Schmetterling), **-or** (Motor, Reaktor), **-ismus** (Organismus, Mechanismus), **-ant / -ent** (Assistent, Patient, Dozent), **-ist** (Spezialist, Biologe), **-er** bei handelnden Personen/Geräten (Forscher, Computer, Bohrer).</li><li class="rule-item">  - *Semantische Gruppen:* Wochentage (*der Montag*), Monate (*der Januar*), Jahreszeiten (*der Sommer*), Himmelsrichtungen (*der Norden*), Wetterereignisse (*der Regen, der Schnee, der Wind, der Nebel*), alkoholische Getränke (*der Wein, der Wodka*; Ausnahme: *das Bier*), Automarken (*der BMW, der Mercedes*).</li><li class="rule-item">**2. Feminine Nomen (die):**</li><li class="rule-item">  - *Morphologische Suffixe (nahezu 100% feminin):* **-ung** (Zellkultur, Forschung, Lösung, Prüfung), **-heit / -keit** (Krankheit, Möglichkeit, Flüssigkeit, Sauberkeit), **-schaft** (Wissenschaft, Eigenschaft, Gesellschaft), **-tät** (Universität, Stabilität, Permeabilität), **-tion / -sion** (Reaktion, Diffusion, Konzentration, Fusion), **-ie** (Biologie, Chemie, Mikroskopie), **-ik** (Mikrofluidik, Genetik, Physik, Musik), **-anz / -enz** (Differenz, Toleranz, Sequenz), **-ur** (Kultur, Temperatur, Natur, Struktur), **-e** (ca. 90% aller zweisilbigen Nomen auf -e: *die Lampe, die Grenze, die Phase, die Pumpe, die Zelle*; Ausnahmen: *der Name, der Käse, das Auge, das Ende*).</li><li class="rule-item">  - *Semantische Gruppen:* Weibliche Personen &amp; Berufsbezeichnungen (*die Professorin, die Ärztin*), Bäume &amp; Blumen (*die Eiche, die Rose*; Ausnahme: *der Baum*), Schiffs- und Flugzeugnamen (*die Titanic, die Boeing 747*).</li><li class="rule-item">**3. Neutrale Nomen (das):**</li><li class="rule-item">  - *Morphologische Suffixe:* **-chen / -lein** (Verkleinerungsformen: *das Teilchen, das Röhrchen, das Mädchen*), **-ment** (Experiment, Instrument, Dokument, Segment), **-um** (Zentrum, Laboratorium, Medium, Spektrum, Serum), **-tum** (Wachstum; Ausnahme: *der Reichtum, der Irrtum*), **-ma** (Klima, Thema, Schema, Prisma).</li><li class="rule-item">  - *Substantivierte Infinitive &amp; Adjektive:* **das + Verb-Infinitiv** (*das Messen, das Forschen, das Pipettieren, das Verstehen*), substantivierte Farben &amp; Sprachen (*das Blau, das Deutsch*).</li><li class="rule-item">  - *Semantische Gruppen:* Metalle &amp; chemische Elemente (*das Gold, das Silber, das Silizium, das Platin, das Kupfer*; Ausnahmen: *der Stahl, die Bronze*), Bruchzahlen (*das Drittel, das Viertel*).</li><li class="rule-item">**4. Zusammengesetzte Nomen (Komposita):** Das letzte Nomen bestimmt das Geschlecht und den Plural des gesamten Wortes: *das Labor + die Tür = die Labortür*; *die Zelle + der Kern = der Zellkern*.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Homonyme mit unterschiedlichem Genus &amp; Bedeutung (Vorsicht Falle!)</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Wort</th><th>Genus 1 &amp; Bedeutung</th><th>Genus 2 &amp; Bedeutung</th></tr></thead>
                        <tbody><tr><td>See</td><td>der See (Binnengewässer, Lake)</td><td>die See (das Meer, Ocean/Sea)</td></tr><tr><td>Band</td><td>das Band (Streifen/Schnur, Ribbon/Tape)</td><td>der Band (Buchband, Volume) / die Band (Musikgruppe)</td></tr><tr><td>Leiter</td><td>der Leiter (Chef/Direktor, Director/Conductor)</td><td>die Leiter (Klettergerät, Ladder)</td></tr><tr><td>Kiefer</td><td>der Kiefer (Knochen im Mund, Jaw)</td><td>die Kiefer (Nadelbaum, Pine tree)</td></tr><tr><td>Steuer</td><td>die Steuer (Abgabe an den Staat, Tax)</td><td>das Steuer (Lenkrad/Ruder, Steering wheel)</td></tr><tr><td>Gehalt</td><td>das Gehalt (Monatslohn, Salary)</td><td>der Gehalt (Inhalt/Anteil, Content/Percentage)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Untersuchung (f) der Membranstabilität (f) erfordert ein hochpräzises Messinstrument (n).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The investigation of membrane stability requires a high-precision measuring instrument.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Das Pipettieren (n, substantivierter Infinitiv) muss unter sterilen Bedingungen erfolgen.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Pipetting must take place under sterile conditions.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch02-plural" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 02</div>
                <h2 class="ch-heading">Kapitel 2: Die 5 Hauptklassen der Pluralbildung &amp; Sonderformen</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**Klasse 1: Endung -(e)n (ohne Umlaut):** Betrifft ca. 95% aller Feminina (*die Zelle -&gt; die Zellen, die Reaktion -&gt; die Reaktionen, die Fakultät -&gt; die Fakultäten*), maskuline N-Deklinationswörter (*der Student -&gt; die Studenten*) und wenige Neutra (*das Auge -&gt; die Augen, das Ohr -&gt; die Ohren*).</li><li class="rule-item">**Klasse 2: Endung -e (oft mit Umlaut bei a/o/u):** Sehr viele Maskulina (*der Tag -&gt; die Tage, der Arzt -&gt; die Ärzte, der Kanal -&gt; die Kanäle*), viele Neutra (*das Jahr -&gt; die Jahre, das Modell -&gt; die Modelle*) und einige einsilbige Feminina (*die Hand -&gt; die Hände, die Stadt -&gt; die Städte, die Nacht -&gt; die Nächte*).</li><li class="rule-item">**Klasse 3: Endung -er (fast immer mit Umlaut):** Hauptsächlich Neutra (*das Bild -&gt; die Bilder, das Buch -&gt; die Bücher, das Feld -&gt; die Felder, das Glas -&gt; die Gläser*) und wenige Maskulina (*der Mann -&gt; die Männer, der Wald -&gt; die Wälder*). NIEMALS bei Feminina!</li><li class="rule-item">**Klasse 4: Endung -s (ohne Umlaut):** Fremdwörter aus dem Englischen/Französischen (*das Auto -&gt; die Autos, der Chip -&gt; die Chips, das Labor -&gt; die Labors / Labore, das Team -&gt; die Teams*), Abkürzungen (*die PKWs, die LKWs*) und Nomen auf Vollvokal (*das Foto -&gt; die Fotos, das Sofa -&gt; die Sofas*).</li><li class="rule-item">**Klasse 5: Endungslos (nur Umlaut möglich):** Maskuline und neutrale Nomen auf *-el, -er, -en* sowie Verkleinerungsformen auf *-chen / -lein* (*der Computer -&gt; die Computer, der Apfel -&gt; die Äpfel, der Fehler -&gt; die Fehler, das Röhrchen -&gt; die Röhrchen, das Zeichen -&gt; die Zeichen*).</li><li class="rule-item">**Sonderkategorien:**</li><li class="rule-item">  - *Singulariatantum (nur im Singular):* Stoffnamen (*das Gold, das Wasser, das Blut, der Sauerstoff*), Abstrakta (*der Hunger, der Durst, die Kälte, die Geduld, das Wissen*).</li><li class="rule-item">  - *Pluraliatantum (nur im Plural):* *die Eltern, die Ferien, die Kosten, die Leute, die Lebensmittel, die Personalien, die Gebrüder*.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Übersichtstabelle der 5 Pluralbildungsklassen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Klasse</th><th>Pluralendung</th><th>Umlaut?</th><th>Typische Wortgruppe</th><th>Musterbeispiel Singular -&gt; Plural</th></tr></thead>
                        <tbody><tr><td>1</td><td>-(e)n</td><td>Nein</td><td>Feminina (-ung, -heit, -keit, -tät, -tion)</td><td>die Probe -&gt; die Proben, die Kultur -&gt; die Kulturen</td></tr><tr><td>2</td><td>-e</td><td>Ja / Nein</td><td>Maskulina, Neutra, einsilbige Feminina</td><td>der Tisch -&gt; die Tische, der Fluss -&gt; die Flüsse, das Protokoll -&gt; die Protokolle</td></tr><tr><td>3</td><td>-er</td><td>Ja (stets)</td><td>Einsilbige Neutra, wenige Maskulina</td><td>das Experiment -&gt; die Experimente (Kl.2), das Bild -&gt; die Bilder</td></tr><tr><td>4</td><td>-s</td><td>Nein</td><td>Fremdwörter, Kurzwörter, Endung auf Vokal</td><td>der Mikrochip -&gt; die Mikrochips, der Sensor -&gt; die Sensoren (Kl.1)</td></tr><tr><td>5</td><td>— (Null)</td><td>Teilweise</td><td>Nomen auf -er, -el, -en, -chen, -lein</td><td>der Filter -&gt; die Filter, der Schalter -&gt; die Schalter, das Mikroskop -&gt; die Mikroskope (Kl.2)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir haben heute fünf neue Mikrochips (pl, Kl.4) und mehrere Proben (pl, Kl.1) getestet.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We tested five new microchips and several samples today.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Kosten (Pluraliatantum) für die neuen Laborgeräte (pl, Kl.2) sind budgetiert.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The costs for the new laboratory equipment are budgeted.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch03-articles-pronouns" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 03</div>
                <h2 class="ch-heading">Kapitel 3: Artikelwörter, Negation (kein vs. nicht) &amp; Possessivartikel</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**Artikeldeklination:**</li><li class="rule-item">  - *Nominativ (Subjekt):* der / ein / kein (m); die / eine / keine (f); das / ein / kein (n); die / — / keine (pl).</li><li class="rule-item">  - *Akkusativ (Objekt):* den / einen / keinen (m); die / eine / keine (f); das / ein / kein (n); die / — / keine (pl).</li><li class="rule-item">**Regeln für die Negation:**</li><li class="rule-item">  - **kein / keine:** Negiert Nomen mit unbestimmtem Artikel (*Ich habe ein Auto -&gt; Ich habe kein Auto*) oder Nomen mit Nullartikel (*Ich habe Zeit -&gt; Ich habe keine Zeit*).</li><li class="rule-item">  - **nicht:** Negiert Verben (*Ich arbeite heute nicht*), Adjektive (*Das Medium ist nicht steril*), Adverbien (*Er spricht nicht schnell*), Eigennamen (*Das ist nicht Professor Weber*) und Nomen mit bestimmtem Artikel oder Possessivartikel (*Das ist nicht der richtige Sensor; Das ist nicht mein Protokoll*).</li><li class="rule-item">**Possessivartikel im Nominativ &amp; Akkusativ:**</li><li class="rule-item">  - *ich -&gt; mein / meine*; *du -&gt; dein / deine*; *er / es -&gt; sein / seine*; *sie (Singular) -&gt; ihr / ihre*; *wir -&gt; unser / unsere*; *ihr -&gt; euer / eure* (Beachte Wegfall des *e*: *eure*, nicht *euere*); *sie (Plural) / Sie (Höflichkeit) -&gt; ihr / ihre / Ihr / Ihre*.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Vollständige Possessivartikel-Tabelle (Nominativ &amp; Akkusativ)</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Person</th><th>Maskulin Nom. / Akk.</th><th>Feminin Nom. / Akk.</th><th>Neutrum Nom. / Akk.</th><th>Plural Nom. / Akk.</th></tr></thead>
                        <tbody><tr><td>ich</td><td>mein / meinen</td><td>meine / meine</td><td>mein / mein</td><td>meine / meine</td></tr><tr><td>du</td><td>dein / deinen</td><td>deine / deine</td><td>dein / dein</td><td>deine / deine</td></tr><tr><td>er / es</td><td>sein / seinen</td><td>seine / seine</td><td>sein / sein</td><td>seine / seine</td></tr><tr><td>sie (sg.)</td><td>ihr / ihren</td><td>ihre / ihre</td><td>ihr / ihr</td><td>ihre / ihre</td></tr><tr><td>wir</td><td>unser / unseren</td><td>unsere / unsere</td><td>unser / unser</td><td>unsere / unsere</td></tr><tr><td>ihr</td><td>euer / euren</td><td>eure / eure</td><td>euer / euer</td><td>eure / eure</td></tr><tr><td>sie / Sie</td><td>ihr(Ihr) / ihren(Ihren)</td><td>ihre(Ihre) / ihre(Ihre)</td><td>ihr(Ihr) / ihr(Ihr)</td><td>ihre(Ihre) / ihre(Ihre)</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Haben Sie Ihren Personalausweis (m, Akk) und Ihre Versichertenkarte (f, Akk) dabei?</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Do you have your identity card and health insurance card with you?</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir haben heute kein Experiment (n, Negation), weil das Messgerät nicht kalibriert (Adjektiv-Negation) ist.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We have no experiment today because the measuring device is not calibrated.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch04-verbs-present" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 04</div>
                <h2 class="ch-heading">Kapitel 4: Konjugation im Präsens (Schwache, Starke &amp; Unregelmäßige Verben)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Regelmäßige schwache Verben:** Verbstamm + Personalendungen: *-e, -st, -t, -en, -t, -en* (*lernen -&gt; ich lerne, du lernst, er lernt, wir lernen, ihr lernt, sie lernen*).</li><li class="rule-item">**2. Phonetische Anpassungen des Verbstamms:**</li><li class="rule-item">  - *Stamm auf -d oder -t:* Einschub eines *-e-* bei *du, er/sie/es, ihr* (*arbeiten -&gt; du arbeitest, er arbeitet, ihr arbeitet; finden -&gt; du findest, er findet*).</li><li class="rule-item">  - *Stamm auf -s, -ß, -z, -x:* In der 2. Person Singular entfällt das *-s-* der Endung (*heißen -&gt; du heißt; reisen -&gt; du reist; sitzen -&gt; du sitzt*).</li><li class="rule-item">  - *Stamm auf -eln / -ern:* In der 1. Person Singular entfällt oft das *-e-* im Stamm (*handeln -&gt; ich handle / handele, wir handeln; sammeln -&gt; ich sammle*).</li><li class="rule-item">**3. Starke Verben mit Stammvokalwechsel (NUR bei du &amp; er/sie/es):**</li><li class="rule-item">  - *e -&gt; i:* *helfen (hilfst, hilft), sprechen (sprichst, spricht), treffen (triffst, trifft), vergessen (vergisst, vergisst), sterben (stirbst, stirbt), werfen (wirfst, wirft)*.</li><li class="rule-item">  - *e -&gt; ie:* *sehen (siehst, sieht), lesen (liest, liest), empfehlen (empfiehlst, empfiehlt), stehlen (stiehlst, stiehlt)*.</li><li class="rule-item">  - *a -&gt; ä:* *fahren (fährst, fährt), schlafen (schläfst, schläft), tragen (trägst, trägt), waschen (wäschst, wäscht), lassen (lässt, lässt)*.</li><li class="rule-item">  - *au -&gt; äu:* *laufen (läufst, läuft), saufen (säufst, säuft)*.</li><li class="rule-item">**4. Unregelmäßige Hilfsverben:** *sein (bin, bist, ist, sind, seid, sind)*, *haben (habe, hast, hat, haben, habt, haben)*, *werden (werde, wirst, wird, werden, werdet, werden)*, *wissen (weiß, weißt, weiß, wissen, wisst, wissen)*.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Vollständige Konjugationsmatrix wichtiger Verbtypen im Präsens</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Person</th><th>analysieren (regelm.)</th><th>arbeiten (-t Stamm)</th><th>lesen (e-&gt;ie)</th><th>fahren (a-&gt;ä)</th><th>wissen (Sonderform)</th><th>werden (Hilfsverb)</th></tr></thead>
                        <tbody><tr><td>ich</td><td>analysiere</td><td>arbeite</td><td>lese</td><td>fahre</td><td>weiß</td><td>werde</td></tr><tr><td>du</td><td>analysierst</td><td>arbeitest</td><td>liest</td><td>fährst</td><td>weißt</td><td>wirst</td></tr><tr><td>er/sie/es</td><td>analysiert</td><td>arbeitet</td><td>liest</td><td>fährt</td><td>weiß</td><td>wird</td></tr><tr><td>wir</td><td>analysieren</td><td>arbeiten</td><td>lesen</td><td>fahren</td><td>wissen</td><td>werden</td></tr><tr><td>ihr</td><td>analysiert</td><td>arbeitet</td><td>lest</td><td>fahrt</td><td>wisst</td><td>werdet</td></tr><tr><td>sie/Sie</td><td>analysieren</td><td>arbeiten</td><td>lesen</td><td>fahren</td><td>wissen</td><td>werden</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Der Wissenschaftler liest (e-&gt;ie) das Manuskript und weiß (Sonderform) sofort die Antwort.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The scientist reads the manuscript and immediately knows the answer.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wirst du morgen pünktlich im Laboratorium sein?</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Will you be in the laboratory on time tomorrow?</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch05-syntax-fields" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 05</div>
                <h2 class="ch-heading">Kapitel 5: Satzbau, Stellungsfelder, Inversion &amp; Satzklammer</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Das Grundgesetz des Hauptsatzes:** Das finite (konjugierte) Verb besetzt ausnahmslos **Position 2**!</li><li class="rule-item">**2. Das Vorfeld (Position 1):** Hier steht genau EIN Satzglied. Das kann das Subjekt sein (*Der Forscher testet heute die Probe*) oder eine adverbiale Bestimmung (*Heute testet der Forscher die Probe*).</li><li class="rule-item">**3. Inversion (Subjekt-Verb-Umstellung):** Steht nicht das Subjekt auf Position 1, wandert das Subjekt automatisch direkt hinter das Verb auf Position 3 (*Am Montag präsentiere ich die Daten*).</li><li class="rule-item">**4. Die Satzklammer (Rahmenkonstruktion):**</li><li class="rule-item">  - *Linke Satzklammer (Position 2):* Finites Verb (Hilfsverb, Modalverb oder finiter Teil eines trennbaren Verbs).</li><li class="rule-item">  - *Rechte Satzklammer (Satzende):* Infiniter Verbteil (Partizip II, Infinitiv oder trennbares Präfix).</li><li class="rule-item">  - *Mittelfeld:* Alle Objekte, Adverbialangaben und Pronomen.</li><li class="rule-item">**5. TEKAMOLO-Regel für Angaben im Mittelfeld:**</li><li class="rule-item">  - **TE**mporal (Wann?): *heute um 9 Uhr*</li><li class="rule-item">  - **KA**usal (Warum?): *wegen der Messung*</li><li class="rule-item">  - **MO**dal (Wie?): *mit großer Präzision*</li><li class="rule-item">  - **LO**kal (Wo/Wohin?): *im Reinraum*.</li><li class="rule-item">  - *Beispiel:* Ich fahre **heute (Te) wegen des Kongresses (Ka) mit dem ICE (Mo) nach München (Lo)**.</li><li class="rule-item">**6. Fragesätze:**</li><li class="rule-item">  - *W-Fragen (Ergänzungsfragen):* Fragewort (Pos 1) + Finites Verb (Pos 2) + Subjekt (Pos 3)... (*Wo forschen Sie zurzeit?*)</li><li class="rule-item">  - *Ja/Nein-Fragen (Entscheidungsfragen):* Finites Verb ganz vorne auf **Position 1** (*Haben Sie die Proben sterilisiert?*)</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Stellungsfelder-Modell des deutschen Hauptsatzes</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Vorfeld (Pos. 1)</th><th>Linke Klammer (Pos. 2)</th><th>Mittelfeld (TE-KA-MO-LO &amp; Objekte)</th><th>Rechte Klammer (Satzende)</th></tr></thead>
                        <tbody><tr><td>Der Doktorand</td><td>startet</td><td>jeden Morgen um 8 Uhr (Te) im Labor (Lo)</td><td>die Perfusion.</td></tr><tr><td>Gestern (Te)</td><td>hat</td><td>unser Team (Subj) mit Erfolg (Mo) im Institut (Lo)</td><td>geforscht (Partizip II).</td></tr><tr><td>Aufgrund des Drucks (Ka)</td><td>müssen</td><td>wir (Subj) die Flussrate (Akk)</td><td>reduzieren (Infinitiv).</td></tr><tr><td>Um 10:00 Uhr (Te)</td><td>schaltet</td><td>die Assistentin (Subj) das Mikroskop (Akk)</td><td>ein (Präfix).</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Morgen präsentiere ich an der Universität meine Dissertation.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Tomorrow I present my dissertation at the university.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Haben Sie heute Morgen die Messwerte im Protokoll notiert?</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Did you write down the measurement values in the log this morning?</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch06-akkusativ-prepositions" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 06</div>
                <h2 class="ch-heading">Kapitel 6: Der Akkusativ (Direktes Objekt) &amp; Feste Akkusativ-Präpositionen</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**Akkusativ-Funktion:** Der Akkusativ (Wen/Was-Fall) bezeichnet das Ziel, den Gegenstand oder den Empfänger der direkten verbalen Handlung.</li><li class="rule-item">**Verben mit obligatorischem Akkusativ (Transitive Verben):** *haben, brauchen, suchen, finden, kaufen, lesen, schreiben, trinken, essen, sehen, hören, verstehen, untersuchen, kalibrieren, pipettieren, reinigen, vorbereiten*.</li><li class="rule-item">**Personalpronomen im Akkusativ:** *mich (ich), dich (du), ihn (er/der Mann), sie (sie/die Frau), es (es/das Kind), uns (wir), euch (ihr), sie (sie pl.), Sie (Höflichkeit)*.</li><li class="rule-item">**Die reinen Akkusativ-Präpositionen (Merkhilfe DOGFU + bis &amp; entlang):**</li><li class="rule-item">  - **D**urch (+ Akk): Räumliche Durchquerung (*durch den Filter*) oder Mittel/Vermittlung (*durch präzise Steuerung*).</li><li class="rule-item">  - **O**hne (+ Akk): Fehlen, Ausschluss (*ohne Kontamination, ohne Handschuhe*).</li><li class="rule-item">  - **G**egen (+ Akk): Richtung/Kollision (*gegen die Wand*), Bekämpfung (*gegen Bakterien*), ungefähre Zeit (*gegen 14:00 Uhr*).</li><li class="rule-item">  - **F**ür (+ Akk): Zweck/Nutzen (*für das Experiment*), Empfänger (*für meinen Kollegen*), Zeitspanne (*für drei Monate*).</li><li class="rule-item">  - **U**m (+ Akk): Räumlich herum (*um das Gebäude*), exakte Uhrzeit (*um 08:30 Uhr*).</li><li class="rule-item">  - **Bis** (+ Akk): Zeitlicher/räumlicher Endpunkt (*bis nächsten Freitag, bis München*).</li><li class="rule-item">  - **Entlang** (nachgestellt + Akk): Parallele Bewegung (*den Kanal entlang*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Akkusativ-Präpositionen und semantische Anwendungsfelder</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Präposition</th><th>Kasus</th><th>Semantische Funktion</th><th>Musterbeispiel im wissenschaftlichen Kontext</th></tr></thead>
                        <tbody><tr><td>durch</td><td>Akkusativ</td><td>Durchquerung / Kausales Mittel</td><td>Das Kulturmedium strömt kontinuierlich durch den Mikrokanal.</td></tr><tr><td>ohne</td><td>Akkusativ</td><td>Ausschluss (Gegenteil von mit)</td><td>Ohne eine konstante CO2-Begasung überleben die Zellen nicht.</td></tr><tr><td>für</td><td>Akkusativ</td><td>Bestimmung / Zweck / Empfänger</td><td>Wir benötigen hochreine Reagenzien für die Synthese.</td></tr><tr><td>gegen</td><td>Akkusativ</td><td>Widerstand / Richtzeit</td><td>Der Antikörper bindet spezifisch gegen das Oberflächenprotein.</td></tr><tr><td>um</td><td>Akkusativ</td><td>Exakte Zeit / Kreisbewegung</td><td>Das Seminar beginnt pünktlich um 11:15 Uhr im Hörsaal.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Ich habe einen neuen Antikörper (m, Akk) für das Experiment (n, Akk) bestellt.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> I ordered a new antibody for the experiment.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Er führt die Messung ohne seinen Betreuer (m, Akk) durch.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> He carries out the measurement without his supervisor.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch07-prefixes" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 07</div>
                <h2 class="ch-heading">Kapitel 7: Trennbare &amp; Untrennbare Verben im Detail</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Trennbare Verben (Präfix ist immer STARK BETONT):**</li><li class="rule-item">  - Typische Präfixe: *ab-, an-, auf-, aus-, bei-, ein-, fern-, fest-, fort-, her-, hin-, los-, mit-, nach-, vor-, weg-, weiter-, zu-, zurück-, zusammen-*.</li><li class="rule-item">  - *Präsens-Hauptsatz:* Finites Verb auf Position 2, Präfix am Satzende (*Ich schalte das Spektrometer ein*).</li><li class="rule-item">  - *Perfekt:* Das Ge-Element steht zwischen Präfix und Stamm (*ein-ge-schaltet, ab-ge-lesen*).</li><li class="rule-item">  - *Infinitiv mit zu:* Das zu-Element steht dazwischen (*ein-zu-schalten, vor-zu-bereiten*).</li><li class="rule-item">**2. Untrennbare Verben (Präfix ist immer UNBETONT):**</li><li class="rule-item">  - Die 8 untrennbaren Präfixe (Merksatz: *be-emp-ent-er-ge-miss-ver-zer*):</li><li class="rule-item">    - **be-** (macht Verben oft transitiv: *antworten -&gt; beantworten, schreiben -&gt; beschreiben*).</li><li class="rule-item">    - **ent-** (Entfernung, Beginn: *entfernen, entstehen, entladen*).</li><li class="rule-item">    - **er-** (Erreichen eines Ziels: *erreichen, erforschen, erkennen, erklären*).</li><li class="rule-item">    - **ver-** (Fehler, Änderung, Ende: *verändern, verbessern, verbrauchen, vergessen*).</li><li class="rule-item">    - **zer-** (Zerstörung in Teile: *zerstören, zerlegen, zersetzen*).</li><li class="rule-item">    - **miss-** (Falsch: *missverstehen, missbrauchen*).</li><li class="rule-item">  - *Perfekt:* Bildet das Partizip II NIEMALS mit &#x27;ge-&#x27; (*hat beschrieben, hat verstanden, hat erforscht*).</li><li class="rule-item">**3. Duale Präfixe (Kontextabhängig trennbar oder untrennbar):**</li><li class="rule-item">  - *durch-, über-, unter-, um-, wieder-*: Betont = trennbar (wörtlich/konkret); Unbetont = untrennbar (übertragen/abstrakt).</li><li class="rule-item">  - *Beispiel:* *übersetzen (trennbare Betonung: setzt über)* = ans andere Ufer fahren; *übersetzen (untrennbar: übersetzt)* = Sprache dolmetschen.</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Vergleich trennbarer und untrennbarer Verbformen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Verb</th><th>Präfix-Typ</th><th>Präsens-Hauptsatz</th><th>Perfekt-Form</th><th>Bedeutung</th></tr></thead>
                        <tbody><tr><td>einstellen</td><td>Trennbar (ein-)</td><td>Der Forscher stellt den Druck ein.</td><td>hat eingestellt</td><td>justieren / kalibrieren</td></tr><tr><td>ablesen</td><td>Trennbar (ab-)</td><td>Sie liest die Skala sorgfältig ab.</td><td>hat abgelesen</td><td>Messwert erfassen</td></tr><tr><td>vorbereiten</td><td>Trennbar (vor-)</td><td>Wir bereiten die Nährlösung vor.</td><td>hat vorbereitet</td><td>präparieren</td></tr><tr><td>beschreiben</td><td>Untrennbar (be-)</td><td>Er beschreibt das Phänomen.</td><td>hat beschrieben</td><td>charakterisieren</td></tr><tr><td>untersuchen</td><td>Untrennbar (unter-)</td><td>Das Team untersucht die Probe.</td><td>hat untersucht</td><td>analysieren</td></tr><tr><td>verändern</td><td>Untrennbar (ver-)</td><td>Die Temperatur verändert das Signal.</td><td>hat verändert</td><td>modifizieren</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wann fangen Sie mit der neuen Versuchsreihe an?</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> When do you begin with the new test series?</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Wissenschaftler erforschten (untrennbar) die Ursachen der Zellalterung.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The scientists researched the causes of cellular senescence.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch08-modal-verbs" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 08</div>
                <h2 class="ch-heading">Kapitel 8: Die 6 Modalverben &amp; Das Vollverb &#x27;mögen&#x27;</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**Modalverben-Konjugation Besonderheit:**</li><li class="rule-item">  - 1. Person Singular (*ich*) und 3. Person Singular (*er/sie/es*) haben KEINE Personalendung und sind absolut identisch (*ich kann, er kann; ich muss, er muss*)!</li><li class="rule-item">  - Stammvokalwechsel im Singular bei *können (kann), dürfen (darf), müssen (muss), wissen (weiß)*.</li><li class="rule-item">**Semantische Differenzierung:**</li><li class="rule-item">  - **können:** Fähigkeit (Ich kann programmieren), Möglichkeit (Man kann hier parken), Erlaubnis/Gelegenheit.</li><li class="rule-item">  - **müssen:** Unvermeidbare Notwendigkeit, Pflicht, Naturgesetz (Man muss atmen, um zu leben). Negiert: *nicht müssen* = keine Notwendigkeit (braucht nicht).</li><li class="rule-item">  - **dürfen:** Erlaubnis, behördliche Berechtigung (Hier darf man forschen). Negiert: *nicht dürfen* = STRIKTES VERBOT (Hier darf man nicht rauchen!).</li><li class="rule-item">  - **sollen:** Auftrag, moralische Pflicht, Empfehlung von Dritten (Der Arzt sagt, ich soll mich ausruhen).</li><li class="rule-item">  - **wollen:** Subjektiver starker Wille, Absicht, Entschluss (Ich will promovieren).</li><li class="rule-item">  - **möchten:** Höfliche Form von wollen (Ich möchte gerne einen Termin vereinbaren).</li><li class="rule-item">  - **mögen (Vollverb):** Vorliebe für Dinge/Personen (*Ich mag Kaffee; Ich mag dieses Design*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Vollständige Konjugationstabelle aller Modalverben im Präsens</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Person</th><th>können (Fähigkeit)</th><th>müssen (Pflicht)</th><th>dürfen (Erlaubnis)</th><th>wollen (Wille)</th><th>sollen (Auftrag)</th><th>möchten (Wunsch)</th></tr></thead>
                        <tbody><tr><td>ich</td><td>kann</td><td>muss</td><td>darf</td><td>will</td><td>soll</td><td>möchte</td></tr><tr><td>du</td><td>kannst</td><td>musst</td><td>darfst</td><td>willst</td><td>sollst</td><td>möchtest</td></tr><tr><td>er/sie/es</td><td>kann</td><td>muss</td><td>darf</td><td>will</td><td>soll</td><td>möchte</td></tr><tr><td>wir</td><td>können</td><td>müssen</td><td>dürfen</td><td>wollen</td><td>sollen</td><td>möchten</td></tr><tr><td>ihr</td><td>könnt</td><td>müsst</td><td>dürft</td><td>wollt</td><td>sollt</td><td>möchtet</td></tr><tr><td>sie / Sie</td><td>können</td><td>müssen</td><td>dürfen</td><td>wollen</td><td>sollen</td><td>möchten</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Im Reinraumbereich darf man keine Straßenschuhe tragen (striktes Verbot).</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> In the cleanroom area one must not wear street shoes.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Wir müssen die Flussrate exakt einstellen, um Verwirbelungen zu verhindern.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> We must adjust the flow rate exactly in order to prevent turbulences.</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch09-imperativ" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 09</div>
                <h2 class="ch-heading">Kapitel 9: Der Imperativ (Die Befehls- &amp; Aufforderungsform)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. du-Form (Informell Singular):**</li><li class="rule-item">  - *Regel:* Verbstamm der 2. Person Singular OHNE Personalendung *-st* und OHNE das Pronomen *du* (*du lernst -&gt; Lern!*, *du arbeitest -&gt; Arbeite!*).</li><li class="rule-item">  - *Stammendung auf -d, -t, -m, -n, -ig:* Erhält zwingend ein *-e* (*Warte!, Öffne!, Entschuldige!*).</li><li class="rule-item">  - *Starke Verben mit e-&gt;i/ie Wechsel:* Behalten den Vokalwechsel bei, erhalten NIEMALS ein Endungs-e (*du hilfst -&gt; Hilf!*, *du liest -&gt; Lies!*, *du sprichst -&gt; Sprich!*).</li><li class="rule-item">  - *Starke Verben mit a-&gt;ä Wechsel:* VERLIEREN den Umlaut im Imperativ (*du fährst -&gt; Fahr!*, *du schläfst -&gt; Schlaf!*).</li><li class="rule-item">**2. ihr-Form (Informell Plural):**</li><li class="rule-item">  - *Regel:* Identisch mit der regulären 2. Person Plural Präsens, aber OHNE das Pronomen *ihr* (*ihr lernt -&gt; Lernt!*, *ihr wartet -&gt; Wartet!*, *ihr helft -&gt; Helft!*).</li><li class="rule-item">**3. Sie-Form (Formell Singular &amp; Plural):**</li><li class="rule-item">  - *Regel:* Infinitiv + Pronomen *Sie* in invertierter Stellung (*Lernen Sie!*, *Kommen Sie herein!*, *Warten Sie einen Moment!*).</li><li class="rule-item">**4. wir-Form (Aufforderung an die Gruppe):**</li><li class="rule-item">  - *Regel:* Infinitiv + *wir* (*Gehen wir!*, *Starten wir die Messung!*) oder mit *Lassen Sie uns / Lasst uns + Infinitiv*.</li><li class="rule-item">**5. Das unregelmäßige Verb &#x27;sein&#x27;:**</li><li class="rule-item">  - *du:* **Sei** vorsichtig! | *ihr:* **Seid** ruhig! | *Sie:* **Seien Sie** pünktlich! | *wir:* **Seien wir** optimistisch!</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Systematische Imperativ-Matrix</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Verb</th><th>du-Form</th><th>ihr-Form</th><th>Sie-Form (Höflich)</th><th>wir-Form (Gemeinsam)</th></tr></thead>
                        <tbody><tr><td>machen (schwach)</td><td>Mach(e)!</td><td>Macht!</td><td>Machen Sie!</td><td>Machen wir!</td></tr><tr><td>arbeiten (-t Stamm)</td><td>Arbeite!</td><td>Arbeitet!</td><td>Arbeiten Sie!</td><td>Arbeiten wir!</td></tr><tr><td>helfen (e-&gt;i)</td><td>Hilf!</td><td>Helft!</td><td>Helfen Sie!</td><td>Helfen wir!</td></tr><tr><td>lesen (e-&gt;ie)</td><td>Lies!</td><td>Lest!</td><td>Lesen Sie!</td><td>Lesen wir!</td></tr><tr><td>fahren (a-&gt;ä)</td><td>Fahr(e)!</td><td>Fahrt!</td><td>Fahren Sie!</td><td>Fahren wir!</td></tr><tr><td>sein (unregelmäßig)</td><td>Sei!</td><td>Seid!</td><td>Seien Sie!</td><td>Seien wir!</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Pipettieren Sie die Lösung vorsichtig in die Kammer!</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Pipette the solution carefully into the chamber!</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Sei vorsichtig mit den toxischen Chemikalien!</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Be careful with the toxic chemicals!</div>
            </div>
            </div>
        </div>
        
            </div>
            <div class="chapter-card-footer">
                <a href="#toc-top" class="back-to-top">↑ Nach oben</a>
                <a href="/deutsch/grammatik/" class="hub-link">← Zurück zur Grammatik-Übersicht</a>
            </div>
        </article>
        
        <article id="a1-ch10-perfekt" class="chapter-card">
            <div class="chapter-card-header">
                <div class="ch-badge-num">Kapitel 10</div>
                <h2 class="ch-heading">Kapitel 10: Das Perfekt (Die mündliche Vergangenheitsform)</h2>
            </div>
            <div class="chapter-card-body">
                
                <div class="rule-box"><div class="rule-box-header">💡 Grammatische Regeln & Kernkonzepte</div><ul class="rule-list"><li class="rule-item">**1. Grundstruktur des Perfekts:**</li><li class="rule-item">  - *Hilfsverb (haben / sein)* steht konjugiert auf **Position 2**.</li><li class="rule-item">  - *Partizip II* steht unveränderlich am **Satzende** (rechte Satzklammer).</li><li class="rule-item">**2. Kriterien zur Wahl des Hilfsverbs:**</li><li class="rule-item">  - **Wann &#x27;sein&#x27;?**</li><li class="rule-item">    1. Verben der Ortsveränderung (von Punkt A nach B): *gehen, fahren, fliegen, kommen, laufen, reisen, schwimmen, steigen*.</li><li class="rule-item">    2. Verben der Zustandsänderung (Übergang in neuen Zustand): *aufwachen, einschlafen, sterben, wachsen, schmelzen, gefrieren*.</li><li class="rule-item">    3. Die 6 Sonderverben: *sein (ist gewesen), werden (ist geworden), bleiben (ist geblieben), passieren (ist passiert), gelingen (ist gelungen), scheitern (ist gescheitert)*.</li><li class="rule-item">  - **Wann &#x27;haben&#x27;?**</li><li class="rule-item">    1. Alle transitiven Verben (Verben mit Akkusativobjekt: *Ich habe den Sensor kalibriert*).</li><li class="rule-item">    2. Alle reflexiven Verben (*Ich habe mich gefreut*).</li><li class="rule-item">    3. Alle Modalverben (*Er hat arbeiten müssen*).</li><li class="rule-item">    4. Alle intransitiven Verben ohne Orts-/Zustandswechsel (*Ich habe geschlafen, gestanden, gewartet*).</li><li class="rule-item">**3. Bildung des Partizip II (Die 4 Hauptregeln):**</li><li class="rule-item">  - *Regelmäßige (schwache) Verben:* **ge- + Verbstamm + -t** (*ge-lern-t, ge-kauf-t, ge-arbeite-t*).</li><li class="rule-item">  - *Unregelmäßige (starke) Verben:* **ge- + Verbstamm (oft Ablaut) + -en** (*ge-sproch-en, ge-fahr-en, ge-les-en*).</li><li class="rule-item">  - *Gemischte Verben (Ablaut + -t):* *bringen -&gt; gebracht, denken -&gt; gedacht, wissen -&gt; gewusst, kennen -&gt; gekannt*.</li><li class="rule-item">  - *Verben auf -ieren:* KEIN ge- Präfix! Bilden Partizip auf *-iert* (*analysieren -&gt; analysiert, zentrifugieren -&gt; zentrifugiert*).</li><li class="rule-item">  - *Trennbare Verben:* ge- steht in der Mitte (*ein-ge-stellt, ab-ge-lesen*).</li><li class="rule-item">  - *Untrennbare Verben:* KEIN ge- Präfix (*beschrieben, verstanden, erforscht*).</li></ul></div>
                
            <div class="grammar-table-wrapper">
                <div class="table-title">📊 Kompakte Partizip II Referenztabelle nach Verbklassen</div>
                <div class="table-responsive">
                    <table class="grammar-table">
                        <thead><tr><th>Verbtyp</th><th>Infinitiv</th><th>Hilfsverb</th><th>Partizip II</th><th>Musterbeispiel im Perfekt</th></tr></thead>
                        <tbody><tr><td>Schwach (regelmäßig)</td><td>optimieren</td><td>haben</td><td>optimiert</td><td>Wir haben das Flussdesign optimiert.</td></tr><tr><td>Schwach trennbar</td><td>einschalten</td><td>haben</td><td>eingeschaltet</td><td>Er hat das Gerät eingeschaltet.</td></tr><tr><td>Stark Ortswechsel</td><td>anreisen</td><td>sein</td><td>angereist</td><td>Die Gutachter sind gestern angereist.</td></tr><tr><td>Stark Zustandswechsel</td><td>absterben</td><td>sein</td><td>abgestorben</td><td>Einige Zellen sind über Nacht abgestorben.</td></tr><tr><td>Stark untrennbar</td><td>verstehen</td><td>haben</td><td>verstanden</td><td>Sie hat die Funktionsweise verstanden.</td></tr><tr><td>Gemischt</td><td>erkennen</td><td>haben</td><td>erkannt</td><td>Das System hat das Fehlersignal erkannt.</td></tr></tbody>
                    </table>
                </div>
            </div>
            
                
        <div class="examples-section">
            <div class="examples-header">📖 Beispielsätze & Anwendungskontext</div>
            <div class="examples-grid">
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Die Wissenschaftler sind nach Berlin geflogen und haben dort ihre Ergebnisse präsentiert.</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> The scientists flew to Berlin and presented their results there.</div>
            </div>
            
            <div class="example-card">
                <div class="ex-de"><span class="ex-flag">🇩🇪</span> Haben Sie die Konzentration der Lösung bereits berechnet?</div>
                <div class="ex-en"><span class="ex-flag">🇬🇧</span> Have you already calculated the concentration of the solution?</div>
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
        <span class="nav-btn disabled">← Stufe A1 (Start)</span>
        <a href="/deutsch/grammatik/" class="nav-btn" style="background: #ffffff; color: #0284c7; border: 1px solid #0284c7;">📖 Zurück zum 40-Kapitel-Hub</a>
        <a href="/deutsch/grammatik/a2/" class="nav-btn">Stufe A2 →</a>
    </div>
</div>
