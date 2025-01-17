# Big data for specific emotion detection model: 

Prediction of human emotion has been and remains a major challenge in many research fields such as psychology, neuroscience, and computer science. Tweets are considered as a suitable source for collecting big data using emotion hashtags as automated emotion annotations. However, little is known about data collection criteria. To elucidate unclear criteria, this paper collected over five million tweets (n=5,626,219) that were divided into six datasets. Machine learning (ML) models were evaluated on both internal (30 analyses) and external test sets (30 analyses), proposing the 6H-AP dataset (n=1,367,254; any position of representative emotions hashtags). Furthermore, this paper cross evaluates the 6H-AP dataset with a small dataset, showing that this large dataset can make a greater contribution to improving model performance in deep learning (12 analyses) than in traditional ML algorithms (20 analyses). Finally, we share the 6H-AP dataset with other researchers to contribute to future specific emotion detection model studies.
Keywords: big data, specific emotion, emotion hashtags, emotion labelled tweets, natural language processing

# Python code example
import pandas as pd

df = pd.read_csv('6H-AP_emotion-labelled_tweets_dataset.dat', sep='\t', encoding='utf-16')

![image](https://user-images.githubusercontent.com/85970005/122152643-b241ef00-ceb5-11eb-96af-a64fe20c3675.png)

import seaborn as sns

sns.countplot(df['emotions'])

![image](https://user-images.githubusercontent.com/85970005/122173082-8171b200-ced5-11eb-8137-aa835eb57fb5.png)





