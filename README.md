<div align="center">

# asdf-periphery [![Build](https://github.com/sergiymomot/asdf-periphery/actions/workflows/build.yml/badge.svg)](https://github.com/sergiymomot/asdf-periphery/actions/workflows/build.yml) [![Lint](https://github.com/sergiymomot/asdf-periphery/actions/workflows/lint.yml/badge.svg)](https://github.com/sergiymomot/asdf-periphery/actions/workflows/lint.yml)

[periphery](https://github.com/peripheryapp/periphery/blob/master/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add periphery https://github.com/sergiymomot/asdf-periphery.git
```

periphery:

```shell
# Show all installable versions
asdf list-all periphery

# Install specific version
asdf install periphery latest

# Set a version globally (on your ~/.tool-versions file)
asdf global periphery latest

# Now periphery commands are available
periphery version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sergiymomot/asdf-periphery/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sergiy Momot](https://github.com/sergiymomot/)
