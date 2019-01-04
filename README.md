# FunkSVD_Model_based_recommendation_engine
FunkSVD_Model_based_recommendation_engine
## tallation
Anaconda 4.5.11 distribution 
Python 3.6 
Numpy and Pandas
Matplotlib
Scipy

## ject Motivation
In the notebook, we write the code to implement Funk Singular Value Decomposition.
First, consider we have a user-item matrix that looks like the matrix below, where we want to make an update of U and V matrices based on the 4 highlighted.

![User-movier ratings](https://github.com/Tsakunelson/FunkSVD_Model_based_recommendation_engine/blob/master/Figure5.png)

Also consider we have the following U and V matrices:

![U and V matrices](https://github.com/Tsakunelson/FunkSVD_Model_based_recommendation_engine/blob/master/Figure6.png)

To identify what the current prediction would be for the rating 4 (highlighted in the first image above) based on the current values in the U and V matrices, we perform a linear combination of the corrsponding row and column, resulting to -1.8. This is quite far from the expected rating value, and would prodice a large error with respect to the original value. With the help of gradient descent and a loss function, we would be able to make accurate predictions in this project. 

## File Descrition 
This repository consists of:
- Cleaned movies dataset (movies_clean.svs)
- Cleaned reviews dataset (reviews_clean.svs)

Authors, Licensing, Acknowledgements
- Nelson Zange Tsaku 
- Licensing Code and documentation copyright 2018 the Author's Code released under Udacity License 
- Thanks to the Udacity Community for related support
