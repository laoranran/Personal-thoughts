I used to be confused with the concept of eigenvalue and eigenvector.
Just few days ago, when I relearned linear algebra, I got the idea of EIGEN suddenly. I will manage to explain it clearly.

In the field of electro-magnetic without resources, the solution of eigen-solver in some software is the frequency of electro-magnetic wave which can be transmitted.
However, in the respect of mathmatic, the eigenvalue should be $-\omega^2\mu\varepsilon$ where $\omega$ represent angle frequency, while $\mu$ and $\varepsilon$ represent permeability and permittivity of media seperately. The reseason is below.

When we write Maxwell equation without resources, we will put two curve equations which are $\nabla\times E$ = $-j\omega\mu H$ and $\nabla\times H$ = $j\omega\varepsilon E$.
And then, taking curve on both equations above, we will get $\nabla^2\times E$ = $-\omega^2\mu\varepsilon E$ and $\nabla^2\times H$ = $-\omega^2\mu\varepsilon H$, sharing the same formation with $A\times x$ = $\lambda x$ where $A$ is the linear calculation, $x$ is eigenvector and $\lambda$ is THE EIGENVALUE.
According to the comparation above, we will know that the $-\omega^2\mu\varepsilon$, the counterpart of $\lambda$, is the eigenvalue of wave equation. The frequency of the electro-magnetic wave can be extracted from the engivalue by $f = \frac {\omega}{2\pi}$.

When it comes to the situation of static electrofield whose frequency is zero due to the zero value of $\omega$, we can conclude that the eigenvalue is zero. And the wave equation will degenerate to the Laplace equation, which can be deduced from Maxwell equation withouot resources and the change to time.