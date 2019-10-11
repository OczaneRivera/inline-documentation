# Don't Make Me Think: On Software Inline Documentation

## _(draft)_

## Why inline documentation

Meaningful documentation should not be used to explain bad code, but rather to explain good code.

_"Self-documentation"_ is not a valid argument.

Imagine visiting your code 6 months from now. Will you remember every reasoning behind every decision?

**Pain Points**

- More code to maintain \*\*\*
- Verbosity
- Delays a task \*\*\*
- Redundancy
- visually unappealing

**Selling Points**

- Helps scale the organization
- Helps you understand your own code better
- Less tech debt
- Speeds up onboarding

## When to inline document

In an ideal world, we would want to document anything and everything, but in the real world,we should always try to shoot for the most cost-effective scenario. By giving a measurable value to each piece of code, perhaps we can find a good compromise. For ex:

| Value | Significance |
| ----- | ------------ |
| 0     | None         |
| 1     | Fair         |
| 2     | Major        |

- Public methods - 2
- Modules - 2
- Components - 2
- Classes - 2
- File headers - 1
- Closures - 1
- Services - 2
- Business logic that doesn't translate well - 1

## A soft approach

In the case that we just want a bare minimum of documentation, we could follow certain metrics to go by when developing or when reviewing someone else's code.

- What is the bare minimum to you ?
- Person doing the task as well as person reviewing the pr with the task ?

1. Module has more than X lines of code
2. Component has no documentation in its file header
3. Have to read over a piece of logic thrice to understand what it does
4. You're staring at a piece of logic for more than 5 minutes.

## Templates

Will provide templates that can be easily copy-pasted for use.

## Measurable metrics on how documentation helps improve the development process (tentative section)

- Onboarding speed (huge variable)
- WTFs per minute

## FAQ

-

## Resources

[js-inline-documentation-standards based on JSDocs](https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/javascript/)
