## Starbug Coding Standard

This package provides coding standard specifications and validation tools including [phpcs](https://github.com/squizlabs/PHP_CodeSniffer) and [PHPMD](https://github.com/phpmd/phpmd).

## Installation

Install this package with composer.

    composer require --dev starbug/standard

### Git pre-commit hook

Install the git pre-commit hook:
```
ln -s vendor/starbug/standard/git/pre-commit .git/hooks/pre-commit
ln -s vendor/starbug/standard/git/config .git/hooks/config
```

### VSCode workspace settings

Install the VSCode workspace settings by copying them into the `.vscode` directory in your workspace root:
```
mkdir -p .vscode
cp vendor/starbug/standard/.vscode/settings.json .vscode/
```