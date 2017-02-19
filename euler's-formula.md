# Euler's formula
When analytical methods do not work, we can use numerical methods to get an approximate answer. In order to solve $$\frac{dy}{dx} = f(x, y)$$ subject to $$y(x_0) = y_0$$ we can use euler formula which considers each point on the curve to be a strait line hence
$$
\begin{align}
\frac{y_1 - y_0}{h} &= f(x_0, y_0)\\
y_1 - y_0 &= hf(x_0, y_0)\\
y_1 &= y_0 + hf(x_0, y_0)\\ 
\end{align}
$$
which we can repeat to acieve a better approximation using
$$
y_{r + 1} = y_r + hf(x_r, y_r)
$$

#### Example
$$\frac{dy}{dx} = \sin(x + y)$$ given $$y(1) = 0$$ find estimates for $$y(1.1)$$, $$y(1.2)$$ and $$y(1.3)$$.

$$
\begin{align}
x_0 &= 1\\
y_0 &= 0\\
h &= 0.1\\
f(x, y) &= \sin(x + y)\\
\end{align}
$$

$$
\begin{align}
y(1.1) &= 0 + 0.1 \times \sin(1 + 0)\\
&= 0.0841\\

y(1.2) &= 0.0841 + 0.1 \times \sin(1.1 + 0.0841...)\\
&= 0.1768\\

y(1.3) &= 0.1768 + 0.1 \times \sin(1.2 + 0.1768...)\\
&= 0.2749
\end{align}
$$