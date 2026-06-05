# Baseline - Polarity | AICC Round 7

Fast synonym-vs-antonym solution for the Kaggle competition `polarity-aicc-round-7`.

The notebook uses WordNet synonym/antonym evidence, simple morphology rules, a curated set of common complementary pairs, and a tiny ExtraTrees fallback. It avoids BERT fine-tuning and runs locally in about 20 seconds on the provided files.

## Files

- `baseline-polarity-aicc-round-7.ipynb` - optimized solution notebook.
- `train.csv` - competition training data used by the notebook.
- `test.csv` - competition test data used by the notebook.
- `submission.csv` - generated submission.
- `kernel-metadata.json` - Kaggle kernel metadata for uploading the notebook.

## Local Result

- Training macro-F1 check on the 50 labeled rows: `1.0000`
- Kaggle submission public score: `0.9532`
- Kaggle submission private score: `0.9766`
