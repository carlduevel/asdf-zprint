<div align="center">

# asdf-zprint [![Build](https://github.com/carlduevel/asdf-zprint/actions/workflows/build.yml/badge.svg)](https://github.com/carlduevel/asdf-zprint/actions/workflows/build.yml) [![Lint](https://github.com/carlduevel/asdf-zprint/actions/workflows/lint.yml/badge.svg)](https://github.com/carlduevel/asdf-zprint/actions/workflows/lint.yml)


[zprint](https://github.com/kkinnear/zprint) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add zprint
# or
asdf plugin add zprint https://github.com/carlduevel/asdf-zprint.git
```

zprint:

```shell
# Show all installable versions
asdf list-all zprint

# Install specific version
asdf install zprint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zprint latest

# Now zprint commands are available
zprint -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/carlduevel/asdf-zprint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carl Düvel](https://github.com/carlduevel/)
