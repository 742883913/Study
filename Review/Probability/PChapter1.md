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

- 事件基本公式

$$\begin{split}
    &A-B=A\bar{B}=A-AB\\
    &A\cap(B\cup C)=(A\cap B) \cup (A\cap C)\\
    &A\cup (B\cap C)=(A\cup B) \cap (A\cup C)\\
    &A \cap (B-C)=A\cap B-A\cap C\\
    &\overline{A\cap B}=\bar{A}\cup \bar{B};\overline{A\cup B}=\bar{A}\cap \bar{B}
\end{split}$$

- 互斥事件 (<font color =red>Mutually Exclusive Event</font>)
- 对立事件(<font color =red>Contrary Event</font>)

古典概型(<font color =red>Classical probability</font>):1. 有限个样本点;2. 发生的可能性一样

- 概率基本公式

$$\begin{cases}
  P(A\cup B)=P(A)+P(B)-P(AB)\\
  P(A\cup B \cup C)=P(A)+P(B)+P(C)-P(AB)-P(AC)-P(BC)+P(ABC)
\end{cases}$$

$$\begin{split}
  &P(A-B)=P(A\bar{B})=P(A)-P(AB)\\
  &P(A|B)=\frac{P(AB)}{P(B)}\\
  &P(AB)=P(A)P(B|A)
\end{split}$$

> $P(\cdot|B)$ 符合一切运算规律

- 全概率公式: