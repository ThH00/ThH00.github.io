# Relationship between Small Rotation Tensors and Skew Symmetric Tensors

If ${\bf R}$ represents a small rotations around some axis by a small angle $\Delta \theta$, we can Taylor-expand it in the form

${\bf R} = {\bf I}+{\bf A}\Delta\theta+O(\Delta\theta)^2$,

for some tensor ${\bf A}$ where ${\bf I}$ is the identity and $O(\Delta\theta)^2$ denotes terms of second or higher orders in $\Delta\theta$. Since ${\bf R}$ is a rotation tensor,

${\bf R}{\bf R}^T = ({\bf I}+{\bf A}\Delta\theta+O(\Delta\theta)^2)({\bf I}+{\bf A}\Delta\theta+O(\Delta\theta)^2)^T = {\bf I}+({\bf A}+{\bf A}^T)\Delta\theta+O(\Delta\theta)^2$

must be identically ${\bf I}$ for any $\Delta\theta$. Hence, ${\bf A}+{\bf A}^T={\bf 0}$, or

${\bf A}^T = -{\bf A}$.


Sources
- [Lie Algebra Method for Pose Optimization Computation](https://iim.cs.tut.ac.jp/member/kanatani/papers/Liealgebra.pdf)
