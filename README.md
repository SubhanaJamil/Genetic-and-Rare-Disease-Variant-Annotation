# Genetic and Rare Disease Variant Annotation

## Overview
This repository contains a curated set of **six disorders** (3 Genetic Diseases and 3 Rare Diseases) with fully annotated variants. The project aims to demonstrate comprehensive variant annotation using ClinVar, OMIM, AlphaMissense, RAVEL, and ACMG/AMP classification standards.  

Each variant is documented with:

- HGVS nomenclature  
- Gene and protein change  
- Variant type (missense, nonsense, frameshift)  
- Disease association  
- ClinVar classification and review status  
- Functional explanation  
- Phenotype information (from OMIM)  
- AlphaMissense and RAVEL pathogenicity scores  
- ACMG/AMP classification  

---

## Disorders Included

### Genetic Diseases
1. Phenylketonuria (PAH)  
2. Marfan Syndrome (FBN1)  
3. Tay-Sachs Disease (HEXA)  

### Rare Diseases
4. Gaucher Disease (GBA1)  
5. Fabry Disease (GLA)  
6. Alkaptonuria (HGD)  

---

## Methodology

The following steps were systematically performed to annotate the variants:

1. **Selection of Variants**  
   - Three genetic disorders and three rare diseases were selected.  
   - Variants were chosen based on clinical relevance and pathogenicity reports in ClinVar.  

2. **ClinVar Annotation**  
   - Each variant was searched in [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) to retrieve detailed information.  
   - Data recorded in the Excel sheet included:
     - Variation (HGVS)  
     - Gene/protein change  
     - Type/consequence  
     - Condition  
     - ClinVar classification and review status  

3. **Functional Annotation and Literature Review**  
   - Publications and functional studies linked in ClinVar were reviewed.  
   - Detailed explanations were documented for each variant describing:
     - Protein structure and function impact  
     - Molecular and biochemical consequences  
     - Clinical significance  

4. **Phenotype Annotation (OMIM)**  
   - Phenotype data for each variant was retrieved from [OMIM](https://www.omim.org/).  
   - Phenotypic features and inheritance patterns were included in the Excel sheet.  

5. **AlphaMissense and RAVEL Scoring**  
   - Each variant was visualized in [UCSC Genome Browser](https://genome.ucsc.edu/)  
   - AlphaMissense and RAVEL tracks were enabled to assess pathogenicity.  
   - Scores and classifications were recorded, and screenshots were saved in:
     - `Screenshots/AlphaMissense/`  
     - `Screenshots/RAVEL/`  

6. **ACMG/AMP Classification**  
   - Each variant was evaluated according to [ACMG/AMP guidelines](https://www.acmg.net/ACMG/Medical-Genetics-Practice-Resources/Standards-Guidelines.aspx).  
   - The Excel sheet includes ACMG/AMP criteria based on:
     - Functional studies (PS3)  
     - Population frequency (PM2)  
     - Computational predictions (PP3)  
     - Reports from ClinVar (PP5)  
     - Null or loss-of-function evidence (PVS1)  

7. **VCF File Creation**  
   - Variants were formatted into a VCF file, including the header, simulating patient WGS/WES data.  

8. **VCF Annotation Verification**  
   - The VCF file was submitted to ClinVar (or equivalent tools) to validate annotations.  

---

---

## References
- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) – Variant clinical significance  
- [OMIM](https://www.omim.org/) – Gene-phenotype relationships  
- [UCSC Genome Browser](https://genome.ucsc.edu/) – Visualization of genomic variants  
- [VarSome](https://varsome.com/) – Variant interpretation support  
- [ACMG/AMP Guidelines](https://www.acmg.net/ACMG/Medical-Genetics-Practice-Resources/Standards-Guidelines.aspx) – Standard for variant classification  
---
