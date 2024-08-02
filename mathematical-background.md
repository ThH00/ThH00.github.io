# A Linear Space

A linear space (or vector space) $\{V,+;\mathbb{R},.\}$ consists of a set $V$ and two operations, an addition $(+)$ and a scalar multiplication $(.)$ with the following properties for all ${\bf u}, {\bf v}, {\bf w}\in V$, $\alpha, \beta\in\mathbb{R}$[^1]
1.   $\alpha\cdot{\bf u}+\beta\cdot{\bf v}\in V\qquad$ (closure)
2.   $({\bf u}+{\bf v})+{\bf w} = {\bf u}+(\bf v)+{\bf w}\qquad$ (associativity w.r.t. +)
3.   ${\bf 0}+{\bf v} = {\bf v}\qquad$ (existence of a zero element)
4.   ${\bf u}+(-{\bf u}) = {\bf 0}\qquad$ (existence of a negative $-{\bf u}$ for any ${\bf u}$)
5.   ${\bf u}+{\bf v} = {\bf v}+{\bf u}\qquad$ (commutativity w.r.t. +)
6.   $\alpha\cdot(\beta\cdot{\bf u}) = (\alpha\beta)\cdot{\bf u}\qquad$ (commutativity w.r.t. $\cdot$)
7.   $(\alpha+\beta)\cdot{\bf u} = \alpha\cdot{\bf u}+\beta\cdot{\bf u}\qquad$ (distributivity w.r.t. $\mathbb{R}$)
8.   $\alpha\cdot({\bf u}+{\bf v}) = \alpha\cdot{\bf u}+\alpha\cdot{\bf v}\qquad$ (distributivity w.r.t. $V$)
9.   $1\cdot{\bf v} = {\bf v}\qquad$ (existence of identity)

# An Algebra

A linear space is called an algebra if it is closed under some product operation.[^2]

# A Lie Bracket

An operation $[\cdot,\cdot]$ which maps two elements to another element is called a Lie bracket if the following three identities hold.[^2]
1. $[{\bf A},{\bf B}] = -[{\bf B},{\bf A}]\qquad$ (anticommutative, skew)
2. $[{\bf A}+{\bf B},{\bf C}] = [{\bf A},{\bf C}]+[{\bf B},{\bf C}],\quad [c{\bf A},{\bf B}]=c[{\bf A},{\bf B}],\quad c\in\mathbb{R}\qquad$ (bilinear)
3. $[{\bf A},[{\bf B},{\bf C}]]+[{\bf B},[{\bf C},{\bf A}]]+[{\bf C},[{\bf A},{\bf B}]]={\bf 0}\qquad$ (Jacobi identity)

# A group


[^1]: Source: Papadopoulos Berkeley's ME281 notes
[^2]: Source: [Modern Robotics Textbook](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf)

