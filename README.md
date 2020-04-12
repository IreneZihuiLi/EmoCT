## EmoCT Dataset
This is the repo for the EmoCT (Emotion-Covid19-Tweet) Dataset.

We provide two versions: single-tag and multi-tag. Each folder contains 800 samples for training and 200 for testing.

### Emotion and its tag code used: 

| Emotion   |      tag code      | 
|----------|:-------------:|
|Anger| 0 |
|Anticipation| 1 |
|Disgust| 2 |
|Fear| 3 |
|Joy | 4  |
|Sadness | 5  |
|Surprise | 6  |
|Trust | 7  |

### Format for each line

`TweetID` \t `Label1`	\t `Label2` \t `Label3`

### Our performance


| Method | Accuracy | F1 | 
|------------------|----------|------------|
| BERT             | 0.9549   | 0.9545     | 
| BERT(ft)         | 0.9562   | 0.9558     | 

 
