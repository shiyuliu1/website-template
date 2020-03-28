---
layout: post
title: Handwritten Bengali Grapheme Classification
subtitle: A Word Recognition Problem
image: /img/bengali1.png
tags: [Machine Learning, CNN, Deep Learning, Image Recognition, Neural Network]
---

Bengali is the 5th most spoken language in the world with hundreds of millions of speakers. Considering this, there’s a significant business and educational interest in developing AI that can optically recognize images of the language handwritten. In this project, we used trasfer leanring based CNN to classify the three constituents of Bengali Graphemes, grapheme roots, vowel diacritic and consonant diacritic.
![](/img/bengali2.png){:height="49%" width="49%" .center-block :}

As shown above, there are 168 types of consonant diacritic roots, 11 types of vowel diacritics, and 7 types of consonant diacritics, a total of 186 classes. For the neural network architecture, we built convolutional neural network and used ResNet. By implementing data augmentation, image resizing and parameter tuning, we achieved classification accuracy of 96%, 99% and 99% for the three consitituents, and an overall accuracy of 95% (correctly classifying all three constituents). We also implemented bagging strategy to use the mode value of predicitons from different models as our final prediction. This further increased the overall accuracy very close to 96%.

Please check out our final post [here](https://medium.com/@shiyu_liu/hand-written-bengali-grapheme-classification-21936b7405df). 
Our video demonstration can be viewed [here](https://www.youtube.com/watch?v=HszJ-d8CF6s) or played below.
<div>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/HszJ-d8CF6s" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
