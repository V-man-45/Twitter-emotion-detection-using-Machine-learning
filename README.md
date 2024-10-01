Fine-Tuning Large-Scale NLP Models with Parameter-Efficient Methods (LoRA & QLoRA)
This project explores fine-tuning large pre-trained NLP models using parameter-efficient techniques such as Low-Rank Adaptation (LoRA) and Quantized Low-Rank Adaptation (QLoRA). The models were fine-tuned on sentiment analysis tasks using the Kaggle Emotion Detection dataset, which includes binary labels for emotions such as anger, joy, love, optimism, and more.

Key Features
Model Architecture: Utilized models from the Hugging Face hub, specifically google/gemma-1.1-2b-it and a similar-sized latest model, likely based on the transformer architecture.
Tasks: Fine-tuned models on sentiment analysis using LoRA and QLoRA. Also evaluated model performance on Named Entity Recognition (NER) and Emotion Detection tasks.
Dataset: The Kaggle Emotion Detection dataset, which classifies tweets into multiple emotional categories such as anger, joy, sadness, and others.
Evaluation Metrics: The models were evaluated based on accuracy, macro F1, micro F1 scores, and loss value. Results from different fine-tuning approaches were compared to highlight their effectiveness.
Results
LoRA Fine-Tuning:
Macro F1 Score: ~55.89%
Micro F1 Score: ~66.77%
Accuracy: ~21.52%
Loss: ~0.72
Alternate Fine-Tuning (parameter-efficient method):
Macro F1 Score: ~54.26%
Micro F1 Score: ~65.40%
Accuracy: ~18.67%
Loss: ~0.62
QLoRA Fine-Tuning:
Macro F1 Score: ~56.21%
Micro F1 Score: ~66.90%
Accuracy: ~19.19%
Loss: ~1.04
Conclusion
Although all models showed moderate performance improvements, the QLoRA fine-tuning method achieved the best results in terms of classification accuracy and F1 scores. These parameter-efficient techniques demonstrated their ability to fine-tune large language models without sacrificing much performance while maintaining computational efficiency.
