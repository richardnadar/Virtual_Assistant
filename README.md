# Virtual_Assistant
Basic Virtual Assistant model trained on FAQ type dataset using NLP and ML concepts with the help of Kandi openweaver where all the necessary libraries and kits are available to create an application.

# My Kandi Kit: https://kandi.openweaver.com/collections/nlp/virtualassistant-kit

This is an NLP based application which is trained on Question-Answer type dataset. If the question the user queries is almost similar to the question in dataset then the model will give the same answer as of the dataset corresponding to the question. Even if the user query contains punctuations then too the prediction will be accurate.

Here I have used **all-MiniLM-L6-v2** pre trained model and trained my model using pre trained weights and bias to get the results. This model got the accuracy of approximately 85%. The NLP libraries used in this program are **sentence-transformers** to clean the dataset of any punctuations, digits, etc. and **bert-cosine-sim library** for Fine-tune BERT to generate sentence embedding for cosine similarity.
