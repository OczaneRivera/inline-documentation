# Don't Make Me Think: On Software Inline Documentation

## _(draft)_

## Why enforce inline documentation

- The true meaning of inline documentation: Ambiguous or convoluted code is just bad code, don't hide it behind documentation. Meaningul documentation should not be used to explain good code, but rather explain good code.
- "self-documentation" is not a valid argument.
- Imagine your code 6 months from now. Will you remember every single reasoning behind every detail?
- When is it NOT good to have documentation or what is too much documentation

## When to inline document (tentative)

Explain hard and soft approach. How much value does each one give to the overal result?

| Value | Significance |
| ----- | ------------ |
| 0     | None         |
| 1     | Fair         |
| 2     | Major        |

- Public methods - 2
- Modules - 2
- Components - 2
- Classes - 2
- TFile headers (?) - 1
- Closures - 2
- Services (?) - 2
- Business logic that doesn't translate well - 1

## Metrics (the soft approach)

In the case that a file has zero documentation in it, for the sake of moving on quickly, you could use the following metrics to enforce some basic documentation.

1. Module has more than X lines of code
2. Component has no documentation in its file header
3. Have to read over a piece of logic thrice to understand what it does

## FAQ

- ??

## Resources

[js-inline-documentation-standards](https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/javascript/)
