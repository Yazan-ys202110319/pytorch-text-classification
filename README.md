# AG News Classification with PyTorch

This project is a PyTorch learning notebook for text classification on the AG News dataset. It focuses on understanding the full workflow of building an LSTM-based model from scratch, from loading data to making predictions.


## Project Goal

The goal is to learn PyTorch by implementing a news classifier step by step. The notebook covers data loading, preprocessing, vocabulary building, tokenization, padding, model creation, training, and evaluation.

## Dataset

The project uses the AG News dataset, which contains news headlines and descriptions grouped into four categories:

You can view the dataset here: [Hugging Face AG News](https://huggingface.co/datasets/fancyzhx/ag_news)

- World
- Sports
- Business
- Sci/Tech

## The Main Lessons From The Project

- How to load and inspect a text dataset with Hugging Face
- How to prepare text data for PyTorch models
- How to build an LSTM model for multi-class classification
- How to train and evaluate a model in PyTorch
- How to run inference on new text samples

## How to Run

1. Open the project in VS Code.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open `main.ipynb`.
4. Run the notebook cells from top to bottom.
5. Train the model and use the final cell to test predictions on new text.
   