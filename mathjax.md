{% include mathjax.html %}
###### Borrowing from [Gaston Sanchez](http://www.gastonsanchez.com/visually-enforced/opinion/2014/02/16/Mathjax-with-jekyll/)
*Kramdown (used on GitHub-pages) has special support for $$ to delimit both inline and block equations.*
'''
For example, $$ \frac{1}{n^{2}} $$ is rendered as a block equation here:
$$ \frac{1}{n^{2}} $$
'''

It's the same process for more complex formulae, such as 
'''$$ J(\theta) = \frac{1}{2m}(\sum_{i=1}^m(h_\theta (x^{(i)}) - y^{(i)})^2 + \lambda\sum_{j=1}^n\theta^2_j) $$''' 

Rendered as:
$$ J(\theta) = \frac{1}{2m}(\sum_{i=1}^m(h_\theta (x^{(i)}) - y^{(i)})^2 + \lambda\sum_{j=1}^n\theta^2_j) $$

You use the same basic syntax to render'''$$a^2 + b^2 = c^2$$''' inline: $$a^2 + b^2 = c^2$$

You can also use different typesets or [math alphabets](http://milde.users.sourceforge.net/LUCR/Math/math-font-selection.xhtml), such as \mathbf

$$ \mathbf{X}_{n,p} = \mathbf{A}_{n,k} \mathbf{B}_{k,p} $$

Additional Resources: 


