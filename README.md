# Using Supervised Machine Learning for Large-Scale Classification in Management Research

Code and data companion for:

Miric, M., Jia, N., & Huang, K. G. (2023). **Using supervised machine learning for large-scale classification in management research: The case for identifying artificial intelligence patents.** *Strategic Management Journal*, 44(2), 491–519. [https://doi.org/10.1002/smj.3441](https://doi.org/10.1002/smj.3441)

---

## Abstract

Researchers increasingly rely on unstructured text to construct quantitative variables. Traditional keyword-based approaches require researchers to curate dictionaries that map terms to theoretical constructs. Recent advances in machine learning (ML) for text classification and natural language processing (NLP) enable automated construction of such variables from documents at scale. This repository demonstrates how to apply ML tools for that purpose, using the identification of artificial intelligence (AI) technologies in patents as a worked example. We compare ML methods to keyword-based approaches and illustrate the advantages of ML. We also use model outputs to examine broad patterns in AI technology development.

---

## Repository Overview

This repository contains the notebooks used to reconstruct tables and figures from the paper and to reproduce core classification workflows. Click a badge to open each notebook directly in Google Colab.

- **Notebook A** · Text Classification with a Bag-of-Words Representation  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_JsC9opZjrI4p-V_5ojWO_6JAYEt2xcs?usp=sharing)

- **Notebook B** · Text Classification with an Embedding-Based Representation  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pC-c2z7_laajvOZ4Rky8AfjoMx_kq1uB?usp=sharing)

- **Notebook C** · Text Classification using a Convolutional Neural Network  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11it0K0wOOLzf9fWvs1eFaFHA-R_bNVB9?usp=sharing)

- **Notebook D** · Text Classification using Transformer-Based Models  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AGiy2zggSVMwO7OYPaOujw9hHN6Jb7mj?usp=sharing)

- **Notebook X** · Summary and Comparison of Classification Approaches  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1U9SN_vWDveJhsb_RbqxGH0DDMqTui4Y0?usp=sharing)

> Notebooks render on GitHub, but for execution we recommend opening them in Colab via the badges above.

---

## How to Use

1. **Open a notebook in Colab** using the corresponding badge.  
2. **Provide data** (if required by the notebook) by uploading files to your Colab session or mounting Google Drive.  
3. **Run cells top-to-bottom** to train models, generate predictions, and reproduce tables/figures.

---

## License & Reuse

This code is available under an **Attribution–NonCommercial (CC BY-NC)** license. You are welcome to use and adapt the materials for research and teaching with appropriate attribution. If you find this repository useful, please cite the paper below.

We aim to iteratively improve the materials as NLP and text classification evolve. Suggestions and extensions are welcome—feel free to open an issue.

---

## Citation

```bibtex
@article{miric2023using,
  title   = {Using supervised machine learning for large-scale classification in management research:
             The case for identifying artificial intelligence patents},
  author  = {Miric, Milan and Jia, Nan and Huang, Kenneth G},
  journal = {Strategic Management Journal},
  volume  = {44},
  number  = {2},
  pages   = {491--519},
  year    = {2023},
  publisher = {Wiley},
  doi     = {10.1002/smj.3441}
}
