# HuggingFace-x-LangChain-Text-Summarization-from-Youtube-

This Streamlit app allows users to summarize content from YouTube videos or website URLs using HuggingFace language models and LangChain components. It is integrated with a HuggingFace model to generate summaries based on video or website text content.

# Features

Summarize content from YouTube or website URLs.

Uses HuggingFace Mistral-7B-Instruct model for summarization.

Validates URLs and handles exceptions with useful feedback.

Customizable API integration.

# Installation:

Clone the repository:

git clone https://github.com/your-repo/your-app.git
cd your-app

# Install dependencies:

pip install -r requirements.txt

# Usage

Run the app:

streamlit run app.py

Enter your HuggingFace API key in the sidebar.

Input a YouTube or website URL to summarize and click "Summarize the Content from YT or Website."

# Components

# HuggingFace API Integration:
Uses the HuggingFace Mistral-7B-Instruct model for generating summaries.
# LangChain PromptTemplate:
Provides a customizable prompt template for summarization.
# Document Loaders:
Handles both YouTube video and website content extraction.

# Requirements

Python 3.x

Streamlit

LangChain

HuggingFace API Token







