<head>
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
  <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
      skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
      inlineMath: [['$','$']]
      }
    });
  </script>
</head>

## 离散型随机变量的分布(<font color =green>Discrete random variable</font>)

- 0-1分布 $B(1,p)$
- 二项分布 $B(n,p)$ (<font color =green>Bionomial Distribution</font>)
- 泊松分布 $P(\lambda)$ (<font color =green>Poisson Distribution</font>)

$$P(X=k)=\frac{\lambda ^k}{k!}e^{-\lambda}$$

- 几何分布 $G(P)$ (<font color =green>Geometric Distribution</font>)

$$P(X=k)=(1-p)^{k-1}p^k$$

> 首中停止

- 超几何分布 $H(n,N,M)$ (<font color =green>Hyper Geometric Distribution</font>)

$$P(X=k)=\frac{C_M^kC_{N-M}^{n-k}}{C_N^n}$$

> 总数: $N$,不合格:$M$ ,取数: $n$, 取出的不合格数: $k$ ;这是不放回,放回用二项分布近似

## 连续型随机变量的分布(<font color =green>Continuous random variable</font>)

- 指数分布 $E(\lambda)$ (<font color =green>Exponential Distribution</font>)
  
$$f(x)=\begin{cases}
    \lambda e^{-\lambda x},x>0\\
    0\qquad ,else
\end{cases}$$

$$F(x)=\begin{cases}
    1-e^{-\lambda x},x>0\\
    0\qquad ,else
\end{cases}$$

- 正态分布 $N(\mu ,\sigma ^2)$(<font color =green>Normal Distribution</font>)

$$f(x)=\frac{1}{\sqrt{2\pi}\sigma}e^{-\frac{1}{2}(\frac{x-\mu}{\sigma})^2}$$

>对与符合正态分布的随机变量都有: 

> $$P(a<X<b)=\Phi(\frac{b-\mu}{\sigma})-\Phi(\frac{a-\mu}{\sigma})$$