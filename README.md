# Capstone Project - Deceptive Opinion Spam

## Introduction

In this project, I am utilizing machine learning, and semi-supervised learning on a deceptive spam classification project on Tripadvisor reviews. Labeled dataset is from  dataset from Myle Ott's reserch paper. 1600 unlabeled data was web scraped from tripadvisor for the same hotels for semi-supervised learning models. The goal is to predict the probability of hotel reivews wheather if it is decpetive or not by binary target isFraud.

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
- 93% of consumers are influenced by reviews for there purchasing descisions.
- 82% of Consumers have read a fake review in previous year.
- 62% of consumers have experienced discrepency of the product from reviews.
- It is very important from costomer's aspect to have filtered reviews for true

## Methodology

### Natural Language Processing

Using varius machine learning models below, I will predict true/deceptive reviews.

1. Machine Learning
<br />a. Logistics Regression
<br />b. Support Vector Machine 
<br />c. Naive Bayes Classifier
<br />d. word2vec Model

2. Semi Supervised Learning
<br />a. Label Propagation

## Files

1. README.md - Explanatory page
2. Capstone_Coding.ipynb - Python coding file
3. KangCapstoneProject - Presentation powerpoint/PDF slides
4. Capstone Record Addres - Textfile for youtube address for recorded presentation video
