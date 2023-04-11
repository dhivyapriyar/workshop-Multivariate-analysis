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

![WORK1](https://user-images.githubusercontent.com/119477552/231072543-9cb9e8e8-0d49-45e4-bfac-7dcd80d0d04d.jpg)

![WORK2](https://user-images.githubusercontent.com/119477552/231072570-4479d974-e07a-4d0e-a0d4-c1b6024fe2ae.jpg)

![WORK3](https://user-images.githubusercontent.com/119477552/231072587-b38f9dcc-ca47-4ed7-bd34-1fbf4ac435f7.jpg)

![WORK4](https://user-images.githubusercontent.com/119477552/231072627-87003867-e0d1-406e-8caa-e6ab1b61b7dd.jpg)

![WORK5](https://user-images.githubusercontent.com/119477552/231072833-09654d97-55fb-469e-977e-c006762f9ea1.jpg)


