# Rock-vs-Mine-Prediction-KNN-

1. The data set contains the response metrics for 60 separate sonar frequencies sent out against a known mine field (and known rocks). These frequencies are then labeled with the known object they were beaming the sound at (either a rock or a mine).
2. Performed a grid-search with the sklearn pipeline to test various values of k and report back the best performing parameters.Plotted mean test scores(cv result) against k values.
3. Used the grid classifier object from the previous step, to get a final performance classification report and confusion matrix
3. Acheived an accuracy of 90% on test set.
