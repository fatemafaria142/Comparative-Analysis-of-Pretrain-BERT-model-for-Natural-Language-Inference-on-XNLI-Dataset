# Comparative Analysis of Pretrained BERT Models for Natural Language Inference on XNLI Dataset

## Overview
This project aims to perform a comparative analysis of various pre-trained BERT models for Natural Language Inference (NLI) using the XNLI dataset available from Hugging Face. The selected BERT models for analysis are:
- mBERT (Multilingual BERT)
- BanglaBERT
- Bangla-bert-base
- DistilBERT
- XLM-Roberta
- SahajBERT

## Dataset
The XNLI dataset used in this project is obtained from Hugging Face datasets: [XNLI Dataset Link](https://huggingface.co/datasets/csebuetnlp/xnli_bn?row=8)

### Dataset Overview
The XNLI dataset is utilized for Natural Language Inference (NLI) tasks. It consists of three main columns:

- `sentence1`: Represents the first sentence or premise in the NLI pair.
- `sentence2`: Denotes the second sentence or hypothesis in the NLI pair.
- `label`: Contains categorical labels indicating the relationship between `sentence1` and `sentence2`. The labels include:
  - `'Contradiction'`: Indicates a contradictory relationship between the two sentences.
  - `'Entailment'`: Denotes an entailment or logical relationship where one sentence logically follows from the other.
  - `'Neutral'`: Represents a neutral or unrelated relationship between the sentences.

### Dataset Structure
- **Dataset Size:**
  - **Train Samples:** took 15,000 samples from the main train dataset for training.
  - **Test Samples:**  4,895 samples for testing.
  - **Validation Samples:**  2,419 samples for validation.

## Evaluation Metrics
The evaluation of the models is based on the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Jaccard Score
- Logloss
- Specificity
- ROC AUC

