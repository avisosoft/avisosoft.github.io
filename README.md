## About us

Our company has been created back in 2007. Initial work was done in web development. Later we have moved to build mobile applications. Since 2015 main area of work is supervised learning.

### Logistic Regression

```python
def loss_function(Y, A):

    """
        calculates loss function

        L( y^, y) = - ( y * log(y^) + (1-y) * log(1- y^))
    """
    return - (Y * np.log(A) + (1 - Y) * np.log(1 - A))
```

### Support or Contact

Contact us via e-mail: webmaster@avisosoft.com
