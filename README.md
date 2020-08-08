# diabetes-classification
Implementing general-purpose Bayesian classifier to determine if a patient has a risk of diabetes.
I created a general-purpose classifier by using density-estimation to find structure in the dataset
given if a patient had diabetes or not. Also implemented a method for taking into account prior 
ratios of class-labels to account for class-imbalance without resorting to over-sampling methods.

New EDIT: I've been able to figure out a way using the density curves to actually predict the model's 
false-predictive rate BEFORE any testing! So I can calculate approximately the false-positive and false
negative rate BEFORE we've even tested the model, which means we can troubleshoot the model before doing any
tests.
