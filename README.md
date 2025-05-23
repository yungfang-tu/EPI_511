
# Genetic Modeling & Biomedical Machine Learning Projects

This repository contains a collection of computational genetics and biomedical machine learning projects completed as part of the *Advanced Population and Medical Genetics* (EPI511) course at Harvard T.H. Chan School of Public Health, as well as additional independent projects. The work integrates statistical genetics, deep learning, and large-scale health data analysis to explore population structure, ancestry, polygenic prediction, fine-mapping, and real-world biomedical applications.

---

## 🔬 Projects Overview

### 1. HapMap3 Genetic Structure and LD Patterns
- **Tasks:**
  - Estimated FST among CEU, YRI, CHB populations using multiple estimators.
  - Calculated LD decay and average r² between SNPs across populations.
  - Performed Armitage Trend Tests for association mapping.
  - Evaluated SNP independence for fine-mapping design.
- **Skills:** Numpy-based masked arrays, SNP-level filtering, matrix ops.

### 2. Global and Local Ancestry Inference
- **Tasks:**
  - EM-based clustering for unsupervised population inference (TSI, JPT, LWK).
  - Supervised ancestry inference using CEU and YRI references.
  - Computed covariance matrix, principal components, and ancestry correlations.
- **Skills:** EM algorithm, power iteration for PCA, local ancestry windows.

### 3. Population Stratification & Fine-Mapping Analysis
- **Tasks:**
  - Simulated GWAS in CEU/YRI and applied Genomic Control (λ_GC ≈ 2.01).
  - Applied eigenvector correction and structured association analysis.
  - Conducted lactase persistence GWAS using proxy SNP (rs13404551).
  - Performed fine-mapping around rs3131972 using Bayes Factors and posterior probabilities.
  - Assessed consistency of odds ratios between CEU and YRI (slope ≈ 0.79).
- **Skills:** λ_GC inflation, LD score analysis, cross-population Bayesian fine-mapping.

### 4. Selection Scan, LD Span, and Heritability Estimation
- **Tasks:**
  - Genome-wide selection scan with FST and χ² thresholds.
  - Analyzed LD span around LCT SNP (rs13404551) across CEU, TSI, YRI.
  - Simulated polygenic phenotypes and computed ATT and MLMi statistics.
  - Used Haseman-Elston and variance component methods for heritability estimation.
- **Skills:** Phenotype simulation, GRM computation, H-E regression.

### 5. Polygenic Risk Prediction & LDpred
- **Tasks:**
  - Simulated cross-population prediction (CEU → TSI).
  - Compared ATT-based, P-thresholded, BLUP, and LDpred (no LD) methods.
  - Evaluated prediction R² under different causal SNP proportions.
- **Skills:** Polygenic score modeling, LDpred implementation, effect-size estimation.

### 6. Rare Variant Association and LD Score Enrichment
- **Tasks:**
  - Simulated SNPs under various MAF distributions and tested burden vs. Madsen-Browning.
  - Performed forward simulations of drift and negative selection.
  - Simulated functional enrichment with even vs. odd SNPs and LD-based groupings.
- **Skills:** Rejection sampling, LD score computation, rare variant modeling.

---

## 📁 Repository Structure

```
📂 experience1/      # FST, LD decay, CEU/CHB/YRI SNP-level analysis
📂 experience2/      # Ancestry estimation using EM & supervised models
📂 experience3/      # GWAS inflation, eigenvector correction, fine-mapping
📂 experience4/      # Selection scans, LD span, quantitative trait simulation
📂 experience5/      # Polygenic prediction across populations
📂 experience6/      # Rare variant testing and enrichment analysis
```

---

## 🧪 Tools & Technologies

- **Languages:** Python
- **Libraries:** NumPy, pandas, SciPy, scikit-learn, PyTorch, Matplotlib
- **Genetic Data:** HapMap3 SNPs, simulated phenotypes
- **Environments:** Jupyter Notebook, GitHub, UNIX/Linux

---

## ✍️ Author

**Yung-Fang (Tina) Tu, M.D.**  
Master’s Student in Computational Biology and Quantitative Genetics  
Harvard T.H. Chan School of Public Health

--- 
