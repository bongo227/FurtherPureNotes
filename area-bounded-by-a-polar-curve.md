# Area bounded by a polar curve
Given $$r = f(\theta)$$ and $$\alpha \leq \theta \leq \beta$$ the area of the curve is 
$$
A = \int_{\alpha}^{\beta}{\frac{1}{2}r^2 d\theta} 
$$

#### Example
Find the area of the polar curve $$r = a \cos 2 \theta$$

$$
\begin{align}
A &= 2 \times \int_{\alpha}^{\beta}{\frac{1}{2}r^2 d\theta} \\

&= 2 \times \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{\frac{1}{2}(a \cos 2 \theta)^2 d\theta}\\

&= 2 \times \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{\frac{1}{2} a^2 \cos^2 2 \theta \; d\theta}\\

&= a^2 \times \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{\cos^2 2 \theta \; d\theta}\\

&= a^2 \times \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{\frac{1}{2} (1 + \cos 4 \theta) \; d\theta}\\

&= a^2 \times \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{\frac{1}{2} (1 + \cos 4 \theta) \; d\theta}\\

&= \frac{1}{2} a^2 \times \left( \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{1\; d\theta} + \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}{\cos 4 \theta
\; d\theta} \right)\\

&= \frac{1}{2} a^2 \times \left( \left[ \theta \right]_{-\frac{\pi}{4}}^{\frac{\pi}{4}} + \left[\frac{1}{4}\sin(4 \theta)\right]_{-\frac{\pi}{4}}^{\frac{\pi}{4}} \right)\\

&= \frac{1}{2} a^2 \times \left( \left[\frac{\pi}{4} --\frac{\pi}{4}\right] + \left[\frac{1}{4}\sin(\pi) - \frac{1}{4}\sin(-\pi)\right] \right)\\

&= \frac{1}{2} a^2 \times \left( \left[\frac{\pi}{2}\right] + \left[0\right] \right)\\

&= \frac{\pi a^2}{4}\\

\end{align}
$$