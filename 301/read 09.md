## “Complexity is anything that makes software hard to understand or to modify." — John Outerhout ##

## Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia ##
## definition of purity:
## It returns the same result if given the same arguments (it is also referred as deterministic)
## It does not cause any observable side effects ##
## If our function reads external files, it’s not a pure function — the file’s contents can change. ##
## Any function that relies on a random number generator cannot be pure. ## 
## When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value. ##