# Sci-kit-Learn
Everything you need to know about Sci-kit learn(Sklearn Basics, NLP, Classifiers, etc)

## Bag of Words

Machine learnig deals with Numerical or quantitative factors, so to be able to handle text-data we need to apply BAG OF WORDS rule to enable us convert the text-data into Numerical features. this is archive with a *countVectorizer function()* check the documentation on sklearn.

### Example of how it works
[This book is great] and [This book was so bad] = [this,book,is,great,was,so,bad] this are the words and the rule will be #[1,1,1,1,0,0,0]