# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
        <<INCLUDE YOUR CODING AND OUTPUT SCREENSHOTS>>
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

dt = pd.read_csv("/content/titanic_dataset (2).csv")
dt
![Screenshot 2025-04-18 191733](https://github.com/user-attachments/assets/6b895433-52dd-4295-9bce-4227670eff5a)
![Screenshot 2025-04-18 191900](https://github.com/user-attachments/assets/f7b940f2-6165-4401-955b-5846eb187f1a)
![Screenshot 2025-04-18 191956](https://github.com/user-attachments/assets/75817e7b-c741-4a9a-beff-f4db64e88c73)
![Screenshot 2025-04-18 192027](https://github.com/user-attachments/assets/b29d0070-f29c-4e34-8039-dce0d04a4c11)
![Screenshot 2025-04-18 192143](https://github.com/user-attachments/assets/7b7d18cb-c068-471b-b88c-a883db91b80b)
![Screenshot 2025-04-18 192208](https://github.com/user-attachments/assets/4a54e1f9-e947-43fc-86d1-f86b555240b3)
![Screenshot 2025-04-18 192230](https://github.com/user-attachments/assets/f946cbee-42a3-4f40-8c2a-dc208f3fbff5)
![Screenshot 2025-04-18 192252](https://github.com/user-attachments/assets/b8e41a07-83f9-4a0e-b404-76c8676c0abb)
![Screenshot 2025-04-18 192317](https://github.com/user-attachments/assets/29682b07-1cf3-4c15-a0da-73ac4fa952b8)
![Screenshot 2025-04-18 192336](https://github.com/user-attachments/assets/cd17141c-88da-448f-8246-9c7873423a8b)
![Screenshot 2025-04-18 192401](https://github.com/user-attachments/assets/1d41f833-ee03-430e-9045-e5eaa314d0a3)
![Screenshot 2025-04-18 192421](https://github.com/user-attachments/assets/c5d9c496-079e-4d82-8d62-beb18f859f0b)
![Screenshot 2025-04-18 192441](https://github.com/user-attachments/assets/0a779b81-6b54-453e-9ea9-5ae2b3d31c7b)
![Screenshot 2025-04-18 192522](https://github.com/user-attachments/assets/321ebbeb-dc0c-4ecd-ac75-c78d8afcf823)

# RESULT
        <<INCLUDE YOUR RESULT HERE>>

![image](https://github.com/user-attachments/assets/27720386-62d7-484c-ab4c-f1a8f36158da)

