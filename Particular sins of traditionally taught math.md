# Particular sins of traditionally taught math.md

Here's a list of sins that traditional explanations of math commit, grouped by subject. A good amount of these sins are resultant from the "conjecture and prove" philosophy, but not all of them are.

## Precalculus

- Saying things such as "let $y = f(x)$", and thereby conflating functions (e.g. $f$) with functions evaluated on inputs (e.g. $f(x)\hspace{0mm}$). One should instead say "let $f$ be a function"!
- Relying on the "FOIL" mnemonic ("first, outside, inside, last") instead of just applying the distributive property, which straightforwardly tells us $(a + b)(c + d) = a(c + d) + b(c + d) = ac + ad + bc + bd$.
- Not stopping to pause at the fact that $\pi$ being a constant, and not a function of a circle's radius, is actually kinda cool.
- Not explaning why definitions involving exponents such as $b^{-x} := \frac{1}{b^x}$ are natural.
- Glossing over the fact that the $n$th root of $x$ is *different notation* for $x^{\frac{1}{n}}$, and instead insinuating that one could somehow prove that the $n$th root of $x$ is equal to $x^{\frac{1}{n}}$. (Both denote the evaluation of the inverse function of $x \mapsto x^n$ at $x$.)
- Not giving memorable intuition for the facts $\log_b(x y) = \log_b(x) + \log_b(y)$ and $\log_b(x^y) = y \log_b(x)$. At best, the traditional approach relies on the proof that begins by applying $\log_b$ to both sides of $b^{x + y} = b^x + b^y$. (That's the best *proof* there is, but it isn't the best intuition.)
- Making students memorize rules that describe the end behavior of rational functions rather than emphasizing the practice of deriving these rules with limits at infinity. 

## Calculus

- Stating the chain rule by using the vague notion of differentiation with respect to " $u = g(x)$ ", rather than stating the chain rule as $\frac{d(f(g(x))}{dx} = \frac{df(g(x))}{dg(x)} \frac{dg(x)}{dx}$.
- Defining $e$ and the natural logarithm by "jumping to the conclusion" and skipping all relevant motivation. (Typically, $\ln$ will defined to be $\int_0^x \frac{1}{x} dx$, and and $e$ will either be defined to be $e := \lim_{n \rightarrow \infty} (1 + \frac{1}{n})^n$, or to be $e := 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + ...$, or to be $e := \ln^{-1}(1)$).
- Proving that FTC 1 $\implies$ FTC 2 rather than FTC 2 $\implies$ FTC 1. (FTC 2, the second fundamental theorem of calculus, is more intuitive than FTC 1, the first fundamental theorem of calculus).
- Not explaining why "canceling differentials" works.
  - Presenting the change of variables formula for integrals to be a chance discovery instead of a natural mirroring of the chain rule.

## Linear algebra

- Emphasizing thinking of matrices as grids of numbers rather than as lists of vectors.
- Presenting the correspondence between linear transformations and matrices as a coincidence.
- Not explaining why the following two definitions of the dot product are equivalent: (1) $\mathbf{v} \cdot \mathbf{w} := ||\mathbf{v}|| ||\mathbf{w}|| \cos(\theta)$ and (2) $\mathbf{v} \cdot \mathbf{w} := v_1 w_1 + ... + v_n w_n$. When traditional math *does* explain, it uses the unintuitive law of cosines to do so.
- Insisting that you have to make weird shapes with your hand to apply the right hand rule rather than explaining the concept of orientation, and how orientation (and therefore the direction of the cross product) flips when the counterclockwise angle from one vector to another exceeds $\pi$.
- Not making it clear that the right hand rule is a *convention* that is tied to the convention of depicting coordinate systems in the "right handed way"  (that is, $\hat{\mathbf{e}}\_1 = \hat{\mathbf{x}}$ is into the page, $\hat{\mathbf{e}}\_2 = \hat{\mathbf{y}}$ is right, $\hat{\mathbf{e}}\_3 = \hat{\mathbf{z}}$ is up).

## Logic and proofs

- Not explaining that the implication operator only takes on its English-langauge meaning when you use it inside a "for all" quantifier.

### Tensors

- Favoring the "multilinear function" definition of tensor over the "multilinear element" definition of tensor.

## Topology

-Not explaining how each and every one of the topological space axioms generalizes the topological properties of the real numbers.
- Not mentioning the closure operator characterization of topologies.
