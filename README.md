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
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

dt = pd.read_csv("/content/titanic_dataset (2).csv")
dt
![image](https://github.com/user-attachments/assets/73923c70-cdb0-4215-a261-d3b9d059a214)
![image](https://github.com/user-attachments/assets/6fc4325f-c1aa-4f5a-a065-118cfaff1571)
![image](https://github.com/user-attachments/assets/9012f688-bc5d-4a8c-8518-d1b842cb9042)
![image](https://github.com/user-attachments/assets/8f32403a-3b82-4f6c-82ad-99d75c7876d8)
![image](https://github.com/user-attachments/assets/7ffdf59c-666f-4433-9211-496c66e221fb)
![image](https://github.com/user-attachments/assets/265893fe-0390-492e-ae3c-977c7f4eac16)
![image](https://github.com/user-attachments/assets/98f3dd5e-92a6-4b00-b883-7ed1d7db6b1d)
![image](https://github.com/user-attachments/assets/9ed90e62-f3be-40a1-98f4-3532bbb5ff74)
![image](https://github.com/user-attachments/assets/0d1f8ff8-e529-46c3-8134-f35dacfb3c9b)
![image](https://github.com/user-attachments/assets/a09e99c2-e8a6-483f-b613-5fc16ab66286)
![image](https://github.com/user-attachments/assets/abf064c8-2aaa-43ad-af59-d0e6c8dc9f3f)
![image](https://github.com/user-attachments/assets/634cf5b5-db7f-4f9c-90d9-2b14fc8ddbd0)
![image](https://github.com/user-attachments/assets/9530f3b9-8372-4326-8b94-3d3565e2af06)
![image](https://github.com/user-attachments/assets/70c8030d-7ed7-4e08-82b2-1470e9788300)
sns.pairplot(dt)


# RESULT
![image](https://github.com/user-attachments/assets/044c0078-7c64-4012-bd6b-8b9908b1c1fb)

