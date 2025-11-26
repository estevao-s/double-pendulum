# The Double Pendulum, chaos and Lagrangian Mechanics

## The Double Pendulum System

## Lagrangian Mechanics

### Equation of Motion

Applying the Euler-Lagrange equation to the double pendulum you may find two coupled equations that describes the angular acceleration of each mass. Considering $\Delta = \theta_1 - \theta_2$, the equations are shown bellow:

$$\ddot{\theta}_1 = \dfrac{-g(2m_1+m_2)sen(\theta_1)-m_2gsen(\theta_1-2\theta_2)-2sen(\Delta)m_2(\dot{\theta}_2^2l_2+\dot{\theta}_1^2l_1cos(\Delta))}{l_1(2m_1 + m_2 - m_2cos(2\Delta)}$$
\
$$\ddot{\theta}_2 =\dfrac{2sen(\Delta)(\dot{\theta}_1^2l_1(m_1+m_2)+g(m_1+m_2)cos(\theta_1)+\dot{\theta}_2^2l_2m_2cos(\Delta))}{l_2(2m_1+m_2-m_2cos(2\Delta)}$$

Both equations don't have analitical solution. Therefore is necessary to use a numerical method to obtain the solution.

## References

* BURDEN, Richard L.; FAIRES, Douglas J.; BURDEN, Anette M. Problema de valor inicial para equações diferenciais ordinárias. In: BURDEN, Richard L.; FAIRES, Douglas J.; BURDEN, Anette M. __Análise Numérica__. 10. ed. [S. l.]: CENGAGE, 2022. cap. 5, p. 283-394.
  
* TAYLOR, John R. Lagrangian Approach: The Double Pendulum. In: TAYLOR, John R. __Classical Mechanics__. [S. l.: s. n.], 2005. cap. 11, p. 430-436.
