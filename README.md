# Generative AI

## Overview 

This is a Python-based project that leverages the power of GPT-4 for All and LangChain. 


## Key Components 

This project has notebooks and local models : 

```
promptengineering
├─ models
│  ├─ model1.bin
├─ 0_LangChain_overview.ipynb 
├─ 1_LangChain_Obsidian_loader.ipynb   
├─ 2_gpt4all_overview.ipynb  
├─ 3_LangChain_gpt4all.ipynb   
├─ 4_chatbot_openai.ipynb 
├─ 5_chatbot_gpt4all.ipynb 
└─ ...
```

Folder `models` contains download locally models for gpt4all.
They are loaded in notebooks by command : 
```python
model = GPT4All(model_name, model_path="models")
```
The folowing table contains the description of the notebook:  

| Notebook Filename                        | Description                                                   |
|-------------------------------------------|---------------------------------------------------------------|
| 0_LangChain_overview.ipynb               | Overview of the LangChain framework                            |
| 1_LangChain_Obsidian_loader.ipynb        | Querying local documents created with Obsidian               |
| 2_gpt4all_overview.ipynb                 | Overview of the locally-running LLM GPT4ALL                   |
| 3_LangChain_gpt4all.ipynb                | Example of using LangChain to interact with GPT4All models |
| 4_chatbot_openai.ipynb                   | Example of chatbot using  OpenAI's model                                |
| 5_chatbot_gpt4all.ipynb                  | Example of chatbot using GPT4All model                        |




## Getting Started

To get started with this project, follow these steps :

1. Clone the Repository 

2. Configure API keys 

Optain API key for OpenAI. Insert these keys in the configuration file .env : 

```.env
OPENAI_API_KEY= <obtained API key>
```


### Optain API key for OpenAI

You can do this by following the link to [generate OpenAI API key](https://platform.openai.com/account/api-keys).  
Additionally, you can use another link to [monitor your API usage](https://platform.openai.com/account/usage).