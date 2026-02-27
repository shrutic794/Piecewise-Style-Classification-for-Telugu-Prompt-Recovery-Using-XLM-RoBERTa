# Piecewise-Style-Classification-for-Telugu-Prompt-Recovery-Using-XLM-RoBERTa

# Telugu Prompt-Style Recovery (DravidianLangTech ACL 2026)

This repository contains the implementation of our submission to the
DravidianLangTech @ ACL 2026 shared task on Telugu Prompt-Style Recovery.

## Model
- Backbone: XLM-RoBERTa-base
- Piecewise segment aggregation with max pooling
- Optimizer: AdamW
- Learning rate: 2e-5

## Requirements

Install dependencies:

pip install -r requirements.txt

## Training

Run the Jupyter notebook:
telugu_style_recovery.ipynb

## Citation

If you use this code, please cite our ACL 2026 paper.
