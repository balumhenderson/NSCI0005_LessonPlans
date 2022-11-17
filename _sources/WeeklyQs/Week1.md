# Weekly Questions
## Complex Numbers - 28/10/2022
Problem sheet 1 on complex numbers is found [here](https://ucl-eu-west-2-moodle-sitedata.s3.eu-west-2.amazonaws.com/37/cd/37cd34eca46bbdd8af8291ab18eb65fe94452335?response-content-disposition=inline%3B%20filename%3D%22PS1.pdf%22&response-content-type=application%2Fpdf&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA47YHZF637GKGWUJC%2F20221026%2Feu-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221026T132845Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21555&X-Amz-Signature=a6b02e12061420226099d9ce1297c2b2ef7f29b9dd4f9426e4a2b07a0281c503).

Solutions for some of the problems you were given are shown below.

1\. c) Find $i^5$

```{admonition} Solution
:class: dropdown, seealso
For this question, it is good to notice the pattern of $i^n$.

$i^1 = i$, $i^2 = -1$, $i^3 = -i$, $i^4 = 1$, and then this repeats. 

From here, we can see that $i^{25} = (i^5)^5 = i^5 = i^1 = i$
```

1\. f) Evaluate $\frac{7-i}{3-5i}$

```{admonition} Solution
:class: dropdown, seealso
We multiply both the top and bottom of the fraction by the complex conjugate of the denominator, then simplify down.

$\frac{7-i}{3-5i} = \frac{7-i}{3-5i} \cdot \frac{3+5i}{3+5i} = \frac{26+32i}{34} = \frac{13}{17} + \frac{16}{17}i$
```

2\. a) Find the roots of $x^2-6x+13=0$

```{admonition} Solution
:class: dropdown, seealso
The quadratic formula, $x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$, is essential for this question.
    
$x^2 - 6x + 13 = 0 \hspace{0.5cm} \Rightarrow \hspace{0.5cm} x = \frac{6\pm\sqrt{-16}}{2} = \frac{6\pm4i}{2} = 3\pm2i$
```

2\. b) Find the roots of $x^4=256$

```{admonition} Solution
:class: dropdown, seealso
We expect that we will find 4 roots here, so keep that in your mind when solving this problem.

First, we take the square root of both sides to obtain $x^2 = \pm 16$

Next, we can find the square root again, of both of the previous results:

$x = \sqrt{+16} = \pm 4$ and $x = \sqrt{-16} = \pm 4i$.
```

3\. Show that $\overline{z^2} = \overline{z}^2$

```{admonition} Solution
:class: dropdown, seealso
We start with the usual $z=a+bi$

$$\overline{z^2} = \overline{(a+bi)(a+bi)} = \overline{a^2+2abi-b^2} = a^2 -b^2 - 2abi$$
    
$$\overline{z}^2 = (a-bi)^2 = (a-bi)(a-bi) = a^2 - 2abi +(bi)^2 = a^2 - b^2 -2abi$$
```

4\. Find the roots of $x^5=1$

```{admonition} Solution
:class: dropdown, seealso
For problems of the type $x^n=1$, we want to look at the notes on the ``roots of unity''.
    
For this problem, we use the cyclic relation $z = re^{i\theta} = re^{i(\theta+2\pi k)}$, for $k \in \mathbb{Z}$.
    
We start with:
    
$$z = 1 \hspace{0.5cm} \Rightarrow \hspace{0.5cm} re^{i(\theta+2\pi k)} = 1$$
    
Setting $r=1$ and $\theta=0$ is sensible in this case. We then take the fifth root:
    
$$z_k^{\frac{1}{5}} = 1^{\frac{1}{5}} = e^{i\frac{(2\pi k)}{5}}$$
    
And now we can use $k=0,1,2,3,4$ to find our 5 roots:

1. $k=0 \rightarrow e^{0} = \cos(0) + i\sin(0) = 1$,
2. $k=1 \rightarrow e^{2\pi/5 i} $,
3. $k=2 \rightarrow e^{4\pi/5 i} $,
4. $k=3 \rightarrow e^{6\pi/5 i} \equiv e^{-4\pi/5 i}$,
5. $k=4 \rightarrow e^{8\pi/5 i} \equiv e^{-2\pi/5 i}$.
    
    Remember that we want to keep our solutions in principal range $-\pi < \theta \leq \pi$
```


## Derivatives and Integrals - 28/10/2022
Problem sheet 2 can be found [here](https://ucl-eu-west-2-moodle-sitedata.s3.eu-west-2.amazonaws.com/4c/0a/4c0afc15dec935cbdbf249abc552c867c616da0b?response-content-disposition=inline%3B%20filename%3D%22diff_int_Q.pdf%22&response-content-type=application%2Fpdf&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA47YHZF637GKGWUJC%2F20221117%2Feu-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221117T162557Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21543&X-Amz-Signature=906020d7ceffe94b6a020df9db593672e568c144da050e286b6c822ce8930db1).

Solutions for some of the problems you were given are shown below.