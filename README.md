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
```shell
pip install -r requirements.txt
```

2. Add your text document and update its path in 'run-llm.py' as INPUT_DOCUMENT_PATH.

3. Place your desired LLM in the models/LLM_NAME directory. Ensure that the path is updated in 'run-llm.py' under MODEL_PATH.

4. Run the file:
```shell
python run-llm.py
```
  Note: It might take some time to run.

5. Ask your query and wait for the LLM to respond!


## Example 

![image](https://github.com/mrunal-z/llm-qna-system/assets/79525611/8f16cfc7-06e0-4c70-9ef4-f9352e2e36e1)


