---
permalink: /knowledge-hub/
title: "Knowledge Hub & Research Notes"
author_profile: true
---

Welcome to my academic knowledge hub. This space serves as a living synthesis of research notes, methodologies, curated databases, and technical guides spanning bioengineering, computational biology, and translational medicine.

---

## Table of Contents
1. [Organ-on-a-Chip (OOC) & Microphysiological Systems](#1-organ-on-a-chip-ooc--microphysiological-systems)
2. [Python for Biology & Bioinformatics](#2-python-for-biology--bioinformatics)
3. [R in Biology & Bioconductor](#3-r-in-biology--bioconductor)
4. [Genomics, Single-Cell RNA-Seq & Spatial Transcriptomics](#4-genomics-single-cell-rna-seq--spatial-transcriptomics)
5. [Cancer Biology & Oncology Informatics](#5-cancer-biology--oncology-informatics)
6. [Drug Screening, Assays & Pharmacology](#6-drug-screening-assays--pharmacology)
7. [Translational & Clinical Research](#7-translational--clinical-research)
8. [Scientific Tools & Academic Resources](#8-scientific-tools--academic-resources)

---

## 1. Organ-on-a-Chip (OOC) & Microphysiological Systems

Organ-on-a-Chip (OOC) technologies merge microfluidics, biomaterials, and cell biology to emulate the structural, mechanical, and biochemical microenvironments of living human tissues in vitro.

### Core Concepts & Architectures
* **Microfluidic Perfusion**: Dynamic laminar flow providing physiological shear stress ($\tau = \frac{6\mu Q}{w h^2}$ in rectangular microchannels), continuous nutrient replenishment, and waste elimination.
* **Membrane Barrier Models**: Porous ECM-coated membranes (e.g., PDMS, PET, polycarbonate) establishing tissue-tissue interfaces:
  * **Blood-Brain Barrier (BBB)**: Brain microvascular endothelial cells (BMECs), astrocytes, and pericytes under flow; monitored via Transepithelial/Transendothelial Electrical Resistance (TEER).
  * **Gut-on-a-Chip**: Intestinal epithelial monolayer (Caco-2 / organoids) subjected to cyclic peristaltic-like mechanical deformation and microbial co-culture.
  * **Lung Alveolus-on-a-Chip**: Epithelial-endothelial air-liquid interface (ALI) mimicking physiological breathing motions.
  * **Tumor-on-a-Chip**: Microfluidic 3D tumor spheroids/organoids embedded in hydrogels to study hypoxia gradients, angiogenesis, and immune extravasation.
* **Sensing & Readouts**: Integrated electrodes for real-time TEER, optical dissolved oxygen ($O_2$) sensors, micro-pH probes, and confocal imaging windows.

### Key Organizations, Databases & Links
* **[EUROoCS (European Organ-on-Chip Society)](https://euroocs.eu/)**: Premier European network advancing research, standards, and regulatory qualification of OOC models.
* **[ORCHID Roadmap](https://h2020-orchid.eu/)**: European infrastructure roadmap for organ-on-chip technology.
* **[FDA Modernization Act 2.0 (FDA Guidance)](https://www.fda.gov/)**: Legislation enabling non-animal alternatives (such as cell-based microphysiological systems) for drug evaluation and safety testing.
* **[Lab on a Chip (RSC)](https://pubs.rsc.org/en/journals/journalissues/lc)**: Leading journal for microfluidics and microscale bioengineering.

---

## 2. Python for Biology & Bioinformatics

Python is a cornerstone of computational biology, data science, and machine learning in biomedical discovery.

### Essential Ecosystem & Toolkits
* **Sequence & Structure Analysis**:
  * `BioPython` (`Bio.Seq`, `Bio.PDB`, `Bio.Align`): Sequence manipulation, FASTA/FASTQ/GenBank parsing, and PDB coordinate extraction.
  * `PyMOL API` / `ChimeraX scripting`: Headless structural visualization, cavity detection, and ligand binding pocket analysis.
* **Single-Cell & High-Dimensional Omics**:
  * `Scanpy`: Large-scale single-cell RNA sequencing data analysis (quality control, PCA, UMAP, Louvain/Leiden clustering, marker genes).
  * `Squidpy`: Spatial transcriptomics and cellular neighborhood graph analysis.
  * `Anndata`: Annotated data matrix standard holding count matrices (`X`), observation metadata (`obs`), and feature metadata (`var`).
* **Machine Learning & Modeling**:
  * `PyTorch` / `PyTorch Geometric (PyG)`: Graph Neural Networks (GNNs) for molecular property prediction and spatial cellular networks.
  * `Scikit-learn`: Dimensionality reduction, classification, regression, and survival analysis models.

### Recommended Workflows
```python
# Quick start: Inspecting an AnnData object for single-cell analysis
import scanpy as sc

# Load standard 10x dataset
adata = sc.datasets.pbmc3k()
sc.pp.filter_cells(adata, min_genes=200)
sc.pp.filter_genes(adata, min_cells=3)
sc.pp.normalize_total(adata, target_sum=1e4)
sc.pp.log1p(adata)
sc.pp.highly_variable_genes(adata, n_top_genes=2000)
sc.tl.pca(adata, svd_solver='arpack')
sc.pp.neighbors(adata, n_neighbors=10, n_pcs=40)
sc.tl.umap(adata)
```

---

## 3. R in Biology & Bioconductor

R provides the most statistically rigorous environment for differential expression, multi-omics integration, and publication-ready biological visualization.

### Core Bioconductor Packages
* **Differential Gene Expression (Bulk RNA-seq)**:
  * `DESeq2` & `edgeR`: Negative binomial generalized linear models for count-based transcriptomic quantification and normalization ($sizeFactors$, $vst$, $rlog$).
  * `limma-voom`: Linear modeling adapted for RNA-seq and microarray data.
* **Single-Cell RNA-seq**:
  * `Seurat` (v5): End-to-end framework for quality control, batch correction (Harmony, CCA, RPCA), multimodal data integration, and marker identification.
  * `SingleCellExperiment`: S4-class container for scRNA data in the Bioconductor ecosystem.
* **Pathway & Functional Enrichment**:
  * `clusterProfiler`: GO (Gene Ontology), KEGG, and Reactome over-representation analysis (ORA) and Gene Set Enrichment Analysis (GSEA).
  * `pathview`: Overlaying expression data directly onto KEGG pathway maps.
* **Visualization**:
  * `ggplot2`, `ComplexHeatmap`, `EnhancedVolcano`, `patchwork`.

### Curated Bioconductor Resources
* **[Bioconductor Project](https://bioconductor.org/)**: The premier repository of open-source bioinformatics software in R.
* **[Orchestrating Single-Cell Analysis with Bioconductor (OSCA)](https://bioconductor.org/books/release/OSCA/)**: Comprehensive, peer-reviewed guide for scRNA-seq in R.

---

## 4. Genomics, Single-Cell RNA-Seq & Spatial Transcriptomics

Understanding tissue heterogeneity requires resolving gene expression from single cells to spatial tissue coordinates.

### 1. Single-Cell RNA Sequencing (scRNA-seq)
* **Assays**: Droplet-based microfluidics (10x Genomics Chromium, Drop-seq, inDrops), plate-based full-length sequencing (Smart-seq2/3).
* **Key Analytical Steps**:
  1. **Pre-processing**: Cell Ranger / STARsolo alignment, UMI de-duplication, doublet removal (`DoubletFinder`, `scrublet`).
  2. **QC Metrics**: Total UMI counts, detected gene counts ($nFeature$), mitochondrial gene fraction ($% \text{mito} < 10-20\%$).
  3. **Batch Correction & Integration**: Harmony, Seurat CCA, BBKNN, scVI (variational autoencoders).
  4. **Cell Type Annotation**: Curated marker databases (CellMarker 2.0, PanglaoDB) and automated label transfer (`SingleR`, `CellTypist`).
  5. **Downstream Inference**: Pseudotime trajectory analysis (`Monocle3`, `Slingshot`, `scVelo` RNA velocity), cell-cell communication (`CellChat`, `CellPhoneDB`).

### 2. Spatial Transcriptomics (ST)
* **Technologies**:
  * **Sequencing-based (Grid/Barcoded)**: 10x Genomics Visium (55 $\mu$m spots), Stereo-seq, Slide-seq (sub-cellular barcoding).
  * **Imaging-based (In situ hybridization/sequencing)**: 10x Xenium, Vizgen MERSCOPE (MERFISH), CosMx SMI (Spatial Molecular Imager).
* **Core Tasks**:
  * **Cell-type deconvolution** for multi-cellular spots (e.g., `RCTD`, `Seurat Anchor Transfer`, `cell2location`).
  * **Spatial domain identification** (`SpaGCN`, `BayesSpace`).
  * **Spatially variable genes (SVGs)** and ligand-receptor proximity networks.

---

## 5. Cancer Biology & Oncology Informatics

Dissecting tumor heterogeneity, microenvironmental interactions, and therapeutic vulnerabilities through multi-omics datasets.

### Biological Pillars
* **The Hallmarks of Cancer**: Sustained proliferative signaling, evading growth suppressors, resisting cell death, enabling replicative immortality, inducing angiogenesis, activating invasion and metastasis, reprogramming energy metabolism, and evading immune destruction.
* **Tumor Microenvironment (TME)**: Complex interaction network of malignant cells, cancer-associated fibroblasts (CAFs), tumor-associated macrophages (TAMs: M1/M2 polarization), endothelial cells, and cytotoxic T lymphocytes ($CD8^+$ TILs).
* **Immune Checkpoints**: PD-1/PD-L1, CTLA-4, LAG-3, TIGIT regulation in immune exhaustion and immunotherapy response.

### Public Oncology Databases & Platforms
* **[cBioPortal for Cancer Genomics](https://www.cbioportal.org/)**: Interactive exploration of multidimensional cancer genomics data (mutations, copy number, expression, clinical outcomes).
* **[The Cancer Genome Atlas (TCGA / GDC Data Portal)](https://portal.gdc.cancer.gov/)**: Molecular characterization over 20,000 primary cancer and matched normal samples across 33 cancer types.
* **[Cancer Dependency Map (DepMap)](https://depmap.org/portal/)**: Systematic CRISPR knockout screens and PRISM drug screens identifying genetic dependencies and drug vulnerabilities across hundreds of cancer cell lines.
* **[COSMIC (Catalogue of Somatic Mutations in Cancer)](https://cancer.sanger.ac.uk/cosmic)**: The world's largest database of somatic mutations in human cancer.

---

## 6. Drug Screening, Assays & Pharmacology

Transitioning from molecular targets to lead candidates through high-throughput and physiological model screening.

### Screening Methodologies
* **Target-Based Screening**: Biochemical assays (enzymatic kinase assays, TR-FRET, surface plasmon resonance / SPR) evaluating binding affinity ($K_d$) and inhibition constant ($K_i$).
* **Phenotypic Screening**: Cell-based or organ-on-a-chip functional assays monitoring viability, apoptosis, cell cycle arrest, or phenotypic changes without requiring upfront target commitment.
* **High-Throughput (HTS) & High-Content Screening (HCS)**: Automated 384/1536-well plate systems coupled with automated confocal fluorescence microscopy for multiparametric cellular analysis.
* **Dose-Response Pharmacology**: Fitting non-linear 4-parameter logistic models (Hill equation) to extract:
  $$\text{Response} = \text{Bottom} + \frac{\text{Top} - \text{Bottom}}{1 + 10^{(\log IC_{50} - X) \cdot \text{HillSlope}}}$$
  Evaluating $IC_{50}$ (half-maximal inhibitory concentration), $EC_{50}$, and Area Under Curve (AUC).

### Chemical Biology Databases
* **[PubChem](https://pubchem.ncbi.nlm.nih.gov/)**: World's largest open collection of chemical substances and bioactivity assay results.
* **[ChEMBL](https://www.ebi.ac.uk/chembl/)**: Manually curated database of bioactive molecules with drug-like properties maintained by EMBL-EBI.
* **[DrugBank](https://go.drugbank.com/)**: Comprehensive knowledge base of drug mechanisms, metabolism, and drug-drug interactions.
* **[Broad Institute Connectivity Map (CMap / L1000)](https://clue.io/)**: Systematic perturbation database linking gene expression changes to small molecules and genetic knockdowns.

---

## 7. Translational & Clinical Research

Translational research bridges fundamental biological discoveries with clinical validation and regulatory qualification.

### The Translational Continuum
1. **T0 / Basic Discovery**: Target validation, molecular pathology, in vitro & in silico mechanism elucidation.
2. **T1 / Preclinical & Proof-of-Concept**: Organ-on-chip, animal models, toxicology, PK/PD (pharmacokinetics / pharmacodynamics), ADME (Absorption, Distribution, Metabolism, Excretion).
3. **T2 / Clinical Trials**:
   * **Phase I**: Safety, tolerability, maximum tolerated dose (MTD), and pharmacokinetics in healthy volunteers or refractory patients ($N \approx 20-80$).
   * **Phase II**: Efficacy, dose-ranging, and initial safety in target patient population ($N \approx 100-300$).
   * **Phase III**: Randomized controlled trials (RCTs) against standard-of-care across multicenter cohorts ($N \approx 1,000-3,000$).
   * **Phase IV**: Post-marketing surveillance and real-world evidence (RWE).
4. **T3 & T4 / Clinical Practice & Public Health**: Guideline integration, comparative effectiveness, and healthcare policy.

### Regulatory & Clinical Trial Registries
* **[ClinicalTrials.gov](https://clinicaltrials.gov/)**: The global standard registry of clinical research studies.
* **[EU Clinical Trials Information System (CTIS)](https://euclinicaltrials.eu/)**: European registry for clinical trials in the EU/EEA.
* **[FDA Guidance for Industry](https://www.fda.gov/regulatory-information/search-fda-guidance-documents)**: Official protocols for IND (Investigational New Drug) and NDA (New Drug Application) filings.
* **[EMA (European Medicines Agency)](https://www.ema.europa.eu/)**: Scientific advice, orphan designation, and Marketing Authorisation Applications (MAA).

---

## 8. Scientific Tools & Academic Resources

For dedicated guides on scientific illustration, vector graphics tools, paper writing templates, and Academic English sentence banks, visit our **[Resources & Tools](/resources/)** page.
