# Deconvolution analysis of Localized Scleroderma
<div align="center">

[![medRxiv](https://img.shields.io/badge/medRxiv-10.64898%2F2026.11.23.26368779v1-b31b1b?style=flat&logo=academia&logoColor=white)](https://www.medrxiv.org/content/10.64898/2026.11.23.26368779v1)

</div>
This repository contains the analysis scripts for the deconvolution analyses performed in the study titled: 

_Interferon-driven T-cell activation and a senescence-associated signature characterize clinically active adult localized scleroderma_

Deconvolution was performed using the [SpaTM package](https://github.com/li-lab-mcgill/SpaTM).

## Analysis Pipeline

| Step | Script | Description |
| :--- | :--- | :--- |
| **1** | [`Final_GTM_Analysis.qmd`](./Final_GTM_Analysis.qmd) | Estimates and visualizes cell type abundance. |
| **2** | [`CTS_Deconvolution.qmd`](./CTS_Deconvolution.qmd) | Estimates cell-type-specific gene expression profiles. |
| **3** | [`CTS_DESeq2.qmd`](./CTS_DESeq2.qmd) | Performs cell-type-specific differential gene expression analysis with `DESeq2`. |
| **4** | [`ImmuneSignature.qmd`](./ImmuneSignature.qmd) | Computes and visualizes immune signature activity with respect to background gene expression. |


![Overview Figure](https://github.com/aosakwe/LS_GTM/blob/main/Overview.jpg)
