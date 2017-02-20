# Differential equations with constants

To solve a differential in the form of $$a \dfrac{d^2y}{dx^2} + b \dfrac{dy}{dx} + cy = 0$$ we must use an auxiliray equation which is  a quadratic in the form $$ak^2 + bk + c = 0$$. If $$k_1$$ and $$k_2$$ are the roots then the general solution will be

| $$k_1 \ne k_2$$ | $$y = Ae^{k_1x} + Be^{k_2x}$$ |
| --- | --- |
| $$k_1 = k_2$$ | $$y = (Cx + D)e^{k_1x}$$ |

#### Example
Find the general solution in to form of trigonometric functions of
$$
\frac{d^2y}{dx^2} + 2 \frac{dy}{dx} + 5y = 0
$$

Find the roots of the auxilary equation
$$
\begin{align}
k^2 + 2k + 5 &= 0\\
k &= \dfrac{-2 \pm \sqrt{4 - 20}}{2}\\
&= \dfrac{-2 \pm 4i}{2}\\
&= -1 \pm 2i\\
\end{align}
$$

Find the general solution
$$k_1 \ne k_2$$ so
$$
\begin{align}
y &= Ae^{(-1 + 2i)x} + Be^{(-1-2i)x}\\
y &= Ae^{-x + 2ix} + Be^{-x -2ix}\\
y &= e^{-x}\left(Ae^{2ix} + Be^{-2ix}\right)\\
y &= e^{-x}\left[A(\cos 2x + i \sin 2x) + B(\cos 2x - i \sin 2x) \right]\\
\end{align}
$$

Combine the constants
$$
C = A + B \\
D = Ai - Bi \\
\quad\\
y = e^{-x}(C \cos2x + D \sin 2x)
$$
