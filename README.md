# Workshop on Type Theory and Lambda Calculus

Thursday, 6th September 2018, 10.00-16.00

Room ED, EDIT Building, Chalmers Johanneberg campus, Gothenburg, Sweden

## Schedule (preliminary)

| Time | Talk |
| --- | --- |
| 09.45 | Coffee in the lunch room |
| 10.15 | Rasmus Møgelberg, Bisimulation as path type for guarded recursive types |
| 11.15 | Andy Pitts, Crisp Type Theory in Agda-flat |
| --- | --- |
| 12.00 | Lunch break |
| --- | --- |
| 13.15 | Hugo Herbelin, Proving with side effects |
| 14.00 | Bob Atkey, TBA |
| 14.45 | Coffee break in the lunch room |
| 15.15 | Ken-Etsu Fujita, A constructive proof of the Church—Rosser theorem |
| --- | --- |
| 16.00 | End |

## Talks and abstracts

### Rasmus Møgelberg (ITU Copenhagen), Bisimulation as path type for guarded recursive types

In type theory, coinductive types are used to represent processes, 
and are thus crucial for the formal verification of non-terminating 
reactive programs in proof assistants based on type theory, such 
as Coq and Agda. Currently, programming and reasoning about 
coinductive types is difficult for two reasons: The
need for recursive definitions to be productive, and the lack of 
coincidence of the built-in identity types and the important notion 
of bisimilarity. 

Guarded recursion in the sense of Nakano has recently been 
suggested as a possible approach for dealing with the problem of 
productivity, allowing this to be encoded in types. Indeed, 
coinductive types can be encoded using a combination of guarded
recursion and universal quantification over clocks. 

This talk studies the notion of bisimilarity for guarded recursive types 
in Ticked Cubical Type Theory,
an extension of Cubical Type Theory with guarded recursion. 
As a worked example we study a guarded
notion of labelled transition systems, and show that path equality coincides 
with an adaptation of the usual notion 
of bisimulation for processes. In particular, this implies that guarded recursion
can be used to give simple equational reasoning proofs of 
bisimilarity.

If I have time I will also describe a general result stating that, 
for any functor, an abstract, category theoretic 
notion of bisimilarity for the final guarded coalgebra 
is equivalent (in the sense of homotopy type theory)
to path equality (the primitive notion of equality in cubical type 
theory). This work should be seen as a step towards obtaining 
bisimilarity as path equality for coinductive types using the 
encodings mentioned above.

### Andy Pitts (Cambridge), Crisp Type Theory in Agda-flat

I will describe how recent work by Licata, Orton, Spitters
and myself axiomatizing cubical sets models of univalent foundations
forced us to use a modal type theory, implemented by Andrea Vezzosi as
an exension of Agda called agda-flat.

### Hugo Herbelin (INRIA Paris), Proving with side effects

We shall explore how to use memory assignment to express forcing in
direct style, the same way as classical logic can be seen as direct
style for the double-negation translation. In particular, our
attention shall be retained by a new and short proof with memory
assignment of Gödel's completeness theorem.

### Ken-etsu Fujita (Gunma University), A constructive proof of the Church—Rosser theorem

My motivation behind this talk comes from a quantitative analysis of
reduction systems
based on the two viewpoints, computational cost and computational orbit.

In the first part, we show that an upper bound function for the
Church—Rosser theorem
of type-free lambda-calculus with beta-reduction must be in the fourth
level of the
Grzegorczyk hierarchy. That is, the number of reduction steps to arrive
at a common
reduct is bounded by a function in the smallest Grzegorczyk class
properly extending
that of elementary functions. At this level we also find common reducts
for the confluence
property. The proof method developed here can be applied not only to
type-free lambda-calculus
with beta-eta-reduction but also to typed lambda-calculi such as Pure
Types Systems.

In the second part, we propose a formal system of reduction paths for
parallel reduction,
wherein reduction paths are generated from a quiver by means of three
path-operators,
concatenation, monotonicity, and cofinality. Next, we introduce an
equational theory
and reduction rules for the reduction paths, and show that the rules on
paths are
terminating and confluent so that normal paths are obtained. Following
the notion of
normal paths, a graphical representation of reduction paths is provided,
based on which
unique path and universal common-reduct properties are established.
Finally, transformation
rules from a conversion sequence to a reduction path leading to the
universal common-reduct
are given, and path matrices are also defined as block matrices of
adjacency matrices in
order to count reduction orbits.



