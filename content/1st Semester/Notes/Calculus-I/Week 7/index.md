#notes #calculus 

# Calculus-I Week 7

### Tangent/derivative/instantaneous rate of change at a point

of some function f(x) at $x_o$ is slope of tangent is number: $$m = \lim_{h \to 0} \frac{f(x_o + h) - f(x)}{h} = f'(x_o)$$
Tangent is a line with slope m passing through $x_o$.

- [[Ex Tangents Derivatives|Examples]]

### Derivative

A [[1st Semester/Notes/Calculus-I/Week 7/derivatives|derivative]] of a function f(x) with respect to variable x is a function whose value at x is:
$$f'(x) = \lim_{x \to h} \frac{f(x+ h)- f(x)}{h} \ \ \ \ \ .......\ \ \ (i)$$ provided that the limit exists.

Sounds familiar? YES IT IS! The derivative at a point is the same as the slope of tangent at that point!

#### Alternate formula:
An alternate formula for derivative can be derived by replCING  few values.
Let $z = x + h$, which makes $h = z - x$
Put the values in (i)
$$f'(x) = \lim_{z \to x} \frac{f(z) - f(x)}{z - x} \ \ \ \ \ ..... \ \  \ \ (ii)$$
- [[Ex Tangents Derivatives|Examples]]

#### Differentiability implies Continuity

If a f(x) is differentiable at a point c, it is also continuous at that point c.
If that's true, then we must be able to get the definition of continuity from the definition of derivative (ii).

So our goal is to get:
$$\lim_{z \to x} f(z) = f(x)$$
from the definition of derivative.


##### Proof

Given that $f'(c)$ exists, we must show that $\lim_{x \to c} f(x) = f(c)$, or equivalently that:
$$
\lim_{h \to 0} f(c+h) = f(c)
$$
If $h \ne 0$, then
$$
f(c+h) = f(c+h) \\\\
f(c+h) = f(c+h) - f(c) + f(c)\\\\
f(c+h) = h \times \left( \frac{f(c+h) - f(c)}{h}\right) + f(c)
$$
Taking $\lim_{h \to x}$ on both sides
$$
\lim_{h \to 0} f(c+h) = \lim_{h \to 0} f(c) + \lim_{h \to 0}\left(\frac{f(c+h) - f(c)}{h} \right) \times h \\\\
\lim_{h \to 0} f(c + h) = f(c) + 0 \\\\
\lim_{h \to 0} f(c + h) = f(c)
$$
Which is the definition of continuity.

This is how sir "proved" the statement in class.
***Here's a [[Differentiability implies Continuity.svg|better solution]] for this***
### Random Stuff
What is a curve? Is $y = x^2$ a curve?
Sure it is!
Is $y = e^x$ a curve?
Sure it is!
Is $y=\log{x}$ a curve?
Sure it is!

Now what about this? $$y = 2x + 1$$Not a curve? Haha, jokes on you! It is a curve!

Everything of the form $$y = f(x)$$is, by deifinition, a curve!