# My First GenAI App

A simple Streamlit chatbot powered by Google's Gemini model.

## Overview
This project is a beginner-friendly Generative AI app where users can:
- Enter a Gemini API key in the sidebar
- Ask a question in the main input box
- Get a response from `gemini-2.5-flash`

The app is built with Streamlit and the `google-genai` SDK.

## Tech Stack
- Python
- Streamlit
- Google Gemini API (`google-genai`)

## Project Structure
- `app.py` - Main Streamlit application
- `requirements.txt` - Python dependencies
- `README.md` - Project documentation

## Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd My_first_GenAI_app
```

### 2. Create and activate a virtual environment (recommended)
```bash
python -m venv .venv
```

Windows (PowerShell):
```bash
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
streamlit run app.py
```

## How to Use
1. Open the app in your browser (Streamlit will show the local URL).
2. Paste your Gemini API key in the sidebar.
3. Type your question.
4. Click **Ask AI Assistant**.

## API Key
Get a Gemini API key from Google AI Studio:
https://aistudio.google.com/

## Notes
- The API key is entered at runtime through the UI.
- Basic error handling is included for failed API calls.

## Future Improvements
- Add chat history/stateful conversation
- Support model selection from the UI
- Add environment variable support for API key
- Improve UI styling and response formatting

