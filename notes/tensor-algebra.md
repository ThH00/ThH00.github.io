# Tensor Algebra

## The Tensor Product

A tensor is a linear transformation that maps a vector into another vector. Tensors are invariant is that they are independent of the chosen basis

We define the tensor product operation $\otimes$, also know as the bun product after its resemblence to [the hot cross bun](https://en.wikipedia.org/wiki/Hot_cross_bun), such that for the vectors ${\bf a}$, ${\bf b}$, and ${\bf u}$,
$$
\begin{align}
    ({\bf a}\otimes{\bf b}) {\bf u} = ({\bf b}\cdot{\bf u}){\bf a}
% \label{eq:tensor-product-def}
\end{align}
$$
The object $({\bf a}\otimes{\bf b})$ acts on the vector ${\bf u}$ and maps it to the vector $({\bf b}\cdot{\bf u}){\bf a}$. Hence, ${\bf a}\otimes{\bf b}$ is a tensor. We read ${\bf a}\otimes{\bf b}$ as ${\bf a}$ tensor product ${\bf b}$ or ${\bf a}$ bun ${\bf b}$.


## Some Derivations

Key point: if two tensors acting on any vector always produce the same result, then the two tensors are equal.

- 
$$
\begin{align}
    ({\bf a}\otimes{\bf b})({\bf c}\otimes{\bf d}) = ({\bf b}\cdot{\bf c})({\bf a}\otimes{\bf d}),
\end{align}
$$
since, considering any vector ${\bf u}$,
$$
\begin{align*}
    & ({\bf a}\otimes{\bf b})({\bf c}\otimes{\bf d}){\bf u},\\
    & = ({\bf a}\otimes{\bf b})({\bf d}\cdot{\bf u}){\bf c},\\
    &= ({\bf d}\cdot{\bf u})({\bf b}\cdot{\bf c}){\bf a},\\
    &= ({\bf b}\cdot{\bf c})({\bf a}\otimes{\bf d}){\bf u.}
\end{align*}
$$


- For any tensor ${\bf A}$ and vectors
$$
\begin{align}
    {\bf A}({\bf b}\otimes{\bf c}) = ({\bf A}{\bf b})\otimes {\bf c}
\end{align}
$$