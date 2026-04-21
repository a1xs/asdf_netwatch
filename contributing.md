# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test netwatch https://github.com/a1xs/asdf-netwatch "netwatch --help"
```

Tests are automatically run in GitHub Actions on push and PR.
