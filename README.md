# Hotel-Reviews-Text-Analysis
Text mining and analysis of reviews of hotels over the US by applying Natural Processing Language (NLP) to the customer-review text and obtain valuable information from it.

#### Data source: https://www.kaggle.com/datafiniti/hotel-reviews

The data contain a list of hotels in the US and their online ratings and reviews given by the customers.


#### Objectives:
```
●	Analyze the customers review from positive and negative ratings 

●	Come up with an overall output based on defined features to describe a hotel

●	Compare hotels based on the different aspects to get better judgement
```

#### Design and Methodology:

Based on the data, certain attributes were listed to get better judgement of the hotel as a basis for analysis.
The model takes state as the input from the user, giving user a list of hotels in the state given as input. User can select any two hotels from the list. The selected hotels are then classified based on hotel rating as positive or negative. The review text obtained from the specified hotels is then analyzed based on customers experiences expressed in the reviews and compared with each other on the basis on the attributes defined for analysis.

To achieve the objectives, process followed is: 

1. Cleaning the reviews by tokenizing and lemmatizing
2. Matching the tokens with a set of defined features in the form of word lists
3. Separating the tokens into positives and negatives 
4. Generating an overall analysis of hotel based on tokens and defined features
