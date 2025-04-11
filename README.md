# Refactoring Type Prediction with Transformers

This repository contains code and experiments from master's thesis on predicting software refactoring types using Transformer-based models (CodeBERT and CodeT5).

## 🔍 Overview

- **Task**: Classify source code snippets into one of three refactoring types:  
  `Extract Method`, `Move Class`, `Pull Up Method`
- **Models**: Fine-tuned `CodeBERT` and `CodeT5` using Hugging Face Transformers
- **Dataset**: Labeled Java code extracted using RefactoringMiner
- **Evaluation**: Accuracy, F1-score, precision, recall, and confusion matrix analysis

## 🚀 Usage

1. Clone the repo  
2. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
3. Run training notebooks:  
   - `notebooks/CodeBERT.ipynb`  
   - `notebooks/CodeT5.ipynb`

## 📂 Structure

```
├── notebooks/       # Jupyter notebooks for CodeBERT and CodeT5
├── data/            # Dataset (TSV format)
├── requirements.txt
└── README.md
```

## 📄 License

MIT License. Open for academic use and further research.
