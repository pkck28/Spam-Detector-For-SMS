# Spam Detector For SMS
Simple Spam Detector using Navies Bayes Algorithm.

## Dataset :-
Dataset contains simply two columns, one containing the SMS and other contains the category to which SMS belongs to i.e where  spam or ham. It contains 5572 entries. Dataset is uploaded in Master branch.

## Naives Bayes Algorithm :-
This algortihm is based on Bayes Theorem used in probability. It is an probabilistic approach to classify mainly text. It is one of the most widley used algorithm for Email and SMS spam filtering. To get more insight into the algorithm and how it works go to this [link](http://www.inf.ed.ac.uk/teaching/courses/inf2b/learnnotes/inf2b-learn-note07-2up.pdf)

## How it works :-
- Importing important libraries like pandas and sklearn.
- The dataframe is created and is properly formated so that it can be used.
- It is split into trainig and test data.
- The model is trained and tested for accuracy.

## How to use :-
- Install Jupyter Notebook.
- Clone the Repository after forking it and open Jupyter Notebook.(keep the code file of spam detector in same director in which Jupyter notebook is installed)
- Open the code and run it completely before using it.
- The input your SMS in Line 14 in place of xtest.
- Run this line pred=mnb.predict(x_testtf).
- Check value of pred for your answer.(1 for ham and 0 for spam).

## Accuracy :-
Accuracy at present is 96.77 %. 

## Future Advancements :-
- To improve it's accuracy by varing the train and test date ratio.
- To check if there is any better algorithm for this task.

## Licsening :-
This Repository is under standard MIT License.
