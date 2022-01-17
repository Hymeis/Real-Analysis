## 0. Preliminaries: Sets, Functions, Cardinality, and Sequences
(Some may be familar in your Discrete Math course, but some else in here is beyond the scope of Discrete Math.)

Notion: 
"**x ∈ A**" means "x is an element of the set A"
"**A ⊆ B**" means "A is a subset of the set B"

**Definition:** Let A and B be sets. A **function** f: A-->B is a rule assigning to each x∈A exactly one f(x) ∈ B. A is the domain, and B is the codomain.

**Images and Inverse Images:** Let f:A-->B be a function.

1. If A'⊆ A, we define the **image** of A' to be: f(A') = { b∈B | b = f(a) for some a∈A'} = { f(a) | a∈A'}

2. If B'⊆ B, the **inverse image** of B' is: f<sup>-1</sup>(B') = { a∈A | f(a)∈B'}

Note that the definition of inverse images always makes sense even if there's no inverse function.

**Proposition:** f(∪A<sub>i</sub>) = ∪f(A<sub>i</sub>)
**Pf:** Practice

**Definition:** We say f is **injective** if ∀a,a'∈A, f(a) = f(a') --> a = a'

**Definition:** We say f is **surjective** if ∀b∈B, ∃a∈A s.t. b = f(a)

**Definition:** f is **bijective** if f is both injective and surjective

Note f is bijective if and only if it has an inverse function

**Definition:** We say A and B have the same **cardinality** if ∃ h: A-->B bijective.

Useful Theorem for cardinality: **Schroder-Bernstein Theorem:**

**Suppose A and B are sets and ∃ f: A-->B injective and ∃g: B--A injective, then A and B have the same cardinality**

**Pf:** Homework

**Observation:** If A is injective then ∃ an injective f: N --> A

Then, let A be an infinite set, the followings are equivalent (TFAE):

1. A is countable
2. ∃g: N --> A surjective
3. ∃f: A --> N injective

**Pf:** TBD

**Example:** N * N is countable

**Example:** If A<sub>1</sub>, A<sub>2</sub>, ... are countable, then so is ∪A<sub>i</sub>

**Corollary:** Z is countable; Q is countable

**Definition:** If A and B are sets, set A<sup>B</sup> = {f | f: B --> A}

**Example:** A<sup>N</sup> = {f | f: n --> A}. In this case, let a∈A<sup>N</sup> i.e a: N --> A. a(1)∈A, a(2)∈A, a(3)∈A ...

Really, a is a **sequence** in A: a(1)=a<sub>1</sub>, ..., a(n)=a<sub>n</sub>

**Proposition:** {0,1}<sup>N</sup> is not countable.

**Pf:** TBD

## 1. Construction of R

**TBC**
