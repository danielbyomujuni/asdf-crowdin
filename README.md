<div align="center">

# asdf-crowdin [![Build](https://github.com/danielbyomujuni/asdf-crowdin/actions/workflows/build.yml/badge.svg)](https://github.com/danielbyomujuni/asdf-crowdin/actions/workflows/build.yml) [![Lint](https://github.com/danielbyomujuni/asdf-crowdin/actions/workflows/lint.yml/badge.svg)](https://github.com/danielbyomujuni/asdf-crowdin/actions/workflows/lint.yml)

[crowdin](https://github.com/danielbyomujuni/asdf-crowdin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add crowdin
# or
asdf plugin add crowdin https://github.com/danielbyomujuni/asdf-crowdin.git
```

crowdin:

```shell
# Show all installable versions
asdf list-all crowdin

# Install specific version
asdf install crowdin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global crowdin latest

# Now crowdin commands are available
crowdin --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/danielbyomujuni/asdf-crowdin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [danielbyomujuni](https://github.com/danielbyomujuni/)
