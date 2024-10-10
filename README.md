# ChatGPT-Agents-for-Customized-Text-Labelling

![Image description](https://drive.google.com/uc?export=view&id=12nUcFLbe3De1MhqJjuN41VpXwq13pgEU)

#### In this project, we explore the application of a simple use case in which two ChatGpt agents are tasked with labelling reviews based on pre-defined category definitions.

### Steps involved:

1. List of reviews + document of categories and their definitions are passed to the first agent for classification.
2. The second agent checks the classifications and reasoning of the first agent to see if it agrees with the classification given.
3. A final document is produced with the original review + assigned category + reason for the choice.


#### As this is just a simple illustration, only 50 randomly chosen reviews were classified. However, this method can be applied to very large datasets in multiple use cases and with further complexity using additional. The cost of calling the API should be kept in mind.

##### The exact Chatgpt version used for this illustration is gpt-4o-mini-2024-07-18.


