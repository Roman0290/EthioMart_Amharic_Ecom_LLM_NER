# EthioMart Amharic E-Commerce LLM NER

## Overview

EthioMart aims to revolutionize the Ethiopian e-commerce landscape by becoming the central hub for Telegram-based e-commerce activities. With the rise of decentralized e-commerce channels on Telegram, vendors and customers face challenges in managing multiple channels for product discovery, order placement, and communication.  

This project focuses on developing a system that fine-tunes large language models (LLMs) for **Amharic Named Entity Recognition (NER)**. The goal is to extract key business entities—such as product names, prices, and locations—from messages, images, and documents shared in these channels and use the extracted data to power EthioMart's centralized platform.

---

## Key Objectives

1. **Real-time Data Extraction**: Extract and process data from Ethiopian Telegram e-commerce channels.  
2. **Fine-tuning LLMs**: Adapt LLMs to accurately perform NER tasks in Amharic.  
3. **Entity Extraction**: Identify and extract key entities, including:
   - **Product Names or Types**
   - **Materials or Ingredients**
   - **Location Mentions**
   - **Monetary Values (Prices)**

4. **Model Interpretability**: Use tools like SHAP and LIME to explain model predictions.  

---

## Data Sources

1. **Telegram Channels**: Data from Ethiopian e-commerce Telegram channels (e.g., Shager Online Store).  
2. **NER Dataset**: Amharic news-labeled NER dataset for training and evaluation.  

### Data Types
- **Text**: Amharic-language messages from Telegram.  
- **Images**: Product photos, marketing materials, and infographics.  

---

## Project Workflow

1. **Data Collection & Preprocessing**  
   - Scrape and preprocess messages and images from Telegram channels.  
   - Perform Amharic tokenization and text preprocessing.  

2. **Model Fine-tuning**  
   - Fine-tune LLMs for Amharic NER tasks.  
   - Experiment with different architectures and pre-trained models.  

3. **Evaluation & Analysis**  
   - Evaluate model performance using metrics like F1-score, precision, and recall.  
   - Use SHAP and LIME for model interpretability.  

4. **Entity Extraction Pipeline**  
   - Extract entities from text and images.  
   - Populate EthioMart’s centralized database with the extracted data.  

---

## Skills & Tools

### Required Knowledge:
- **Amharic Text Processing**: Tokenization, stemming, and preprocessing.  
- **NER Fine-tuning**: Adapting LLMs to extract named entities.  
- **Model Evaluation**: Metrics such as F1-score, precision, and recall.  
- **Interpretability Tools**: Using SHAP and LIME to understand predictions.  

### Tools & Frameworks:
- **LLMs**: Hugging Face Transformers, BERT, or similar.  
- **Libraries**: TensorFlow, PyTorch, spaCy.  
- **Database**: Centralized data storage for extracted entities.  
- **Scraping Tools**: For extracting Telegram channel data.  

---


