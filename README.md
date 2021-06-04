# Experiment descriptions
OT_entropy.ipynb contains our experiments on regularized instances for our algorithm and Sinkhorn. The implementation is in Python3 and the required dependencies are numpy, matplotlib, scipy, IPython.display, and pandas.
The Sinkhorn implementation in cell 3 of the notebook is borrowed from pythonot.github.io.
To change the regularizer parameter or run multiple repetitions, toggle mu and q respectively in cell 5.
OT_entropy_NOLINE8.ipynb is the same as OT_entropy.ipynb except we did not include Line 8 of Algorithm 4 in our paper in its implementation. This is included for reproducibility purposes regarding the plots of the main paper (see discussion at start of Appendix E).
OT_unregularized.ipynb contains our experiments on unregularized instances for our (unregularized) algorithm and the [JST19] algorithm. 
To run multiple repetitions, toggle q in cell 5.
