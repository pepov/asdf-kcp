<div align="center">

# asdf-kcp [![Build](https://github.com/pepov/asdf-kcp/actions/workflows/build.yml/badge.svg)](https://github.com/pepov/asdf-kcp/actions/workflows/build.yml) [![Lint](https://github.com/pepov/asdf-kcp/actions/workflows/lint.yml/badge.svg)](https://github.com/pepov/asdf-kcp/actions/workflows/lint.yml)


[kcp](https://www.kcp.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kcp
# or
asdf plugin add kcp https://github.com/pepov/asdf-kcp.git
```

kcp:

```shell
# Show all installable versions
asdf list-all kcp

# Install specific version
asdf install kcp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kcp latest

# Now kcp commands are available
kcp --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pepov/asdf-kcp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Wilcsinszky](https://github.com/pepov/)
