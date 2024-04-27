# Benchmarking README

This repository contains benchmarking data and code for several tasks which is held by AlBert & DistilBert models:

## ARC Benchmarking
- ARC (AI2 Reasoning Challenge) benchmarking assesses algorithms' ability to solve elementary science questions.
- Dataset: Custom Dataset
- Evaluation Metrics: Accuracy, F1 Score, etc.

## GSM8K Benchmarking
- GSM8K (General Social Media Sentiment 8K) benchmarking evaluates sentiment analysis models on social media data.
- Dataset: Custom Dataset
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, etc.

## MMLU Benchmarking
- MMLU (Multi-Modal Language Understanding) benchmarking assesses models' language comprehension in multi-modal contexts.
- Dataset: MMLU dataset (SQUAD)
- Evaluation Metrics: Accuracy, BLEU Score, ROUGE Score, etc.

## TruthfulQA Benchmarking
- TruthfulQA benchmarking evaluates models' ability to answer questions truthfully based on context.
- Dataset: TruthfulQA dataset (SQUAD)
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, etc.

## HellaSwag Benchmarking
- HellaSwag benchmarking assesses models' ability to predict commonsense reasoning in everyday situations.
- Dataset: HellaSwag dataset (SQUAD)
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, etc.

Each benchmarking task includes code for running experiments and evaluating models.

### Note:
 The models may show 0.0 or 1.0 at some places, as we know that these models used in the benchmarking (AlBert & DistilBert) are not efficient model to perform upto the mark. 
 Finetuning  may Yeild better results!!
