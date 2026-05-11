# 🚀 Python AI Chatbot

A lightweight AI chatbot built with Python, Streamlit, and Google Gemini. This app provides a browser-based conversational interface and uses session-only memory, so no user data or chat history is stored permanently.

## Project Overview

This project is a simple AI assistant web app designed for fast, intuitive interactions. It uses Streamlit for the UI and the Google Generative AI Gemini model for response generation.

## ✨ Features

- 🚀 Real-time chat interface
- 🔐 Session-based memory only (no database)
- 🎨 Clean UI using Streamlit chat components
- ⚡ Powered by Google Gemini 1.5 Flash for fast responses
- 🧠 Minimal architecture and deployment overhead

## 🛠️ Getting Started

### Prerequisites

- Python 3.10 or newer
- `pip` package manager
- Google Cloud API key with access to the Generative AI API

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd Chatbot
```

2. Install required dependencies:

```bash
pip install streamlit google-generativeai
```

3. Configure your API key.

> Do not commit your API key to GitHub.

You can set the key directly in `app.py` while testing, but for production you should use environment variables instead.

Example using PowerShell:

```powershell
$env:GOOGLE_API_KEY="YOUR_API_KEY"
```

### Running the App

Start the Streamlit app:

```bash
streamlit run app.py
```

Then open the URL shown in the terminal (usually `http://localhost:8501`).

## 💬 Usage

- ✍️ Type your question in the chat input field.
- 📤 The app sends the message to the Google Gemini API.
- 💬 The response is displayed in the Streamlit chat window.
- 🕒 Chat history is only retained for the current browser session.

## 🔒 Notes on Security

- 🧭 The app is intentionally designed without a database.
- 🔐 User messages are stored only in the current Streamlit session and are not persisted.
- ⚠️ Remove any hard-coded API keys before pushing to GitHub.

## 📁 Project Structure

- `app.py` — main Streamlit application file
- `README.md` — project documentation

## 🧩 Tech Stack

- Python
- Streamlit
- Google Generative AI (Gemini)

## 📝 License

This project is available under the MIT License. Feel free to adapt it for academic or personal use.
