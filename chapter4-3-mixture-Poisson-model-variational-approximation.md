# ポアソン混合モデルの変分推論

## ポアソン混合モデル
$$
\begin{aligned}
p(x_n|\lambda_k) &=  Poi(x_n|\lambda_k) \\
&= \frac{\lambda^x}{x!}e^{-\lambda}
\end{aligned}
$$

混合分布における条件付き分布は
$$

p(x_n|\mathbf{s}_n, \mathbf{\lambda}) = 
$$
