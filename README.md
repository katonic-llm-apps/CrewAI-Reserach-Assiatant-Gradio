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


## Usage

1. Run the application:
   ```
   python app.py
   ```

2. Open your web browser and navigate to the URL displayed in the terminal (typically http://127.0.0.1:7860).

3. In the app:
   - Enter your OpenAI API key (if not provided in the `.env` file)
   - Select the model and set the temperature
   - Choose the process type (Sequential or Hierarchical)
   - Enter a research topic
   - Select the content type and tone
   - Click "Run CrewAI" to generate the content

## Understanding the Process Types

- **Sequential Process**: Agents work one after another, with the output of one agent serving as input for the next.
- **Hierarchical Process**: Agents work in a hierarchical structure, with some agents delegating tasks to others.

## Requirements

- Python 3.8+
- An OpenAI API key with access to the models you want to use

