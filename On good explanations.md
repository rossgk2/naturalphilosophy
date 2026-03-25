# On good explanations

## "Conjecture and prove" math

Here are some more specifics on the failings of "conjecture and prove" math. Hopefully this is theraputic to someone else out there who's been similarly frustrated.

The "conjecture and prove" pedagogy is defined by the following three failings:

- Concept definitions are often given no real motivation (the "motivation" is often historical- e.g. "the Greeks noticed this", "Euler noticed that").
  - In particular, the following malpractice regarding definitions is often followed. Textbooks often first define what it means for an object to have a certain property $P$, and then prove a theorem that states that having this property is equivalent to some important statement $S$. This approach is malpractice because the reader likely pauses after the definition of property $P$ to ask themselves, "Why are objects with propety $P$ important?". Of course, if the reader is experienced, then they will know to expect that the answer to the question is coming soon (they get their answer when they read the theorem that equates property $P$ to the statement $S$), but if the reader is not experienced, then they will feel lost. A much better way to present the same information is to switch the order of theorem and definition. That is: first derive via a natural investigation that statement $S$ is true for objects that have a certain property, and then define an object to have property $P$ if statement $S$ is true. This provides automatic motivation for why objects with property $P$ are important.
- The proposed truths (conjectures) are always plausible enough, but also lack motivation and seem to somewhat pop out of thin air.
- The proofs of truths are unenlightening, since they are treated as tasks to be ticked off of a to-do list rather than as lines of reasoning to be deeply understood.

## Satisfyingly explained math as the opposite of "conjecture and prove"

Satisfyingly explained math is diametrically opposed to "conjecture and prove" math, and recognizes these three core tenets:

- Concept definitions must be given real motivation.
  - As is suggested in the corresponding sub-bullet-point above, a common way to motivate a definition is to prove, *before* the definition is stated, that the definition describes objects for which a meaningful statement holds. 
- Conjectures must be given real motivation. The best way to motivate a conjecture is to derive it (prove that it is true) by starting from previously known ideas and following a natural/plausible avenue of investigation.
- A good proof is simultaneously a proof and an explanation. That is, a good proof is a self-explaining proof.

If you combine the above three core tenets, you realize that satisfyingly explained math is characterized by the following *two* tenets:

- Concept definitions must be given real motivation.
- Whenever possible, truths should be derived via self-explaining proof instead via conjecture and proof. If you must use the conjecture-prove approach, make sure the conjecture has real motivation and that the proof is self-explaining.

## The dreaded "efficency" pedagogy

Another mathematical philosophy to be desperately avoided, even worse than "conjecture and prove", is what I call the "efficiency" pedagogy. The "efficiency" pedagogy goes as follows. Suppose we are describing a mathematical object, and that we know that the object has a natural intuitive property $N$ exactly whenever the object also has a wacky and esoteric property $W$.

If we are presenting this material, what we *should* do is first define property $N$, since it is more intuitive, and then prove that property $W$ follows from property $N$, *even if* it is easier to prove that property $N$ follows from property $W$. It doesn't make sense to start with $W$- no one would dream up $W$ in the first place without discovering $N$ first!

The "efficiency" pedagogy doesn't care about this. If it is easier to prove that $N$ follows from $W$, then the "efficiency" pedagogy will first state $W$ and then prove $N$.

If you think about it, the "efficency" pedagogy isn't actually that efficent. Sure, it may take less logic to prove $W \implies N$ than it does to prove $N \implies W$, but, if one is to truly *understand* the material, they will eventually have to prove $N \implies W$. It is better to start with $N \implies W$, as it eliminates unnecessary confusion and elucidates what is really going on.

A prime example of the "efficiency" pedagogy is the typical way in which $e$, $e^x$, and $\ln(x)$ are defined. One common approach in to define $\ln(x)$ as $\ln(x) := \int_0^x \frac{1}{x} dx$, then define $x \mapsto e^x$ to be the inverse function to $\ln$, and then define $e := e^1$. This approach establishes all relevant facts about $x \mapsto e^x$ and $\ln$, including the fact $\frac{d}{dx} e^x = e^x$, but it does not give an intuition for why the facts are true. All of the other common approaches have this same issue. (The one pedagogically correct approach is to notice that $\frac{d}{dx} b^x = c(b) b^x$ for some function $b \mapsto c(b)$, and then define $e$ to be the $b$ for which $c(b) = 1$. Thus $\frac{d}{dx} e^x = e^x$. We also define $\ln$ to be the inverse function to $x \mapsto e^x$. You can the details in my calculus textbook).

### The worst mathematical mindset: brute force

Often associated with the "efficency" pedagogy is the worst mathematical mindset, the "brute force" mindset. This mindset is of the opinion that certain topics are "just hard", but you’ll get them eventually if you keep trying. 

Yes, math is indeed hard. It is very hard. But it shouldn’t be hard for the wrong reasons. *Of course*, if you bang your head against the wall again and again to instill the mechanical steps of a technique you don’t really understand into your brain, you will become adept at the technique. Math should never be hard in this sort of way. In situations where persistence is the most common recommendation, there is often a better explanation than the traditional one that makes things easier.

The brute force mindset is unfortunately followed by many who have sufficient work ethic to become professors.
