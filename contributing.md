# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test crowdin https://github.com/danielbyomujuni/asdf-crowdin.git "crowdin --help"
```

Tests are automatically run in GitHub Actions on push and PR.
