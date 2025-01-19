# Assignment details

The following repository contains the Machine learning assignment for predicting type of Colon cancer

## Project Overview
1 . df1_main.ipynb -> contains the work done on dataset1 , all the analysis, visualisation , correlation analysis and feature selection based on feature importance. Also new features were constructed based on domain knowledge.

2 . df2_main.ipynb -> contains the work done on dataset2 , all the analysis, visualisation , correlation analysis and feature selection based on feature importance , outliers removal using inter quartile range method. Also engineered new features based on domain knowledge.

3 . df3_main.ipynb -> contains the work done on dataset3 , all the analysis, visualisation , correlation analysis and feature selection based on feature importance , outliers removal using inter quartile range method. Also engineered new features based on domain knowledge. Here I also made an crutial assumption that typeX corresponds to typeA colon cancer , typeY corresponds to typeB colon cancer , typeZ corresponds to typeC colon cancer.

4 . model.ipynb -> This contain the modeling part , here a early fusion model technique is used , where model for each of the dataset is created and the final output is average of all the probablities of individual models.

## Dataset
Dataset1.csv , Dataset2,csv , Dataset3.csv are the original datasets provided. And reduced_df1 , reduced_df2 , reduced_df3 are the datasets which only have features with high feature importance.

## Usage
1. Links to all colab notebooks 
df1_main.ipynb-->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MywUMYEbvRvmihGVSXanG1cNDGaTEAAQ?usp=sharing)

df2_main.ipynb-->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OOUBXnIOe3Gxy_iRg7S5POzt5xlU7gas?usp=sharing)

df3_main.ipynb-->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DJJW-Qi_pgHiQdipHoSqqYmzKzdG3PHr?usp=sharing)

model.ipynb-->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zokFG7VbdiFdmOeLjLknYebALayz5xwt?usp=sharing)




