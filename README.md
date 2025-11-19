Project Overview:
This project implements a text classification system using Large Language Models (LLMs) to categorise traveller questions into coarse-grain intent classes. The goal was to evaluate LLM performance under different prompting strategies (zero-shot, few-shot) and compare them with a supervised fine-tuned model using Unsloth.

The system analyses 5,000 real-world travel-related questions and assigns one of seven classes:
TTD – Things to do
TGU – Travel guide
ACM – Accommodation
TRS – Transport
WTH – Weather
FOD – Food
ENT – Entertainment.

This project demonstrates end-to-end ML capability including data preparation, prompt engineering, LLM-based classification, few-shot learning, supervised fine-tuning, and model evaluation.

Dataset:
The dataset contains 5,000 traveller questions, each originally labelled with:
Coarse-grain class (7 categories above)
Fine-grain class (not used in this project)
✔ Data preparation steps
Loaded the CSV dataset
Removed the fine-grain label column
Split the remaining data into:
Split	Size
Training	4,000 samples
Testing	700 samples
Validation	300 samples

Tech Stack:
Python,
Unsloth (efficient LLM fine-tuning),
Hugging Face Transformers,
OpenAI / LLM APIs for zero-shot & few-shot experiments,
Pandas, NumPy,
Matplotlib for visualisation,
Scikit-learn for evaluation metrics.

Project Objectives:
Perform zero-shot and few-shot prompting on an LLM.
Select effective prompt templates for the task.
Use 1-shot and 3-shot examples to test performance improvements.
Perform supervised fine-tuning using Unsloth.
Evaluate and compare accuracy across all techniques.

Project Location: https://colab.research.google.com/drive/1kDnT0Jq7VDZS3BHy6M6junVm5l4YdT1x?usp=sharing

