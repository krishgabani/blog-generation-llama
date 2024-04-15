### Guidelines while using Google Colab
```
1. !huggingface-cli login

2. upload files: .env, app.py, requirments.txt

3. !pip install -r "/content/requirments.txt"

4. !wget -q -O - ipv4.icanhazip.com

5. !streamlit run app.py & npx localtunnel --port 8501
```

### Secrets to use Langsmith
```js
LANGCHAIN_TRACING_V2 = "true"
LANGCHAIN_ENDPOINT = "https://api.smith.langchain.com"
LANGCHAIN_API_KEY =
LANGCHAIN_PROJECT = "Blog Generation"
```
