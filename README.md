# Conversation Assesment with LangChain


https://github.com/int-code/conversation-assesment/assets/74727186/9c258052-0019-4421-bafd-935edd67ad86





## AIM:
A langchain project that is able to demonstrate conversation assesment abilities. Given a conversation between a human and an AI, the project should be able to evaluate the quality of responses that the AI gave to the human in that conversation. It should have a robust system of rating conversations between 0-10 based on how helpful the AI was in that conversation and how did the human react to the AIs responses

This goal has been pursued through two directions: One with the help of prompt and LLM chain binding and another through Langchain evalutation functions. The prompt+LLM has been turned into a Rater class which can be used to rate a list of conversations on selective metrics as well.


## Setting up
Set `OPENAI_API_KEY` in a .env file in root

pip install -r requirements.txt

Everything is now set up!

## Files

`conversation-assesment.ipynb` : main notebook file containing all the code

`conversations.csv` : list of sample conversations used in the notebook file

`conversations2.csv` : list of rated conversations saved as csv
