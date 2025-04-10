# AI Agents Implementation

This repository contains various implementations of AI agents and RAG (Retrieval Augmented Generation) systems using different frameworks.

## Project Structure

- `chatbot_rag_langgraph.ipynb` - Implementation of a RAG-based chatbot using LangGraph
- `ragagents-ipynb.ipynb` - RAG agents implementation 
- `smolagents.ipynb` - Implementation using SmalAgents framework

## Dependencies

- Python 3.10+
- langgraph
- langchain-mistralai
- langchain_huggingface
- tavily-python
- langchain_community
- smolagents

## Setup

1. Install the required dependencies:
```bash
pip install -q langgraph langchain-mistralai langchain_huggingface
pip install -U tavily-python langchain_community
pip install smolagents
```

2. Set up the required API keys:
- Mistral AI API key
- Tavily API key

## Features

- RAG-based chatbot implementation using LangGraph
- Tool-based conversation flows
- Integration with search APIs
- Custom state management
- Graph-based conversation routing

## Usage

The notebooks can be run in any Jupyter environment. Each notebook is self-contained with its own setup and implementation details.

For example, to run the main RAG chatbot:
1. Open `chatbot_rag_langgraph.ipynb`
2. Set up your API keys
3. Run all cells sequentially
4. Interact with the chatbot through the provided interface

## License

MIT License

## Contributors

- Kunal Mishra