# Hx
*H<sub>x</sub>* is an incomplete axiomatic system in propositional logic. There are 145 formulas in __*data set.pdf*__, they are all tautologies (always being true). 115 (actually 114) of them are provable in *H<sub>x</sub>*; 30 of them are unprovable in *H<sub>x</sub>*. For any formula φ provable in *H<sub>x</sub>*, there is a proof of φ; for any formula φ unprovable in *H<sub>x</sub>*, it will be proved that φ is unprovable in *H<sub>x</sub>*. Based on these formulas, by substitution, it's very easy to obtain millions of formulas provable in *H<sub>x</sub>*, millions of formulas unprovable in *H<sub>x</sub>*, millions of tautologies, and  millions of contradictions (always being false).

## Generating Data Set
For example:

p->p is provable in *H<sub>x</sub>* and a tautology (see Proposition 22). 

So, by substitution( p->(q->~r)/p ),

(p->(q->~r))->(p->(q->~r)) is also provable in *H<sub>x</sub>* and a tautology. It will be guaranteed by a Theorem. 

Moreover, by substitution( a/p,b/q,c/r ),

(a->(b->~c))->(a->(b->~c)) is also provable in *H<sub>x</sub>* and a tautology. 

*A<sub>26</sub><sup>3</sup>=26\*25\*24=15600*, *114\*15600=1,778,400*, so millions of formulas can be generated very quickly in this way.

## Peirce' Law
__*((p->q)->p)->p*__ (the Peirce' law) is unprovable in *H<sub>x</sub>* itself (see Proposition 160), but __*~~(((p->q)->p)->p)*__ (the double negation of Peirce' law) is provable in *H<sub>x</sub>* (see Proposition 159).

## Thanks
Thanks for the book *Symbolic Logic* (Xu, 2008) very much, and all the basic concepts come from it.

## To be continued ...
