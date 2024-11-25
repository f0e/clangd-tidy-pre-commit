clangd-tidy mirror
===================

Mirror of `clangd-tidy` package for pre-commit.

Shamelessly copied from <https://github.com/pre-commit/mirrors-clang-format>

For pre-commit: see <https://github.com/pre-commit/pre-commit>

For clangd-tidy: see <https://github.com/lljbash/clangd-tidy>

### Using clangd-tidy with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/f0e/clangd-tidy-pre-commit
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: clangd-tidy
```
