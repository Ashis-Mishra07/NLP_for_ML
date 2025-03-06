### Advantages and Disadvantages of One Hot Encoding



#### Advantages
- Easy to implement with python programming
- way sklearn one hot encoder   ,   pd.get_dummies 



#### Disadvantages
- Sparse matrix so created have a lot of 1 and 0
- leads to overfitting
- if the length of sentence is different , then ML algorithms difficult to integrate
- No semantic meaning get captured .
- out of vocabulary -> means there comes a new word come , it will be out of vocabulary
- is vocabulary(unique words) is very high then it leads to sparse matrix which will lead to overfitting .


