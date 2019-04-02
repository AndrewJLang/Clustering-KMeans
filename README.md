Instructions:

 - The program was compiled and run on Python version 3.7.1. The libraries used within this project were numpy, pandas, matplotlib.pylot, and scipy.

Clustering-Unsupervised:
 - This is the file that should be ran to display how the clustering works.

 - The code calculates the centroids and their new locations for every iteration.  If the unbalanced dataset is selected to be clustered, the parameter reassign must be set to True for the kmeans method.  This checks to see if the centroids are within a certain Euclidean distance of each other, and resets them if they are too close.

 - Iterations must be changed manually at the top of the kmeans method, although the designated value show work properly.

 - The parameter for plot and kmeans methods must have the datasets changed according to what dataset one wishes to cluster and plot.

Clustering-Supervised:
 - Calculates the entropy of the dataset based on how the clusters were assigned.  All that needs to be changed is the dataset selected (other datasets will be commented out at top of program).

 - No need to run this file if you don't wish to calculate the entropy.
