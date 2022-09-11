# Cryptocurrencies
## Overview of Analysis
For this analysis, I created a report that includes cryptocurrencies on the trading market, grouped to create a classification system for potential new investments. This was accomplished by first preprocessing the data to fit an unsupervised machine learning model. I then grouped the cryptocurrencies through PCA and used a clustering algorithm with  K-means to predict the K clusters. Multiple data visualizations were created to display the data.


- Graphed the Elbow Curve to determine the best value for K:

<img width="1030" alt="Screen Shot 2022-09-11 at 10 18 00 AM" src="https://user-images.githubusercontent.com/105119531/189532966-c051989d-0305-4837-bc1b-25354b3f99fd.png">


- Created a 3D-Scatter with the PCA data and the clusters:

<img width="983" alt="Screen Shot 2022-09-10 at 4 24 27 PM" src="https://user-images.githubusercontent.com/105119531/189533024-2d8409dd-deca-4233-990c-d0303458e6db.png">

- Created a final table with tradable cryptocurrencies:

<img width="1051" alt="Screen Shot 2022-09-11 at 10 17 21 AM" src="https://user-images.githubusercontent.com/105119531/189533060-066c7676-524e-4562-ae51-deee2eb52075.png">

- Created a hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply" :

<img width="926" alt="Screen Shot 2022-09-10 at 4 23 57 PM" src="https://user-images.githubusercontent.com/105119531/189533120-0a15f3ad-0596-494c-bc42-f3b67f2045f2.png">
