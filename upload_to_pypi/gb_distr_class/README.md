# gb_distr_class package
This package defines a class Distribution and two inheriting classes Gaussian and Binomial.
It allows to perform basic operations and plotting for Gaussian and binomial distribution objects.
# Files
## Binomialdistribution.py
Binomial distribution class for calculating and visualizing a Binomial distribution. 
    
Attributes:
* mean (float) representing the mean value of the distribution
* stdev (float) representing the standard deviation of the distribution
* data_list (list of floats) a list of floats to be extracted from the data file
* p (float) representing the probability of an event occurring
* n (int) number of trials

## Gaussiandistribution.py
Gaussian distribution class for calculating and visualizing a Gaussian distribution.

Attributes:
* mean (float) representing the mean value of the distribution
* stdev (float) representing the standard deviation of the distribution
* data_list (list of floats) a list of floats extracted from the data file

## Generaldistribution.py
Generic distribution class for calculating and visualizing a probability distribution.

Attributes:
* mean (float) representing the mean value of the distribution
* stdev (float) representing the standard deviation of the distribution
* data_list (list of floats) a list of floats extracted from the data file

# Installation
## from test.pypi
`pip install --index-url https://test.pypi.org/simple/ gb-distr-class`
## from pypi
`pip install gb-distr-class`