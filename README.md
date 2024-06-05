### Front end:

#### file function：

1. use `chat_autogen_based.ipynb` to perform chat between to llm, save chat result into txt
2. use `chat_evaluation.ipynb` to analysis chat history.

3. TO BE DONE: use `chat_langchain_based` to analysis chat history. 
#### environment：

1. chat_autogen_based.ipynb worked with env: pyautogen, to install pyautogen: 
  [https://microsoft.github.io/autogen/docs/installation/](https://microsoft.github.io/autogen/docs/installation/)
2. chat_evaluation.ipynb worked with env: evaluation, to install evaluation: 
`conda create -n evaluation python=3.9 -y
pip install langchain`

### Back end

1. install fastchat in env: fschat

​	https://github.com/lm-sys/FastChat

2. run fastchat:

​	https://github.com/lm-sys/FastChat/blob/main/docs/langchain_integration.md

