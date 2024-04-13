## Chatbot with tools

This is the code associated with my Medium post "Power-up Ollama Chatbots with tools".

To try the app out yourself, follow these steps:

1. Install [Ollama](https://ollama.com/) locally on your machine.
2. Ensure the Mistral Instruct LLM is downloaded
```ollama pull mistral:instruct```
3. Install dependencies.
```pipenv install```
4. Run the streamlit app.
```streamlit run chatbot.py```