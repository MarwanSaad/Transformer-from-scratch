# Transformer from Scratch for Multi-Label Classification

## Overview
This repository contains a Jupyter Notebook that implements a transformer model from scratch for a multi-label text classification task. It covers data preprocessing, transformer block implementation, training, and evaluation.

## Features
- Implements a transformer model using PyTorch.
- Performs data cleaning and text preprocessing (tokenization, stopword removal, and lemmatization).
- Splits data into training and testing sets.
- Uses BERT tokenizer for input tokenization.
- Trains the model with batch processing.
- Evaluates model performance using precision, recall, F1-score, and accuracy.

## Installation
### Prerequisites
Ensure you have Python installed along with Jupyter Notebook. The required libraries include:
- `numpy`
- `pandas`
- `nltk`
- `torch`
- `transformers`
- `scikit-learn`

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/transformer-classification.git
   cd transformer-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
1. Open `Transformer_from_scratch.ipynb` in Jupyter Notebook.
2. Run the notebook step by step:
   - Import necessary libraries.
   - Load and preprocess the dataset.
   - Define the transformer architecture.
   - Train the model using PyTorch.
   - Evaluate the model performance.
3. Modify hyperparameters or dataset configurations for experimentation.

## Data Description
The dataset consists of textual data used for multi-label classification. The preprocessing steps include:
- Removing punctuation and special characters.
- Tokenizing text.
- Removing stopwords.
- Applying lemmatization.

## Model Training
- The transformer model is built from scratch using PyTorch.
- BERT tokenizer is used for tokenizing the text.
- Training is done using the Adam optimizer with loss computation.
- Data is processed in batches using DataLoader.

## Evaluation
The model performance is evaluated using:
- **Accuracy**: Measures the percentage of correctly predicted labels.
- **Precision, Recall, F1-score**: Assesses the model's performance in multi-label classification.

## Contributing
Feel free to fork the repository and submit pull requests for improvements.

## Contact
For questions or collaborations, contact ma.saadabbas@gmail.com or open an issue on GitHub.
