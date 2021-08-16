# Big data for specific emotion detection model: 

Prediction of human emotion has been and remains a major challenge in many research fields such as psychology, neuroscience, and computer science. Tweets are considered as a suitable source for collecting big data using emotion hashtags as automated emotion annotations. However, little is known about data collection criteria. To elucidate unclear criteria, this paper collected over five million tweets (n=5,645,139) that were divided into six datasets. Machine learning (ML) models were evaluated on both internal (30 analyses) and external test sets (30 analyses), proposing the 6H-AP dataset (n=1,478,116) any position of representative emotions hashtags). Furthermore, this paper compared the model trained on 6H-AP dataset with the model trained on a small dataset. We find that this large dataset further improved the model performance in deep learning (12 analyses) than in traditional ML algorithms (20 analyses). Finally, we share the 6H-AP dataset with other researchers to contribute to future specific emotion detection model studies.

# Python code example
import pandas as pd

df = pd.read_csv('6H-AP_emotion-labelled_tweets_dataset.dat', sep='\t', encoding='utf-16')

![image](https://user-images.githubusercontent.com/75097749/129504511-d3f2c46e-8525-49ad-9974-5ecab8b5051a.png)

import seaborn as sns

sns.countplot(df['emotions'])

![image](https://user-images.githubusercontent.com/75097749/129504583-6d52221b-55bc-41e6-b223-3d3bab271312.png)





