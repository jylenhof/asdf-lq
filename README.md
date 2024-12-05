<div align="center">

# asdf-lq [![Build](https://github.com/jylenhof/asdf-lq/actions/workflows/build.yml/badge.svg)](https://github.com/jylenhof/asdf-lq/actions/workflows/build.yml) [![Lint](https://github.com/jylenhof/asdf-lq/actions/workflows/lint.yml/badge.svg)](https://github.com/jylenhof/asdf-lq/actions/workflows/lint.yml)

[lq](https://github.com/clux/lq) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lq
# or
asdf plugin add lq https://github.com/jylenhof/asdf-lq.git
```

lq:

```shell
# Show all installable versions
asdf list-all lq

# Install specific version
asdf install lq latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lq latest

# Now lq commands are available
lq --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jylenhof/asdf-lq/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jean-Yves LENHOF](https://github.com/jylenhof/)
