# LocalAIAgentWithRAG
forked from: https://www.youtube.com/watch?v=E4l91XKQSgw

## install dependencies

install uv for managing your python environment https://docs.astral.sh/uv/
``` bash
uv venv
source .venv/bin/activate
uv pip install requirements.txt
```

install ollama: https://ollama.com/download and pull the LLM and embedding model 

``` bash
ollama pull llama3.2
ollama pull mxbai-embed-large
```

## run the RAG system:

``` bash
uv run main.py
```