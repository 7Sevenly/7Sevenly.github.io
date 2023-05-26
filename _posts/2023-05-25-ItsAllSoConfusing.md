# It's All So Confusing

A confusion matrix is a useful tool to visualise the performance of a machine learning classification. It essentially breaks up the models results into their categories.
These categories are based on the models prediction and the actual classification. An example matrix is shown below, it shows my models performance based on its own validation set.

![Confusion Matrix of Validation Set](/images/confusion_matrix_valid.jpg)

The elements on the diagonal are cases where the model predicted the animal correctly. Outside of this diagonal, it shows what it predicted and whatthe animal actually was.
It's as simple as that!

We can learn from this matrix by seeing which animals the model are consistently getting confused on, and which animal it thinks it is. We can make theories for why this happened, 
and also investigate deeper by looking at the actual images where the model fails. Then with the cleaner tool, which I previously discussed, we can prune the images if it actually 
turns out the image isn't part of the classififcation.
