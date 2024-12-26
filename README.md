# Finetune Llama-3-2-3b-instruct on Custom Dataset

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Leya-LI/LLM-API-Explorer/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/Leya-LI/LLM-API-Explorer.svg)](https://github.com/Leya-LI/LLM-API-Explorer/issues)
[![GitHub stars](https://img.shields.io/github/stars/Leya-LI/LLM-API-Explorer.svg)](https://github.com/Leya-LI/LLM-API-Explorer/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Leya-LI/LLM-API-Explorer.svg)](https://github.com/Leya-LI/LLM-API-Explorer/network)

## Overview
This repository provides a comprehensive guide and implementation for fine-tuning large language models (LLMs) for custom applications. It covers the entire pipeline, from task formulation and dataset preparation to hyperparameter tuning and evaluation. The primary goal is to help users adapt LLMs to specific domains or tasks while achieving optimal performance.

## Features
- **Task Formulation**: Define the objectives and desired outputs of the model.
- **Data Preparation**: Clean, preprocess, and format datasets for fine-tuning.
- **Model Configuration**: Select and configure pre-trained LLMs for adaptation.
- **Training**: Fine-tune the model using advanced techniques to prevent overfitting and improve generalization.
- **Evaluation**: Assess model performance using metrics such as ROUGE.
- **Hyperparameter Tuning**: Optimize training parameters for the best results.

## Prerequisites

- **Hardware Requirements**:
  - A GPU with at least 16 GB memory.
- **Library Requirements**:
  - Python 3.10.12 or higher.
  - bitsandbytes: 0.45.0
  - transformers: 4.47.1
  - peft: 0.14.0
  - accelerate: 1.2.1
  - datasets: 3.2.0
  - scipy: 1.13.0
  - einops: 0.8.0
  - evaluate: 0.4.3
  - trl: 0.13.0
  - rouge_score: 0.1.2

## References
- [Fine Tune Large Language Model (LLM) on a Custom Dataset with QLoRA] (https://dassum.medium.com/fine-tune-large-language-model-llm-on-a-custom-dataset-with-qlora-fb60abdeba07)
  
## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
