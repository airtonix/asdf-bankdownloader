# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]
```

for example:


```shell
asdf plugin test bankdownloader https://github.com/airtonix/asdf-bankdownloader.git "bankdownloader --help"
```

Tests are automatically run in GitHub Actions on push and PR.
