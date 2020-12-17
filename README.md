# Face Mask Detection             
<img align="right" src="https://github.com/sdhani/face-mask-detection/blob/master/assets/Face_Masks.jpg" width=500 height=auto>


## Objective

Use Machine Learning concepts to design several models that determine whether an individual is *wearing a face mask*, *not wearing a face mask*, or *wearing a face mask incorrectly*. We will use the performance metrics gathered on these models (including accuracy, precision, recall, and f1 scores) to determine which model performs the best. The models explored include KNN, Decision Trees, CNN, Naive Bayes, and SVM. To conclude our findings, we will evaluate all of our models on two distinct group datasets to examine potential biases in our models (One dataset will consist of People of Color [POC], and the other dataset will consist of White [W] indiviudals, both mentioned in greater detail below).

<Related Works>

# Overview
 
## Dataset
We combined 2 different datasets together to form a three class classification dataset with *face mask*, *no face mask*, or *incorrect face mask wear* categories. This new dataset containes over 17,000 images. As for the dataset we used to test bias, we created a W (white) and POC (people of color) dataset. Since there was not an existing dataset available, we obtained the images for W and POC by creating our own dataset collections, each containing around 100-200 image samples. 

- https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset
- https://github.com/cabani/MaskedFace-Net

## Results
`KNN`
The optimal parameters resulted in 86.7% accuracy, and performed lower when dimensionality reduction techniques were included.

`Decision Tree`
The optimal parameters resulted in 84% accuracy, and performed lower when dimensionality reduction techniques were included.

`SVM`
Reached an accuracy of ~93% with our testing dataset.

`Naive Bayes`
Because of naive bayes assumption and how much pixels correlate with each other, it performed with ~68% for multinomial and ~77% for Gaussian.

`CNN`
Best performing: Reached an accuracy of ~98% with our testing data. 


## Conclusion
In conclusion our best performing model was CNN, achieving 98% testing accuracy. Models that were comparable to our baseline paper underperformed by 11-16%. In regards to our POC and W datasets, all models also underperformed dramatically, with an emphasis on poorer results for the W dataset. We suspect differences in image perspectives and dataset quality led to this disparity.

## Project Poster
<img align="right" src="https://github.com/sdhani/face-mask-detection/blob/master/assets/FMD-Poster.png" width=100% height=auto>


## Contributors
- [Shania Dhani](https://github.com/sdhani)
- [Xuejin Gao](https://github.com/xuejingao)
- [Michelle Lucero](https://github.com/MichelleLucero)

## Links
- [Presentation](https://github.com/sdhani/face-mask-detection/blob/master/Face_Mask_Detection_Presentation.pdf)
- [Paper](https://github.com/sdhani/face-mask-detection/blob/master/research/Group7FinalProject353.pdf)
- [Project Board](https://github.com/sdhani/face-mask-detection/blob/master/assets/FMD-Poster.png)

> Dec. 2020
