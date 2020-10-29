# Fake-News-Detection-1.0

Do you trust all the news you hear from social media? All news are not real, right? So how will you detect the fake news? The answer is Python.
This Python Project helps us detecting fake news, you will easily make a difference between real and fake news. 
Before moving up, we should know about the terms **tfidfvectorizer**, **PassiveAggressive Classifier**.

### What is a TfidfVectorizer?
TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

### What is a PassiveAggressiveClassifier?
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

## Now we are good to go.
You don't have to worry, I have included the steps in the main jupyter file too.

## Conclusion 
Today, we learned to detect fake news with Python. We took a political dataset, implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier, and fit our model. We ended up obtaining an accuracy of 92.82% in magnitude.
Hope you enjoyed this Project.
