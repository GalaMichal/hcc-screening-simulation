# HCC Screening Simulation

This repository contains a reproducible Python analysis exploring hepatocellular carcinoma (HCC) screening using published sensitivity and specificity estimates for serum alpha-fetoprotein (AFP) and abdominal ultrasound (US).

The analysis examines how diagnostic performance depends on disease prevalence, AFP threshold and population size, with particular emphasis on:

- sensitivity and specificity
- false-positive and false-negative results
- positive predictive value (PPV)
- expected screening outcomes
- sampling variability
- effects of disease prevalence on predictive value

## Notebook

[hcc_screening_prevalence_analysis.ipynb](hcc_screening_prevalence_analysis.ipynb)

All simulated observations are synthetic. No patient-level clinical data are included in this repository.

## Reproducibility

The analysis was validated using Python 3.12.

Install the required dependencies with:

```bash
python -m pip install -r requirements.txt
```

Then open and run:

```text
hcc_screening_prevalence_analysis.ipynb
```

A fixed random seed is used.

## Data and interpretation

Published diagnostic-performance estimates are used as model inputs rather than individual-level patient data.

The simulations are intended to illustrate statistical properties of screening tests and the relationship between prevalence and predictive value.

## Source

Tong MJ, Blatt LM, Kao VWC. *Surveillance for hepatocellular carcinoma in patients with chronic viral hepatitis in the United States of America.* Journal of Gastroenterology and Hepatology. 2001;16:553–559.

[PubMed publication](https://pubmed.ncbi.nlm.nih.gov/11350553/)

Diagnostic-performance inputs used in the notebook are attributed to the original publication.
