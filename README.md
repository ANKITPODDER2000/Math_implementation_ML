#Machine Learning :
******************************************************************************************************************************
A field of study that gives the comupter ability to learn with out explicitly programmed.
Or , machine learning is extract knowledge from training data and predict for unseen data properly.

Tools for machine Learning:
******************************************************************************************************************************
  >>Scikit-learn (sklearn)

  >>Tensorflow

  >>Turi

But Each & Every algrorithm is nothing but a mathematical implementation of basic rules.

Types of Machine learning Algorithm:
>>Supervised Machine Learning : For this type of learning labeled data are used.
  >>Regression     : Predict continuous valued output or price for some Input Variable.
    ==Example : Predict House Price,Income of a person
    
  >>Classification : Predict distinct valued output or price for some Input Variable.
    ==Example : Predict a cancer is benign or malignent, pic of a cat.
    
>>Unsupervised Machine Learning : Find out group from a given dataset.

Necessary tools for implementation in python :
******************************************************************************************************************************
>>Numpy

  >>Important numpy methods :
  
    >>np.exp()
    
    >>np.log()
    
    >>np.dot()
    
    >>a.T
    
>>Pandas

  >>Important Pandas method:
  
    >>pd.read_csv(path)
>>Matplotlib

  >>Important Matplotlib method
  
    >>plt.plot()
    
    >>plt.figure(row,column)
    
    >>plt.subplots()
    
    >>plt.title()
    
    >>plt.xlabel()
    
    >>plt.ylabel()
    
    >>plt.xticks()
    
    >>plt.yticks()
    
>>Seaborn

<>*Regression* :
******************************************************************************************************************************
In statistical modeling, regression analysis is a set of statistical processes for estimating the relationships between a dependent
variable (often called the 'outcome variable')and one or more independent variables (often called 'predictors', 'covariates', or 
'features').

>>
  >>>>h(x) = (theta.T . X) + b  where theta is the coefficient and b is the intercept.
  >>To meansure the efficency of an algorithm we need an error function or cost function.There is different type of Error function:
    
    >>MAE(mean absolute error):
      
      MAE = (1 / m) * |h(x) - y|
    
    >>MSE(mean squared error):
     
     MSE = (1 / 2*m) * (h(x)-y)^2
   
   >>RMSE(root mean squared error):
     
     RMSE = ((1 / m)* (h(x)-y)^2 )^(1/2)
   
   >>binary_crossentropy(For classification)
    
    >>categorical_crossentropy(For classification)
   
   >>sparse_categorical_crossentropy(For classification)
  
  >>**Cost function** : (1 / 2*m) * (h(x)-y)^2
