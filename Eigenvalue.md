%% In order to represent the equation correctly by LateX, I change the format of this file into .md(markdown).

I used to be confused with the concept of eigenvalue and eigenvector. Just few days ago, when I relearned linear algebra, I got the idea of EIGEN suddenly. I will try to explain it clearly step by step.

In the field of electro-magnetic without resources, the solution of eigen-solver in some commercial software, such as CST, is the frequency of electro-magnetic wave which can be transmitted. However, in the respect of mathmatics, in my own opinion, the eigenvalue should be $-\omega^2\mu\varepsilon$, where $\omega$ represents angular frequency, while $\mu$ and $\varepsilon$ represent permeability and permittivity of media seperately. The concret reseason is below.

The two curve Maxwell equations without resources are $\nabla\times E = -j\omega\mu H$ and $\nabla\times H = j\omega\varepsilon E$, having been replaced $\frac{\partial}{\partial t}$ by $j\omega$. And then, taking curve of both equations, we can get $\nabla^2 E = -\omega^2\mu\varepsilon E$ and $\nabla^2 H = -\omega^2\mu\varepsilon H$ where $\nabla\cdot E = 0$ and $\nabla\cdot H = 0$(due to the condition 'without resources') have been used, sharing the same formation with $Ax = \lambda x$, where $\nabla^2$ and $A$ are both linear calculators, $x$ is eigenvector and $\lambda$ is the eigenvalue.

According to the comparation above, we can conclude that the $-\omega^2\mu\varepsilon$, the counterpart of $\lambda$, is THE EIGENVALUE of wave equations. The frequency of the electro-magnetic wave can be extracted from the engivalue by $f = \frac {\omega}{2\pi}$.

When it comes to the situation of static electrofield whose frequency is zero($f = \frac{\omega}{2\pi} = 0$) due to the zero value of $\omega$, we can conclude that the eigenvalue($-\omega^2\mu\varepsilon$) of wave equation is zero. And the wave equation will degenerate to the Laplace equation($\nabla^2 X = 0$), which can be deduced or verified from Maxwell equation withouot resources in static field.

Maxwell Equation without resources in static field:
1. $$\nabla\times E = 0$$
2. $$\nabla\times H = 0$$
3. $$\nabla\cdot D = 0$$
4. $$\nabla\cdot B = 0$$
where $D = \varepsilon E$, and $B = \mu H$.

Take curl of equation 1 and 2,
$$\nabla\times\nabla\times E = \nabla(\nabla\cdot E) - \nabla^2 E = 0$$
$$\nabla\times\nabla\times H = \nabla(\nabla\cdot H) - \nabla^2 H = 0$$
Then, replace equation 3 and 4 into two equations above,
$$\nabla^2 E = 0 = 0E$$
$$\nabla^2 H = 0 = 0H$$
comparing last two Laplace equations with $Ax = \lambda x$. We can preceive the eigenvalues of last two Laplace equations(which are wave equations in static field. However, the frequency is zero) are both zero.
