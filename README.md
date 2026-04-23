# Bioinformatics Project – RNA-seq Analysis

---

## Project Title
RNA-seq Analysis of Breast Cancer vs Healthy Samples

---

## Project Purpose
This project aims to analyze RNA-seq data from human breast cancer and healthy tissue samples.  
The objective is to compare gene expression patterns between disease and normal conditions and prepare the dataset for downstream bioinformatics analysis and machine learning classification.

---

## Dataset Description

### Source:
Public data downloaded from NCBI SRA database.

### Classes:
- Class 0: Healthy samples (Adult normal breast)
- Class 1: Cancer samples (Breast invasive ductal carcinoma)

### Number of Samples:
- 5 Cancer samples
- 5 Healthy samples

### Data Type:
- RNA-seq
- Single-end reads
- FASTQ format

---

## Accession IDs

### Cancer Samples:
- SRR191639
- SRR191640
- SRR191641
- SRR191642
- SRR191643

### Healthy Samples:
- SRR537099
- SRR537100
- SRR537101
- SRR537102
- SRR537103

---

## Metadata File

A metadata file (metadata.csv) is included to describe the dataset.

### Columns:
- sample_id → FASTQ file name
- class_label → (0 = Healthy, 1 = Cancer)
- disease_type → Breast Cancer

This file is important for organizing the dataset and enabling machine learning classification.

---

## Project Structure

bioinformatics_project/
│
├── data/                # Contains FASTQ files
├── bioinfo_env/         # Virtual environment (ignored using .gitignore)
├── requirements.txt     # Python dependencies
├── metadata.csv         # Dataset labels
└── README.md            # Project documentation

---

## Quick Start Guide

### 1. Create Virtual Environment
python -m venv bioinfo_env

### 2. Activate Environment
bioinfo_env\Scripts\activate

### 3. Install Requirements
pip install -r requirements.txt

---

## Tools & Libraries Used

- Biopython
- Pandas
- Matplotlib
- Seaborn
- Scikit-bio

---

## Data Processing

- Data was downloaded using SRA Toolkit
- FASTQ files were generated using:
  fasterq-dump
- Each file represents sequencing reads from human tissue samples

---

## Biological Explanation

The dataset represents RNA sequencing reads from healthy and cancerous breast tissues.

### Healthy Samples:
- Normal gene expression levels
- Balanced nucleotide distribution
- Lower mutation rate
- Stable genomic regions

### Cancer Samples:
- Altered gene expression (oncogenes & tumor suppressor genes)
- Higher mutation rate
- SNP-like variations
- Possible GC-content shifts
- Increased sequence variability

These biological differences are essential for distinguishing between healthy and cancer samples and are used in:
- Feature extraction
- k-mer analysis
- Machine learning classification

---

## Notes

- FASTQ files are large, so they are excluded from GitHub using .gitignore
- The project focuses on dataset preparation and organization
- metadata.csv is used for labeling and classification

---

## Author

Khaled Lotfy  │ ID 4221168
Abdulrahman Mahjoub │ ID 4231010
Mohamed Hazem │ ID 421206


---

## GitHub Repository

https://github.com/KhaledLotfy11/bioinformatics-project
