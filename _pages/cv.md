---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Summary
Researcher at the **University of Pisa** (*Università di Pisa*), Pisa, Italy, specializing in microfluidic Organ-on-a-Chip (OOC) systems, single-cell and spatial transcriptomics, computational biology in Python/R, and translational drug screening assays.

<!-- 
Optional: If you have a PDF CV, place it in /files/cv.pdf and uncomment this button:
<p><a href="/files/cv.pdf" class="btn btn--primary"><i class="fas fa-file-pdf"></i> Download Full CV (PDF)</a></p>
-->

---

## Education
* **Researcher / Graduate Studies**
  * University of Pisa (*Università di Pisa*), Pisa, Italy
* *(Update with your previous degrees, universities, and graduation years)*

---

## Research & Professional Experience
* **Researcher** | University of Pisa
  * Focus: Microfluidic tissue barrier models, organ-on-a-chip technologies, bioinformatics pipelines, and translational oncology.
* *(Update with past lab rotations, internships, or academic positions)*

---

## Technical & Research Skills
* **Microfluidics & Tissue Engineering**:
  * Organ-on-a-Chip (OOC) microchannel fabrication and perfusion modeling
  * 3D cell culture, organoids, spheroids, and barrier models (TEER measurement)
  * Immunofluorescence staining, confocal microscopy, and live-cell imaging
* **Computational Biology & Bioinformatics**:
  * **Python**: `Scanpy`, `Squidpy`, `BioPython`, `PyMOL` API, `Pandas`, `NumPy`, `Scikit-learn`, `PyTorch`
  * **R / Bioconductor**: `Seurat` (v5), `DESeq2`, `edgeR`, `clusterProfiler`, `ComplexHeatmap`, `ggplot2`
  * **Omics Pipelines**: Bulk RNA-seq, Single-cell RNA-seq (10x Chromium), Spatial Transcriptomics (Visium, Xenium)
* **Pharmacology & Drug Screening**:
  * High-throughput screening (HTS) assay design, dose-response fitting ($IC_{50}$ / $EC_{50}$), toxicity profiling
* **Scientific Communication & Illustration**:
  * BioRender, Inkscape, Adobe Illustrator, LaTeX / Overleaf, Zotero

---

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

## Talks & Presentations
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
