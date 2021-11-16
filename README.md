<div align="center">

# asdf-ktlint [![Build](https://github.com/esensar/asdf-ktlint/actions/workflows/build.yml/badge.svg)](https://github.com/esensar/asdf-ktlint/actions/workflows/build.yml) [![Lint](https://github.com/esensar/asdf-ktlint/actions/workflows/lint.yml/badge.svg)](https://github.com/esensar/asdf-ktlint/actions/workflows/lint.yml)


[ktlint](https://ktlint.github.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `java` - just like [asdf-kotlin](https://github.com/asdf-community/asdf-kotlin), this requires java, [asdf-java](https://github.com/halcyon/asdf-java) can be used

# Install

Plugin:

```shell
asdf plugin add ktlint
# or
asdf plugin add ktlint https://github.com/esensar/asdf-ktlint.git
```

ktlint:

```shell
# Show all installable versions
asdf list-all ktlint

# Install specific version
asdf install ktlint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ktlint latest

# Now ktlint commands are available
ktlint --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/esensar/asdf-ktlint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ensar Sarajčić](https://github.com/esensar/)
