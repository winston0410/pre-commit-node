# pre-commit-node

Useful for setting pre-commit hook for a repo with multiple languages

## Usage

Using the hook and pass custom args

```yaml
-   repo: https://github.com/winston0401/pre-commit-node
    rev: develop
    hooks:
    -   id: lint-staged
        args: ['-C', './web']
```