# EuclidExtended
Extended Euclidean algorithm using coordinate matrices

General version of the <a href="https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm">extended Euclidean algorithm</a> that, given a list of integers, returns their greatest common divisor and its <a href="https://en.wikipedia.org/wiki/B%C3%A9zout%27s_identity">Bézout coefficients</a>. 

The algorithm treats the integers as a 1-dimensional vector space and uses the list of integers given as a linearly dependent spanning set for that space, using coordinate matrices to find coefficients such that the GCD can be expressed as a linear combination of those integers.
