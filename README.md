# Assignment 1

## Comparison of pre-trained models (and fine-tune [FT])

Here you will find the comparisons of all the different pre-trained models we tested, and if the fine-tuned we trained.

The models were trained locally using an NVIDIA RTX 3060 Laptop GPU (6GB VRAM), and 32GB of RAM

| Model codename            | Model in code                         | Training time (m) | (FT) Learning Rate | (FT) Epochs | (FT) Batch size | Test Accuracy | Test Loss Test | F1 Score |
| ------------------------- | ------------------------------------- | ----------------- | ------------------ | ----------- | --------------- | ------------- | -------------- | -------- |
| `bert-base-uncased`       | `BertForSequenceClassification`       | 6m14s             | 1e-5               | 3           | 32              | 0.879         | 0.395          | 0.879    |
| `bert-base-uncased`       | `BertForSequenceClassification`       | 6m33s             | 1e-5               | 3           | 16              | 0.901         | 0.344          | 0.901    |
| `distilbert-base-uncased` | `DistilBertForSequenceClassification` | 3m33s             | 1e-5               | 3           | 16              | 0.891         | 0.352          | 0.891    |



