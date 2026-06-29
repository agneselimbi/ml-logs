# Goals for this week:
- Intro to Linear Algebra (chap 5: linear independence)
- Review Chebyshev inequality

# What did I learn this week?
I read chap3 on Vector Norms. 
The norm of a vector is an indication of how "big" the vector is.. There are many types of norms but the book concentrates on the Euclidean norm defined as :
$\|x\| = \sqrt(xTx) = \sqrt{\sum_{i} x_i^{2}}$

- Norm properties 
$\|x\|  >= 0
$\|x\|  = 0 iff x = 0 $
$\|\alpha x\| = \|\alpha\| |x\|$
$\|x+y\| <= \|x\| + \|y\|$

- RMS (root mean squared)
$rms = norm(x)/\sqrt(n)$

- Average $avg(x) = 1^{T}x$
- Standard deviation 
$ std(x) = \|(x - (1^{T}x)1) \| / \sqrt(n)$$$
- Properties of std 
$$
std(x+k) = std(x) (k \in \R) 

std(\alpha x)  = |\alpha| std(x)
$$

- Distance between vectors x,y 
$ dist(x,y) = \|x-y\|$
Distance measure how close 2 vectors are to each other 

- Triangular ineqaulity
$ \|a+b\| <= \|a\| +\|b\|$

- Cauchy-Schwarz formulation 
$ \|x^{T}y| <= \|x\|\|y\|$

- Cosine and norm relationship 
$\|(x+y)\|^{2} = \|x\|^{2} + \|y\|^{2} + 2\|x^{T}y\|$

- How do i use the cosine as a measure of similarity?
if $cos\phi = 1$ => $ x = \alpha y $ where $\alpha >0$ they are going in the same direction 

if $cos\phi = -1$ => $ x = -alpha y $ where $\alpha <0$ they are going in opposite directions 

if $cos\phi = 0$ => x orth to y $. They are uncorrelated. 

# Problem sets 
- Add link 

# What problems did I encounter? 
Can't remember because i was not keeping track of an error log. Need to add the pdf of the problem sets 
- Understanding the Chebyshev inequality and when to use it. 
- Rememberingg the Caushy Shwarz inequality 