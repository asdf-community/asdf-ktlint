# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test ktlint https://github.com/esensar/asdf-ktlint.git "ktlint --help"
```

Tests are automatically run in GitHub Actions on push and PR.
