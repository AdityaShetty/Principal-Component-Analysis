# Principal-Component-Analysis
Mulitvariate data analysis on broad data, dimension reduction technique using R

The data we are going to review is a part of dairy production for different breeds of cows and their characteristics which affect the quality of milk.

## Objective we will cover in this project:

-> To understand the data and share our inference to it.  
-> Create clusters using unsupervised learning methods and compare them (hierarchical and k-means).  
-> Understanding PCA algorithm and implementing on our given data.  
-> Predicting value of alpha casin using the MIR spectra data.  
-> Creating a function which works similar to PLSR and predict.  


We can interpret from this plot that all MIR spectra 500+ columns data which are wavelengths ranges from 0-0.65 and they are highly collinear. 

![spectra](https://user-images.githubusercontent.com/20254772/184480464-b94beb20-85e4-40f4-84c6-edbd5991cfd4.png)

Applying clustering methods to know the number of groups/types of milks with similar properties: Hierarchical and K-means method

| Hierarchical     |   K-means     |
|------------|-------------|
| ![hierarchical](https://user-images.githubusercontent.com/20254772/184480548-a459622d-4c5d-4678-91c1-9515c16fdc83.PNG) | ![kmeans](https://user-images.githubusercontent.com/20254772/184480551-be1be96d-f760-41f9-b167-096960876bcd.PNG) |

## Principal Component analysis:
Here, we find the most significant columns which can represent the deviation or variance of entire data set.

The first three columns seems to cover the variance of more than 90% of the data, this is how we reduce dimensions after using these components and multiplying it again with our data set.

![pca](https://user-images.githubusercontent.com/20254772/184480785-c2126686-c8a3-4399-aa77-a8cee778fcb8.PNG)

## Finally creating our own function for plsr and check prediction:

![plsr](https://user-images.githubusercontent.com/20254772/184480851-7d6169bb-4e96-40e3-bd7c-6eb13b9efe21.PNG)


