# Fitting using Roofit in python notebook

`fit_double_gaussian.ipynb` contains most of the code needed
to fit a double Gaussian signal and a Chebychev background.

`lambda_small.root` is a root file containing the mass distribution
of `Lambda`. The `mva` branch of the tree is the classification output
for a boosted decision tree. Cutting on `mva`, eg. `mva > 0.5` will
reject most of the background.

`rootnotes.py` is a script I copied from other people to get the plot
to display within the jupyter notebook
