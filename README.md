# Assignment 13: Generative AI with GPT

## Overview
This project is about Generative AI using a GPT-2 model. The goal is to see how the model generates text and how different settings like temperature and sampling affect the output.

The notebook uses a simple dataset and shows basic text generation examples.

---

## Dataset
The dataset used is *Alice’s Adventures in Wonderland* from Project Gutenberg.

I chose this dataset because it is:
- Free and publicly available  
- Easy to work with  
- A good example of natural language text  

https://www.gutenberg.org/

---

## Model Used
This project uses a pre-trained GPT-2 model from Hugging Face.

- Model: GPT-2  
- Library: Transformers (PyTorch)  
- Used for: generating text from prompts  

I did not train the model from scratch because it is too heavy, so I used a pre-trained version instead.

---

## What This Notebook Does
The notebook includes:

- Loading the dataset  
- Loading the GPT-2 model  
- Generating text from prompts  
- Changing output length  
- Testing temperature (creativity)  
- Using top-k and top-p sampling  
- Trying different prompts  

---

## Example Output
Example input:
“Write a short blog introduction about artificial intelligence”

The model generates a short paragraph based on that prompt.

---

## Ethical Notes
Generative AI can sometimes produce incorrect or biased text. Because of this, it should be used carefully, especially in real-world situations.

---

## How to Run
1. Open the notebook in Google Colab  
2. Run each cell from top to bottom  
3. Make sure internet is enabled so the model and dataset can load  

---

## Install Requirements 

pip install transformers torch requests

---
