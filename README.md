# Local LLM-based Question-Answering System

This project is a simple Question Answering system powered by local Large Language Models (LLMs), built with [LangChain](https://github.com/hwchase17/langchain). 

## Overview
You can feed this system with any text document and then ask questions related to the topics in the document. For demonstration purposes, "stellarcorp.txt" has been included, which contains information about a fictional company and its employees.
The system accepts one text document about any topic, then you can query that document using a local LLM of your choice. As an example, the document "stellarcorp.txt" has been used, which contains information about a fictional company and its employees. The primary LLM used is [gpt4all-j-v1.3-groovy](https://gpt4all.io/models/ggml-gpt4all-j-v1.3-groovy.bin). 

## Getting Started
### Requirements
Python 3.10 or newer.

### Setup & Run
1. Start by installing the required dependencies:
pip install -r requirements.txt

2. Add your text document and update its path in 'run-llm.py' as INPUT_DOCUMENT_PATH.

3. Place your desired LLM in the models/LLM_NAME directory. Ensure that the path is updated in 'run-llm.py' under MODEL_PATH.

4. Run the file:
python run-llm.py
