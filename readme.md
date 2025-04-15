# AI Agents Implementation

This repository contains various implementations of AI agents and RAG (Retrieval Augmented Generation) systems using different frameworks.

## Project Structure

- `human-in-loop.ipynb` - Implementation of a human-in-the-loop chatbot using LangGraph
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