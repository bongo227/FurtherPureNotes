# Mid-point formula
Euler's formula isn't very accurate since it only considers two points, the midpoint formula uses three points: $$P_{r-1}$$, $$P_{r}$$ and $$P_{r+1}$$. Provided the points are close together then the gradient between $$P_{r-1}$$ and $$P_{r+1}$$ will approximately equal the gradient at $$P_{r}$$ which gives:
$$
\begin{align}
\frac{y_{r+1} - y_{r-1}}{2h} &= f(x_r, y_r)\\
y_{r+1} &= y_{r-1} + 2h f(x_r, y_r)
\end{align}
$$
Since we need two values (and we are normaly only given $$x_0$$ and $$y_0$$) we must use another method (euler's method would work) to find the second value before you can use mid-point forumla.