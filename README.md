# Disaster Tweets Authenticity Classification

**Disaster Tweets Authenticity Classification: Using Multiple Machine Learning Methods**

## Abstract

Nowadays, people often exchange information in emergencies on social platforms such as Twitter, where the information is not always reliable due to the freewheeling nature of the platform. This paper introduced multiple machine-learning methods to predict which tweets are about real disasters and which are not. In other words, this is a textual binary classification problem. Our data comes from a publicly available dataset that includes 10,000 tweets that have been manually labelled. We first pre-processed the dataset, then implemented K-Means, TFIDF-SVM, Bert-MLP, and RNN models in turn to do the classification, and finally fine-tuned several State-of-the-art models such as DistilBert, RoBERTa and XLNet. The results show that the best-performing models as measured by the F1 score are those fine-tuned models, followed by SVM, RNN, and MLP, while the worst performing algorithm is the unsupervised K-Means algorithm, as we expected.