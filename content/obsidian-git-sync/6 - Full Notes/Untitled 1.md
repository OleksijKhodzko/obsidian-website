The Quadric can also be represented in Matrix form Where $b_{i j}=b_{j i}$
$$
\left[\begin{array}{c}
x_1 \\
x_2 \\
\vdots \\
x_n \\
1
\end{array}\right]\left[\begin{array}{ccccc}
a_1 & b_{12} & \ldots & b_{1 n} & -c_1 \\
b_{21} & a_2 & & & \vdots \\
\vdots & & \ddots & & \vdots \\
b_{n 1} & & & a_n & -c_n \\
-c_1 & -c_2 & \ldots & -c_n & d
\end{array}\right]\left[\begin{array}{llllll}
x_1 & x_2 & \ldots & \ldots & x_n & 1
\end{array}\right]=0
$$

Which is the same as
$$
D M D^T=0
$$

Where $D$ represents the Matrix whose size corresponds to the dimension of $M$ and $M$ represents the Matrix of coefficients of dimensions in $\mathbb{S}$. The above is the general Matrix form of any Quadric Surface.
2. Procedure

We know that the centre of a Quadric is the intersection point of all its diameters. This can be found out by differentiating (Partially) the curve with respect to every dimension, setting its value to 0 and solving the so obtained system of equations to obtain the centre.
We set its value equal to zero for the following reason.
We can view the curve as a level set of the function
$$
f\left(x_1, x_2, \ldots, x_n\right)=\sum_{i=1}^n a_i x_i^2+2 \sum_{i, j, i \neq j}^n b_i x_i x_j-2 \sum_{i=1}^n c_i x_i
$$

The level sets of this function create the family of curves $\sum_{i=1}^n a_i x_i^2+2 \sum_{i, j, i \neq j}^n b_i x_i x_j-$ $2 \sum_{i=1}^n c_i x_i+d=0$, where the parameter $\mathrm{d}$ is changing.
For the cases $\frac{\partial S}{\partial x_i}>0$ or $\frac{\partial S}{\partial x_i}<0$,