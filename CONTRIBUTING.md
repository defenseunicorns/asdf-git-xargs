# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test git-xargs https://github.com/defenseunicorns/asdf-git-xargs.git "git-xargs --version"
```

Tests are automatically run in GitHub Actions on push and PR.
