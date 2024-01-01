%% In order to represent the equation correctly by LateX, I change the format of this doc into .md(markdown).
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

I used to be confused with the concept of eigenvalue and eigenvector. Just few days ago, when I relearned linear algebra, I got the idea of EIGEN suddenly. I will try to explain it clearly step by step.

In the field of electro-magnetic without resources, the solution of eigen-solver in some commercial software, such as CST, is the frequency of electro-magnetic wave which can be transmitted. However, in the respect of mathmatics, the eigenvalue, in my own opinion, should be $-\omega^2\mu\varepsilon$, where $\omega$ represents angular frequency, while $\mu$ and $\varepsilon$ represent permeability and permittivity of media seperately. The concret reseason is below.

The two curve Maxwell equations without resources are $\nabla\times E$ = $-j\omega\mu H$ and $\nabla\times H$ = $j\omega\varepsilon E$, having been replaced $\frac{\partial}{\partial t}$ by $j\omega$. And then, taking curve on both equations, we will get $\nabla^2\times E$ = $-\omega^2\mu\varepsilon E$ and $\nabla^2\times H$ = $-\omega^2\mu\varepsilon H$, sharing the same formation with $Ax$ = $\lambda x$ where $A$ is the linear calculation, $x$ is eigenvector and $\lambda$ is the eigenvalue.

According to the comparation above, we can preceive that the $-\omega^2\mu\varepsilon$, the counterpart of $\lambda$, is THE EIGENVALUE of wave equations. The frequency of the electro-magnetic wave can be extracted from the engivalue by $f = \frac {\omega}{2\pi}$.

When it comes to the situation of static electrofield whose frequency is zero due to the zero value of $\omega$, we can conclude that the eigenvalue is zero. And the wave equation will degenerate to the Laplace equation, which can be deduced from Maxwell equation withouot resources and the change to time.
