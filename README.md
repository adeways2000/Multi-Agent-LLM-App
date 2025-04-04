# Multi-Agent-LLM-App
Multi agentic Large Languge Model Application using Langchain

#Goal
LangGraph: Basic Multi-Agent App to replace a Content Marketing Team

Why use LangGraph?
To build Multi-Agent LLM Apps.
LangGraph can coordinate multiple agents.
The LLM Apps of the future: Agentic Behavior.



# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a Poetry environment after opening the repository 

# In terminal:

```bash
cd project_name
pyenv local 3.11.4
poetry install
poetry shell
```



### Create a `.env` file in the root directory and here is where you will add your confidential api keys. Remember to include:

```bash
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name
```




```bash
# Finally run the following command
python 001-basic-multiagent.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- LangGraph
- Tavily


### workflow
The content marketing manager asks the online researcher to research online about the article topic and write the first draft.
The online researcher delivers the draft.
When the content marketing manager is satisfied with the work of the online researcher, the content marketing manager asks the blog manager to fine tune the draft.
The blog manager delivers the final article.
When the content marketing manager is satisfied with the work of the blog manager, the content marketing manager asks the social media manager to write a tweet about the article.
The social media manager delivers the tweet.
When the content marketing manager is satisfied with the work of the social media manager, the content marketing manager ends the workflow.


### Take a look at LangSmith
See that the project takes a lot of tokens.
See that each agent is monitored.
Click on each agent and see input and output.
See how the online researcher agent is using Tavily for online searching.
See the output of the content marketing manager in the last step ("FINISH").

### One important caveat: Multi-Agent Networks take time to deliver the final solution, so you will have to be patient.¶
Multi-Agent Networks, also called LLM Apps with Agentic Behavior or Multi-Agent LLM Apps take time, but their results are often better than the ones got from Non-Agentic LLM Apps.

    
