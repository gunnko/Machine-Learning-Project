Midterm Project of Machine Learning

autohor: Miraç Aydın

*Overview:
In this project, we used pandas, scikit-learn, matplotlib and searborn libraries. We also applied supervised and unsupervised algorithms on the two databases

*What we did:
1. Splitting the Data: hid 20% of data for the final test, the other %80 got splitted into 2 parts as %70 Train / %10 Confirmation, on 3 different seeds(42, 52 and 62).
2. Preprocessing: We used "StandartScaler". ALso to prevent the data leakage, we only fit scaler on training data.
3. Models evaluated: Decision Tree(depths), K-Nearest Neighbours(different k values) and Gaussian Naive Bayes
4. Unsupervised Learning: Lastly K-means clustering is applied to scaled data without answers to calculate Rand Index and Silhouette Score.

*Results:
Breast Cancer Winner = Algorithm: knn, Scale: scaled, Setting: k7
Wine Winner = Algorithm: knn, Scale: scaled, Setting: k11

*Information:
Also used help from famous coding sites and youtube videos. 
For scikit-learn : https://youtu.be/SIEaLBXr0rk
For pandas : https://youtu.be/VXtjG_GzO7Q