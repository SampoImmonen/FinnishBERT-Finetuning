# Finetuning a Finnish BERT model for text classification
Notebook to finetune Finnish BERT for text classification using data from https://github.com/aajanki/eduskunta-vkk

- BERT achieves a validation accuracy of 0.777 and test accuracy of 0.761
- baseline classifier achieves accuracy of 0.71


## features
- Class weights
- Tensorboard for visualization
- Gradient clipping
- learning rate scheduler
- testing with dynamically quantized model
- heat matrix for evaluation
- grouped parameters for optimizer weight decay