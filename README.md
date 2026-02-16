# Transformer-From-Scratch

Build a Transformer model from scratch in PyTorch, with a step-by-step notebook that covers the full training pipeline.

## What is inside

- Input embeddings and positional encoding
- Multi-head self-attention
- Add & norm (layer normalization) and residuals
- Encoder and decoder blocks
- Tokenizer and dataset loading
- Training and validation loops

## Project layout

- Transformer_from_scratch.ipynb: main notebook
- assets/: images used in the notebook

## Requirements

- Python 3.9+
- PyTorch
- datasets
- tokenizers
- tqdm
- tensorboard

Install with:

```bash
pip install torch datasets tokenizers tqdm tensorboard
```

## Usage

Open the notebook and run the cells in order:

```bash
jupyter notebook Transformer_from_scratch.ipynb
```

## Notes

- If you see a missing module error, install the package listed in the error and rerun the import cell.
- The notebook includes a model diagram image in the assets folder.
