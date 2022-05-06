### EX NO: 1
### DATE: 1/4/2022
# <p align="center">RANDOM CLASSIFICATION </p>
## AIM:
To write a python program to perform random classification.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook

## Related Theoritical Concept:

## Algorithm
1.In Random forest n number of random records are taken from the data set having k number of records.
2.Individual decision trees are constructed for each sample.
3.Each decision tree will generate an output.
4..Final output is considered based on Majority Voting or Averaging for Classification and regression respectively.

## Program:
```
Program to implement random classification.
Developed by   : ASHWIN A O
RegisterNumber : 212220230005
```
```python
import matplotlib.pyplot as plt
from sklearn import datasets
x,y=datasets.make_blobs(n_samples=100,n_features=2,centers=2,cluster_std=1.05,random_state=2)
fig=plt.figure(figsize=(10,8))
plt.plot(x[:,0][y==0],x[:,1][y==0],'r^')
plt.plot(x[:,0][y==1],x[:,1][y==1],'bs')
plt.xlabel("feature 1")
plt.ylabel("feature 2")
plt.title('Random Clasification Data with 2 classes')
```

## Output:
![164029481-c7e16b50-90a7-4f2a-8639-eea7cd1ded97](https://user-images.githubusercontent.com/75235601/164067114-52d9ecc4-410d-4bd0-b0a4-1931d9a00c90.jpeg)


## Result:
Thus the random classifier was successfully implemented using python programming.
