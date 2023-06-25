# SentimentAnalysis

The study was conducted on a highly unbalanced dataset, where the class distribution was identified as 19190 instances for class 1, 4163 instances for class 2, and 1430 instances for class 0. It was observed that due to the class imbalance, even a simplistic model that predicts every instance as class 1 can achieve more than 90% accuracy. However, the study aimed to develop an unbiased model that could perform well on all classes. To address the issue of class imbalance, two basic options were considered, namely minority up sampling and majority down sampling. However, as the dataset consisted of textual data, it was observed that minority up sampling was prone to overfitting. Hence, the majority down sampling approach was implemented. This approach involves randomly selecting instances from the majority class and removing them from the dataset until the distribution of classes becomes more balanced. The downside of this approach is the reduction of data size.
After balancing the dataset, the data was preprocessed using basic Natural Language Processing (NLP) techniques. This involved removing punctuation, converting all letters to lowercase, and removing stop words. 
