# (Unofficial) `stack.yaml` Configuration for [`semantic`]

[![Semantic stack.yaml](https://github.com/jkachmar/semantic-stack-yaml/workflows/stack.yaml%20validation/badge.svg)](https://github.com/jkachmar/semantic-stack-yaml/actions?query=workflow%3A%22stack.yaml+validation%22)

This is an unofficially supported `stack.yaml` configuration file for GitHub's [`semantic`] project.

The plan is to test for valid build configurations against a matrix of LTS snapshots using GitHub Actions as the CI runner. At the time of writing, the latest configuration is [`stack-lts-15.yaml`].

## How do I use this?

1. Ensure that the [Haskell Tool Stack](https://docs.haskellstack.org/en/stable/README/) is installed
2. Clone the [`semantic`] repository
3. Navigate to the cloned repository directory
4. Copy the contents of [`stack-lts-15.yaml`]  into a file named `stack.yaml` in that directory
5. Run `stack build` (this can take a long time)

If that doesn't work, for whatever reason, please [open an issue](https://github.com/jkachmar/semantic-stack-yaml/issues/new)!

[`semantic`]: https://github.com/github/semantic
[`stack-lts-15.yaml`]: stack-lts-15.yaml
