# CMPS 130: HW1

### Problem 1 (1.5 points) 
An all-NFA M is a 5-tuple (Q, Σ, δ, q_0, F) that accepts a string x if every 
possible state that M could be in after reading x is an accepting state. (This 
is different from a standard NFA, where only one possible non-deterministic path
needs to lead to an accepting state.) Prove that all-NFAs recognize the class of
regular languages.

### Problem 2 (1.5 points)
Let L be a regular language. Define PREFIX(L) = {x|∃w, xw ∈ L}. (Thus, PREFIX(L)
contains all prefixes of strings in L.) Prove that PREFIX(L) is regular.

### Problem 3 (1.5 points)
Define a pebbling finite state automaton (PFSA) as follows. Start with a DFA M, 
and an arbitrary number of pebbles at the start state. Consider input x. Every 
time M processes a symbol of x, it nondeterministically chooses to move one of 
the pebbles, according to the transition function of M. At the end, if an 
accepting state contains a pebble, then x is accepted. More generally, x is 
accepted by M if there exists a number of starting pebbles, and a sequence of 
moves that leads to some pebble ending at an accepting state. Prove that any 
language recognized by a PFSA is regular.

### Problem 4 (1.5 points) 
Prove that these are not regular languages. (Let the alphabet Σ = {0, 1}.)
(a) The set of strings that are not of the form ww. (Meaning, the strings that 
    are not formed by a double repetition of another string.)
(b) C = {1^k y | y has at most k 1s, k ≥ 1}.

### Problem 5 (1 point) 
Let Σ = {0, 1}. Curiously, B = {1^k y | y has at least k 1s, k ≥ 1} is regular. 
Prove that.

### Problem 6 (1.5 points)
The rotational closure of a language L is defined RC(L) = {xy|yx ∈ L}. Prove 
that regular languages are closed under rotational closures.

### Problem 7 (1.5 points)
Let L and M be languages. Define language L (-) M = {x|x ∈ L and x does not 
contain any string of M as substring}. Prove that: if L and M are regular, 
L (-) M is regular.
