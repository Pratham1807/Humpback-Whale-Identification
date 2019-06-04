# Humpback-Whale-Identification
My submission for the Kaggle Humpback Whale Identification competition.

In this competition, you’re challenged to build an algorithm to identifying whale species in images. You’ll analyze Happy Whale’s database of over 25,000 images, gathered from research institutions and public contributors. By contributing, you’ll help to open rich fields of understanding for marine mammal population dynamics around the globe.

**Playground dataset an be downloaded using [this link](https://www.kaggle.com/c/whale-categorization-playground)**

### Libraries used :- 
  * Keras(tensorflow backend)
  * Numpy
  * Pandas
  * scikit-learn
  * Pillow
  * Matplotlib
  
 ### Result:-
  1. **On train data :-**
  On converting all images to a 100 x 100 size and training a small neural network on those images  with *adam optimizer, categorical_crossentropy loss and evaluating on accuracy metric* we achived
  <br>Accuracy :- 88.71%
  <br>Loss :- 0.3857
  <br><br>
  ![Training result screenshot](https://github.com/Pratham1807/Humpback-Whale-Identification/blob/master/images/2019-06-05(1).png)

  2. **On test Data :-**
  My final submission score was 0.36030 which put me on 211th position of 528 on the competition playground leaderboard.
  <br><br>
  ![final kaggle score screenshot](https://github.com/Pratham1807/Humpback-Whale-Identification/blob/master/images/2019-06-03(1).png)
  
