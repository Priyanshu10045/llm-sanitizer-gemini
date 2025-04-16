# 🛡️ LLM Input/Output Sanitizer with Gemini

This Python-based chatbot uses Google's Gemini Pro API and sanitizes both user inputs and model outputs to prevent prompt injection and sensitive data leaks.

## 📦 Features

- ✅ Input filtering (removes injection attempts)
- ✅ Output filtering (removes hallucinated sensitive data)
- ✅ Command-line interface (CLI)
- ✅ Gemini Pro integration

 ## 🚀 Getting Started

### 1. Clone the repo 

```bash
git clone https://github.com/Priyanshu10045/llm-sanitizer-gemini.git
cd llm-sanitizer-gemini
```

### 2. Set up the environment

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Add your API key
Create a .env file in the root with:

```env
GOOGLE_API_KEY=your-api-key
```

### 5. Run the chatbot
```bash
python run.py
```
