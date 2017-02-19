# Important limits
Their are two intresting limits that occor frequently in mathmatics that you must know.

#### The limit of $$x^ke^{-x}$$ as $$x \to \infty$$
$$
\lim_{x \to \infty}{x^ke^{-x}} = 0 \\
\text{where } k \in \mathbb{R}
$$

To prove this we look at $$k = 0$$ which would make the expression $$e^{-1}$$ which tends towards zero. When $$k < 0$$ both terms tend toward zero so the limit is zero. When $$k > 0$$ then:

$$
\begin{align}
x^ke^{-x} &= \frac{x^k}{e^x}\\
&= \frac{x^k}{1 + x + \frac{x^2}{2!} + {...} + \frac{x^n}{n!} + \frac{x^{(n + 1)}}{(n + 1)!} + {...}}\\
&= \frac{x^{k - n}}{x^{-n} + x^{1 - n} + \frac{x^{2 - n}}{2!} + {...} + \frac{1}{n!} + \frac{x}{(n + 1)!} + {...}}\\
\end{align}
$$

Let $$n > k$$, then as $$x \to \infty$$, $$x^{k-n} \to 0$$. The terms after $$\frac{1}{n!}$$ tend towards infinity so the denominator tends towards infinity, hence $$x^ke^{-1} \to \frac{0}{\infty} = 0$$

#### The limit of $$x^k \ln x$$ as $$x \to 0$$
$$
\lim_{x \to 0}{x^k \ln x} = 0 \\
\text{where } k > 0
$$

Let $$x = e^{-\frac{y}{k}}$$, then when $$y \to \infty$$, $$x \to 0$$

$$
\def\dumb{e^{-\frac{y}{k}}}
$$

$$
\begin{align}
\lim_{x}{1}\\
\lim_{x \to 0}{x^k \ln x} &= \lim_{y \to \infty}{{\dumb}^k \ln e^{-\frac{y}{k}}}\\
&= \lim_{y \to \infty}{-\frac{y}{k} e^{-y}}\\
&= -\frac{1}{k} \lim_{y \to \infty}{y e^{-y}}\\
&= -\frac{1}{k} \times 0\\
&= 0
\end{align}
$$

We know $$\lim_{y \to \infty}{y e^{-y}} = 0$$ becauses its the same form as the first limit $$x^ke^{-x}$$
