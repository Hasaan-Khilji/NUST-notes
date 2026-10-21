#notes #calculus 

# Horizontal Asymptotes

An [[asymptotes|asymptote]] that is horizontal is called a horizontal asymptote.
A line $y = b$ is a horizontal asymptote to $y = f(x)$ if 
$$\lim_{x \to \pm \infty} f(x) = b$$

![[horizontal asymptote.svg]]
### Which functions?

Again with the same question we asked in [[asymptotes]]. which functions have ***horizontal*** asymptotes?

The following functions always have horizontal asymptotes:
1) Rational Functions (Bottom Heavy)
2) Rational Functions (Equal Degrees)
3) Exponential Functions
4) Trigonometric Functions (except sinx and cosx)
5) Inverse Trigonometric Functions (except arcsinx and arccosx)

### How to find Horizontal Asymptotes?

Now we'll look in detail, how to find horizontal asymptotes. We'll go through each type of function one by one. But before that, we need to know one basic rule:
- #### Basic Rule
	To find all horizontal asymptote, we always take the limit of f(x) as x approaches both positive and negative infinity. The horizontal asymptotes of any function are:  $$y = \lim_{x \to +\infty} f(x) \\\\ \text{and} \\\\ y = \lim_{x \to -\infty} f(x)$$
	We have to check both cases always.<br><br>
- #### Rational functions
	Rational functions may or may not have horizontal asymptotes.
	Whether or not they have horizontal asymptotes depends on the degree of numerator and denominator.
	Rational functions are of the form $$f(x) = \frac{p(x)}{q(x)}$$
	Here, horizontal asymptotes are possible in two cases:
	1) Degree of p(x) < Degree of q(x):
		- In this case, the horizontal asymptote is always at: $\\ {y = 0}$
	2) Degree of p(x) = Degree of q(x):
		- In this case, the horizontal asymptote is at the ratio of leading coefficient of p(x) to the leading coefficient of q(x). i.e. $$y = \frac{\text{lead coeff. top}}{\text{lead coeff. bottom}}$$
		- Example: For the following function $$f(x) = \frac{x^4 + 1}{2x^4 - x^3 +9x -13}$$The horizontal asymptote is at $y=1/2$.
	For the third case where degree of p(x) > degree of q(x), there is an [[oblique asymptotes|oblique asymptote]] instead (only if the difference in degree is 1).
- #### Exponential Functions
	Exponential Functions always have their horizontal asymptote when the input variable approaches $-\infty$ (unless modified).
	1) The asymptote itself is $y = 0$ in unmodified exponential functions of the form $y = a^x$. 
	2) In shifted exponential function $y = a^x + k$, the horizontal asymptote is at $y = k$.<br><br>
- #### Inverse Trigonometric Functions
	Inverse Trigonometric functions have horizontal asymptotes at the value where the original trigonometric function is undefined.
	
	Example: for arctanx the horizontal asymptote is where tanx is undefined i.e. at
	$y = \pi/2$
	<br>
	arcsinx and arccosx do not have asymptotes because sinx and cosx are defined everywhere.
### Examples
Check out some examples [[Excalidraw/horizontal asymptotes.svg|here]].
