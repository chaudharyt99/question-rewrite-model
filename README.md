# question-rewrite-model
Question rewrite model for the Disfl-QA benchmark dataset

## BART Model Fine-Tuning and Inference Guide

### Overview

This guide covers the essentials of fine-tuning the bart-base model and using it for inference. The provided resources include two Jupyter notebooks and a detailed development process document.

#### Notebooks

- **bart-experiment.ipynb**
  - This notebook contains the complete workflow for fine-tuning a bart-base model using the [Disfl-QA Dataset](https://github.com/google-research-datasets/Disfl-QA). After fine-tuning, the model is uploaded to [Huggingface](https://huggingface.co/tchoudh8/bart-base-finetuned-w-data-augm-4e-5) to ensure easy access and training and hyperparameter optimisation logs are also updated on [WandB](https://wandb.ai/tchoudh8/chata-ai?nw=nwuserchoudharytushar1599).

- **bart-inference.ipynb**
  - Designed for performing inference with the fine-tuned bart-base model hosted on Huggingface. 

#### Project Overview Document

- This document delineates the methodology followed during the research, model development and improvement phases. It includes comprehensive details about data processing, augmentation, model choice, hyperparameters, and the fine-tuning strategy.

### Usage Instructions

To test the model using your dataset:

1. Put the file path og your `.json` dataset in this function `load_and_process_json_datasets('<file.json>')`
2. Execute the appropriate notebook, whether for training or inference, depending on your requirements.

