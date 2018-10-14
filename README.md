# :musical_note: bars 

## Basically,
I want to see how well I can predict an artist name from a given song lyric.

## Metrics for Success
My goal is to train this model with 5 artists and be able to predict the right artist from a given song lyric with an F1 score of at least 80%. 

## Data
All of my train and test data is scraped from Genius.com using songs from each artist.

## Language Processing 

The method of language processing I decided to use is **vectorizing words based on occurance** which is also 
used in the classical machine learning problem of spam email classification. Note that I did not base it on relative frequency because each lyric is approximately the same length.

## Classifier 

I decided to use the **Naive Bayes Classifer** which is also clasically used for spam email classification. This classifier compares the
probability of each feature belonging to a certain target and selects the most likely target for a particular feature vector. 

## Accuracy 
TBA - working on adding more artists. 
Currently, I am able to differentiate between Ed Sheeran and Kendrick Lamar Lyrics with **~80% accuracy** and an **~83% F1 score**.

### TODO
Add more artists  
Adding the ability to scrape songs with features (ignoring lyrics sang by the feature artist)
