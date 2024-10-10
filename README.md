# ChatGPT-Agents-for-Customized-Text-Labelling

![Image description](https://drive.google.com/uc?export=view&id=12nUcFLbe3De1MhqJjuN41VpXwq13pgEU)

#### In this project, we explore the application of a simple use case in which two ChatGpt agents are tasked with labelling texts based on pre-defined category descriptions.

### Steps involved:

1. List of reviews + document of categories and their definitions are passed to the first agent for classification.
2. The second agent checks the classifications and reasoning of the first agent to see if it agrees with the classification given.
3. A final document is produced with the original review + assigned category + reason for the choice.


#### As this is just a simple illustration, only 50 randomly chosen reviews are classified. This method can be applied to very large datasets and augmented with multiple agents, keeping in mind the cost of calling the API.

##### The exact Chatgpt version used for this illustration is gpt-4o-mini-2024-07-18.


