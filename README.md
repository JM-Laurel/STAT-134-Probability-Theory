# STAT-134 Probability Theory

University of California, Berkeley (Summer 2019)

**Author**: John-Michael Laurel

**Remarks:** *These documents assume understanding of basic probabilistic knowledge such as independence, conditioning, Bayes' rule, joint distributions, et cetera, counting methods (combinatorics), and set theory e.g. deMorgan's laws. Happy Studying :coffee:* 


## Continuous Treatise 


### version 1.5 (08-12-2019)
- Section 8.3 Rayleigh Distribution
	- fixed the pdf and cdf, had the 1/2 in the wrong place
	
### version 1.4 (08-11-2019)
**Big update** today. Material Slate is no more, say hello to its successor: *Black Slate*.

#### Changes and Additions
- Section 5.1 Uniform Distribution
	- retracted fix (from version 1.3) on construction for expectation, actually is (a+b)/2
- Section 7 Poisson Arrival Process
	- new additions (section 7.4 and 7.5) for merging and thinning Poisson processes, along with diagrams
	- fixed indices for inter-arrival times, if there are r arrivals, there are r inter-arrival times *not* r-1
	- fixed parameter for inter-arrival times should be lambda not lambda times t
- Section 9 Operations
		- removed density for Z = X-Y, it's really just another case of Z = X+Y
- Section 10 Conditional Expectation
	- Law of Iterated Expectation (Towering Rule)
	- other properties
- Section 11 Co-Variance
	- defintion
	- bi-linearity
	- variance of a sum of exchangeable random variables
	- variance covariance matrix
- Section 12 Correlation
	- definition 
	- properties
	- sampling an entire population
- Section 13 Standard Bi-Variate Normal
	- construction 
	- properties


### version 1.3 (08-07-2019)
- Section 6 Gamma Distribution 
	- added namedDistribution "Gamma" with respective parameters
- Section 5.1 Uniform Distribution
	- fixed construction for expectation should be (b-a)/2 not (a+b)/2

### version 1.2 (08-07-2019)
- Section 8.2 Linear Combinations of Normal
	- changed "rotational symmetry" to "spherical symmetry" since we're technically in n dimensions
	- appended footnote to specify rotational symmetry when we're dealing with a sum of two independent standard normals
- Section 8.3 Rayleigh Distribution 
	- Corrected named distribution on the square root of a sum of two squared standard normals, should be Rayleigh not N(0,1).
- Added Section 9 Operations

### version 1.0 (08-06-2019)
- Dark Mode is here! I made two variations:
	- *Material Slate* (Comfortable Contrast)
	- *Jet Black* (High Contrast)
- Content
	- Continuous Random Variables
	- Change of Variable for Densities
	- Cumulative Distribution Functions (CDF)
		- minimums and maximums
		- using CDF to compute expectation
	- Distributions
		- Uniform
		- Exponential
			- memoryless property
			- competing exponentials
		- Gamma
			- Gamma function
			- Diagram: Poisson Arrival Process
		- Beta
			- Order Statistics
			- Uniform Order Statistics
		- Normal
			- linear combinations of normal
			- Rayleigh 
			- sum of squared normals

### Future Updates
- operations
- conditional expectation


## Discrete Treatise 

### version 2.0 (08-06-2019)
- Updated document description
- Added metadata to PDF file
- Section 3.4 Multinomial Distribution
	- added index starting value for N

### Version 1.3 (07-22-2019)
- updates headers styles: small caps -> boldface
- added section: Law of Large Numbers
- Section 3.8 Poisson Distribution
	- added sums of Poissons is Poisson
- Section 7.2 Chebyshev's Inequality
	- update some notation
- Section 10.2.1 Variance of a Sum of Indicators
	- added a matrix containing indicator terms in product expansion of a sum of indicators
	- cleaned up paragraph structures

### Version 1.2 (07-18-2019)
- Section 3.5 Geometric Distribution
	- updated synopsis and description
- Schematic
	- segregated "Uniform Distribution" and updated its parameters to match parameters in section 3.1
- added a "Techniques and Important Problems" section

### Version 1.1 (07-17-2019)
- Additions
	- tail bounds Markov and Chebyshev
	- variance of a sum of dependent indicators
	- Craps Principle
- Section-5 Central Limit Theorem
	- rule of thumb for CLT approximation instead of {range of X} should be {range of S_n}
	- added standardization asterisk for a and b

### Version 1 (07-16-2019)
- brief treatise on discrete probability
- random variables and names distributions
- overview of distributions
	- probability mass function
	- expectation
	- variance
- schematic
