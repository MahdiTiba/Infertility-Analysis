# Infertility-Analysis

This project employs deep learning techniques for comprehensive semen analysis, focusing on parameters such as sperm motility, morphology, and vitality.

## Overview

Accurate assessment of semen quality is crucial in the diagnosis and treatment of male infertility. Traditional methods can be subjective and time-consuming. This project aims to leverage deep learning to automate and enhance the accuracy of semen analysis.

## Methodology

The analysis is conducted using Jupyter Notebooks, which include:

- **Data Preprocessing**: Handling missing values, normalization, and augmentation to prepare the dataset for modeling.
- **Model Development**: Building and training convolutional neural networks (CNNs) to classify and evaluate sperm characteristics.
- **Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

## Repository Structure

- `notebooks/`: Contains Jupyter Notebooks detailing data preprocessing, model development, and evaluation.
- `data/`: Placeholder for datasets used in the analysis (datasets are not included due to size constraints).
- `models/`: Directory to save trained models for future inference.
- `results/`: Stores evaluation metrics and visualizations of model performance.

## Requirements

To replicate the analysis, install the necessary Python packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/MahdiTiba/Infertility-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Infertility-Analysis
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebooks in the `notebooks/` directory to preprocess data, train models, and evaluate performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

