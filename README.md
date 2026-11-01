# Hi, I'm Md Abrar Faiyaj 👋

**M.S. in Biotechnology, BRAC University | Junior Research Collaborator | Bioinformatics**  
**Reproducible pipelines and analyses in microbial genomics, AMR surveillance and cancer structural bioinformatics**

[![Website](https://img.shields.io/badge/Website%20%26%20Blog-mdabrarfaiyaj.github.io-2E8B57?style=for-the-badge&logo=githubpages&logoColor=white)](https://mdabrarfaiyaj.github.io/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--9646--4508-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0005-9646-4508)
[![Email](https://img.shields.io/badge/Email-faiyaj.mdabrar%40gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faiyaj.mdabrar@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-abrar-faiyaj-559246381/)

---

## 🔬 What I Work On

```mermaid
flowchart LR
    A[Biological Question\nAMR · Genomics · Epidemiology] --> B[Data Collection\nGEO · SRA · TyphiNET · NCBI]
    B --> C[Reproducible Pipeline\nR · Bash · DESeq2 · HISAT2]
    C --> D[Statistical Analysis\nDEG · AMR Trend · Variant Surveillance]
    D --> E[Interactive Visualization\nShiny Dashboard · Quarto Report]
    E --> F[Communication\nGitHub Pages · LinkedIn · Documentation]
```

I work at the intersection of **infectious disease biology**, **cancer genomics** and **computational data analysis** — turning messy genomic and epidemiological datasets into reproducible, interactive tools that researchers can actually use.

---

## 🧰 Technical Toolkit

**Languages & Frameworks**

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)

**Bioinformatics & Genomics**

![DESeq2](https://img.shields.io/badge/DESeq2-Bioconductor-brightgreen?style=for-the-badge)
![HISAT2](https://img.shields.io/badge/HISAT2-RNA--Seq-orange?style=for-the-badge)
![featureCounts](https://img.shields.io/badge/featureCounts-Subread-blueviolet?style=for-the-badge)
![SPAdes](https://img.shields.io/badge/SPAdes-Assembly-red?style=for-the-badge)
![Galaxy](https://img.shields.io/badge/Galaxy-Workflow-lightblue?style=for-the-badge)
![Nextflow](https://img.shields.io/badge/Nextflow-DSL2-0DC09D?style=for-the-badge)
![Panaroo](https://img.shields.io/badge/Panaroo-Pangenome-8A2BE2?style=for-the-badge)
![IQ-TREE](https://img.shields.io/badge/IQ--TREE-Phylogenetics-darkgreen?style=for-the-badge)

**Structural Bioinformatics**

![AlphaFold](https://img.shields.io/badge/AlphaFold-DB-1A73E8?style=for-the-badge)
![PDB](https://img.shields.io/badge/RCSB-PDB-8B0000?style=for-the-badge)
![PyMOL](https://img.shields.io/badge/PyMOL-3D%20Rendering-orange?style=for-the-badge)
![Biopython](https://img.shields.io/badge/Biopython-Bio.PDB-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Visualization & Dashboards**

![Shiny](https://img.shields.io/badge/Shiny-Dashboard-blue?style=for-the-badge&logo=rstudio&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-Report-374151?style=for-the-badge)
![ggplot2](https://img.shields.io/badge/ggplot2-Visualization-green?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

**Tools & Reproducibility**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![renv](https://img.shields.io/badge/renv-Reproducibility-blue?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux%20%2F%20WSL-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Posit Cloud](https://img.shields.io/badge/Posit%20Cloud-Deployed-75AADB?style=for-the-badge)

---

## 🚀 Featured Projects

### 1. Cancer Mutation Hotspots in 3D — TP53, KRAS and PIK3CA

Mapped about 5,000 TCGA missense mutations from 32 cancer types onto experimental (PDB) and predicted (AlphaFold) protein structures to ask where cancer mutations sit in 3D, and why.

**Highlights:**
- Oncogene vs. tumor suppressor pattern: KRAS mutations hit 32 positions (73% at G12), TP53 mutations spread over 173
- Separated TP53 DNA-contact hotspots (R248, R273) from structural hotspots (R175, Y220, zinc-site C176/H179)
- Permutation tests for 3D clustering; distances to DNA and GDP; interactive 3Dmol.js viewers

**Tech:** `Python` `Biopython` `cBioPortal API` `PDB` `AlphaFold` `PyMOL` `3Dmol.js`

![Cancer mutation hotspots in 3D](assets/cancer_3d_preview.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/cancer-mutation-3d-hotspots) · [🧬 Interactive 3D](https://mdabrarfaiyaj.github.io/cancer-mutation-3d-hotspots/results/interactive/TP53_3D.html) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/Where-Do-Cancer-Mutations-Sit-in-3D/)

---

### 2. Typhoid Fever AMR Surveillance Dashboard — Bangladesh (1999–2022)

A 24-year retrospective analysis of *Salmonella* Typhi antimicrobial resistance trends in Bangladesh, extending Tanmoy et al. 2024 (PLOS NTDs) with TyphiNET genomic data. Fully deployed as an interactive Shiny dashboard and a Quarto report on GitHub Pages.

**Highlights:**
- Integrated clinical AMR phenotype data with whole-genome sequencing genotype data from TyphiNET
- Visualized multi-drug resistance (MDR), XDR, and H58 lineage trends over 24 years
- Deployed interactive Shiny dashboard with tabbed navigation and downloadable outputs
- Published reproducible Quarto report with embedded figures and methodology

**Tech:** `R` `Shiny` `ggplot2` `Quarto` `renv` `GitHub Pages` `TyphiNET` `AMR genomics`

![Typhoid AMR Dashboard](assets/typhoid_dashboard_preview.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/Typhoid-Fever-in-Bangladesh) · [📊 Live Dashboard](https://u3j9z9-md0abrar-faiyaj.shinyapps.io/typhoid-amr-bangladesh/) · [📄 Quarto Report](https://mdabrarfaiyaj.github.io/Typhoid-Fever-in-Bangladesh/) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/Typhoid-in-Bangladesh-Why-Falling-Resistance-Can-Still-Be-Bad-News/)

---

### 3. Bacterial Pangenome & AMR Pipeline — *Bacteroides vulgatus*

A modular Nextflow DSL2 pipeline that takes bacterial genomes from QC to annotation, pangenome, resistance genes and a core-genome tree, run on 16 human gut isolates.

**Highlights:**
- Only 30% of 8,697 gene families are shared by all strains
- 11 resistance genes, none in every strain; *lnu(AN2)* and *mef(En2)* always co-occur, suggesting a shared mobile element
- Resistance genes do not follow the core-genome phylogeny

**Tech:** `Nextflow` `Prokka` `Panaroo` `AMRFinderPlus` `IQ-TREE` `Python`

![Pangenome and AMR](assets/pangenome_preview.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/human-gut-bacterial-pangenome-analysis) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/Same-Species-Different-Genes-The-Pangenome-of-a-Gut-Bacterium/)

---

### 4. RNA-Seq Replication — Shemer et al., *Immunity* 2020 (GSE157234)

Reproduced bulk RNA-Seq analysis from a high-impact immunology paper on IL-10 receptor-deficient microglia. Discovered that the GEO deposit contains UTAP-normalized counts (not raw counts) — a methodological finding documented publicly and shared with the research community, attracting engagement from scientists at Illumina, Novartis, Pfizer, and GSK.

**Highlights:**
- Rebuilt the analysis from raw SRA reads (HISAT2 → featureCounts → DESeq2 with apeglm shrinkage)
- V2 finds 1,597 DEGs (paper: 1,647), with *Tnf*, *Il6*, *Il12b* up and homeostatic markers *Tmem119*, *P2ry12* down
- Documented the GEO normalized-counts issue publicly, reaching 6,300+ LinkedIn impressions

**Tech:** `R` `DESeq2` `apeglm` `ggplot2` `pheatmap` `Shiny` `GEO` `SRA` `Bioconductor`

![RNA-seq Replication Results](assets/rnaseq_replication_preview.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/rna-seq-shiny-pipeline) · [📊 Live Dashboard](https://019cd22f-689b-acc2-4b56-472725ef4a7b.share.connect.posit.cloud/) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/Why-I-Rebuilt-My-RNA-seq-Analysis-From-Raw-Reads/)

---

### 5. Metastatic Breast Cancer Single-Cell Atlas — Klughammer et al., *Nature Medicine* 2024

Reanalysis of 15 single-cell and single-nucleus RNA-seq biopsies to ask what shapes metastatic breast cancer cells.

**Highlights:**
- Malignant-cell expression is dominated by patient identity (~43% of variance), not biopsy site (~0.1%)
- Corrected a strong fresh-cell vs. frozen-nucleus technical effect with Harmony and ComBat
- Verified every clinical label against the paper's supplementary tables

**Tech:** `R` `Harmony` `ComBat` `variancePartition` `pseudobulk` `Quarto`

![Metastatic breast cancer atlas](assets/sc-snRNA-seq-metastatic-breast-cancer.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/sc-snRNA-seq-metastatic-breast-cancer) · [🌐 Project website](https://mdabrarfaiyaj.github.io/sc-snRNA-seq-metastatic-breast-cancer/) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/Patient-Not-Place-What-Shapes-Metastatic-Breast-Cancer-Cells/)

---

### 6. Bangladesh Dengue Genomic Surveillance Dashboard

Interactive R Shiny dashboard analyzing DENV-2 sequences from the 2023 Bangladesh dengue outbreak (Dhaka & Chattogram isolates). Includes QC filtering, motif detection, and comparative visualization.

**Highlights:**
- Analyzed 13 real DENV-2 sequences from the 2023 Bangladesh outbreak
- Sequence quality control (length, GC content, ambiguous bases) and motif counts across isolates
- Deployed interactive dashboard with modern tabbed UI

**Tech:** `R` `Shiny` `Bioconductor` `sequence analysis` `genomic surveillance`

![Dengue Surveillance Dashboard](assets/dengue_dashboard_preview.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/bangladeshi-dengue-strain-tracker) · [📊 Live Dashboard](https://u3j9z9-md0abrar-faiyaj.shinyapps.io/bangladesh-denv-tracker/) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/Building-My-First-Dashboard-Dengue-in-Bangladesh/)

---

### 7. Heart Disease Patient Data Analysis

Python + SQL exploration of the Kaggle heart disease dataset, which turned into a lesson in data quality.

**Highlights:**
- Found that the 1,025 rows contain only 302 unique patients
- Showed that the disease labels in this dataset version appear reversed (checked against the original Cleveland study)
- SQLite queries and a six-panel Matplotlib/Seaborn dashboard

**Tech:** `Python` `SQL` `SQLite` `Pandas` `Matplotlib` `Seaborn` `Jupyter`

![Patient Data Visualization](assets/heart_disease_preview.png)

[🔗 View Repository](https://github.com/mdabrarfaiyaj/patient-data-analysis) · [📝 Blog post](https://mdabrarfaiyaj.github.io/posts/When-My-Data-Disagreed-With-the-Textbook/)

---

## 📝 Blog

I write about each project for a general audience: the question, what I did, and what the results mean, including the mistakes I found along the way.

**[Read all posts → mdabrarfaiyaj.github.io](https://mdabrarfaiyaj.github.io/archives/)**

---

## 📚 Research Interests

- Infectious Disease Genomics & AMR Surveillance
- Cancer Genomics & Structural Bioinformatics
- RNA-Seq & Multi-omics Data Analysis
- Reproducible Bioinformatics Tools & Workflows
- Public Health Data Science
- Computational Biology & Interactive Dashboards

---

## 📫 Let's Connect

- **Email**: faiyaj.mdabrar@gmail.com
- **ORCID**: [0009-0005-9646-4508](https://orcid.org/0009-0005-9646-4508)
- **LinkedIn**: [md-abrar-faiyaj](https://www.linkedin.com/in/md-abrar-faiyaj-559246381/)
- **Website & blog**: [mdabrarfaiyaj.github.io](https://mdabrarfaiyaj.github.io/)

Open to **research collaborations**, bioinformatics roles, and PhD opportunities in computational biology, infectious disease genomics and cancer genomics.

---

*Last updated: October 2026*
