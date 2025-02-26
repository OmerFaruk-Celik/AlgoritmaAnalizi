# Proof that \( (\ln(x))^5 \) is \( O(x^{1/2}) \)

To show that \( (\ln(x))^5 \) is \( O(x^{1/2}) \), we need to find constants \( c \) and \( x_0 \) such that for all \( x \geq x_0 \):

\[ (\ln(x))^5 \leq c \cdot x^{1/2} \]

Let's start by taking the natural logarithm of both sides:

\[ \ln((\ln(x))^5) = 5 \ln(\ln(x)) \]
\[ \ln(c \cdot x^{1/2}) = \ln(c) + \frac{1}{2} \ln(x) \]

We need to find \( c \) and \( x_0 \) such that:

\[ 5 \ln(\ln(x)) \leq \ln(c) + \frac{1}{2} \ln(x) \]

For large \( x \), the term \( \frac{1}{2} \ln(x) \) will dominate \( \ln(c) \). So we can focus on:

\[ 5 \ln(\ln(x)) \leq \frac{1}{2} \ln(x) \]

To show this, we need to find \( x_0 \) such that:

\[ 10 \ln(\ln(x)) \leq \ln(x) \]

Let's divide both sides by \( \ln(x) \):

\[ \frac{10 \ln(\ln(x))}{\ln(x)} \leq 1 \]

For large \( x \), the term \( \frac{\ln(\ln(x))}{\ln(x)} \) approaches 0. Therefore, there exists an \( x_0 \) such that for all \( x \geq x_0 \), the inequality holds.

Thus, we have shown that:

\[ (\ln(x))^5 \leq c \cdot x^{1/2} \]

for some constant \( c \) and for all \( x \geq x_0 \). Hence, \( (\ln(x))^5 \) is \( O(x^{1/2}) \).
