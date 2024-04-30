# Natural-Language-Understanding-for-Dialog-Systems
Rasa NLU for a customer service chatbot

<img width="511" alt="image" src="https://github.com/AlokChedambath64/Natural-Language-Understanding-for-Dialog-Systems/assets/110228030/93b6de2c-eb11-4fc5-b7e8-7627365a7687">

#
# Rasa 

Rasa Open Source is an open source conversational AI platform that allows you to understand and hold conversations, and connect to messaging channels and third party systems through a set of APIs. It supplies the building blocks for creating virtual (digital) assistants or chatbots.

# Set Up

In a virtual enviornment, run 

pip install rasa

Open the directory you want to work on

then run rasa init

Use "rasa train" to train the model, and "rasa test" to test it. 

# Process

Dataset: https://www.kaggle.com/datasets/bitext/training-dataset-for-chatbotsvirtual-assistants?resource=download

Subset of which was then taken to populate the nlu.yml file

Corresponding words and their intents were mapped.

Stories.yml was changed to link the intents to responses. Responses were then mapped onto domain.yml file. 

Changes made in the pipeline and policies in the config.yml file.

