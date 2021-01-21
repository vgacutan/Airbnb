# A data-driven analytics based on Seattle Airbnb Open Data

## Table of Contents

 1. **[Installation](https://github.com/vgacutan/Airbnb/new/main?readme=1#installation)**
 2. **[Project Motivation](https://github.com/vgacutan/Airbnb/new/main?readme=1#project-motivation)**
 3. **[File Descriptions](https://github.com/vgacutan/Airbnb/new/main?readme=1#file-descriptions)**
 4. **[Results](https://github.com/vgacutan/Airbnb/new/main?readme=1#results)**
 5. **[Acknowledgement](https://github.com/vgacutan/Airbnb/new/main?readme=1#acknowledgement)**

## Installation
The code should run on Anaconda distribution of Python using Python 3.* .  Part of the code uses NLTK for natural language processing.  
NLTK package can be installed using anaconda by entering this command in the anaconda command prompt:

`conda install -c anaconda nltk`

## Project Motivation
I'm familiar with Seattle area and I'd like to confirm my thoughts using Seattle Airbnb actvity open data and uncover these questions:
  1.  What is the busiest time of the year to visit Seattle?
  2.  What are the rental properties available in the area?
  3.  Is there a price seasonality of rental properties?
  4.  How does price seasonality affect property types and room types?
  5.  What is the vibe of the neighborhood in Seattle?
  

## File Descriptions
Seattle Airbnb open data consist of 3 different `csv` files that are publicly available in Kaggle.  These are also available here and were used in the analysis
to uncover the above questions. These are the brief description of the 3 files:

  `listings.csv` - This includes full host property descriptions, price and review score.
  
  `reviews.csv` - This includes unique id for each reviewer and detailed comments.
  
  `calendar.csv` - This includes listing id and price availability for that day.
 
The jupyter notebook with file extension `.ipynb` contains the analysis that was used to uncover the above question.  This file includes visualization and sentiment analysis.
The 2 `.png` images where also included here for presentation purposes.

## Results
The full result of the analysis and the Author's view point where posted on this [link]() in Medium.

## Acknowledgement
The dataset that was used on this analysis comes from Airbnb as part of the Airbnb Open Data available in Kaggle on this [link](https://www.kaggle.com/airbnb/seattle).
