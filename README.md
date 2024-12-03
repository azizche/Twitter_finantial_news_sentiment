# Sentiment Analysis on Financial News Using LoRA-Fine-Tuned GPT-2

## Overview
This project demonstrates the application of **Parameter-Efficient Fine-Tuning (PEFT)** using **QLoRA (Low-Rank Adaptation)** to adapt the **GPT-2** model for sentiment analysis on financial news from Twitter. The goal is to analyze and compare the model's performance before and after fine-tuning with a domain-specific dataset, highlighting the benefits of LoRA in reducing computational requirements while achieving effective results.

## Features
- Fine-tuning GPT-2 using LoRA, a PEFT technique designed for efficient training with minimal parameter updates.
- Use of a **Twitter Financial News Sentiment** dataset for domain-specific adaptation.
- Performance comparison between:
  - Pre-trained GPT-2 (before fine-tuning).
  - Fine-tuned GPT-2 (after applying LoRA).

## Dataset
The dataset contains Twitter posts related to financial news labeled with sentiment (e.g., bearish (associated with falling share prices), Bullish(associated with rising share prices) and neutral). This domain-specific dataset allows the model to adapt to financial sentiment nuances.

## Methodology
1. **Model Selection**: GPT-2, chosen for its robust language generation capabilities.
2. **Fine-Tuning with LoRA**: LoRA is employed to modify only a subset of model parameters, making the fine-tuning process parameter-efficient and less computationally expensive.
3. **Evaluation**: Compare the sentiment analysis performance of the base GPT-2 model with the fine-tuned version using key metrics (e.g., accuracy, F1-score).

