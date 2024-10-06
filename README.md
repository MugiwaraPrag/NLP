NLP - Text classification

Dataset description
The dataset contains a collection of chat messages that can be used to develop a sentiment
analysis machine learning model to classify messages into 3 sentiment classes - positive,
negative, and neutral.
The messages are diverse in nature, containing not only simple text but also special characters,
numbers, emoji/emoticons, and URL addresses. The dataset can be used for various natural
language processing tasks related to chat analysis.

Column description
1. message: the content of the chat message.
2. sentiment: the sentiment of the chat message, can be positive, negative, or neutral.

Project description
1. First of all, Explore the data.
a. Whether positive, negative, neutral occur for the same number of times?
b. Answer such questions about the dataset, and try to find information on the data
we are operating on.
2. Use any meaningful preprocessing on the text data.
a. Such as lowercasing, removing special characters and so on..
3. Use a bag of words / count vectorizer on the preprocessed messages.
4. Split into train and test data.
5. Build a classification model to find the sentiment of a message.
