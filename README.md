# Bioinformatics Project – RNA-seq Analysis

## Project Title

RNA-seq Analysis of Breast Cancer vs Healthy Samples

---

## Project Purpose

This project aims to analyze RNA-seq data from human breast cancer and healthy tissue samples.
The objective is to compare gene expression patterns between disease and normal conditions.

---

## Dataset Description

### Source:

Public data downloaded from NCBI SRA database.

### Classes:

* Class 1: Breast invasive ductal carcinoma (Cancer)
* Class 2: Adult normal breast (Healthy)

### Number of Samples:

* 5 Cancer samples
* 5 Healthy samples

---

## Accession IDs

### Cancer Samples:

* SRR191639
* SRR191640
* SRR191641
* SRR191642
* SRR191643

### Healthy Samples:

* SRR537099
* SRR537100
* SRR537101
* SRR537102
* SRR537103

---

## Project Structure

bioinformatics_project/
│
├── data/                # Contains FASTQ files
├── bioinfo_env/         # Virtual environment
├── requirements.txt     # Python dependencies
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

* Biopython
* Pandas
* Matplotlib
* Seaborn
* Scikit-bio

---

## Notes

* Data was processed using SRA Toolkit
* FASTQ files are single-end reads
* Project focuses on dataset preparation and environment setup

---

## Author

Khaled Moahmed Lotfy │ ID 4221168
