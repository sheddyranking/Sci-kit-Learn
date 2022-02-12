# Sci-kit-Learn
Everything you need to know about Sci-kit learn(Sklearn Basics, NLP, Classifiers, etc)

## Bag of Words

Machine learnig deals with Numerical or quantitative factors, so to be able to handle text-data we need to apply BAG OF WORDS rule to enable us convert the text-data into Numerical features. this is archive with a *countVectorizer function()* check the documentation on sklearn.

### Example of how it works
[This book is great] and [This book was so bad] = [this,book,is,great,was,so,bad] this are the words and the rule will be #[1,1,1,1,0,0,0]


## Improvement on our Model

### ReviewContainer
In other to evenly distribute the dataSet[POSITIVE,NEGATIVE] we created a of Reviewcontainer Class that we call evenly distribute Methods that we even out our training data and test data equally. 

### Increasing Numerical Features
We replaced the CountVectorize() method in bag of words with TfidfVectorizer() in other to increase the models performace.

### Turning our Model (with grid search)
With the GridSearchCV() method you could increase the kernel rating by turning the model

### Others
you can also diverse so many ways in improving your models such removing PUNTUATION marks and all that. for example [good!, good] these two words shouldn't be treated the same. 