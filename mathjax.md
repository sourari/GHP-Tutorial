{% include mathjax.html %}
###### Borrowing from [Gaston Sanchez](http://www.gastonsanchez.com/visually-enforced/opinion/2014/02/16/Mathjax-with-jekyll/)

$$[ \frac{1}{n^{2}} $$]

$$[ J(\theta) = \frac{1}{2m}[\sum_{i=1}^m(h_\theta (x^{(i)}) - y^{(i)})^2 + \lambda\sum_{j=1}^n\theta^2_j] $$]

$$[ F'(\theta_*)=\lim\limits_{\theta\to\theta_*}\frac{F(\theta)-F(\theta_*)}{\theta-\theta_*} $$]

$$a^2 + b^2 = c^2$$

To display inline math use $$( ... $$) like this $$( sin(x^2) $$)

Kramdown (used on GitHub-pages) has special support for $$ to delimit both inline and block equations.

If you want to use subscripts like this Xn,pXn,p you need to scape the underscores with a backslash like so {X}\_{n,p}:
$$ \mathbf{X}_{n,p} = \mathbf{A}_{n,k} \mathbf{B}_{k,p} $$
