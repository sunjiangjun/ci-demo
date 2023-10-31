# workflow demo

# feature
 - go build
 - lint
 - PR-label
 - PR-lint
 - releaser
 - stale

# PR


Always validate the PR title, and ignore the commits

types:
  - feat
  - fix
  - docs
  - style
  - refactor
  - perf
  - test
  - build
  - ci
  - chore
  - revert



 By default types specified in commitizen/conventional-commit-types is used.
 
 See: https://github.com/commitizen/conventional-commit-types/blob/v3.0.0/index.json
 
 You can override the valid types
