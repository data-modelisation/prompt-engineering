# Generative AI
![alt Application Cover](images/cover.png)

## Presentation 
This is a Python-based project focused on explore the power of llm model and framework such as GPT4ALL and LangChain. 

It includes notebooks providing an overview of the LangChain framework, querying local documents with Obsidian, and integrating with GPT4All models. 
 
You can exploring notebooks for in-depth demonstrations of various prompt processing in Python and chatbot functionalities.


## Key Components 

The project's structure involves organized notebooks and locally downloaded GPT4All models. 

The collection of Jupyter notebooks are organized as follows: 

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
The following table provides an overview of the notebooks contained within this project:  

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

````
git clone https://github.com/data-modelisation/prompt-engineering.git
````

2. Configure API keys 

Optain API key for OpenAI. Insert these keys in the configuration file .env : 

```.env
OPENAI_API_KEY= <obtained API key>
```


### Optain API key for OpenAI

You can do this by following the link to [generate OpenAI API key](https://platform.openai.com/account/api-keys).  
Additionally, you can use another link to [monitor your API usage](https://platform.openai.com/account/usage).