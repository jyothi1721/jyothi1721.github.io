---
title: Rheumatoid Arthritis Project
tools: [RNA-seq]
description: DESeq analysis for RA datasets
---

Link to code repo and results: [GitHub Repo](https://github.com/jyothi1721/Rheumatoid_arthritis_RNA_seq)

---

## 🧬 Overview

This project focuses on elucidating potential molecular mechanisms differentiating osteoarthritis (OA) and rheumatoid arthritis (RA) in patient synovial cells. The goal is to identify differentially expressed genes (DEGs) and pathways that may be associated with RA progression, thus providing insights for potential biomarkers or therapeutic targets. 

---

## 🧪 Introduction

Rheumatoid Arthritis is a chronic autoimmune disorder that primarily affects joints but can also cause systemic inflammation. The purpose of this study is to use bioinformatics methods to conduct a dual-disease joint study of osteoarthritis and rheumatoid arthritis, revealing the internal connections and differences between the two. RNA-seq technology enables high-throughput analysis of gene expression levels, making it ideal for investigating transcriptomic changes in RA and OA. This project aims to analyze and examine the datasets from the publication - <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0303506" target="_blank" style="color: #007acc; text-decoration: underline;"> published in PLOS ONE (2024).
    
In this project:

- Microarray datasets for RA and OA from Gene Expression Omnibus (GEO) database were obtained
- DESeq2 was employed for normalization and differential expression analysis
- Batch effect correction was applied
- Enrichment analysis (Gene Ontology & KEGG Pathway) was performed to identify key pathways
- Volcano plots and heatmaps were generated for data visualization

---

## 🛠 Tools & Methods

- **Data Source**: GEO Database
- **Language**: R
- **Key Packages**: `DESeq2`, `ggplot2`, `pheatmap`, `biomaRt`, `limma`
- **Pipeline**:
  1. Data import and preprocessing
  2. Quality control
  3. Normalization (DESeq2)
  4. DEG analysis
  5. Visualization (PCA, Volcano plot)
  6. Functional enrichment (GO, KEGG)

---

## 📊 Results

### 🔹 PCA Plot


---

### 🔹 Volcano Plot


---

### 🔹 Top Differentially Expressed Genes

---

---
