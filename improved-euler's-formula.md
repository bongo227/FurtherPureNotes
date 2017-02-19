# Improved Euler's formula
Euler's formula works out the gradient of the line segment between two points, but a more accurate method would be to take the average of the gradients at each point which gives:
$$
\begin{align}
\frac{y_{r+1} - y_{r}}{h} &= \frac{1}{2} \times \left[ f(x_r, y_r) + f(x_{r+1}, y_{r+1}) \right]\\
y_{r + 1} &= y_r + \frac{h}{2} \times \left[ f(x_r, y_r) + f(x_{r+1}, y_{r+1}) \right]
\end{align}
$$
Notice that we need $$y_{r+1}$$ to find $$y_{r+1}$$ so we must use another method (Euler's formula) to find the estimator for $$y_{r+1}$$ denoted as $$y^*_{r+1}$$, then the improved Euler's formula can be used.

By substituting in Euler's formula we can rewrite it as:
$$
y_{r+1} = y_r + \frac{1}{2}(k_1 + k_2)
$$ 
where $$k_1$$ and $$k_2$$ are:
$$
\begin{align}
k_1 &= hf(x_r, y_r)\\
k_2 &= hf(x_r + h, y_r + k_1)
\end{align}
$$ 
