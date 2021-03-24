# Richter-s-Predictor-Modeling-Earthquake-Damage

![image](https://user-images.githubusercontent.com/48840280/112375021-86054080-8cc1-11eb-8859-1f412950bc1b.png)


Based on aspects of building location and construction, was made a MLP (MuiltiLebal Perceptron) to predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal.

The Notebook was developed in Google Colab. When using it, you must mount a disk relative to your Drive and rewrite the directory of files relative to it.
First, it was seen that the training dataset was unbalanced, and the process of underfitting (relative to class 1 data) was used.

After this, 57 of the 70 variables were selected in the feature extraction process by the PCA method.

Then a few models were selected to decide which would be the final one to be used, where MLP had the best result among the options.
 In the end, the K-fold process was employed for training the MLP.
 
 
Competition's F1-score: 0,7409!
