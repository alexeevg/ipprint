__UPDATE__: deprecated, superseded by http://hackage.haskell.org/package/pretty-show

# ipprint

Tiny helper for pretty-printing values in ghci console.

## Usage example
```haskell
>Prelude> let e = replicate 5 [1..14] -- value we want to print                
>Prelude> :m + IPPrint                
>Prelude IPPrint> pprint e                
>   [[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14],               
>    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14],                
>    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14],                
>    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14],                
>    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]]
```
