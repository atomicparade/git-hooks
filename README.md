# git-hooks

[![Unlicense](https://img.shields.io/badge/license-Unlicense-blue)](https://choosealicense.com/licenses/unlicense/) [![CC0](https://img.shields.io/badge/license-CC0-blue)](https://creativecommons.org/publicdomain/zero/1.0/)

Easily keep git hooks updated.

## How to use

1. Copy `git-hooks/` to your project folder.
2. Add any pre-commit tasks to `git-hooks/pre-commit`. Add any additional hooks as necessary.
3. Run `git-hooks/install-hooks`. This will copy the contents of `git-hooks/` to `.git/hooks/`.

Hooks will be updated upon `commit`, `pull`, `rebase`, etc. To add or edit a hook, add or edit the file in `git-hooks/` and then run `git-hooks/install`.
