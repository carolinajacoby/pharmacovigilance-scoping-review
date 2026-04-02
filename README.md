# Data mining methods, tasks, and algorithms for pattern identification in the context of pharmacovigilance: a scoping review

## Abstract

**Background:** Pharmacovigilance is dedicated to the identification, evaluation, and prevention of adverse effects associated with the use of medicines after their commercialization. In this context, data mining techniques have been widely used for safety signal detection. Although machine learning algorithms have the potential to identify complex patterns and improve the prediction of adverse reactions, their application in pharmacovigilance databases is still limited.

**Objective:** To map the computational approaches used in pharmacovigilance, identify the prevalence of traditional statistical methods and data mining techniques, and evaluate the role of machine learning algorithms.

**Methods:** This scoping review was conducted according to the PRISMA-ScR guidelines, with a protocol registered on the Open Science Framework platform (10.17605/OSF.IO/KZJDT). PubMed, Scopus, Embase, and Web of Science databases were consulted to identify studies published between 2015 and July 2025.

**Results:** The search identified 1,468 records, of which 162 studies were included after screening and eligibility assessment. Traditional disproportionality methods, such as Reporting Odds Ratio (ROR) and Proportional Reporting Ratio (PRR), were used in 87.7% of the studies, while 12.3% applied machine learning or deep learning techniques, mainly in classification tasks, with logistic regression being the most used algorithm. The most investigated drugs included immune checkpoint inhibitors, such as nivolumab, pembrolizumab, atezolizumab, and durvalumab. The most studied therapeutic classes were antineoplastic agents, immunosuppressants, and psycholeptics.

**Conclusion:** Signal detection in pharmacovigilance remains predominantly based on classical statistical methods. The advancement of the field is still limited by the slow incorporation of advanced machine learning techniques and the limited public availability of datasets used in the analyses.

**Keywords:** Pharmacovigilance, Data Mining, Adverse Drug Reactions, Signal Detection.

---

## Repository Structure

This repository is organized as follows:

- **`/data`**: Contains all datasets used in the review:
  - **`/excluded`**: List of studies excluded after full-text reading, including reasons for exclusion.
  - **`/processed`**: Cleaned and structured datasets used in the analysis:
    - **`articles.csv`**: Initial list of articles after duplicate removal.
    - **`exploded_technique.csv`**: Structured classification of identified techniques and algorithms identified.
    - **`reference.csv`**: Articles included after title and abstract screening.
  - **`/supplementary_material`**: Additional materials supporting the review.
- **`/docs`**: Contains the study protocol registered at OSF and supplementary methodological materials (S1 - Detailed Search Strategy).
- **`/prisma`**: Includes the PRISMA flow diagram describing the study selection process.
- **`/scripts`**: Contains the Google Colab/Jupyter Notebook (**`scope_review__data__analysis.ipynb`**) used for data analysis, as well as the **`requirements.txt`** file for reproducibility.

---

## Supplementary Material

This material provides detailed methodological information and extended data tables supporting the findings of this review.

- **S1. Detailed Search Strategy:** Full search strings and filters used across PubMed, Scopus, Embase, and Web of Science.
- **S2. Data Extraction Form:** Standardized template used for data collection from the included studies.

---

## Reproducibility

To reproduce the analysis:

1. Navigate to the `/scripts` folder.
2. Install the dependencies using:
```bash
pip install -r requirements.txt
