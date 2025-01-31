# Hints

## 1. Calculate the interest rate

- By default, any floating-point number defined in F# code is treated as a `float`. To use a different floating-point type (like `single` or `decimal`), one must add the appropriate [suffix][literals] to the number.

## 2. Calculate the interest

- When calculating interest, it might be helpful to convert a negative balance to a positive one. One could use arithmetic here, or [this method](https://fsharp.github.io/fsharp-core-docs/reference/fsharp-core-operators.html#abs).

## 3. Calculate the annual balance update

- When calculating the annual yield, it might be useful to temporarily convert a negative balance to a positive one. One could use arithmetic, or one of the built-in [math functions][math-functions].

[literals]: https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/literals
[math-functions]: https://www.dotnetperls.com/math-fs
