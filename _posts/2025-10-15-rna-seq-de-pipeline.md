---
title: "RNA-seq Differential Expression Pipeline"
layout: single
permalink: /rna-seq-de-pipeline/
---

# RNA-seq Differential Expression Pipeline
![QC Plot](figures/qc_plot.png)

## 🧠 Overview
A reproducible RNA-seq differential expression workflow built with **R/DESeq2**.

## ⚙️ Features
- Quality control (FastQC summaries, sample correlation)  
- Normalization and DE analysis via DESeq2  
- Volcano and MA plots  
- Configurable metadata file  
- Clean output tables

## 🚀 Quick Start
```bash
conda env create -f environment.yml  
bash run_pipeline.sh  
