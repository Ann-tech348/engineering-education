---
layout: engineering-education
status: publish
published: true
url: /how-cart-algorithms-are-substantial-in-speech-emotion-recognition/
title: How CART Algorithms are Substantial in Speech Emotion Recognition
description: In this article, we will assess the use of CART algorithms in speech emotion recognition.
author: lynn-njoki
date: 2021-11-22T00:00:00-18:00
topics: [Machine Learning]
excerpt_separator: <!--more-->
images:

  - url: /engineering-education/how-cart-algorithms-are-substantial-in-speech-emotion-recognition/hero.jpg
    alt: CART example image 
---
Unlike humans, who have the human ability to recognize emotion from speech, machines do not have the sense to analyze feelings. Speech emotional recognition is vital in understanding human emotions such as amusement, frustration, or disappointment.
<!--more-->
Emotions are vital in day-to-day life, especially in interpersonal human interaction. They are helpful both in intelligent and rational decisions. Unlike humans, who have the human ability to recognize emotion from speech, machines do not have the sense to analyze feelings. Speech emotional recognition is vital in understanding human emotions such as amusement, frustration, or disappointment. Speech emotion recognition informs the computer on the physical and emotional state of an individual from a speech.

A wide range of studies have focused on detecting a person's emotions. They include the use of computer games, audio surveillance, robots, others. Machine learning algorithms have been termed as more efficient in classification and prediction, which is vital in speech emotion recognition. However, there is a lot of information about the use of [CART](/engineering-education/decision-tree-in-python/) in speech emotion recognition that needs assessment which the study focuses on.

The article focuses on assessing the substantial use of CART algorithms in speech emotion recognition. In achieving the purpose, the article reviews the speech emotion system, how CART works, and various reasons affiliated with its effectiveness.

### The system of emotion recognition

The system of speech emotion recognition highly comparable to the pattern recognition task which is highly structural. The system automatically identifies the human beings' emotions from a voice. The system is usually based on the signal of speech and emotion recognition methods. The system consists of five main steps;

- Emotional speech input
- Feature selection and extraction
- Training
- Classification
- Emotion recognition

#### Emotional speech input

The step entails the collection of voice samples, which will be analyzed for emotion recognition. This ensures that the vital aspects of speech that could be used in extracting emotion features are inputted. The emotional address signal must also be inputted before extraction.

#### Feature extraction and selection

There is a wide range of speech signal parameters that emotional characteristics reflect. The features which are extractable can be categorized in various main aspects. They include pitch, energy, formant, modulation spectral features, and linear prediction coefficients. From the features selected, the selection is made to reduce the elements which characterize the database. The chosen ones are a subset of more relevant features from the extracted ones based on the relevance evaluation criterion.

The various emotional recognition extracts critical emotional features from speech. Pitch is one of the essential features, which is the sound's frequency. The features also include standard deviation, energy intensity, and shimmer. Others include zero-crossing rate, short-time energy autocorrelation, and [MFCC](https://musicinformationretrieval.com/mfcc.html#) (Mel frequency cepstral coefficient). Other features include spectral roll-off, spectral flux, noise to harmonic ratio, harmonics to noise ratio, and jitter.

#### Training

This is another crucial step of the speech recognition system. The step entails voice training of the computers for speech recognition. It involve assigning a weight of features using estimators and considering small sets of features. The estimators are trained on the features of the initial stage and predictive power.

#### Classification

The features are classified based on the trained samples. The emotions may be classified based on primary or secondary and basic or complex. The classification informs the features which are represented in the decision tree represented.

#### Emotion recognition

Based on the Classification, the key emotions based on the analysis are recognized. The recognition is based on the results presented by the algorithm used. This represented the well-constructed decision tree.

### How CART algorithms work in speech emotion recognition

CART is vital in different steps of speech emotion recognition. CART is a decision tree that uses historical data in the glory of the speech emotion. The algorithm is a procedure of binary recursive partitioning. CART is used in various steps of speech emotional training as discussed below;

#### Training

CART is vital in the training step to learn the models for data sample classification. CART binaries different voice files of various emotions. Training is essential in classifying the data into multiple classes. The training is usually done in percentage split, which may range from 0-100%. The percentage reflects the relevance rate of the primary emotion selected. This is the critical basis of classifying the emotions recognized from speech.

#### Classification

CART classifies the main 13 features from recognizing emotions. The key models which are used in the learning stage are used in the classification. CART classification mechanism entails dynamic feature construction, and automatic class balancing. The classification tree under CART is based on the binary feature's splitting. The classification uses Gini-index for attribute splitting. CART puts into inner clusters of the file, which are vital in making decisions.

#### Emotion recognition

The emotion recognition is determined based on the actual positive (TP) and false-positive rate (FP). The TP rate is used in indicating the proportion correctly classified. The FP reflects the values which have been classified incorrectly. The figures are ten drawn on a learning curve studied to reflect whether the recognition rate is increasing or decreasing.

### Factors determining CART effectiveness in speech emotion recognition

#### Database selection

Speech emotion recognition is highly dependent on proper selection of the database. The naturalness of database selection determines the efficiency of CART. CART is only able to analyze a natural database of speech from humans to identify the emotions. Data is essential in speech emotion recognition. The decision tree of CART depends on the input variables, which are split until the construction of a suitable tree.

#### Data preparation

For CART to be effective in recognizing speech emotion, good presentation of data is significant. This is vital in ensuring that the decision tree is well split to the point that a suitable are reflected. Thus, this calls for efficient efficiency in emotional speech input and feature extraction processes.

### Why should you choose CART algorithms in speech emotion recognition?

A wide range of algorithms could be used in speech emotion recognition, such as CART, SVM, logistic regression, others. However, choosing CART would be very efficient in recognizing speech emotion recognition compared to other algorithms. The following are some of the reasons why one should choose CART for speech emotional recognition;

- **CART Algorithms are non-parametric algorithms**. Thus, CART use in the voice training stage is efficient. This is on assigning weight to features identified from speech recognition. Thus, the CART algorithm is significant in generalizing data and deriving informed features. So, ensuring flexibility due to the ability to fit the functional forms. The Non-parametric nature of CART enhances power and performance due to training efficiency.
- **CART is very sensitive to outliers**. CART is so susceptible to any variables irrelevant or situated away from the tree. So, CART treats the outlier as the terminal nodes in speech emotion recognition, which cannot affect the decision tree. Due to the splitting process of the decision tree, CART is more robust to the predictors than the outlier.
- **CART also incorporates data tests and cross-validation**. This is vital in ensuring that the goodness of fit is accurate. Thus, the decision tree created is authentic in representing the emotions represented in the speech.
- **CART is also efficient in using different variables in varying levels of the decision tree**. This ensures that it is easy to unwrap complex interdependencies between variable sets. Thus, ensuring that various emotion ties are identified in different levels of the decision tree.
- **CART in speech emotional recognition can be conjoined with other algorithms**. For example, CART can be utilized with [SVM](/engineering-education/supervised-learning-algorithms/) for outlier detection, classification, and regression. The ability to use CART with other algorithms, which enhances accuracy in speech emotion recognition.

### Conclusion

Thus, CART is vital in speech emotion recognition process. There are various stages of the speech emotion recognition system vital in identification. They entail emotional speech input, classification, training, extraction/selection, and emotion recognition. The CART algorithm could be used in training, classification, and emotion recognition stages. Data selection and preparation are two of the vital aspects in enhancing the effectiveness of CART.

There are various reasons why one should choose CART in speech emotion recognition compared to other algorithms. Some of the key reasons include CART being non-parametric. CART is easily used in conjunction with different algorithms, and unwrapping complex interdependence. Other key reasons include the ability to do data-test and cross-validation and not affected by the outliers.

As we can see, CART is an efficient algorithm in speech emotion recognition.

Happy Learning!



### Further reading

[How to Implement MLOps](/engineering-education/how-to-implement-mlops/)

[Decision Trees in Python](/engineering-education/decision-tree-in-python/)
