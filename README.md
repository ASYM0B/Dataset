# Dataset
ASYM0B (A framework for SYsteMatically assessment Of chatBots) is a framework to analyse and assess conversational agents or chatbots built in different tools. To support chatbots from different platforms, ASYM0B relies on a neutral chatbot definition called [CONGA](https://saraperezsoler.github.io/CONGA/).

The repository contains a dataset used in evaluations of the ASYM0B tool of 259 chatbots in CONGA format from 4 different sources: Code repositories like Github, predefined chatbots from the Dialogflow and Rasa platforms, as well as predefined bots from other platforms, like [Kommunicate](https://www.kommunicate.io/). The following table summarizes the content of the dataset. We classify the chatbots as open-source, if they were located in an open-source repository, or predefined if they are available as prebuilt agents in some platform.
|      Source | #Chatbots | Technology |     Kind    |
|------------:|:---------:|:----------:|:-----------:|
| Github      |     96    | Dialogflow | Open source |
| Dialogflow  |     14    | Dialogflow |  Predefined |
| Kommunicate |     7     | Dialogflow |  Predefined |
| Github      |    139    |    Rasa    | Open source |
| Rasa        |     3     |    Rasa    |  Predefined |
| Total       |    259    |            |             |


The chatbots are divided into two folders, Dialogflow and Rasa, depending on the technology to which the chatbot belongs. The folders also contain the source of each chatbot and a table with the results of the evaluation performed with ASYM0B. 

Finally, in this [link](https://github.com/ASYM0B/tool) there are ASYM0B environments, which can be used using these chatbots. 
