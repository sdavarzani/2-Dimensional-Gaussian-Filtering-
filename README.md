# Image-Filtering-2-Dimensional-Gaussian-Filtering-

First of all, a function named "gauss1d(sigma)" is developed to create 1D Gaussian filter a given value of sigma. The filter should be a 1D array with length 6 times sigma rounded up to
the next odd integer. Each value of the filter can be computed from the Gaussian function, exp(- x^2 / (2*sigma^2)), where x is the distance of an array value from the center. This formula for the Gaussian ignores the constant factor. 
Second, a  2D Gaussian  filter is created by convolution of a 1D Gaussian with its transpose. In fact,  ‘gauss2d(sigma)’ function returns a 2D Gaussian filter for a given value of sigma.  
