# What's That Letter!

<p align="center">
 <img src="https://d.newsweek.com/en/full/1394686/asl-getty-images.jpg" />
</p>

<br />

An Americal Sign Language (ASL) recognition system which takes 28X28 grayscale images of the hand gesture and predicts the corresponding letter with **99.5%** accuracy.

<br />

## Data

There are 24 classes corresponding to each letter in the alphabet (J and Z do not have any data because the hand gestures for these letters require motion.

You can get the data from [kaggle](https://www.kaggle.com/datamunge/sign-language-mnist).

<br />

## Performance

| Model | Accuracy |
| --- | --- |
| Logistic Regression | 69.17% |
| Support Vector Classifier | 84.19% |
| Decision Tree Classifer | 43.24% |
| Random Forest Classifier | 81.46% |
| Artificial Neural Network | 82.01% |
| Convolutional Neural Network | 99.5% |
