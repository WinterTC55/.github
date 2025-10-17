# Contributing Guidelines

Anyone is welcome to make PRs for editorial changes to the specification. These include typo fixes, rewordings, or any other changes that don't affect the meaning of the spec.

To submit normative changes, however, you will need to be a WinterTC delegate or invited expert. [See here for more information.](https://github.com/WinterTC55/?view_as=public#joining-the-committee)

## Building the spec

WinterTC specifications are developed using [Bikeshed](https://speced.github.io/bikeshed).

If you have Python 3.9 or higher on your system, you can install Bikeshed with:

```sh
pip3 install bikeshed
```

For other ways of installing it, [see the Bikeshed documentation](https://speced.github.io/bikeshed/#installing).

Then, you can build the specification using:

```sh
bikeshed spec index.bs index.html
```

You might also find the `bikeshed watch` and `bikeshed serve` commands useful.
