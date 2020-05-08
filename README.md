# What's That Letter!

<p align="center">
 <img src="https://storage.googleapis.com/kagglesdsdata/datasets/3258/5337/amer_sign3.png?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1589218364&Signature=VIJaBTVJS6ti9J1X%2FSYc4Fza1CX5uM5WOVDRVZwqQNvgMhhafAUJArfuuQs%2FidGhnd%2Bf%2FsjINFDK2RLO9%2FG%2FqP0g8FnAWWjw21DDCYKqJFuOEMgukiR1QPeFznOTldq%2FpsZAO3aYPsjQLvKxhcEZ%2FNmvk%2BtKRuX8S5lcM8Aqtn86qIy6%2BbKrLbjoZ6oRVhudQbAl7MXgwcX6M1UxhWk1j9hu9WrMqe0X9%2BEdxBoHtF3YXRbd2omyJ894xDf9gKgGwa9bQrpY4omT9SNaAXzqB0bNIC%2F555v6G3hUFy01TNYwweStn4khB95uHfIVaovWV9fMXcZQIc%2BJAEsymVI7TQ%3D%3D" />
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
