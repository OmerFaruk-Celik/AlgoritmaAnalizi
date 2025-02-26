$$
\text{To show that } (\ln(x))^5 \text{ is } O(x^{1/2}), \text{ we need to find constants } c \text{ and } x_0 \text{ such that for all } x \geq x_0:
$$

$$
(\ln(x))^5 \leq c \cdot x^{1/2}
$$

---

$$
\textbf{Step 1: Taking the Natural Logarithm}
$$

$$
\text{Let's start by taking the natural logarithm of both sides:}
$$

$$
\ln((\ln(x))^5) = 5 \ln(\ln(x))
$$

$$
\ln(c \cdot x^{1/2}) = \ln(c) + \frac{1}{2} \ln(x)
$$

$$
\text{We need to find } c \text{ and } x_0 \text{ such that:}
$$

$$
5 \ln(\ln(x)) \leq \ln(c) + \frac{1}{2} \ln(x)
$$

---

$$
\textbf{Step 2: Asymptotic Analysis}
$$

$$
\text{For large } x, \text{ the term } \frac{1}{2} \ln(x) \text{ will dominate } \ln(c). \text{ So we can focus on:}
$$

$$
5 \ln(\ln(x)) \leq \frac{1}{2} \ln(x)
$$

$$
\text{To show this, we need to find } x_0 \text{ such that:}
$$

$$
10 \ln(\ln(x)) \leq \ln(x)
$$

$$
\text{Dividing both sides by } \ln(x):
$$

$$
\frac{10 \ln(\ln(x))}{\ln(x)} \leq 1
$$

$$
\text{For large } x, \text{ the term } \frac{\ln(\ln(x))}{\ln(x)} \text{ approaches } 0. \text{ Therefore, there exists an } x_0 \text{ such that for all } x \geq x_0, \text{ the inequality holds.}
$$

---

$$
\textbf{Conclusion}
$$

$$
\text{Thus, we have shown that:}
$$

$$
(\ln(x))^5 \leq c \cdot x^{1/2}
$$

$$
\text{for some constant } c \text{ and for all } x \geq x_0. \text{ Hence, } (\ln(x))^5 \text{ is } O(x^{1/2}).
$$

