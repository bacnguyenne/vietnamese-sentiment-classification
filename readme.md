# Vietnamese Sentiment Classification

This project classifies Vietnamese text into sentiment categories using deep learning models.

## Overview

The project uses models like PhoBERT and LSTM to decide if a sentence is positive, negative, or neutral. It leverages Vietnamese text processing tools such as VnCoreNLP and Underthesea.

## Requirements

- Python 3.x
- Libraries: `torch`, `transformers`, `vncorenlp`, `underthesea`, `pandas`, `numpy`, `scikit-learn`

Install the necessary libraries with:

```bash
pip install torch transformers vncorenlp underthesea pandas numpy scikit-learn
```

## How to Use

1. Run `preprocessing_data.ipynb` to clean and prepare the data.
2. Open and run a model notebook (e.g., `phobert.ipynb` or `deep-LSTM.ipynb`) to train the model.
3. Review the output to see the model's performance.

## Contributing

Contributions are welcome! If you have improvements or bug fixes, please open an issue or submit a pull request.
