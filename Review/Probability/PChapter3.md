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

## 二维随机变量 (<font color =green>Bivariate Random Variable</font>)

$$P(x_1<X<x_2,y_1<Y<y_2)=F(x_2,y_2)-F(x_2,y_1)-F(x_1,y_2)+F(x_1,y_1)$$

- 边缘分布函数 (<font color =green>Marginal Distribution Function</font>)

$$\begin{cases}
    F_X(x)=F(X,+\infty)\\
    F_Y(y)=F(+\infty,y)
\end{cases}$$

$$\begin{cases}
    f_X(x)=\int ^{+\infty}_{-\infty}f(x,y)dy\\
    f_Y(y)=\int ^{+\infty}_{-\infty}f(x,y)dx
\end{cases}$$

- 联合分布函数(<font color =green>Joint Distribution Function</font>)


$$\begin{cases}
    F(x,y)=\int ^{y}_{-\infty}\int ^{x}_{-\infty}f(u,v)dudv\\
    f(x,y)=\frac{\partial ^2 f(x,y)}{\partial x\partial y}
\end{cases}$$

- 独立性: 对于连续型还包括 $f(x,y)=f_X(x)f_Y(y)$

- 卷积公式只能运用于相互独立的随机变量

- 二维均匀分布:

$$f(x,y)=\begin{cases}
    \frac{1}{S_D},(x,y)\in D\\
    0 \qquad,else
\end{cases}$$

- 二维正态分布

$$f(x,y)=\frac{1}{2\pi \sigma _1 \sigma_2\sqrt{1-\rho^2}}\exp(-\frac{1}{2(1-\rho ^2)}[(\frac{x-\mu _1}{\sigma_1})^2-2\rho(\frac{x-\mu _1}{\sigma_1})(\frac{x-\mu _2}{\sigma_2})+(\frac{x-\mu _2}{\sigma_2})^2])$$

> $\rho=\frac{Cov(X,Y)}{\sigma _1 \sigma _2}$