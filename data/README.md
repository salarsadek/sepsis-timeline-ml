# Data

This repository does not include the dataset due to size/privacy constraints.

## Expected folder structure
data/
raw/ # original files you download (not committed)
processed/ # generated features/windows ready for training (not committed)


## How to reproduce results
1) Obtain the dataset (link/source will be added).
2) Place the raw files under `data/raw/` (keep original filenames).
3) Run preprocessing to generate `data/processed/`:
   - `notebooks/02_preprocessing.ipynb`
4) Train and evaluate models:
   - `notebooks/03_model_lstm.ipynb`
   - `notebooks/04_model_gru.ipynb`
   - `notebooks/05_model_transformer.ipynb`
   - `notebooks/06_evaluation.ipynb`

## Notes
- The `data/` directory is intentionally excluded from version control (see `.gitignore`).
- If you use a different dataset, keep the same folder structure and adapt preprocessing accordingly.
