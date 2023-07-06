# Bias in Natural Language Models
A project that tackles the identification and mitigation of gender bias in natural language processing, presented at a meetup event and streamed live on youtube. Please find the links below, or alternatively follow the notebook material:
* Notebook: nlp_bias_project.ipynb, please ensure you install requirements in requirements.txt to successfully run the notebook
* Meetup event: https://www.meetup.com/real-data-science-denver/events/291330447
* Youtube link: https://www.youtube.com/watch?v=FQCR6QYbJqE

This session will explain where to identify gender bias at different levels of granularity, from products such as Google Translate to a specific word embedding algorithm. We will then present a theoretical and practical solution to remove bias in gender that can be readily translated to other areas of discrimination.

Natural language processing (NLP) uses unsupervised machine learning techniques, primarily neural networks, to reveal the structure and meaning of text. Word embedding is a large component of NLP that represents words in vector space. We will explore how these algorithms link "woman" and "wife" to other subjects than "man" and "husband", by diving into the details of one of the most popular underlying techniques, BERT.

We hope to explain the concepts for any levels of understanding. The structure of the session is as follows:

• Demonstrating examples of gender bias in google translate and predictive text
• Pre-requisites: A brief introduction into NLP, key machine learning definitions that will be used throughout this session
• Identifying bias in word embedding: a key component to NLP applications
• Identifying bias in BERT
• A solution to mitigate bias in word embeddings

The session aims to demystify an important area of AI ethics, helping you to interpret results better and develop NLP tools using our solution. However, the key solution to remove bias entirely is to change the corpus on which NLP models are trained. These are the words we use and publish that are openly accessible. The most important takeaway from the session is to encourage ourselves and others to use language carefully and inclusively.
