# workshop-Multivariate-analysis

# CODE 

import pandas as pd

df=pd.read_excel("/content/FlightInformation (1).xlsx")

df.head()

df.dtypes

import seaborn as sns

sns.scatterplot(x=df['Total_Stops'],y=df['Price'],data=df)

sns.barplot(x=df['Source'],y=df['Price'],data=df)

df.corr()

# OUTPUT:


