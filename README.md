# Infertility-Analysis

This project employs deep learning techniques for comprehensive semen analysis, focusing on parameters such as sperm motility, morphology, and vitality.

## Overview

Accurate assessment of semen quality is crucial in the diagnosis and treatment of male infertility. Traditional methods can be subjective and time-consuming. This project aims to leverage deep learning to automate and enhance the accuracy of semen analysis.

## MHSMA Dataset

The **MHSMA Dataset** is utilized in this project for sperm morphology and motility analysis. It contains structured data that helps in diagnosing male infertility. The dataset includes:

- **Morphology Data** – Describes the shape and structure of sperm cells (normal or abnormal).
- **Motility Data** – Measures the movement efficiency of sperm (progressive, non-progressive, or immotile).
- **Concentration** – The sperm count per unit of semen volume.
- **Vitality** – Determines the percentage of live sperm in a sample.

This dataset is crucial for training deep learning models to automate sperm classification, leveraging **CNNs (Convolutional Neural Networks)** and statistical techniques for feature extraction and analysis.


## Methodology

The analysis is conducted using Jupyter Notebooks, which include:

- **Data Preprocessing**: Handling missing values, normalization, and augmentation to prepare the dataset for modeling.
- **Model Development**: Building and training convolutional neural networks (CNNs) to classify and evaluate sperm characteristics.
- **Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

