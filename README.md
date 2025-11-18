<div align="center">

# asdf-terramate [![Build](https://github.com/terramate-io/asdf-terramate-ce/actions/workflows/build.yml/badge.svg)](https://github.com/terramate-io/asdf-terramate-ce/actions/workflows/build.yml) [![Lint](https://github.com/terramate-io/asdf-terramate-ce/actions/workflows/lint.yml/badge.svg)](https://github.com/terramate-io/asdf-terramate-ce/actions/workflows/lint.yml)

[terramate](https://terramate.io/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add terramate
# or
asdf plugin add terramate https://github.com/terramate-io/asdf-terramate-ce.git
```

terramate:

```shell
# Show all installable versions
asdf list-all terramate

# Install specific version
asdf install terramate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terramate latest

# Now terramate commands are available
terramate version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/terramate-io/asdf-terramate-ce/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Terramate GmbH](https://github.com/terramate-io/)
