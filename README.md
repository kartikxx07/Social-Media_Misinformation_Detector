# Social Media Misinformation Detection Algorithm

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface&logoColor=black)
![OCR](https://img.shields.io/badge/OCR-Tesseract%2FPaddleOCR-lightgrey?logo=google&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-blueviolet)
![LangChain](https://img.shields.io/badge/LangChain-NLP%20Pipelines-orange)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Introduction
A prototype algorithm for detecting misinformation on social media, classifying posts into clickbait or factual errors. Built as a foundation for scalable, robust misinformation detection systems.

## Key Features

Content Classification: Detects clickbait and factual errors in social media posts

Pre-trained NLP Models: State-of-the-art transformer-based analysis

OCR Integration: Can process text from images in posts

Vector Search: Uses FAISS for efficient similarity matching

LangChain: Supports modular pipelines for text processing and analysis

Proof-of-Concept: Focused on algorithmic accuracy over scalability

## 🛠️ Technical Stack

Python 3.11

HuggingFace Transformers – NLP models

OCR (Tesseract/PaddleOCR) – Extracts text from images

FAISS – Vector similarity search

LangChain – Modular NLP pipelines

NumPy & SciPy – Cosine similarity & text analysis

Pandas – Data processing

## 📊 Dataset & Metrics

Dataset Size: ~10,000 social media posts (scraped and self-labeled)

Clickbait Detection Accuracy: 81%

Factual Error Detection Accuracy: 75%

Overall Accuracy: 78%

Metrics are based on a prototype dataset and serve as proof-of-concept.

## 🚀 Challenges & Limitations

Not optimized for real-time or batch processing

Cosine similarity is a naive metric for clickbait detection

Limited labeled data restricts supervised learning performance

Currently supports text-only and image-extracted text; no video or multimedia content yet

## 🗺️ Future Roadmap

Algorithm Improvements: Advanced embeddings and NLP techniques

Scalability: Optimize for batch and real-time processing

Multi-Modal Analysis: Extend to videos, images, and multimedia content

Account-Level Filtering: Detect users spreading misinformation

RLHF Integration: Adaptive learning from human feedback

Commercial-Grade UX: Build intuitive user interfaces for deployment

## 🤝 Contribution

We welcome contributions to:

Improve NLP detection models

Curate larger labeled datasets

Optimize for scalability and performance

Extend support for videos and multi-modal content

Author: Kartikay Luthra
Contact: https://www.linkedin.com/in/kartikay-luthra-656592229/
 | kartikluthra2020@gmail.com
