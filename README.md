# Math as natural philosophy

I am personally very interested in what you might call "philosophically- and physically-inspired math"- that blend of math and physics that, in the olden days, was predominant, and which was simply referred to as *natural philosophy*.

Humans have of course come a long way since we first started puzzling out how to analyze phenomena in the world we inhabit. In the past, the tools of natural philosophy[^1] were very visual (and much more difficult, in my opinion). Now, our tools are symbolic and syntactical (making the manipulations much more accessible, in my opinion).

[^1]: Euclidean geometry, i.e., ruler and compass geometry

In our modern day, I would say that natural philosophy entails representing *abstract principles* from logic as well as *tangible spatial ideas* from our experience in syntactical form, and then using the most basic of those abstract principles to derive further insights. The insights can be new abstract principles that ring true, new spatial ideas we didn't realize are true but are now made clear, or some synthesis of the two.

To me, natural philosophy *is* what math is. My heart is prone to think of other areas of math that don't neatly fit into the "philosophical" or "physically-inspired" categories[^2] as gibberish not having much application, even though my mind knows that they are still very important[^3].

[^2]: Like number theory, combinatorics, graph theory, and many other discrete math topics.

[^3]: This is because, to reference WT Gowers's [*The Two Cultures of Mathematics*](https://www.dpmms.cam.ac.uk/~wtg10/2cultures.pdf), I am much more of a theory-builder than problem-solver.

## Pinnacles of natural philosophy

A striking example of some synthesis is the *generalized fundamental theorem of calculus*,

$$
\int_M d\omega = \int_{\partial M} \omega
$$

It says that "the accumulation of the density over the interior is the difference of the quantity across the boundary". How abstract, how visual, how beautiful.

If you have experience with calculus, you can perhaps see how this generalizes the elementary fundamental theorem of calculus,

$$
\int^a_b \frac{df(x)}{dx} dx = f(b) - f(a),
$$

which says "the accumulation of the density is the difference of the quantity", an already beautiful fact.

Another example, from the more tangible end of things, is Isaac Newton's definition of the total force on a particle of mass $m$ and velocity $\mathbf{v}$:

$$
\mathbf{F}\_{\text{tot}} := \frac{d(m\mathbf{v})}{dt}
$$

This definition says "force is that which changes the conserved quantity of motion". How profound!

And on the more logical end of things, we have the idea of *duality*, which is just the realization that when we have a function $f$ acting on an input $x$ in the expression

$$
f(x),
$$

then the input $x$ is also in some sense acting on the function $f$ (by means of a function that itself takes functions, like $f$, as inputs). This philosophical sort of realization is not just perspective-changing, but actually useful for representing functions as objects[^4]. Doing so is a fundamental part of understanding the machinery behind Albert Einstein's theory of gravity.

[^4]: Via the linear isomorphism $\mathcal{L}(V \rightarrow W) \cong W^{*} \otimes V$.]

I am also extremely partial to the realization that if a function $\mathbf{f}$ sending vectors to vectors is *linear*, and preserves the decomposition of its input, $\mathbf{f}(c\_1 \mathbf{v}\_1 + ... c\_n \mathbf{v}\_n) = c\_1 \mathbf{f}(\mathbf{v}\_1) + ... + c\_n \mathbf{f}(\mathbf{v}\_n)$, then the function can be represented purely by knowing where a representative list of vectors gets sent. This naturally leads to the introduction of matrices (lists of vectors, or *grids* of numbers), and the definition of matrix-vector multiplication. Continue following this trail- by reasoning that, since a composition of two linear functions is linear, the composition must be also representible by a matrix- and a (simple!) formula for matrix-matrix multiplication reveals itself. More complicated formulas that obscure the clarity of the simple one follow. They look like wizardry, but the logic leading to them is indisputable!

Of course, the path of clarity is rarely the one presented. All too often, teachers and books alike set us down at a random, unideal place within the structure of an idea. We are given the complicated formula that is best derived as "end result", and told it is actually a bedrock fact.

## The beauty is obscured

The beauty of math is unfortunately much too often obscured by wrong attitudes. The "that's just the way it is" attitude from high school math class is probably familiar to us all.

There's also the "conjecture and prove" pedagogy that traditional approaches to higher mathematics overuse and abuse. In ["conjecture and prove"](./On%20good%20explanations.md#conjecture-and-prove-math), the proposed truths (conjectures) are always plausible enough, but also always seem to be somewhat unmotivated, somewhat popping out of thin air. It's true that some ideas are radical enough perspective shifts that they can only be perceived as coming out of the blue, but most ideas can be related to a previously known network of ideas in a natural way that lends to their discovery.

Most subtle of all- and perhaps the most destructive for it- is what I call the ["efficiency pedagogy"](./On%20good%20explanations.md#the-dreaded-efficency-pedagogy). The efficiency pedagogy takes shortcuts to establish that facts are true without really explaining them, tricking students into thinking that they understand something, since they can write down a "proof", while secretly tying them up in tangles of circular logic that never get resolved.

## Books

I've spent a large portion of my life developing notes, which have turned into books, that *satisfyingly* explain math and physics, starting from precalculus. 

In my mind, a concept has been satisfactiorly explained if, in the scenario where you are restricted from access to any outside resources- like textbooks, notes, the Internet- you can retrace the concept's story and eventually reobtain all the details. **My books aim to present a plausible avenue by which every mathematical concept they cover could be discovered.**

I admit, it is unlikely that a single person would be able to independently make all of these natural discoveries *for the first time*. But, a book can take care of the first time for you! After you have digested the material, you will be left with that memorable path of discovery for a long while.

These books are incomplete, but are in a good enough state that I feel okay with sharing them:

- [Calculus](https://github.com/rossgk2/Calculus)
- [Physics](https://github.com/rossgk2/Physics)
- [Linear algebra, tensors, and manifolds](https://github.com/rossgk2/Linear-algebra-tensors-manifolds) (the mathematics behind Einstein's theory of gravity)
