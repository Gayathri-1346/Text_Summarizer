# AI Text Summarization System using NLP and Transformer Models

## Overview

AI Text Summarization System is an NLP-based web application that generates concise and meaningful summaries from lengthy textual content. The system leverages the BART Transformer model to perform abstractive text summarization while preserving the core meaning of the original text.

In addition to summarization, the application provides multilingual translation, text-to-speech conversion, keyword extraction, vocabulary simplification, and evaluation metrics to enhance accessibility and user understanding.

## Features

* Abstractive text summarization using BART (facebook/bart-large-cnn)
* Supports text input, file upload, and URL-based content extraction
* Simplified summary generation using synonym replacement
* Multilingual translation support
* Text-to-Speech (TTS) audio generation
* Keyword extraction with meanings
* Spelling correction and text preprocessing
* Summary quality evaluation metrics
* Interactive Streamlit-based user interface

## Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### NLP & Machine Learning

* Transformers (Hugging Face)
* BART (facebook/bart-large-cnn)
* PyTorch
* NLTK
* spaCy

### Additional Libraries

* BeautifulSoup
* Deep Translator
* gTTS
* PySpellChecker
* Requests

## System Workflow

1. User enters text, uploads a file, or provides a URL.
2. Input text is extracted and preprocessed.
3. Text is divided into manageable chunks.
4. BART model generates a professional summary.
5. Simplified summary is created using rule-based synonym replacement.
6. Keywords and important vocabulary are extracted.
7. Users can translate summaries into multiple languages.
8. Text-to-Speech converts summaries into audio.
9. Evaluation metrics are calculated and displayed.

## Project Structure

```bash
AI-Text-Summarizer/
│
├── app.py
├── app/
│   ├── ui.py
│
├── utils/
│   ├── extractor.py
│   ├── nlp.py
│   ├── translator.py
│   ├── audio.py
│
├── assets/
│   ├── logo.png
│
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Text-Summarizer.git
cd AI-Text-Summarizer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Using Streamlit:

```bash
streamlit run app.py
```

The application will start on:

```text
http://localhost:8501
```

## Evaluation Metrics

The system evaluates generated summaries using:

* Retention Score
* Compression Percentage
* Simplicity Score
* Readability Score
* Overall Accuracy Score

## Applications

* Academic research summarization
* News article summarization
* Report analysis
* Content review
* Educational learning assistance
* Multilingual information access

## Future Enhancements

* PDF and DOCX document summarization
* Real-time web content summarization
* Custom summary length selection
* Domain-specific summarization
* Mobile application deployment
* Advanced Transformer model integration

## Authors

* S. Gayathri
* K. Dharani
* N. Harshitha

## License

This project is developed for educational and research purposes.
