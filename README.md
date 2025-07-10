# AF-SOMALI FAKE NEWS DETECTION SYSTEM

Af-Somali language is one of under-resourced language which doesn’t have more language processing tool and techniques. One of difficulties in creating a detection technique that is reliable is lack of proper datasets and good word embedding. This project’s main objective is to design and evaluate a machine learning algorithm that are correctly predicts a Somali language fake news. The specific objectives are to review literature on fake news detection and classification methods,to develop a dataset for Somali language fake news and to evaluate the performance of the machine learning algorithms for detecting Somali fake news.

# Proposed Solution 

The Af-Soomaali fake news detection system architecture is composed of six components namely data collection and annotations, data preprocessing, feature extraction, dataset splitting, model training and building, model testing and evaluations. First, news articles will be collected from various sources then it will be annotated and merged into a single file. Data will be preprocessed before using ML classifier using dataset cleaning, stemming, tokenizing, stop word removal, and normalization subcomponents of data preprocessing. The Word2Vec and term frequency-inverse document frequency (TF-IDF) vector space model applied to dataset to extract feature in feature extraction components. In dataset splitting component, splitting the dataset into training and test dataset conducted. Using the training dataset which contain a set of fake and real news, ML classifiers will train and learn for the dataset in model training and building components. In model testing and evaluation component, the testing dataset will be used to assess the classification performance of our models will be evaluated using accuracy, recall, precision, F1 score, and receiver operating characteristic


![image](https://github.com/user-attachments/assets/535d965f-92d0-4215-885a-7bf0c17e7912)


# Results
The classification result is shown in the table below, and each experiment's overall performance is quite like each other's. We obtain about the same F1, Recall, Precision, and accuracy in most circumstances. Nevertheless, each experiment has a different class's accuracy, precision, recall, and F1-score. For both TF-IDF and Word2Vec, every model in the candidate classifier had accuracy ratings higher than 64%. The random forest classifier (96.1% accuracy and 0.931 F1-score) and support vector machine classifier (94.55% accuracy and 0.829 F1-score) obtain the best classification results. The accuracy result allowed us to evaluate which model and feature extraction approach performed better than the others. The studies suggest the most effective technique for developing a prototype that obtains new data from online Somali news sources. The Experiments show that TF-IDF feature extraction using Random Forest classifier outperforms word2vec feature extraction with an accuracy of 96.1%.


