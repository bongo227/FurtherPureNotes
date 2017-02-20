# Formation of second order differential equations
Consider the function and its derivatives
$$
\begin{align}
y &= Ae^x + Be^{-2x} - x\\
\frac{dy}{dx} &= Ae^x - 2Be^{-2x} - 1\\
\frac{d^2y}{dx^2} &= Ae^x + 4Be^{-2x}
\end{align}
$$

Since we have three equations with $$A$$ and $$B$$ is we can eliminate these constants.
$$
\begin{align}
y - \frac{dy}{dx} &= 3Be^{-2x} - x + 1\\
\frac{d^2y}{dx^2} - \frac{dy}{dx} &= 6 Be^{-2x} + 1\\
\frac{d^2y}{dx^2} - \frac{dy}{dx} - 2y &= 2x - 1\\
\end{align}
$$

#### Example
The function of $$y$$ is given by $$y = A \cos x + B \sin x + e^{-2x}$$ where $$A$$ and $$B$$ are arbitrary constants, find the second order differential equation.

$$
\begin{align}
y &= A \cos x + B \sin x + e^{-2x}\\
\frac{dy}{dx} &= -A \sin x + B \cos x - 2e^{-2x}\\
\frac{d^2y}{dx^2} &= -A \cos x - B \sin x + 4e^{-2x}\\
\end{align}
$$

$$
\begin{align}
\frac{d^2y}{dx^2} + y &= 5e^{-2x} \\
\end{align}
$$