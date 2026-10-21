#notes #calculus 

# Oblique Asymptotes

[[asymptotes|Asymptotes]] aren't always vertical or horizontal, they can also be slanted (making some angle $\theta$ (non-0 non-90) with the x or y-axis).

$$\lim_{x \to \pm \infty} f(x)= ax+ b$$
![[asymptote.svg]]

### Which functions?

1) Rational Functions. If the degree of the numerator of a rational function is 1 greater than the degree of the numerator, then the function has an oblique or slanted asymptote. $$f(x) = \frac{p(x)}{q(x)}$$Where Degree of p(x) == Degree of q(x) + 1<br><br>
2) Some root functions in which the power degree of polynomial inside the the root is equal to the power of root itself, have oblique asymptotes.$$\sqrt[n]{x^n + p(x)}$$Where p(x) is any polynomial with degree n - 1.<br><br>
3) Any mixed function that is the sum of a linear function and a term that tends to zero as x approaches infinity. $$f(x) = (ax+b) + \text{anything that tends to 0}$$

### How to find oblique asymptotes?
- #### Rational Functions
	For rational functions in which the degree of p(x) is one greater  than the degree of q(x). We do division to get the Quotient + Remainder/Divisor form.
	The Quotient will be a linear function and is the oblique asymptote.<br><br>
- #### All other functions
	For all other functions, just find limit at infinity and if it ends up as a linear function, you have an oblique asymptote.


### Examples

Here are some [[Excalidraw/oblique asymptotes.svg|examples]] for oblique asymptotes