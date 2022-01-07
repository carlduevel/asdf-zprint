# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test zprint https://github.com/carlduevel/asdf-zprint.git "zprint -v"
```

Tests are automatically run in GitHub Actions on push and PR.
