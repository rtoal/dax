# The Language Dax

la la la Dax nice story here

## Features

Dax features

- ...
- ...
- ...

## Examples

```
let
  gcd = {x => {y ==> y == 0 ? x : gcd y (x % y)}};
  z = 5
in
  [1, 3, z] |> filter {x => x > 2} |> map {x => x ** 2} |> print
  then
  "hello" |> substring 2 5 |> print
  then
  print (gcd 33 99)   // This is fine, you don't HAVE to use |>
end
```
