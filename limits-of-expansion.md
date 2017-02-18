# Limits of expansion
For tricky expressions we must often use expansions (binomial or maclaurin) to find their limits, in a simular way as dividing through by the highest power of $$x$$.

#### Example
$$
\lim_{x \to 0}{\frac{x}{1 - \sqrt{1 - x}}}
$$
$$
\begin{align}
f(x) &= \frac{x}{1 - \sqrt{1 - x}}\\
&= \frac{x}{1 - (1 - x)^\frac{1}{2}}\\
&= \frac{x}{1 - \left(1 - \frac{1}{2}x - \frac{1}{8}x^2 - \frac{1}{16}x^3\right)}\\
&= \frac{x}{\frac{1}{2}x + \frac{1}{8}x^2 + \frac{1}{16}x^3}\\
&= \frac{1}{\frac{1}{2} + \frac{1}{8}x + \frac{1}{16}x^2}\\

f(0) &= \frac{1}{\frac{1}{2} + \frac{1}{8} \times 0 + \frac{1}{16} \times 0^2}\\
&= \frac{1}{\frac{1}{2}}\\
&= 2
\end{align}
$$