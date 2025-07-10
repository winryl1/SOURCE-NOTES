
> [!question] What are Composite Functions? 
> **Composite Functions** is a combination of two or more functions — where the *output of one function becomes the input of another.*

**EXAMPLE**
Let: $f(x)=2x+1; \ \ g(x)=x^2$ 
Find: $f(g(x))$  if  $x=2$

- [I] We are asked to find composite function $f(g(x))$  if  $x=2$. To do this, we first need to find the **output of g(x)**
$$
g(2)=2^2 = 4
$$
- [I] After that, we take the output of g(x) and plug it in f(x).
$$
f(4)=2(4)+1=9
$$
- [p] Therefore, the answer to this example is 9
---

> [!information]
> We can also write $f(g(x))$  as  $(f∘g)$, which is read as *"f composed with g of x"*. You can also read it as *"To do f, do g first"*. 

> [!tip]
> f

---
# Examples
## Simple (1.X)
> [!example]- Example 1.1
> > [!question]-
> > > $$
> > > \begin{aligned}
> > > f(x) &= x^2 - 6x \ \ \ \ g(x) = \sqrt{x} \\
> > > &Evaluate \ \ \ (f∘g)(25)
> > > \end{aligned}
> > > $$
>
> > [!check]- Answer
> >  > $$
> > > \begin{aligned}
> > > &g(25) = \sqrt{25} = 5 \\
> > > f(5) &= (5)^2-6(5) = 25-30 = -5
> > > \end{aligned}
> > > $$

> [!example]- Example 1.2
> > [!question]-
> > > $$
> > > \begin{aligned}
> > > f(a) &= -4(a+8) \ \ \ \ g(a) = \frac{2}{3}a \\
> > > &Evaluate \ \ \ (f∘g)(-15)
> > > \end{aligned}
> > > $$
> 
> > [!check]- Answer
> > >$$
> > >\begin{aligned}
> > > &g(-15) = \frac{2}{3}(-15) = -10 \\
> > > &f(-10) = -4(-10+8) = -8
> > > \end{aligned}
> > > $$

> [!example]- Example 1.3
> > [!question] 
> > >$$
> > > \begin{aligned}
> > > f(x) &= 3(2^x) \ \ \ \ h(x) = 2x-7 \\
> > > &Evaluate \ \ \ (h∘f)(2)
> > > \end{aligned}
> > > $$
> 
> >[!check]- Answer
> > > $$
> > > \begin{aligned}
> > >&f(2) = 3(2^2) = 12 \\
> > >&h(12) = 2(12)-7 = 17
> > >\end{aligned}
> > >$$

## Advanced (2.X)
> [!example]- Example 2.1
> > [!question]- 
> > >$$
> > >\begin{aligned}
> > > f(x) &= 2x+3 \ \ \ \ g(x) = x^2-3x+1 \\
> > >&\text{Evaluate } (g∘f)(x)
> > >\end{aligned}
> > >$$
>
> > [!check]- Answer 
> > > $$
> > >\begin{aligned}
> > >&f(x) = 2x+3 = 2x+3 \\
> > >&g(2x+3) = (2x+3)^2-3(2x+3)+1 \\
> > > &= (4x^2+12x+9)+(-6x-9)+1 \\
> > > &= 4x^2+6x+1
> > >\end{aligned}
> > >$$

> [!example]- Example 2.2
> > [!question]- 
> > > $$
> > >\begin{aligned}
> > > g(x) &= \frac {8x-1}{x+4} \ \ \ \ h(x) = 3x+10 \\
> > >&\text{Evaluate} (g∘h)(x)
> > >\end{aligned}
> > >$$
>
> > [!check]- Answer 
> > > $$
> > >\begin{aligned}
> > >&h(x) = 3x+10 = 3x+10 \\
> > > \\
> > >&g(3x+10) = \frac {8(3x+10)-1}{(3x+10)+4} \\
> > > &= \frac {24x+79}{3x+14} \\
> > >\end{aligned}
> > >$$

> [!example]- Example 2.3
> > [!question]- 
> > > $$
> > >\begin{aligned}
> > > f(x) &= x^3-6 \ \ \ \ h(x) = \sqrt[3] {2x-15} \\
> > >&Evaluate \ \ (f∘h)(x)
> > >\end{aligned}
> > >$$
>
> > [!check]- Answer 
> > > $$
> > >\begin{aligned}
> > >&h(x) = \sqrt[3] {2x-15} = \sqrt[3] {2x-15} \\
> > > \\
> > >&f(\sqrt[3] {2x-15}) = (\sqrt[3] {2x-15})^3-6 \\
> > > &=2x-15-6 \\
> > > &=2x-21
> > >\end{aligned}
> > >$$