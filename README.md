# Ex03-Univariate-Analysis
# Aim:
  
  To detect the Univariate Analysis by using default functions.
  
 # Algorithm:
 
1.Import pandas(),numpy()and seaborn() for a required detection.

2.use the head()

3.The information and is null function.

4. Use the describe function.

5.Figure the boxplot.

6.plot the countrplot,Displot,Histoplot.

7.Print the program.

# program:
```
import pandas as pd
import numpy as np
import seaborn as sns

data=pd.read_csv('SuperStore.csv')
data

data.head()

data.info()

data.describe()

data.isnull().sum()

data.dtypes

data['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=data)

sns.countplot(x='Postal Code',data=data)

sns.distplot(data["Postal Code"])

sns.histplot(x='Postal Code',data=data)

```
# OUTPUT;

###

Read file()

![image](https://user-images.githubusercontent.com/94165327/192078312-6a82d82c-1dab-4353-8819-e7e744d7247a.png)


###

Head()

![image](https://user-images.githubusercontent.com/94165327/192078330-b112ee55-1e58-46cf-b842-e09b121f65ed.png)


###

Info()

![image](https://user-images.githubusercontent.com/94165327/192078354-132152f0-f2dc-4f40-8819-65fe3087d2eb.png)

###

Describe()

![image](https://user-images.githubusercontent.com/94165327/192078375-020f0851-32e8-42f1-ad14-69459c133066.png)


###

Isnull()

![image](https://user-images.githubusercontent.com/94165327/192078394-a6eb8746-5024-4ba1-933b-bae3d9ad8b0e.png)

###

Dtypes

![image](https://user-images.githubusercontent.com/94165327/192078415-06d07d75-b549-4a13-9304-c3a5391592ff.png)


###
Count

![image](https://user-images.githubusercontent.com/94165327/192078431-db074786-9e1d-4085-bf92-a11d7a59709d.png)

###
Boxplot

![image](https://user-images.githubusercontent.com/94165327/192078442-9d94cf34-d58a-4626-ae69-68f3798a5991.png)

###
Counter plot

![image](https://user-images.githubusercontent.com/94165327/192078460-dfed5242-f2d3-4795-912f-d5982fc3a038.png)

###
Displot

![image](https://user-images.githubusercontent.com/94165327/192078478-f8f33763-4eae-4b87-8681-2894d7540c01.png)

### 

Histplot

![image](https://user-images.githubusercontent.com/94165327/192078499-eeeffd10-a3b0-457b-b061-04fa5c36e87b.png)


# Result

Hence the univariate analyses is verified.

