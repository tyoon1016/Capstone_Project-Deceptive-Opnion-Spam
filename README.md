# Capstone Project - Deceptive Opinion Spam

## Introduction

In this project, I am utilizing machine learning, and semi-supervised learning on a deceptive spam classification project on Tripadvisor reviews. Labeled dataset is from  dataset from Myle Ott's reserch paper. 1600 unlabeled data was web scraped from tripadvisor for the same hotels for semi-supervised learning models. The goal is to predict the probability of hotel reivews wheather if it is decpetive or not by binary target isFraud. Machine learning model on labeled data to see the result will be developed first. Unlabeled data will be test with pre-trained models and semi-supervised learning model will be developed last.

#### Data source is from : Myle Ott, Negative Deceptive Opinion Spam https://myleott.com/

## Dataset

##### Labeled dataset was provided from Myle Ott, https://myleott.com/op-spam

400 truthful positive reviews from TripAdvisor 
400 deceptive positive reviews from Mechanical Turk 
400 truthful negative reviews from Expedia, Hotels.com, Orbitz, Priceline, TripAdvisor and Yelp (described in [2])
400 deceptive negative reviews from Mechanical Turk 

Web Scrapped Data

### 1600 reviews from TripAdvisor
80 reviews from each hotel

- Affinia: Affinia Chicago (now MileNorth, A Chicago Hotel)
- Allegro: Hotel Allegro Chicago - a Kimpton Hotel
- Amalfi: Amalfi Hotel Chicago (Now Kinzie Hotel)
- Ambassador: Ambassador Chicago
- Chicago Autograph
- Conrad: Conrad Chicago
- Fairmont: Fairmont Chicago Millennium Park
- Hilton: Hilton Chicago
- Homewood: Homewood Suites by Hilton Chicago Downtown
- Hyatt: Hyatt Regency Chicago
- Intercontinental: InterContinental Chicago
- James: James Chicago
- Knickerbocker: Millennium Knickerbocker Hotel Chicago
- Monaco: Hotel Monaco Chicago - a Kimpton Hotel
- Omni: Omni Chicago Hotel
- Palmer: The Palmer House Hilton
- Sheraton: Sheraton Chicago Hotel and Towers
- Sofitel: Sofitel Chicago Water Tower
- Swissotel: Swissotel Chicago
- Talbott: The Talbott Hotel

## Problem Statement

- eCommerce has been grown to 25 trillion USD word-wide and US market of 601 billion USD.
- 93% of consumers are influenced by reviews for their purchasing descisions.
- 82% of Consumers have read a fake review in previous year.
- 62% of consumers have experienced discrepency of the product from reviews.
- Online reviews has been one of the most mportant factor of purchasing
- It is crucial for costomer's aspect to have filtered and truthful reviews to make their descisions.

## Methodology

### Natural Language Processing

- Two different Vectorization approaches
<br />a. Count Vectorization: measurement of frequency of each words
<br />b. TF-IDF Vectorization: frequency of each words offset by overall frequency in the corpus

- Word Embedding: Language modeling technique used for mapping words to vectors of real numbers
<br />a. Genism: Open source natural language processing library used for unsupervised topic modeling, handling various complex tasks such as Building document or word vectors, Corpora, performing topic identification, performing document comparison (retrieving semantically similar documents), analysing plain-text documents for semantic structure.
<br />b. GloVe: It is un-supervised learning algorithm for obtaining vector representation for words. Training is performed on aggregated global word-word co-occurrence statistics from a corpus, and the resulting representations showcase interesting linear substructures of the word vector space.

### Models

Using varius machine learning models below, I will predict true/deceptive reviews.

1. Machine Learning
<br />a. Logistics Regression
<br />b. Support Vector Machine 
<br />c. Naive Bayes Classifier
<br />d. word2vec Model

2. Semi Supervised Learning
<br />a. Label Propagation

## Conclusion

- TFidf vectorization perforemd slightly better than count vectorization method.
Bes performing model was supportive vector modeling with 86.4% accuracy.
- Pre-trained SVC model's accuracy was 51% with unlabled data.
- Semi supervised model with label propagation had also 51% accuracy.


## Files

1. README.md - Explanatory page
2. Capstone_Coding.ipynb - Python coding file
3. KangCapstoneProject - Presentation powerpoint/PDF slides
4. Capstone Record Addres - Textfile for youtube address for recorded presentation video
