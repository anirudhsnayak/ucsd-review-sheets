Propositions:
$\hspace{15pt}$ Absurdity:  $F\implies P$ is always true.
$\hspace{15pt}$ Language:
$\hspace{15pt}$ $\hspace{15pt}$ "$P$ only if $Q$"$\hspace{46pt}$ means $P\implies Q$
$\hspace{15pt}$ $\hspace{15pt}$ "$P$ if $Q$"$\hspace{68pt}$ means $Q\implies P$
$\hspace{15pt}$ $\hspace{15pt}$ "$P$ is sufficient for $Q$" $\hspace{10pt}$means $P\implies Q$
$\hspace{15pt}$ $\hspace{15pt}$ "$P$ is necessary for $Q$"$\hspace{11pt}$means $Q\implies P$
$\hspace{15pt}$ Contrapositive:$\hspace{30pt}$ $(A\implies B)$ equals $(!B\implies!A)$
$\hspace{15pt}$ Negation of Implies: $\hspace{3pt}$ $\text{!}(A\implies B)$ equals $(A \text{ and }!B)$
$\hspace{15pt}$ De Morgan's Laws:
$\hspace{15pt}$ $\hspace{15pt}$ $!(P \text{ or } Q) ={} !P\text{ and }!Q$
$\hspace{15pt}$ $\hspace{15pt}$ $!(P\text{ and }Q)={}!P\text{ or }!Q$
Proofs: 
$\hspace{15pt}$ Direct: 
$\hspace{15pt}$ $\hspace{15pt}$ Prove $P$ from known results
$\hspace{15pt}$ $\hspace{15pt}$ Prove $P\implies Q$ by holding $P$ as true and then showing $Q$
$\hspace{15pt}$ Contrapositive: 
$\hspace{15pt}$ $\hspace{15pt}$ $(A\implies B)$ equals $(!B\implies!A)$
$\hspace{15pt}$ Contradiction:
$\hspace{15pt}$ $\hspace{15pt}$ For proving $P$, assume $!P$, and then show a contradiction.
$\hspace{15pt}$ $\hspace{15pt}$ For proving $P\implies Q$, assume that $P$ but $!Q$, and then show a contradiction.
$\hspace{15pt}$ $\hspace{15pt}$ You can nest proofs by contradiction.
$\hspace{15pt}$ Induction:
$\hspace{15pt}$ $\hspace{15pt}$ Base Case: Prove $P(n)$ for some $n=m$.
$\hspace{15pt}$ $\hspace{15pt}$ Inductive Step: Show $P(k)\implies P(k+1)$ for all $k\geq m$
$\hspace{15pt}$ $\hspace{15pt}$ Then $P(n)$ holds for all $n\geq m$.
$\hspace{15pt}$ Strong Induction:
$\hspace{15pt}$ $\hspace{15pt}$  Induction except you can also assume $P(n)$ holds for all $m\leq n\leq k$.
Inequality Rules:
$\hspace{15pt}$  $!(a<b)\iff a\geq b$
$\hspace{15pt}$  $a<b\iff -a>-b$
Sets: Suppose $A$ and $B$ are sets.
$\hspace{15pt}$ Equal, Subset:
$\hspace{15pt}$ $\hspace{15pt}$ $(x\in A \iff x\in B) \leftrightarrow$ $(A=B)$
$\hspace{15pt}$ $\hspace{15pt}$ $(x\in A\implies x\in B) \leftrightarrow (A\subseteq B)$
$\hspace{15pt}$ $\hspace{15pt}$ ($A\subseteq B$ but $A\not=B$) $\leftrightarrow$ $(A\subset B)$   (called a strict subset)
$\hspace{15pt}$ Union, Intersect
$\hspace{15pt}$ $\hspace{15pt}$ $x\in A \cup B$ $\leftrightarrow$ $x\in A \text{ or } x\in B$
$\hspace{15pt}$ $\hspace{15pt}$ $x\in A\cap B$ $\leftrightarrow$ $x\in A \text{ and } x\in B$
$\hspace{15pt}$ $\hspace{15pt}$ Union and Intersect are associative, commutative, and distributive.
$\hspace{15pt}$ Complement, Set Difference
$\hspace{15pt}$ $\hspace{15pt}$ $x\in A^c$ $\leftrightarrow$ $x\not\in A$
$\hspace{15pt}$ $\hspace{15pt}$ $A-B =\{ x\in A\mid\\x\not\in B \}= A\cap B^c$
$\hspace{15pt}$ Power Set: $\mathcal{P}(A)$ or ${2}^A$
$\hspace{15pt}$ $\hspace{15pt}$ The set of all subsets of $A$, $|\mathcal{P}(A)|=2^{|A|}$
$\hspace{15pt}$ Subset vs Element of:  
$\hspace{15pt}$ $\hspace{15pt}$ For singletons, $\{ A \}\subseteq B$ is equivalent to $A\in B$
Quantifiers:
$\hspace{15pt}$ Definition: $\forall$ means "for all", $\exists$ means "there exists" 
$\hspace{15pt}$ Negation of Quantifiers (negate everything, like De Morgan's)
$\hspace{15pt}$ $\hspace{15pt}$ $\neg(\forall a\in A,P(a))=\exists a\in A, \neg P(a)$
$\hspace{15pt}$ $\hspace{15pt}$ $\neg(\exists a\in A,P(a))=\forall a\in A, \neg P(a)$
$\hspace{15pt}$ $\hspace{15pt}$ $\neg(\exists a,\forall b,P(a))=\forall a,\exists b,\neg P(a)$ 
$\hspace{15pt}$ Quantifiers of the *same type* are commutative
$\hspace{15pt}$ Quantifiers only have information on the quantifiers that come before them.
$\hspace{15pt}$ $\hspace{15pt}$  e.g. $\forall x,\exists y,x=y$. The variable $y$ knows $x$ exists, so you can easily pick $y=x$ 
$\hspace{15pt}$ $\hspace{15pt}$ to prove the statement. On the other hand $\exists x,\forall y,x=y$ is false.
$\hspace{15pt}$ Proving Quantifier Statements:
$\hspace{15pt}$ $\hspace{15pt}$  Proving a statement:
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ You prove every statement by providing some substituted expression
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ for every "there exists" statement.
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ Then use known results to prove the "for all" statements
$\hspace{15pt}$ $\hspace{15pt}$ Using a proven statement:
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ You use every statement by substituting whichever value you like into 
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ each "for all" statement
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ Then you obtain a theorem with "there exists" statements
$\hspace{15pt}$ $\hspace{15pt}$ For proving statements false, take the negation and prove it true
$\hspace{15pt}$ $\hspace{15pt}$ Advanced: you can use contradiction on quantifier statements
Set Builder Notation:
$\hspace{15pt}$ Let $S=\{ x\in \mathbb{R}\mid\\P(x) \}$, then
$\hspace{15pt}$ $\hspace{15pt}$$\forall x\in \mathbb{R}$, $P(x)$ is true $\iff$ $x\in S$
$\hspace{15pt}$ Let $S=\{ f(x)\mid\ x \in \mathbb{R} \}$, then
$\hspace{15pt}$ $\hspace{15pt}$ $\forall x\in \mathbb{R}, f(x)\in S$
$\hspace{15pt}$ Bounding Sets:
$\hspace{15pt}$ $\hspace{15pt}$ if $P(x)\implies Q(x)$, then $\{ x\in \mathbb{R}\mid\\P(x) \}\subseteq \{ x\in \mathbb{R}\mid\\Q(x) \}$
$\hspace{15pt}$ $\hspace{15pt}$ if $O(x)\implies P(x)$, then $\{ x\in \mathbb{R}\mid\\O(x) \}\subseteq \{ x\in \mathbb{R}\mid\\P(x) \}$
Functions: Let $X$, $Y$ be sets.
$\hspace{15pt}$ Definition:
$\hspace{15pt}$ $\hspace{15pt}$ A function $f:X\to Y$ is a unique assignment $y=f(x)\in Y$ for every $x\in X$
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$  $X$ is the domain, $Y$ is the codomain
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ $f(x)$ must be defined for every $x\in X$, but it does not necessarily
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ need to be surjective.
$\hspace{15pt}$ $\hspace{15pt}$ When $f$ is provided without an explicit specification of its domain and codomain, 
$\hspace{15pt}$ $\hspace{15pt}$ then in this class we assume the domain is the largest subset of $\mathbb{R}$ where 
$\hspace{15pt}$ $\hspace{15pt}$ the function is defined, and the codomain is $\mathbb{R}$.
$\hspace{15pt}$ Composition: $f\circ g$ 
$\hspace{15pt}$ $\hspace{15pt}$ Definition: $(f\circ g)(x)=f(g(x))$
$\hspace{15pt}$ $\hspace{15pt}$ Consider $f:Y\to Z$, $g:X\to Y$ 
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ Then $f\circ g$ is a function from $X$ to $Z$.
$\hspace{15pt}$ Function Properties
$\hspace{15pt}$ $\hspace{15pt}$ Equality: $f=g$ iff $\forall x\in X, f(x)=g(x)$
$\hspace{15pt}$ $\hspace{15pt}$ Range: $\text{range}(f)=\{ f(x)\mid x\in X \}$
$\hspace{15pt}$ $\hspace{15pt}$ Surjectivity: (onto)
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ $f:X\to Y$ is surjective iff $\text{range}(f)=Y$
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ Basically just covers $Y$
$\hspace{15pt}$ $\hspace{15pt}$ Injectivity: (one-to-one)
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ $f:X\to Y$ is injective iff for all $x_{1},x_{2}\in X$, $x_{1}\not=x_{2} \implies f(x_{1})\neq f(x_{2})$
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ Basically just invertible over its range
$\hspace{15pt}$ $\hspace{15pt}$ Bijectivity:
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ A function is bijective iff it is both injective and surjective
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ A function $f:X\to Y$ is invertible if it has an inverse $g:Y\to X$ 
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ such that $f\circ g= g\circ f=\text{Id}$
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ $f$ is invertible $\iff$ $f$ is a bijection
Cardinality: Let $X, Y$ be sets.
$\hspace{15pt}$ $|X|$ is the cardinality of $X$
$\hspace{15pt}$ Equipotent: $|X|=|Y|$ if there exists a bijection $f:X\to Y$. 
$\hspace{15pt}$ Finite: $X$ is finite and $|X|=n$ if there exists a bijection $f:X\to \mathbb{N}_{n}$ for some $n\in \mathbb{N}$.
$\hspace{15pt}$ Cardinality relations for sets $X$, $Y$ (not necessarily finite).
$\hspace{15pt}$ $\hspace{15pt}$ If there is a bijection $f:$ $X\to Y$, then $|X|=|Y|$
$\hspace{15pt}$ $\hspace{15pt}$ If there is an injection $f:$ $X\to Y$, then $|X|\leq |Y|$
$\hspace{15pt}$ $\hspace{15pt}$ If there is a surjection $f:$$X\to Y$, then $|X|\geq|Y|$
$\hspace{15pt}$ $\hspace{15pt}$ The contrapositives of these statements are useful.
$\hspace{15pt}$ Denumerable/Enumerable: $X$ is equipotent to $\mathbb{Z}^{+}$.
$\hspace{15pt}$ Countable: $X$ is either finite or denumerable.
Inclusion-Exclusion: Let $X, Y$ be finite sets.
$\hspace{15pt}$ Then $|X\cup Y|=|X|+|Y|-|X\cap Y|$
$\hspace{15pt}$  This can be generalized to more unions (just remember to keep alternating the signs)
$\hspace{15pt}$ $\hspace{15pt}$ $|\displaystyle\bigcup_{i=1}^{n}X_{i}|=\sum_{X\subseteq \mathbb{N}_{n}}(-1)^{|I|+1}|X_{I}|$
$\hspace{15pt}$ Draw the Venn diagram if you're stuck
Pigeonhole Principles: Let $X, Y$ be finite sets
$\hspace{15pt}$ Pigeonhole Principle: 
$\hspace{15pt}$ $\hspace{15pt}$ If $|X|>|Y|$, for all functions $f:X\to Y$, there exist $x_{1},x_{2}\in X$ such that $f(x_{1})=f(x_{2})$ 
$\hspace{15pt}$ Generalized Pigeonhole Principle:
$\hspace{15pt}$ $\hspace{15pt}$ For all functions $f:X\to Y$ it's always true that $|X|\leq|Y||\text{max}(f^{-1}(y_{k}))|$.
$\hspace{15pt}$ $\hspace{15pt}$ The maximum is taken over all $y_{k}\in Y$.
Counting: Consider two finite sets $X$ and $Y$, where $|X|=n$ and $|Y|=m$
$\hspace{15pt}$ $\text{Fun}(X, Y)$: set of all functions from $X$ to $Y$
$\hspace{15pt}$ $\hspace{15pt}$ $|\text{Fun}(X, Y)|=$ $m^n$.
$\hspace{15pt}$ $\text{Inj}(X, Y)$: set of all injections from $X$ to $Y$. 
$\hspace{15pt}$ $\hspace{15pt}$ $|\text{Inj}(X, Y)|=(m)_{n}=\text{nPr}(m,n)=\frac{m!}{(m-n)!}$
$\hspace{15pt}$ Number of surjections from $X$ to $Y$
$\hspace{15pt}$ $\hspace{15pt}$ $\displaystyle\sum_{k=0}^{m}\left(-1\right)^{k}{m \choose m-k}\left(m-k\right)^{n}$ 
$\hspace{15pt}$  $\text{Bij}(X)=\text{Perm}(X)$: set of all permutations of $X$. 
$\hspace{15pt}$ $\hspace{15pt}$ $|\text{Perm}(X)|= n!$
$\hspace{15pt}$  $\mathcal{P}(X)$: power set of $X$
$\hspace{15pt}$ $\hspace{15pt}$ $|\mathcal{P}(X)|=2^{n}$
$\hspace{15pt}$  $\mathcal{P}_{k}(X)$: set of all subsets of $X$ with size $k$. 
$\hspace{15pt}$ $\hspace{15pt}$|$\mathcal{P}_{k}(X)$| = $\displaystyle{n \choose k}=\frac{n!}{k!(n-k)!}$
Choose Identities:
$\hspace{15pt}$ Binomial Theorem
$\hspace{15pt}$ $\hspace{15pt}$ $\displaystyle(x+y)^n=\sum_{i=0}^n{n \choose i}x^iy^{n-i}$
$\hspace{15pt}$ Miscellaneous:
$\hspace{15pt}$ $\hspace{15pt}$   $\displaystyle{n \choose k}={n \choose n-k}$ $\\[15pt]$
$\hspace{15pt}$ $\hspace{15pt}$   $\displaystyle{n \choose k}\cdot{}k! =(n)_{k}$
Theorems
$\hspace{15pt}$ Cardinality of Power Set 
$\hspace{15pt}$ $\hspace{15pt}$ For all sets $X$, we have that $|X|<|\mathcal{P}(X)|$  
$\hspace{15pt}$ Schröder-Bernstein:
$\hspace{15pt}$ $\hspace{15pt}$ If there is an injection $X\to Y$ and an injection $Y\to X$, 
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ $\implies$ there is a bijection $f:X\to Y$
$\hspace{15pt}$ $\hspace{15pt}$ This result also applies for surjections (just show that injections exist)
$\hspace{15pt}$ Finite sets:
$\hspace{15pt}$ $\hspace{15pt}$ Every finite set of real numbers has a maximal and minimal element
$\hspace{15pt}$ $\hspace{15pt}$ Suppose $X$ and $Y$ are finite and $|X|=|Y|$.
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ Then every injection is a bijection, and every surjection is a bijection
$\hspace{15pt}$ Infinite Sets: 
$\hspace{15pt}$ $\hspace{15pt}$ If a set is equipotent to a proper subset of itself, it is infinite
$\hspace{15pt}$ $\hspace{15pt}$ An infinite subset of a denumerable set is also denumerable
$\hspace{15pt}$ $\hspace{15pt}$ If $A$ and $B$ are denumerable, then both $A \cup B$ and $A\times B$ are denumerable
$\hspace{15pt}$ $\hspace{15pt}$ If $A$ is denumerable and $n\in \mathbb{N}$, then $A^n$ is denumerable
$\hspace{15pt}$ $\hspace{15pt}$ $\mathbb{Q}$ is denumerable
$\hspace{15pt}$ $\hspace{15pt}$ $\mathbb{R}$ is uncountable
Sequences: 
$\hspace{15pt}$ A sequence is a function $f:\mathbb{Z}^{+}\to \mathbb{R}$.
$\hspace{15pt}$ A sequence converges to a limit $L$ iff 
$\hspace{15pt}$ $\hspace{15pt}$ $\forall\epsilon \in \mathbb{R^+}, \exists N\in \mathbb{Z}^+,\forall n\in \mathbb{Z}^+,(n\geq N\implies |f(n)-L|<\epsilon)$ 
$\hspace{15pt}$ $\hspace{15pt}$ More concisely, $\forall \epsilon>0,\exists N\in \mathbb{Z}^+,\forall n\geq N,|f(n)-L|<\epsilon$
$\hspace{15pt}$ If a sequence converges, it converges to a unique value.
Relations:
$\hspace{15pt}$ For some set $X$, a relation $R$ on $X$ is some $R\subseteq$ $X\times X$.
$\hspace{15pt}$ Relation Properties:
$\hspace{15pt}$ $\hspace{15pt}$ Reflexive:  $a\in X \implies(a,a)\in R$
$\hspace{15pt}$ $\hspace{15pt}$ Symmetric: $(a, b)\in R$ $\implies$ $(b, a)\in R$.
$\hspace{15pt}$ $\hspace{15pt}$ Transitive: $((a,b)\in R\text{ and }(b, c) \in R)\implies$ $(a, c)\in R$.
$\hspace{15pt}$ Equivalence Relation:
$\hspace{15pt}$ $\hspace{15pt}$ An equivalence relation is a relation that is reflexive, symmetric, and transitive.
$\hspace{15pt}$ $\hspace{15pt}$ Equivalence relations partition $X$ into equivalence classes.
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ All elements are equivalent to each other in each equivalence class.
$\hspace{15pt}$ $\hspace{15pt}$ $\hspace{15pt}$ e.g. the integers $\text{mod } n$ partition $\mathbb{Z}$ into $n$ equivalence classes.
GCD:
$\hspace{15pt}$ Denote the set of divisors of an integer $a$ as $D(a)$. 
$\hspace{15pt}$ Then $\gcd(a, b)=\text{max}(D(a) \cap D(b))$
$\hspace{15pt}$ Two integers $a$, $b$ are coprime if $\gcd(a, b)=1$
Notes:
$\hspace{15pt}$ Know how to prove choose identities using intuition, binomial theorem, 
$\hspace{15pt}$ set interpretations, and algebra.
$\hspace{15pt}$ Make sure you know how to count things in general