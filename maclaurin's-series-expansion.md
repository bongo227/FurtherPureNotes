# Maclaurin's series expansion

The Maclaurin series for a function $$f(x)$$ is given by:
$$
f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + {...} + \frac{f^{(r)}(0)}{r!}x^r + {...}
$$

For example the expansion of $$ln(1 + x)$$:

$$
\begin{align}
f(0) &= ln(1 + x) = ln(1 + 0) = 0\\
f'(0) &= \frac{1}{1 + x} = \frac{1}{1 + 0} = 1\\
f''(0) &= -\frac{1}{(1 + x)^2} = -\frac{1}{(1 + 0)^2} = -1\\
f'''(0) &= \frac{2}{(1 + x)^3} = \frac{2}{(1 + 0)^3} = 2\\
\end{align}
$$$$
\begin{align}
ln(1 + x) &= 0 + 1 \times x + \frac{-1}{2!} \times x^2 + \frac{2}{3!} \times x^3 + {...}\\
&= x -\frac{1}{2}x^2 + \frac{1}{3}x^3 + {...}\\
\end{align}
$$

The forumla booklet has several basic expansions including $$\sin x$$ so we can use them to derive more complex expressions such as $$x \sin x^2$$:

$$
\begin{align}
\sin x &= x - \frac{x^3}{3!} + \frac{x^5}{5!} - {...}\\

\sin x^2 &= x^2 - \frac{x^{2^3}}{3!} + \frac{x^{2^5}}{5!} - {...}\\
&= x^2 - \frac{x^{6}}{3!} + \frac{x^{10}}{5!} - {...}\\

x \sin x^2 &= x \left( x^2 - \frac{x^{6}}{3!} + \frac{x^{10}}{5!} - {...} \right)\\
&= x^3 - \frac{x^7}{3!} + \frac{x^{11}}{5!} - {...}
\end{align}
$$