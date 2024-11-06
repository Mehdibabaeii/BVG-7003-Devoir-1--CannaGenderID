# BVG-7003-Devoir-1--CannaGenderID
CannaGenderID is a Python-based framework designed to analyze transcriptomic differences across distinct categories in RNA-Seq data. It can process datasets with defined groupings, though adjustments may be needed if there are more than two categories. Using Mutual Information (MI) feature selection and Support Vector Machine (SVM) classification, CannaGenderID identifies category-specific gene expression patterns, making it a valuable tool for research into genetic diversity and trait differentiation.


## Use Cases

- **Category-Specific Gene Expression Analysis**  
   Identify and compare gene expression patterns unique to specific groups within a dataset (e.g., male vs. female, healthy vs. diseased).
  
- **Feature Selection and Dimensionality Reduction**  
   Filter large transcriptomic datasets by selecting the most informative features using Mutual Information (MI), reducing noise and computational load.

- **Classification of Biological Samples**  
   Train a Support Vector Machine (SVM) classifier to accurately categorize samples based on gene expression profiles, providing predictions for unknown samples.

- **Flexible Application to Multi-Category Datasets**  
   Adapt to datasets with more than two categories by modifying the framework, enabling classification across complex biological conditions.

- **Exploration of Genetic Diversity Across Organisms**  
   Apply to a variety of organisms, from plants to animals, to investigate genetic markers or traits linked to specific biological groups.

- **Supporting Data-Driven Research in Genomics**  
   Provide insights that support research in genomics, phenomics, and biotechnology by pinpointing key gene expression patterns that differentiate categories. 

This framework can be a powerful tool for scientists in genomics, transcriptomics, and computational biology aiming to uncover unique gene expression markers and classify biological data effectively.

## Table of Contents

1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Input Data Format](#input-data-format)
4. [Usage](#usage)
5. [Output](#output)
6. [Directory Structure](#directory-structure)
7. [Workflow Details](#workflow-details)

## Requirements

- **Python**: Version **3.12.7** is recommended for best compatibility.
- **Python Packages**:
  - `numpy>=1.21.0`
  - `pandas>=1.3.0`
  - `matplotlib>=3.4.0`
  - `seaborn>=0.11.0`
  - `scikit-learn>=0.24.0`


 ## Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/Mehdibabaeii/BVG-7003-Devoir-1--CannaGenderID.git
   cd BVG-7003-Devoir-1--CannaGenderID


2. **Install required packages**:
  ```bash
  pip install -r requirements.txt   

