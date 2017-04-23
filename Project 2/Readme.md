## Bloom Filters for Spell Checker ##
1. The key function which takes a word as input and maps it to
its key using the provided cvt character to value mapping.

2. The gen-hash-division-method generates hash functions based on division
and gen-hash-multiplication-method generates hash functions based on the multiplication.

3. The gen-checker takes as input a list of hash functions
and a dictionary of words, and returns a spell checker. A spell
checker is a function that takes a word as input and returns either
#t or #f, indicating a correctly or incorrectly spelled word, respectively.
Your implementation of gen-checker should generate
the bitvector representation for the input dictionary exactly
once.
