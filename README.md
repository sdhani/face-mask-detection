# Face Mask Detection             
<img align="right" src="https://github.com/sdhani/face-mask-detection/blob/master/assets/Face_Masks.jpg" width=300 height=auto>

To design an algorithm that determines whether an individual is *wearing a face mask*, *not wearing a face mask*, or *wearing a face mask incorrectly*.

<Related Works>


## Dataset
We combined 2 different datasets together to form a three class classification. With over 17,000 images and additional images for people of color and people who are white

https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset?

https://github.com/cabani/MaskedFace-Net



## Results
KNN
The optimal parameters resulted in 86.7% accuracy, and performed lower when dimensionality reduction techniques were included.

Decision Tree
The optimal parameters resulted in 84% accuracy, and performed lower when dimensionality reduction techniques were included.

SVM
Reached an accuracy of ~93% with our testing dataset.

Naive Bayes
Because of naive bayes assumption and how much pixels correlate with each other, it performed with ~68% for multinomial and ~77% for Gaussian.

CNN: 
Best performing: Reached an accuracy of ~98% with our testing data. 


## Conclusion
In conclusion our best performing model was CNN, achieving 98% testing accuracy. Our classifers that were comparable to our baseline paper underperformed, within a margin of 6-~15%. In regards to our POC and W datasets, all classifiers underperformed dramatically, with an emphasis on lower accuracies for the W dataset. 


## Contributors
- [Shania Dhani](https://github.com/sdhani)
- [Xuejin Gao](https://github.com/xuejingao)
- [Michelle Lucero](https://github.com/MichelleLucero)

## Links
- [Presentation](https://github.com/sdhani/face-mask-detection/blob/master/research/proposal_presentation.pdf)
- [Project Proposal](https://github.com/sdhani/face-mask-detection/blob/master/research/proposal_condensed.pdf)
