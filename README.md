# CrewAI Gradio Demo

This is a Gradio-based web application that demonstrates the capabilities of CrewAI for conducting research and generating content. 

## Features

- Two AI agents working together:
  - Research Agent: Conducts comprehensive research on specified topics
  - Writing Agent: Creates engaging content based on the research
- Customizable options:
  - Topic selection for research
  - Content type (Blog Post, Article, Report, etc.)
  - Tone of writing (Informative, Conversational, Technical, etc.)
  - Process type (Sequential or Hierarchical)
  - Temperature setting for model creativity
  - Model selection (GPT-4o, GPT-4-turbo, GPT-3.5-turbo)


## 📋 Requirements

- Python >=3.10 and <3.13
- OpenAI API key or GROQ API key
- Exa API key
- Streamlit

## 🚀 Getting Started

1. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
gradio run app.py
```

## 🔑 API Keys Setup

The application requires the following API keys:

1. **OpenAI API Key** or **GROQ API Key**
   - For OpenAI: Get it from [OpenAI Platform](https://platform.openai.com/)
   - For GROQ: Get it from [GROQ Console](https://console.groq.com/)

2. **Exa API Key**
   - Get it from [Exa](https://exa.ai)

Enter these keys in the sidebar of the application when prompted.


