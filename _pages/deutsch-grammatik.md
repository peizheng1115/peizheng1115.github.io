---
layout: single
title: "Deutsche Grammatik: Enzyklopädisches 40-Kapitel-Kompendium (A1 - B2)"
permalink: /deutsch/grammatik/
sidebar:
  nav: "deutsch"
toc: false
---

<style>
/* Modern Light Blue Theme for Master Grammar Hub */
.hub-container {
    max-width: 1100px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    color: #0f172a;
}

/* Hero Section */
.hub-hero {
    background: linear-gradient(135deg, #e0f2fe 0%, #f0f9ff 60%, #ffffff 100%);
    border: 1px solid #bae6fd;
    border-radius: 18px;
    padding: 36px 32px;
    margin-bottom: 32px;
    box-shadow: 0 4px 24px -2px rgba(2, 132, 199, 0.1);
}
.hub-hero-badge {
    display: inline-block;
    background-color: #0284c7;
    color: #ffffff;
    font-weight: 700;
    font-size: 0.85rem;
    padding: 4px 14px;
    border-radius: 9999px;
    letter-spacing: 0.6px;
    text-transform: uppercase;
    margin-bottom: 12px;
}
.hub-hero-title {
    font-size: 2.2rem;
    font-weight: 800;
    color: #0369a1;
    margin: 0 0 14px 0;
    line-height: 1.2;
}
.hub-hero-desc {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #334155;
    margin: 0 0 24px 0;
}
.hub-stats-row {
    display: flex;
    flex-wrap: wrap;
    gap: 18px;
}
.hub-stat-item {
    background: #ffffff;
    border: 1px solid #bae6fd;
    border-radius: 10px;
    padding: 12px 20px;
    display: flex;
    flex-direction: column;
}
.hub-stat-num {
    font-size: 1.4rem;
    font-weight: 800;
    color: #0284c7;
}
.hub-stat-label {
    font-size: 0.82rem;
    color: #64748b;
    font-weight: 600;
    text-transform: uppercase;
}

/* 4 Level Cards Grid */
.hub-levels-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 18px;
    margin-bottom: 36px;
}
.hub-level-card {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-top: 5px solid #0284c7;
    border-radius: 12px;
    padding: 22px 20px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.03);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    transition: transform 0.2s, box-shadow 0.2s;
}
.hub-level-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 24px rgba(2, 132, 199, 0.12);
}
.lvl-card-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 12px;
}
.lvl-badge {
    background: #e0f2fe;
    color: #0284c7;
    font-size: 0.78rem;
    font-weight: 700;
    padding: 3px 10px;
    border-radius: 9999px;
}
.lvl-count {
    font-size: 0.8rem;
    font-weight: 700;
    color: #64748b;
}
.lvl-name {
    font-size: 1.2rem;
    font-weight: 700;
    color: #0f172a;
    margin: 0 0 8px 0;
}
.lvl-desc {
    font-size: 0.9rem;
    color: #475569;
    line-height: 1.5;
    margin-bottom: 18px;
    flex-grow: 1;
}
.lvl-cta-btn {
    display: block;
    background: #f0f9ff;
    color: #0284c7;
    border: 1px solid #7dd3fc;
    font-weight: 700;
    font-size: 0.9rem;
    padding: 8px 14px;
    border-radius: 8px;
    text-align: center;
    text-decoration: none;
    transition: all 0.2s;
}
.lvl-cta-btn:hover {
    background: #0284c7;
    color: #ffffff;
}

/* Syllabus Accordions */
.hub-syllabus-header {
    margin: 40px 0 20px 0;
    padding-bottom: 10px;
    border-bottom: 2px solid #e2e8f0;
}
.hub-syllabus-header h2 {
    font-size: 1.6rem;
    color: #0369a1;
    margin: 0 0 6px 0;
}
.hub-syllabus-header p {
    color: #64748b;
    margin: 0;
    font-size: 0.96rem;
}

.hub-accordion-section {
    margin-bottom: 20px;
}
.level-details {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    overflow: hidden;
}
.level-summary {
    background: #f8fafc;
    padding: 16px 22px;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-weight: 700;
    font-size: 1.08rem;
    color: #1e293b;
    border-bottom: 1px solid #e2e8f0;
    user-select: none;
}
.level-summary:hover {
    background: #f0f9ff;
}
.sum-left {
    display: flex;
    align-items: center;
    gap: 12px;
}
.sum-badge {
    background: #0284c7;
    color: #ffffff;
    padding: 3px 10px;
    border-radius: 6px;
    font-size: 0.82rem;
    font-weight: 800;
}
.sum-title {
    font-weight: 700;
    color: #0f172a;
}
.sum-count {
    font-size: 0.85rem;
    color: #64748b;
    font-weight: 600;
}

.accordion-content {
    padding: 8px 16px;
}
.acc-chapter-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 10px;
    border-bottom: 1px solid #f1f5f9;
}
.acc-chapter-row:last-child {
    border-bottom: none;
}
.acc-ch-left {
    display: flex;
    align-items: flex-start;
    gap: 14px;
}
.acc-ch-num {
    background: #e0f2fe;
    color: #0369a1;
    font-size: 0.78rem;
    font-weight: 800;
    padding: 3px 8px;
    border-radius: 4px;
    white-space: nowrap;
}
.acc-ch-title {
    font-size: 0.98rem;
    font-weight: 700;
    color: #0f172a;
    text-decoration: none;
}
.acc-ch-title:hover {
    color: #0284c7;
}
.acc-rule-preview {
    font-size: 0.86rem;
    color: #475569;
    margin-top: 3px;
}
.acc-ch-right {
    display: flex;
    align-items: center;
    gap: 14px;
}
.acc-formula-preview code {
    background: #f1f5f9;
    color: #0369a1;
    font-size: 0.82rem;
    padding: 3px 8px;
    border-radius: 4px;
}
.acc-ch-link {
    background: #ffffff;
    color: #0284c7;
    border: 1px solid #bae6fd;
    padding: 4px 10px;
    border-radius: 6px;
    font-size: 0.82rem;
    font-weight: 700;
    text-decoration: none;
    white-space: nowrap;
}
.acc-ch-link:hover {
    background: #0284c7;
    color: #ffffff;
}

/* Bottom Action Banner */
.hub-bottom-banner {
    background: linear-gradient(135deg, #0284c7 0%, #0369a1 100%);
    color: #ffffff;
    border-radius: 14px;
    padding: 28px;
    margin-top: 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 18px;
}
.hub-bottom-banner h3 {
    color: #ffffff;
    margin: 0 0 6px 0;
    font-size: 1.3rem;
}
.hub-bottom-banner p {
    color: #e0f2fe;
    margin: 0;
    font-size: 0.95rem;
}
.hub-bottom-btn {
    background: #ffffff;
    color: #0369a1;
    font-weight: 700;
    padding: 10px 22px;
    border-radius: 8px;
    text-decoration: none;
    transition: transform 0.15s;
}
.hub-bottom-btn:hover {
    transform: scale(1.03);
}
</style>

<div class="hub-container">
    <div class="hub-hero">
        <span class="hub-hero-badge">Enzyklopädisches Referenzwerk</span>
        <h1 class="hub-hero-title">Deutsche Grammatik: Das 40-Kapitel-Kompendium</h1>
        <p class="hub-hero-desc">
            Vollständige, lehrwerkgenaue Abdeckung der deutschen Grammatik von <strong>A1 (Elementar)</strong> über <strong>A2 (Grundstufe)</strong> und <strong>B1 (Mittelstufe I)</strong> bis <strong>B2 (Gehobene Fach- & Wissenschaftssprache)</strong>. Konzipiert nach <em>Das Leben A1/A2/B1</em>, <em>Complete German All-in-One (Practice Makes Perfect)</em>, <em>501 German Verbs</em>, <em>DT Training C1</em> und <em>新编大学德语</em>.
        </p>
        <div class="hub-stats-row">
            <div class="hub-stat-item">
                <span class="hub-stat-num">40</span>
                <span class="hub-stat-label">Strukturierte Kapitel</span>
            </div>
            <div class="hub-stat-item">
                <span class="hub-stat-num">4 Stufen</span>
                <span class="hub-stat-label">A1 • A2 • B1 • B2</span>
            </div>
            <div class="hub-stat-item">
                <span class="hub-stat-num">65+</span>
                <span class="hub-stat-label">Grammatik-Tabellen</span>
            </div>
            <div class="hub-stat-item">
                <span class="hub-stat-num">200+</span>
                <span class="hub-stat-label">Zweisprachige Beispielsätze</span>
            </div>
        </div>
    </div>

    <!-- 4 Level Cards -->
    <div class="hub-levels-grid">
        
        <div class="hub-level-card">
            <div class="lvl-card-top">
                <span class="lvl-badge">CEFR A1 Anfänger</span>
                <span class="lvl-count">10 Kapitel</span>
            </div>
            <h3 class="lvl-name">Stufe A1</h3>
            <p class="lvl-desc">Vollständiges Grundstufen-Kompendium: Genus-Systematik &amp; Endungsregeln, die 5 Pluralbildungsklassen, Artikel- &amp; Possessivgefüge, Konjugation...</p>
            <div class="lvl-btn-row">
                <a href="/deutsch/grammatik/a1/" class="lvl-cta-btn">📖 Vollständigen Leitfaden öffnen →</a>
            </div>
        </div>
        
        <div class="hub-level-card">
            <div class="lvl-card-top">
                <span class="lvl-badge">CEFR A2 Grundstufe II</span>
                <span class="lvl-count">10 Kapitel</span>
            </div>
            <h3 class="lvl-name">Stufe A2</h3>
            <p class="lvl-desc">Erweiterte Grundstufe: Dativ-Systematik &amp; Dativ-Verben, Wechselpräpositionen (Wohin vs. Wo), Positions- &amp; Aktionsverbpaare, Reflexive Verben...</p>
            <div class="lvl-btn-row">
                <a href="/deutsch/grammatik/a2/" class="lvl-cta-btn">📖 Vollständigen Leitfaden öffnen →</a>
            </div>
        </div>
        
        <div class="hub-level-card">
            <div class="lvl-card-top">
                <span class="lvl-badge">CEFR B1 Mittelstufe I</span>
                <span class="lvl-count">10 Kapitel</span>
            </div>
            <h3 class="lvl-name">Stufe B1</h3>
            <p class="lvl-desc">Mittelstufen-Standard für selbstständige akademische und professionelle Sprachverwendung: Konjunktiv II in Gegenwart &amp; Vergangenheit, irreal...</p>
            <div class="lvl-btn-row">
                <a href="/deutsch/grammatik/b1/" class="lvl-cta-btn">📖 Vollständigen Leitfaden öffnen →</a>
            </div>
        </div>
        
        <div class="hub-level-card">
            <div class="lvl-card-top">
                <span class="lvl-badge">CEFR B2 Fortgeschritten</span>
                <span class="lvl-count">10 Kapitel</span>
            </div>
            <h3 class="lvl-name">Stufe B2</h3>
            <p class="lvl-desc">Die Meisterschaft des akademischen und publizistischen Ausdrucks: 30+ Nomen-Verb-Verbindungen (Funktionsverbgefüge / FVG), Passiv-Ersatzform...</p>
            <div class="lvl-btn-row">
                <a href="/deutsch/grammatik/b2/" class="lvl-cta-btn">📖 Vollständigen Leitfaden öffnen →</a>
            </div>
        </div>
        
    </div>

    <!-- Complete 40-Chapter Syllabus Accordion -->
    <div class="hub-syllabus-header">
        <h2>📋 Vollständiger Lehrplan aller 40 Kapitel</h2>
        <p>Klicken Sie auf eine Stufe, um die Kapitelübersicht auszuklappen, oder springen Sie direkt zu einem beliebigen Kapitel:</p>
    </div>

    
        <div class="hub-accordion-section">
            <details class="level-details" open>
                <summary class="level-summary">
                    <div class="sum-left">
                        <span class="sum-badge">A1</span>
                        <span class="sum-title">Stufe A1: Grundstufe I – Fundamentale Grammatik &amp; Satzbau</span>
                    </div>
                    <span class="sum-count">10 Kapitel</span>
                </summary>
                <div class="accordion-content">
                    
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-01</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch01-genus" class="acc-ch-title">Kapitel 1: Nomen, Genus-Systematik &amp; Morphologische Erkennung</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Maskuline Nomen (der):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch01-genus" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-02</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch02-plural" class="acc-ch-title">Kapitel 2: Die 5 Hauptklassen der Pluralbildung &amp; Sonderformen</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>Klasse 1: Endung -(e)n (ohne Umlaut):</strong> Betrifft ca. 95% aller Feminina (<em>die Zelle → die Zellen, die Reaktion → die Reaktionen, die Fakultät → die Fakultäten</em>), maskuline N-Deklinationswörter (<em>der Student → die Studenten</em>) und wenige Neutra (<em>das Auge → die Augen, das Ohr → die Ohren</em>).</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch02-plural" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-03</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch03-articles-pronouns" class="acc-ch-title">Kapitel 3: Artikelwörter, Negation (kein vs. nicht) &amp; Possessivartikel</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>Artikeldeklination:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch03-articles-pronouns" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-04</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch04-verbs-present" class="acc-ch-title">Kapitel 4: Konjugation im Präsens (Schwache, Starke &amp; Unregelmäßige Verben)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Regelmäßige schwache Verben:</strong> Verbstamm + Personalendungen: <em>-e, -st, -t, -en, -t, -en</em> (<em>lernen → ich lerne, du lernst, er lernt, wir lernen, ihr lernt, sie lernen</em>).</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch04-verbs-present" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-05</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch05-syntax-fields" class="acc-ch-title">Kapitel 5: Satzbau, Stellungsfelder, Inversion &amp; Satzklammer</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Das Grundgesetz des Hauptsatzes:</strong> Das finite (konjugierte) Verb besetzt ausnahmslos <strong>Position 2</strong>!</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch05-syntax-fields" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-06</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch06-akkusativ-prepositions" class="acc-ch-title">Kapitel 6: Der Akkusativ (Direktes Objekt) &amp; Feste Akkusativ-Präpositionen</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>Akkusativ-Funktion:</strong> Der Akkusativ (Wen/Was-Fall) bezeichnet das Ziel, den Gegenstand oder den Empfänger der direkten verbalen Handlung.</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch06-akkusativ-prepositions" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-07</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch07-prefixes" class="acc-ch-title">Kapitel 7: Trennbare &amp; Untrennbare Verben im Detail</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Trennbare Verben (Präfix ist immer STARK BETONT):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch07-prefixes" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-08</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch08-modal-verbs" class="acc-ch-title">Kapitel 8: Die 6 Modalverben &amp; Das Vollverb &#x27;mögen&#x27;</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>Modalverben-Konjugation Besonderheit:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch08-modal-verbs" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-09</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch09-imperativ" class="acc-ch-title">Kapitel 9: Der Imperativ (Die Befehls- &amp; Aufforderungsform)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. du-Form (Informell Singular):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch09-imperativ" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A1-10</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a1/#a1-ch10-perfekt" class="acc-ch-title">Kapitel 10: Das Perfekt (Die mündliche Vergangenheitsform)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Grundstruktur des Perfekts:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a1/#a1-ch10-perfekt" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
                </div>
            </details>
        </div>
        
        <div class="hub-accordion-section">
            <details class="level-details" open>
                <summary class="level-summary">
                    <div class="sum-left">
                        <span class="sum-badge">A2</span>
                        <span class="sum-title">Stufe A2: Grundstufe II – Kasuskomplex, Relationen &amp; Satzverbindungen</span>
                    </div>
                    <span class="sum-count">10 Kapitel</span>
                </summary>
                <div class="accordion-content">
                    
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-01</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch01-dativ" class="acc-ch-title">Kapitel 1: Der Dativ (Wem-Fall) &amp; Wortstellung bei doppelten Objekten</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Artikelformen im Dativ:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch01-dativ" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-02</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch02-dativ-verbs-prep" class="acc-ch-title">Kapitel 2: Die wichtigsten Dativ-Verben &amp; Feste Dativ-Präpositionen</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Die wichtigsten Verben mit Dativergänzung:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch02-dativ-verbs-prep" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-03</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch03-two-way-prepositions" class="acc-ch-title">Kapitel 3: Wechselpräpositionen (Wohin Akk vs. Wo Dat) &amp; Positionsverben</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Die goldene Regel der 9 Wechselpräpositionen:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch03-two-way-prepositions" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-04</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch04-reflexive" class="acc-ch-title">Kapitel 4: Reflexive &amp; Reziproke Verben (Akkusativ vs. Dativ)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Echte vs. Unechte Reflexivverben:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch04-reflexive" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-05</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch05-adjective-declension" class="acc-ch-title">Kapitel 5: Die vollständige Adjektivdeklination (Typ 1, Typ 2, Typ 3)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>Grundprinzip:</strong> Ein Adjektiv vor einem Nomen (attributiv) MUSS dekliniert werden. Es zeigt Genus, Numerus und Kasus an.</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch05-adjective-declension" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-06</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch06-comparative-superlative" class="acc-ch-title">Kapitel 6: Komparativ &amp; Superlativ (Steigerung &amp; attributive Endungen)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Die drei Steigerungsstufen:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch06-comparative-superlative" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-07</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch07-subordinate-clauses" class="acc-ch-title">Kapitel 7: Nebensätze I: Kausal (weil/da), Objekt (dass), Konditional (wenn/falls) &amp; ob</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Die fundamentale Nebensatz-Regel (Verbletztstellung):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch07-subordinate-clauses" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-08</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch08-temporalsatz" class="acc-ch-title">Kapitel 8: Temporale Nebensätze: Die genaue Unterscheidung von &#x27;wenn&#x27; und &#x27;als&#x27;</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Die Gretchenfrage: &#x27;wenn&#x27; oder &#x27;als&#x27;?</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch08-temporalsatz" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-09</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch09-praeteritum" class="acc-ch-title">Kapitel 9: Das Präteritum (Die schriftliche Vergangenheitsform)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Verwendung des Präteritums:</strong> Hauptsächlich in schriftlichen Berichten, wissenschaftlichen Artikeln, Protokollen, Zeitungsberichten und literarischen Erzählungen. Im Alltag werden <em>sein, haben</em> und Modalverben auch mündlich im Präteritum gebraucht.</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch09-praeteritum" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">A2-10</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/a2/#a2-ch10-indirect-questions" class="acc-ch-title">Kapitel 10: Indirekte Fragesätze &amp; Höfliche Bitten mit Konjunktiv II</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Indirekte W-Fragen:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/a2/#a2-ch10-indirect-questions" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
                </div>
            </details>
        </div>
        
        <div class="hub-accordion-section">
            <details class="level-details" open>
                <summary class="level-summary">
                    <div class="sum-left">
                        <span class="sum-badge">B1</span>
                        <span class="sum-title">Stufe B1: Mittelstufe I – Komplexe Syntax, Passiv &amp; Irrealis</span>
                    </div>
                    <span class="sum-count">10 Kapitel</span>
                </summary>
                <div class="accordion-content">
                    
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-01</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch01-konjunktiv2" class="acc-ch-title">Kapitel 1: Der Konjunktiv II (Gegenwart, Vergangenheit &amp; Irreale Konditionalsätze)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Funktionen des Konjunktiv II:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch01-konjunktiv2" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-02</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch02-vorgangspassiv" class="acc-ch-title">Kapitel 2: Das Vorgangspassiv in allen 6 Zeitformen &amp; Passiv mit Modalverben</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Das Grundprinzip:</strong> Im Passiv steht die Handlung (der Vorgang) im Mittelpunkt; der Handelnde ist unwichtig, unbekannt oder allgemein.</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch02-vorgangspassiv" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-03</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch03-zustandspassiv" class="acc-ch-title">Kapitel 3: Das Zustandspassiv (Stative Passive) &amp; Abgrenzung zum Vorgangspassiv</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Vorgangspassiv vs. Zustandspassiv:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch03-zustandspassiv" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-04</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch04-relativsaetze" class="acc-ch-title">Kapitel 4: Relativsätze (Komplettes 4-Fälle-System, Präpositionen &amp; Indefinite Relativsätze)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Kongruenz und Kasus des Relativpronomens:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch04-relativsaetze" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-05</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch05-genitive" class="acc-ch-title">Kapitel 5: Der Genitiv (Wessen-Fall), N-Deklination &amp; Genitiv-Präpositionen</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Formen des Genitivs:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch05-genitive" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-06</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch06-verbs-prepositions-dawo" class="acc-ch-title">Kapitel 6: Verben mit festen Präpositionen &amp; Pronominaladverbien (da-/wo-)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Präpositionalobjekte:</strong> Viele Verben sind fest an eine bestimmte Präposition gekoppelt, die ihren Kasus bestimmt.</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch06-verbs-prepositions-dawo" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-07</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch07-infinitive-clauses" class="acc-ch-title">Kapitel 7: Infinitivkonstruktionen: Infinitiv mit &#x27;zu&#x27; &amp; Finalsätze (&#x27;um... zu&#x27; vs. &#x27;damit&#x27;)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Der Infinitiv mit &#x27;zu&#x27;:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch07-infinitive-clauses" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-08</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch08-adverbial-clauses" class="acc-ch-title">Kapitel 8: Konzessiv-, Temporal-, Kausal- &amp; Konsekutivsätze im B1-Niveau</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Konzessivsätze (Gegengrund / Einräumung):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch08-adverbial-clauses" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-09</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch09-future-tenses" class="acc-ch-title">Kapitel 9: Futur I &amp; Futur II: Zukunftspläne, Versprechen &amp; Vermutungen</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Futur I (werden + Infinitiv am Satzende):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch09-future-tenses" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B1-10</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b1/#b1-ch10-word-formation" class="acc-ch-title">Kapitel 10: Wortbildung &amp; Wortschatzerweiterung: Derivation &amp; Komposition</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Komposition (Zusammensetzung):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b1/#b1-ch10-word-formation" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
                </div>
            </details>
        </div>
        
        <div class="hub-accordion-section">
            <details class="level-details" open>
                <summary class="level-summary">
                    <div class="sum-left">
                        <span class="sum-badge">B2</span>
                        <span class="sum-title">Stufe B2: Mittelstufe II – Gehobene Wissenschafts- &amp; Fachsprache</span>
                    </div>
                    <span class="sum-count">10 Kapitel</span>
                </summary>
                <div class="accordion-content">
                    
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-01</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch01-fvg" class="acc-ch-title">Kapitel 1: Nomen-Verb-Verbindungen (Funktionsverbgefüge / FVG)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Was ist ein Funktionsverbgefüge (FVG)?</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch01-fvg" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-02</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch02-passiv-alternatives" class="acc-ch-title">Kapitel 2: Passiv-Ersatzformen &amp; Modale Passivumschreibungen</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Warum Passiv-Ersatzformen?</strong> Häufungen des Vorgangspassivs mit <em>werden</em> wirken monoton. Ersatzformen bringen Abwechslung und drücken gleichzeitig modale Nuancen (Können / Müssen) aus.</div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch02-passiv-alternatives" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-03</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch03-participles" class="acc-ch-title">Kapitel 3: Erweiterte Partizipialattribute (Partizip I, II &amp; Gerundivum)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Partizip I als Adjektiv (Partizip Präsens: Verbstamm + -end):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch03-participles" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-04</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch04-connectors" class="acc-ch-title">Kapitel 4: Zweiteilige Konnektoren (Doppelkonjunktionen)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Kopulativ (Aufzählend / Verbindend):</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch04-connectors" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-05</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch05-subjective-modals" class="acc-ch-title">Kapitel 5: Subjektive Bedeutung der Modalverben (Epistemische Modalität)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Was bedeutet &#x27;subjektiver Gebrauch&#x27;?</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch05-subjective-modals" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-06</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch06-nominalstil" class="acc-ch-title">Kapitel 6: Wissenschaftlicher Nominalstil vs. Verbalstil (Systematische Transformation)</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Verbalstil vs. Nominalstil:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch06-nominalstil" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-07</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch07-konjunktiv1" class="acc-ch-title">Kapitel 7: Der Konjunktiv I &amp; Die Indirekte Rede in Wissenschaft und Medien</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Funktion des Konjunktiv I:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch07-konjunktiv1" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-08</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch08-modalpartikeln" class="acc-ch-title">Kapitel 8: Modalpartikeln &amp; Nuancen der mündlichen Fachkommunikation</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Was sind Modalpartikeln?</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch08-modalpartikeln" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-09</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch09-noun-preposition" class="acc-ch-title">Kapitel 9: Feste Nomen-Präposition-Verbindungen in der Wissenschaftssprache</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Warum Nomen-Präposition-Verbindungen?</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch09-noun-preposition" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
            <div class="acc-chapter-row">
                <div class="acc-ch-left">
                    <span class="acc-ch-num">B2-10</span>
                    <div class="acc-ch-meta">
                        <a href="/deutsch/grammatik/b2/#b2-ch10-text-coherence" class="acc-ch-title">Kapitel 10: Textkohärenz, Satzverknüpfung &amp; Konnektoren im akademischen Diskurs</a>
                        <div class="acc-rule-preview">💡 <strong>Schwerpunkte:</strong> <strong>1. Die 4 syntaktischen Konnektoren-Klassen im Deutschen:</strong></div>
                    </div>
                </div>
                <div class="acc-ch-right">
                    
                    <a href="/deutsch/grammatik/b2/#b2-ch10-text-coherence" class="acc-ch-link">Öffnen ↗</a>
                </div>
            </div>
            
                </div>
            </details>
        </div>
        

    <!-- Bottom Banner -->
    <div class="hub-bottom-banner">
        <div>
            <h3>📥 Vollständiges Kompendium offline nutzen</h3>
            <p>Laden Sie die gesamten 40 Kapitel als Markdown-Handbuch für Obsidian, Logseq oder PDF-Druck herunter.</p>
        </div>
        <a href="/files/Deutsch_Grammatik_Kompendium.md" class="hub-bottom-btn" download>Kompendium herunterladen (.md)</a>
    </div>
</div>
