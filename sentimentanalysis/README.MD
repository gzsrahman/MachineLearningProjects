Beginner Sentiment Analysis Script
===
Hello! I hope you're having a good day!

The python script in this folder requires the installation of a pre-established data set. Please type the following into your terminal before running the script:
>pip install datasets


To run the script, simply type into your terminal:
>python3 sentimentanalysis.py

The program looks at a database of sentences that are labeled 0, 1, or 2 in terms of emotional value, corresponding to negative, neutral, or positive, respectively. It parses through the sentences in the dataset so that they can be fed into a Random Forest Classifer, which uses a set of training data to learn the different sentences and their corresponding labels. In the end, the RFC is fed test sentences, to which it assigns predicted emotional labels. These predictions are compared to the actual emotional labels to judge the program's performance.

As of my last run through, the program predicted emotional labels with 85% accuracy. While that is only a B, I'm excited by the fact that a piece of code managed to earn a B in emotional intelligence. That's pretty cool.
