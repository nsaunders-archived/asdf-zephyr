<div align="center">

# asdf-zephyr ![Build](https://github.com/nsaunders/asdf-zephyr/workflows/Build/badge.svg) ![Lint](https://github.com/nsaunders/asdf-zephyr/workflows/Lint/badge.svg)

[zephyr](https://github.com/coot/zephyr) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add zephyr
# or
asdf plugin add zephyr https://github.com/nsaunders/asdf-zephyr.git
```

zephyr:

```shell
# Show all installable versions
asdf list-all zephyr

# Install specific version
asdf install zephyr latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zephyr latest

# Now zephyr commands are available
zephyr --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nsaunders/asdf-zephyr/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Saunders](https://github.com/nsaunders/)
