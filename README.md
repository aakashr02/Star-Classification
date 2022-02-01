# Star-Classification
Identify Giants and Dwarfs through Machine Learning

## **Problem Statement**
Stellar Classification uses the spectral data of stars to categorize them into different categories. The modern stellar classification system is known as the Morgan–Keenan (MK) classification system. It uses the old HR classification system to categorize stars with their chromaticity and uses Roman numerals to categorize the star’s size.
In this Dataset, we will be using Absolute Magnitude and B-V Color Index to Identify Giants and Dwarfs.

## **Dataset**
The dataset used is the Star Dataset: Stellar Classification - https://www.kaggle.com/vinesmsuic/star-categorization-giants-and-dwarfs from Kaggle. 

The dataset contains several attributes of a star. A few of them are -
TargetClass - Whether the Star is Dwarf (0) or Giant (1)
B-V - B-V color index.
Amag - Absolute Magnitude of the Star.

The task is to classify the stars into 2 classes - Dwarf and Large. Here, 0 represents dwarf star and 1 represents large star. 
The 2 class  labels -
1. Dwarf (0) - If the star is dwarf in size
2. Large (1) - If the star is large in size

## **Model(s) Used**
The KNN algorithm is used to classify the stars based on their size. K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique. K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories. KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.
