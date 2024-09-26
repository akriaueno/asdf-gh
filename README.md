<div align="center">

# asdf-gh [![Build](https://github.com/akriaueno/asdf-gh/actions/workflows/build.yml/badge.svg)](https://github.com/akriaueno/asdf-gh/actions/workflows/build.yml) [![Lint](https://github.com/akriaueno/asdf-gh/actions/workflows/lint.yml/badge.svg)](https://github.com/akriaueno/asdf-gh/actions/workflows/lint.yml)

[gh](https://github.com/cli/cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gh
# or
asdf plugin add gh https://github.com/akriaueno/asdf-gh.git
```

gh:

```shell
# Show all installable versions
asdf list-all gh

# Install specific version
asdf install gh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gh latest

# Now gh commands are available
gh --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/akriaueno/asdf-gh/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [akiraueno](https://github.com/akriaueno/)
