# Baseline - Polarity | AICC Round 7

Fast synonym-vs-antonym solution for the Kaggle competition `polarity-aicc-round-7`.

The notebook uses WordNet synonym/antonym evidence, simple morphology rules, a curated set of common complementary pairs, and a tiny ExtraTrees fallback. It avoids BERT fine-tuning and runs locally in about 20 seconds on the provided files.

## Files

- `baseline-polarity-aicc-round-7.ipynb` - optimized solution notebook.
- `submission.csv` - generated submission.
- `kernel-metadata.json` - Kaggle kernel metadata for uploading the notebook.

The Kaggle data files are intentionally not committed. Download `train.csv` and `test.csv` from the competition or run the notebook on Kaggle.

## Local Result

- Training macro-F1 check on the 50 labeled rows: `1.0000`
- Kaggle submission public score: `0.9532`
- Kaggle submission private score: `0.9766`
