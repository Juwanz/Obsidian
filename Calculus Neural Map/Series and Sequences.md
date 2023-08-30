Sequences are defined as a list of numbers that follow a certain pattern, while sequences are the sum of a series of numbers that repeat in a specific pattern. There are two kinds of series: convergent and divergent. 

## Convergence of a sequence
A sequence is said to converge if it the limit has a finite limit as it approaches infinity. For example, $\lim_{x \to \infty}x^2-2x+1 \to \infty$, so a a sequence of $a_{n}=(n-1)^2$ is divergent, while $a_{n}=\frac{n^3}{n!}$ is convergent because $\lim_{x\to\infty}\frac{x^3}{x!}=0$, as $x!$ increases at a faster rate than $x^3$. 

note: unline series, sequence follow a unique set of rules where if both $a_{n}$ and $b_{n}$ converge, then $\lim_{n\to\infty}a_{n}b_{n}=\lim_{n\to\infty}a_{n}*\lim_{n\to\infty}b_{n}$ ; the same applies to divison

A sequence is said to be monotone if it is strictly decreasing or increasing, meaning that the value that comes before must always be either greater than less than; they also cannot repeat. Monoticity can be tested using the following test: 
if $\frac{a_{n+1}}{a_{n}}$ is less than one, the function is strictly decreasing. If it is greater than one, it is strictly increasing. 

A sequence is considered bounded if it is strictly increasing or decreasing and has an upper or lower bound. In this scenario, the function is either always growing or shrinking to approach a bound. All bounded sequences are convergent. 

### The $f'$ test
A sequence may be written as a function to replicate its values at fixed integers. When $f'(x)>0$ , the function will be strictly increasing; the function will be strictly decreasing when $f'(x)<0$. This test paired with the limit test may be used to test whether or not a function is convergent or divergent. 

## Convergence of a series
#### Geometric Series
A geometric series takes the form of $\Sigma_{k=0}^{\infty}a(r)^k$  and may easily be solved for using the formula $\frac{a}{1-r}$. It is important to note that this notation may take peculiar forms, such as $\Sigma_{k=1}^{\infty}\frac{1}{2^{k-1}}$, which is equal to $\Sigma_{k=0}^{\infty}\frac{1}{2}^k$. The rate constant may also take the form of an expression with a variable, such as $\Sigma_{k=0}^{\infty}(n-3)^k$.  

A geometric series converges if $r<1$ and diverges if $r>1$. 
#### Telescoping Series
Telescoping series often take the from of an improper fraction. Write out the first few sequences of be resulting two series, and you will find that many of the terms will cancel out, leaving you with a single expression. If this occurs, the series is convergent. If not, the series is divergent. 
#### The Divergence Test (nth term test)
This test simply states that if $\lim_{k\to\infty}u_{k}\neq0$, the series is diverent.
IMPORTANT: IF THE SERIES DOES APPROACH 0, THIS DOES NOT MEAN THAT THE SERIES IS CONVERGENT. MORE TESTS ARE NEEDED. 
#### The Integral Test
If $\Sigma_{k=a}^{\infty}u_{k}$ is increasing or decreasing, $\int_{a}^{\infty}u_{k}$ must also be increasing or decreasing. 
if the integral is a finite number, then the summation must be convergent
IMPORTANT: THE RESULTING INTEGRAL IS NOT THE SUM OF THE SERIES
#### The p-series test
The p-series test states that if a series takes the form of $\frac{1}{C^r}$, the series will converge if $r>1$ and diverge if $r\le1$.
#### The Direct Comparison Test 
The Direct Comparison relies on other tests. 
If one function $g(x)$ is known to be smaller than another convergent function $f(x)$, then $g(x)$ is also convergent. 
If one function $g(a)$ is known tobe greater than another divergent function $f(a)$, then $g(a)$ is also diverent. 

For example, the p-series test states that $\Sigma_{k=1}^{\infty}\frac{1}{k}$ diverges. Therefore, $\Sigma_{k=1}^{\infty}\frac{ln(k)}{k}$ will also diverge. This is because that the values of $ln(x)$ surpass one as k approaches infinity. 
#### The Limit Comparison Test
The limit comparison test states that if $\lim_{k\to\infty}\frac{a_{k}}{b_{k}}$ approaces a positive, finite value, both functions with behave the same (diverge or converge)

For example, $\Sigma\frac{n^2-10}{4n^5+n^2}$ behaves similarly to $\Sigma\frac{1}{n^3}$, so $\lim_{n\to\infty}\frac{\Sigma_{a}}{\Sigma_{b}}$ may be used to assess, which equals 1/4. Because 1/4 is a finite value greater than zero, the two functions behave the same. Therefore, both functions converge. 
#### The Ratio Test
The ratio test states that taking the limit of a function $\lim_{n\to\infty}\frac{u_{n+1}}{u_{n}}$ may be used to determine the convergency of a series. If the limit is less than one, the series converges. If the series is greater than one or is infinite, the series diverges. If the limit equals one, the convergency cannot be determined. 
#### The Root Test
nth root of the limit as it approache infinity, less than one => converge, greater than => diverge, =1 => cannot tell

$\delta$   