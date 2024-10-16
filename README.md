# WEATHER_PLAY
ID3 Algorithm - Decision Tree Implementation
## Overview
This project is an implementation of the ID3 Algorithm (Iterative Dichotomiser 3), a classic decision tree algorithm used for classification tasks. The main goal of the project is to demonstrate how the ID3 algorithm constructs a decision tree based on a dataset with various attributes. 
- The ID3 algorithm utilizes the information gain and entropy concepts to split data at each node, aiming to create a tree that best classifies the dataset.


## Features
Categorical Data Handling: The algorithm can handle datasets with categorical variables, including:
- OUTLOOK: Weather condition (e.g., sunny, overcast, rainy)
- TEMPERATURE: Temperature ranges categorized as high, normal, and low
- HUMIDITY: Humidity levels categorized as NemY and NemN
- WINDY: Wind conditions as yes and no


- Entropy and Information Gain Calculation: Automatically calculates entropy and gain for each feature.
- Decision Tree Construction: The decision tree is built based on the ID3 algorithm logic, choosing the most informative feature at each node.
- Customizable Data Input: Easily modify the dataset to test the model on various examples.

# Results
The following gain values were obtained from the decision tree analysis using the ID3 algorithm:

- GOLF: 0.940286
- HAVA (Outlook): 0.2467498***
- SICAKLIK (Temperature): 0.04140546
- NEM (Humidity): 0.1518355
- RÜZGAR (Wind): 0.04812703

 
The gain values indicate the effectiveness of each attribute in classifying the target variable (GOLF). The higher the gain, the more informative the attribute is for making decisions in the classification process.


The highest gain value was obtained for HAVA (Outlook), meaning it provides the most information for classifying the target variable (GOLF). Therefore, the first branching in the decision tree will begin with the HAVA (Outlook) attribute at the root node.
![image](https://github.com/user-attachments/assets/7e96337c-c085-4c0b-994e-1e20b9b71110)

![iris](https://github.com/user-attachments/assets/031b7b00-f841-4ef9-bc69-091078390409)
![weatherplay](https://github.com/user-attachments/assets/91a6d908-259a-4a05-9320-42f4a218b3c8)
