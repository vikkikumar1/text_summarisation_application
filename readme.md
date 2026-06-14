# 📝 Text Summarizer using Fine-Tuned T5 Transformer

A powerful NLP-based Text Summarization application built using a fine-tuned T5 (Text-to-Text Transfer Transformer) model. The application generates concise and meaningful summaries from lengthy text inputs through an intuitive web interface.

## 🚀 Live Demo

Hugging Face Space: https://huggingface.co/spaces/vikkikumar123/text-summariser-app

## 📌 Project Overview

This project leverages the T5 Transformer architecture for abstractive text summarization. The model was fine-tuned on a summarization dataset and deployed using FastAPI and Hugging Face Spaces.

Users can enter large blocks of text and instantly receive a concise summary while preserving the key information and context.

## ✨ Features

* Abstractive Text Summarization
* Fine-Tuned T5 Transformer Model
* FastAPI Backend
* Interactive HTML Frontend
* Real-Time Summary Generation
* Hugging Face Model Hosting
* Docker-Based Deployment
* Responsive User Interface

## 🛠️ Tech Stack

### Machine Learning & NLP

* Python
* Transformers (Hugging Face)
* T5 Transformer
* PyTorch

### Backend

* FastAPI
* Uvicorn

### Frontend

* HTML
* CSS
* JavaScript

### Deployment

* Hugging Face Hub
* Hugging Face Spaces
* Docker



## 🤖 Model Information

Model Name:

vikkikumar123/text-summariser-t5

The model is hosted on Hugging Face Hub and loaded dynamically during application startup.

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/vikkikumar1/text_summarisation_application.git
cd text_summarisation_application
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate Environment:

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run Locally

```bash
uvicorn app:app --reload
```

Open:

```text
http://127.0.0.1:8000
```

## 📖 API Endpoint

### Summarize Text

```http
POST /summarize/
```

Request:

```json
{
  "dialogue": "Enter long text here..."
}
```

Response:

```json
{
  "summary": "Generated summary text..."
}
```

## 📊 Example

### Input

Artificial Intelligence is rapidly transforming industries worldwide. Organizations are leveraging AI-powered systems to automate processes, improve efficiency, and enhance decision-making.

### Output

AI is transforming industries by automating processes, improving efficiency, and enhancing decision-making.

## 🎯 Future Enhancements

* PDF Summarization
* Document Upload Support
* Summary Length Controls
* Multi-Language Summarization
* User Authentication
* Summary Download Feature
* Advanced UI Enhancements

## 📜 License

This project is released under the MIT License.

Feel free to use, modify, and distribute this project for educational and research purposes.
