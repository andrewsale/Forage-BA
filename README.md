# Forage-BA
 
This is a project for the British Airways virtual work experience program on Forage.

## Part 1:

Customer reviews were scraped and analyzed. Tasks involved were:

* Scraping the reviews using `Beautiful Soup`.
* Processing the reviews with `pandas`.
* Sentiment analysis using a BERT model with the `transformers` package.
* Topic modelling:
    * `Gensim` and `spaCy` for preprocessing the reviews.
    * Latent Dirichlet Allocation from `sci-kit learn` for topic modelling.
* Creating visualizations:
    * Word clouds created with `wordclouds` package.
    
## Part 2:

Data for 50,000 flight searches were analyzed to determine the important feature that determine whether a booking is completed or not. Tasks involved:

* EDA.
* Prerprocessing with pandas to handle caegorical data.
* Predictive modeling, comparing random forests classifier and a histogram-based gradient boosted tree classifier.
    * Random grid searches were performed for a good set of hyperparameters.
    * Various metrics used to compare the model performances.
 
 Both parts include full reports, and a single summary slide (the latter was required for the Forage program).
