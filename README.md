# DP-trio-TDT
This contains Python codes used in our experiments on methods for privately releasing the top K significant marker loci in TDT. 
We applied the exponential mechanism, which is based on the concept of differential privacy (DP). 

We conducted experiments based on simulation and real data to evaluate the runtime of our algorithms and the accuracy of outputs. 
The distribution of the statistics on our datasets can be found in the datasets file. 
In the evaluation of the accuracy, "evaluation1" is for the case where the distribution of the families in TDT are unbalanced, 
and "evaluation2" is for the case where the families are distributed across all categories. 

Supplements.pdf contains detailed proofs, detailed description of our datasets, and other information about our methods.

### Note
For details of our releasing methods, please see our paper entitled "Efficient Differentially Private Methods for a Transmission Disequilibrium Test in Genome Wide Association Studies".


