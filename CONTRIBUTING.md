# Contributing to Prest

We welcome bug reports and pull requests!

However, we cannot do it all ourselves, and want to make it as easy as possible
to contribute changes to get things working.  Here are a few guidelines that we
would like contributors to follow so that their (and our) effort and time is
put to best use.

## Issue Reporting

Before you report an issue, or wish to add cool functionality please try and
check to see if there are existing
[issues](https://github.com/prestsoftware/prest/issues) and [pull
requests](https://github.com/prestsoftware/prest/pulls).  We do not want you to
waste your time duplicating somebody's work!

### Template

Try as closely as possible to describe the issue, ensuring that it has sections
that match the following headings:

> \# Steps to Reproduce
>
> \# Expected Behavior
> 
> \# Observed Behavior

Where applicable, attach the relevant dataset (or a workspace file). In order
to fix the issue you're observing, we have to _reproduce_ it first -- make it
happen on our computers so any data or advice how to do it is very helpful.

### Feature Requests

You are welcome to file feature requests. Since the development
team consists of volunteers working on Prest in their free time, the
fastest way to have features included in Prest is submitting pull requests.

## Contributing to Prest source

Before contributing, please get in touch via e-mail (**TODO**: add e-mail).
We do not want you to waste your time or duplicate somebody's work!
Also, Prest is relatively new and we still need to document its internals.

We try to adhere to something similar to the [successful git branching
model](http://nvie.com/posts/a-successful-git-branching-model/).

We have a test suite (still somewhat in flux); you can run everything available
using `make longtest`.

## Increasing chances of acceptance.

To help increase the chance of your pull request being accepted:

1. Discuss your change and the overall approach with us before starting substantial work.
1. Run the tests.
1. Update the documentation, the surrounding code, examples elsewhere, guides, whatever is affected by your contribution
1. Use appropriate code formatting for both Rust and/or Python.

Feel free to submit pull requests for review if you're unsure how to e.g. fix
the tests.  We'll do our best to help you out.

## Credits

Adapted from [the contribution guidelines for Idris](https://github.com/idris-lang/Idris-dev/).