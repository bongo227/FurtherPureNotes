# Simple limits

For simple cases its easy to find the limit:
$$
\lim_{x \to 0}{\frac{1 + x}{2 - x}}\\
$$$$
\begin{align}
1 + x &\to 1\\
2 - x &\to 2\\
\frac{1 + x}{2 - x} &\to \frac{1}{2}\\
\end{align}
$$

Others require a transformation:
$$
\lim_{x \to \infty}{\frac{1 + x}{1 - 2x}}\\
$$$$
\begin{align}
1 + \infty &\to \infty\\
2 - \infty &\to -\infty\\
\frac{1 + x}{1 - 2x} &\to \frac{\infty}{-\infty}\\
\end{align}
$$

$$\frac{\infty}{-\infty}$$ is meaningless so divide through by $$x$$.
$$
\lim_{x \to \infty}{\frac{\frac{1}{x} + 1}{\frac{1}{x} - 2}}\\
$$$$
\begin{align}
\frac{1}{x} + 1 &\to 1\\
\frac{1}{x} - 2 &\to -2\\
\frac{1 + x}{1 - 2x} &\to \frac{1}{-2}\\
\end{align}
$$

