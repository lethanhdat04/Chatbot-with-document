***SETUP***

Before running, you need install ```Ollama``` to use model in your local. In this source, I use ```nomic-embed-text```model to embedding text and ```mistral``` to respone to user.
```
ollama pull mistral
ollama pull nomic-embed-text
```

Necessary libraries:
```
pip install langchain
pip install langchain_chroma
pip install pypdf
pip install pytest
pip install langchain_ollama
```

Embedding document and add to database:
```
python .\populate_database.py
```

Embedding query and response to user:
```
python .\query_data.py "query"
```

**Demo**
![image](https://github.com/user-attachments/assets/693b2578-89ab-4082-85af-5c8b458ab465)
