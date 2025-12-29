You can only do 2 basic things with vectors - Adding and Scaling. (Multiplying would introduce higher powers of vectors, which would behave non-linearly.)

The Schrodinger Equation is Linear!
$$
\psi = \psi_{1} + \psi_{2}
$$
Here, vector addition is called superposition.

A scalar (constant) scales stuff (whaaatt??????)

$$
\vec{b} - \vec{a} = \vec{b} + (-\vec{a})
$$

Linear combinations are the polynomials of Linear Algebra.

The **span** of a (single) vector is all vectors $k\vec{v}$, for a given vector $\vec{v}$. For two vectors, the span is the set of all linear combinations of the two. This means that if one vector does not belong to the span of the other (i.e., they are **linearly independent**), the span of both vectors form a plane. In general, the span of $n$ independent vectors gives us an $n$-dimensional space.

The number of independent vectors we can find in a space is called the **dimension** of that space. It tells us how many independent degrees of freedom we have.

## Bases

We pick a point on a plane to represent the zero vector. In principle, vectors are not free to move around in linear algebra. (Any span must always run through the origin.) A line is a subgroup of a plane (yay group theory!) The cosets are other parallel lines that don't go through the origin. 

A **vector space** is any set of vectors that can be added and scaled. A line is not only a subgroup, but also a subspace. The span of any set of vectors will be a subspace.

We then pick any two vectors that are linearly independent (for a 2d plane), and we call them the basis vectors. We usually work with orthonormal bases (the vectors are orthogonal and of unit length.) We can now compose any vector into a linear combination of the bases.
$$
\vec{v} = p\vec{e}_{1} + q\vec{e}_{2}
$$
Here, $p$ and $q$ are called the coordinates. They are usually written as follows.
$$
\begin{pmatrix}
p \\
q
\end{pmatrix}
$$
This decomposition is unique.

Mathematically speaking, an $n$-dimensional vector space is isomorphic to a set of $n$-tuples with addition and scaling.

Coordinates are basis-dependent. Coordinates try to compensate for the change in basis (called **contravariance**). 

The rules of vector spaces do not allow us to measure anything.