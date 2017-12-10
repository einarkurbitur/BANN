Nodes
=====

Data Sorter
***********
Sorts the data by splitting it down into training data for the creators. The data sorter also normalizes the output data from the creators and mixes it with existing data that then goes to the Evaluator


Creator
*******
Creates new imagery based on the training data. This is the main output of
the network. Their goal is to improve and fool the Evaluator.


Evaluator
*********
Evaluates the imagery from the creators in a blind test. Their job is to spot the created content and help the creators get better by dismissing bad creations.


Progress Tracker
****************
Evaluates the results from the Evaluator and gives feedback back to the creators and evaluator.
