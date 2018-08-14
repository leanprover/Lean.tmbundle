# Lean.tmbundle

This repository contains a language grammar for the [Lean](https://leanprover.github.io) theorem prover.
This is used by [github/linguist](https://github.com/github/linguist) to syntax-highlight Lean code in [github.com](http://github.com).  Every time [github/linguist](https://github.com/github/linguist) is newly released, github pulls the latest version of this repository.

The language grammar is copied from our [vscode extension](https://github.com/leanprove/vscode-lean), with only two small changes for consistency with the previous highlighting style:
  - `entity.name.function.lean` has been renamed to `variable.language.lean` (so that `foo` in `def foo` is highlighted blue)
  - operators have been added as `constant.language.lua` (also highlighted blue)

You can preview this grammar using github's syntax highlighter: https://github-lightshow.herokuapp.com/