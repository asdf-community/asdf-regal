<div align="center">

# asdf-regal [![Build](https://github.com/asdf-community/asdf-regal/actions/workflows/build.yml/badge.svg)](https://github.com/asdf-community/asdf-regal/actions/workflows/build.yml) [![Lint](https://github.com/asdf-community/asdf-regal/actions/workflows/lint.yml/badge.svg)](https://github.com/asdf-community/asdf-regal/actions/workflows/lint.yml)

[regal](https://github.com/StyraInc/regal) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add regal
# or
asdf plugin add regal https://github.com/asdf-community/asdf-regal.git
```

regal:

```shell
# Show all installable versions
asdf list-all regal

# Install specific version
asdf install regal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global regal latest

# Now regal commands are available
regal version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/asdf-community/asdf-regal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [czchen](https://github.com/czchen)
