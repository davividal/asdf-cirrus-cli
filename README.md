<div align="center">

# asdf-cirrus-cli [![Build](https://github.com/davividal/asdf-cirrus-cli/actions/workflows/build.yml/badge.svg)](https://github.com/davividal/asdf-cirrus-cli/actions/workflows/build.yml) [![Lint](https://github.com/davividal/asdf-cirrus-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/davividal/asdf-cirrus-cli/actions/workflows/lint.yml)

[cirrus-cli](https://github.com/cirruslabs/cirrus-cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cirrus-cli
# or
asdf plugin add cirrus-cli https://github.com/davividal/asdf-cirrus-cli.git
```

cirrus-cli:

```shell
# Show all installable versions
asdf list-all cirrus-cli

# Install specific version
asdf install cirrus-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cirrus-cli latest

# Now cirrus-cli commands are available
cirrus --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/davividal/asdf-cirrus-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Davi Koscianski Vidal](https://github.com/davividal/)
