# Assignment 13: Generative AI with GPT

## Overview
This project explores Generative Artificial Intelligence using a GPT-2 model. The goal is to understand how transformer-based models generate human-like text and how different sampling parameters affect output quality.

The notebook demonstrates dataset usage, text generation, and parameter tuning using a simple and practical implementation.

---

## Dataset
The dataset used in this project is *Alice’s Adventures in Wonderland* from Project Gutenberg.

This dataset was chosen because:
- It is publicly available and free to use  
- It contains structured narrative text  
- It is suitable for text generation tasks  

Source: https://www.gutenberg.org/

---

## Model Used
This project uses a pre-trained GPT-2 model from Hugging Face Transformers.

- Model: GPT-2  
- Library: Transformers (PyTorch backend)  
- Purpose: Generate text from input prompts  

Note: The model was not trained from scratch due to computational limitations. Instead, a pre-trained model was used for demonstration and parameter experimentation.

---

## Features Implemented
The notebook includes:

- Environment setup and library installation  
- Dataset loading and preprocessing  
- GPT model and tokenizer loading  
- Custom text generation function  
- Basic text generation  
- Output length control  
- Temperature adjustment  
- Top-k and top-p sampling  
- Prompt engineering experiments  
- Real-world application example (content generation)  

---

## Example Output
The model can generate text such as:

> Input: "Write a short blog introduction about artificial intelligence"  
> Output: AI-generated paragraph based on GPT-2 predictions

---

## Ethical Considerations
Generative AI systems may produce biased, incorrect, or nonsensical outputs depending on training data and prompt design. These models should be used responsibly, especially in educational and real-world applications.

---

## Requirements
Install dependencies using:

```bash

pip install transformers torch requests

---

**How to Run**

- Open the notebook in Google Colab
- Run all cells from top to bottom
- Ensure internet access is enabled for model and dataset loading

---

Author: Alyssa I

---
