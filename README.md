
# Regex engine in Haskell

This is a simple implementation of a regex engine in Haskell using epsilon-NFAs. It uses the academic syntax for regular expressions, meaning brackets "(...)" to group terms, "*" for Kleene iteration and "+" for union (either or).

It supports matching a whole regex, searching for all occurrences of a regex in a string and splitting a string by a regex pattern.

## Run
```sh
ghci regex.hs
```
Then, for example: `match "(a+b)*c" "abbac"`, `search "ab" "xxabyab"`, or `split " +," "a b,c"`.
