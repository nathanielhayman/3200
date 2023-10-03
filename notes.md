

### Poisson Distribution

The PMF:

$$
p(x)=P(X=x)=\frac{e^{-\lambda}\lambda^x}{x!},\space x=0,1,2,...,\space \lambda > 0
$$

The mean & variance:

$$
\begin{aligned}
    E(X)=\lambda \\ \sigma^2_X=\lambda
\end{aligned}
$$

- Models events which do not follow the strict criterion of being Bernouli
- Mean and variance are equivalent, meaning rare events are as likely as common events


Ex:

- Let X equal the number of typos on a printed page with a mean of 3 typos per page
  - What is the probability of one typo on a randmly selected page?

$$
P(X=1)=\frac{e^{-3}3^1}{1!}=0.149
$$
  - What is the probability of at least one typo on a randmly selected page?

$$
P(X\geq1)=1-P^c=1-P(X=0)=1-\frac{e^{-3}3^0}{0!}=1-e^{-3}=0.9
$$

### Exponential Distribution

- Models lifetimes of equipment or waiting times until events occur
- Notation

$$
X \dot= \exp(\lambda)
$$
- Expected values are

$$
E(X)=\frac{1}{\lambda}\\
\sigma_X^2=\frac{1}{\lambda}
$$

- Memoryless property of the exponential:


$$
P(X>s+t|X>s)=P(X>t)
$$

where $s$ represents the time already spent, and $t$ represents the future time
