# Some more pinnacles of natural philosophy

## Matrices

Here's some more synthesis in the form of an overview of a neat derivation whose result allows us to handle geometry with algebra. If a function $\mathbf{f}$ sending vectors to vectors is *linear*, that is, if it preserves the decomposition of its input, $\mathbf{f}(c\_1 \mathbf{v}\_1 + ... c\_n \mathbf{v}\_n) = c\_1 \mathbf{f}(\mathbf{v}\_1) + ... + c\_n \mathbf{f}(\mathbf{v}\_n)$, then the function can be represented purely by knowing where a representative list of vectors gets sent:

$$
\begin{pmatrix} \mathbf{f}(\mathbf{e}\_1) & ... & \mathbf{f}(\mathbf{e}\_n) \end{pmatrix}
$$

Since a list of vectors is just a grid, or *matrix*, of numbers, we are led to define the notion of "multiplying" a matrix by a vector (to correspond to the notion of *applying* a linear function to a vector). Continue following this trail- by reasoning that, since a composition of two linear functions is linear, the composition must be also representible by a matrix- and a (simple!) formula for matrix-matrix "multiplication" reveals itself, allowing us to do things such as compute the position of every particle in a rigidbody after the body as a whole has experienced a sequence of translations and rotations. More complicated formulas that obscure the clarity of the simple one follow, indisputably derived, but that would have nevertheless seemed like wizardry if one were shown them out of the blue. (And sadly, as the path of clarity is rarely the one presented, showing the wizardry "out of the blue" is usually exactly what happens.)
