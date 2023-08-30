an integral is the inverse of a derivative. An integral takes the form $\int_{a}^{b}f(x)dx$ and may be visualized as the area underneath the graph of $f(x)$ from $a$ to $b$.

there are two kinds of integrals: indefinite and definite

Integrals may be used to find [[volumes]] and [[surface areas]] of a revolved function, along with [[differential equations]]

### definite integrals
a definite integral is notated as $\int_{a}^{b}f(x)dx$ and may be visualized as the area underneath $f(x)$ from point $a$ to point $b$. 
### indefinite integrals
an indefinite integral simply is the antiderrivative of a function and has no set parameters. 

## solving integrals 
integrals may be solved through [[#u-subsitution]] [[#antiderivatuve]], or [[#by parts]].
#### antiderivative
antiderivatives are the most basic form of solving an integral. An antiderivative is the inverse of a derivative. 
for example, the antiderivative of $sin(x)$ is $-cos(x)$, just as the derivative of $cos(x)$ is $-sin(x)$.  
#### u-subsitution
by subsituting a part of the integrand to $u$, we can solve for $du$ in terms of $dx$ and then solve the integral in terms of $\int f(u)du$. This works based on the chain rule of differentiation. 
#### by parts 
This works based on the product rule of differentiation. The basic formula is $\int udv = uv - \int vdu$. This process may be repeated as many times as necessary in order to find the solution. Another aspect of integration by parts is circular integration, which will take the form of $\int udv=uv-(X- \int udv)$. From there, simply solve algebraically in order to find the value of the original integral. A faster way of solving an integral by parts is by using the tabular method. 
#### by partial fractions
If the integral takes the form of $\int \frac{polynomial}{polynomial}$, it is may be possible to seperate the integral into $\int \frac{A}{ax+b} + \frac{B}{cx+d}dx$. From there, simple logarithms may be used to solve the integral. It is important to note that if one denominator takes the form of $x^2$ or $(ax+b)^2$, then it is important to make another partial fraction of denominator $x$ or $ax+b$, respectively. The cover-up method is a faster way of solving certain integral by partial fraction problems. If the numerator is a polynomial of a larger degree than the denominator, then it is recommended to first use long division to simply the  equation, for this will make it much easier to solve. 
#### trig subsitution
in certain problems, it is possible to subsitute for x for certain trig functions, as per the conditions below: 
$a^2-x^2$ => $x=asin\theta$  => $a^2-a^2sin^2\theta=a^2cos^2\theta$ 
$a^2+x^2$ => $x = atan\theta$ => $a^2+a^2tan^2\theta = a^2sec^2\theta$ 
$x^2-a^2$ => $x = asec\theta$ => $a^2sec^2\theta - a^2 = a^2tan^2\theta$ 
It is also important to subsitute $dx$ for $d\theta$. Do not forget to back subsitute $d\theta$ back into terms of $x$. 

