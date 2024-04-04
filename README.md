---
BERT-Emotion-Classifier:
  - Task:
      Text Classification
  - Metrics:
    - Accuracy: 0.938  
    - F1: 0.9375
---

# Results

This model is a fine-tuned version of [bert-base-uncased](https://huggingface.co/bert-base-uncased) on the emotion dataset.
It achieves the following results on the evaluation set:
- Loss: 0.3890
- Accuracy: 0.938
- F1: 0.9375

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 1e-05
- train_batch_size: 64
- num_epochs: 12
