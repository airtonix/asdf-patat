# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test patat https://github.com/airtonix/asdf-patat.git "patat --help"
```

Tests are automatically run in GitHub Actions on push and PR.
