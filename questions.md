# Questions

## Datatype encodings
- p. 67 defines natural numbers in terms of having zero and operations iszero, succ, and pred. Why these three operations? (That is, if you chose a different set of operations, could you accidentally allow for representations that behave unlike how we expect natural numbers to behave?)
    + EN: These operations seem to come from the Peano axioms (?) 
- Discuss how more complex data types such as lists can be encoded in the untyped lambda calculus     
- Walk through exp/power operation for church numerals (if time allows)           

## Y-combinator
- Do you have to use the Y-combinator to define factorial, or can you write it directly?         
- Walk through CBV vs CVN Y-combinators (if time allows)           

## Substitution
- When we describe a substitution operation as capture-avoiding, does that imply that it also solves the first problem on pg 70 (i.e., the same substitution in two alpha-equivalent terms should get alpha-equivalent results) in addition to the second problem (variable capture), or does it just mean exactly that the substitution avoids capture and nothing else?    
