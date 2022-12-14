## Derivatives and Integrals - 28/10/2022
Problem sheet 2 can be found [here](https://ucl-eu-west-2-moodle-sitedata.s3.eu-west-2.amazonaws.com/4c/0a/4c0afc15dec935cbdbf249abc552c867c616da0b?response-content-disposition=inline%3B%20filename%3D%22diff_int_Q.pdf%22&response-content-type=application%2Fpdf&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA47YHZF637GKGWUJC%2F20221117%2Feu-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221117T162557Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21543&X-Amz-Signature=906020d7ceffe94b6a020df9db593672e568c144da050e286b6c822ce8930db1).

Solutions for some of the problems you were given are shown below.

### 1. a) Find the derivative of $(x^3+2x)\sin(x)$

```{admonition} Solution
:class: dropdown, seealso
Using the chain rule ($v\mathrm{d}u + v\mathrm{d}v$) with $u = x^3+2x$ and $v = sin(x)$, we get:

$(3x^2 + 2)\sin(x) + (x^3+2x)\cos(x)$
```

### 1. c) Find the derivative of $4^x$

```{admonition} Solution
:class: dropdown, seealso
Implicit differentiation is necessary for this problem. First, we want to let $y=4^x$, then find $\mathrm{ln}(y) = x\mathrm{ln}(4)$.

$\frac{\mathrm{d}}{\mathrm{d}x} \mathrm{ln}(y) = \frac{1}{y} \frac{\mathrm{d}y}{\mathrm{d}x}$

But also notice that:

$\frac{\mathrm{d}}{\mathrm{d}x} \mathrm{ln}(y) = \frac{\mathrm{d}}{\mathrm{d}x} x\mathrm{ln}(4) = ln(4)$

$\therefore \frac{1}{y} \frac{\mathrm{d}y}{\mathrm{d}x} = ln(4)$

And hence:

$\frac{\mathrm{d}y}{\mathrm{d}x} = y\mathrm{ln}(4) = 4^x\mathrm{ln}(4)$
```

### 3. Given that $x = t^2 + \sin(t)$, $y = e^t$, calculate $\frac{dy}{dx}$, giving your answer in terms of $t$

```{admonition} Solution
:class: dropdown, seealso

For this we need to find $\frac{dy}{dx} = \frac{dy}{dt}\frac{dt}{dx}$

$\frac{dy}{dt} = e^t$

$\frac{dx}{dt} = 2t + \cos(t)$

$\therefore \frac{dy}{dx} = \frac{dy}{dt}\frac{dt}{dx} = \frac{e^t}{2t + \cos(t)}$
```