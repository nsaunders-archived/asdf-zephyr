<div align="center">

# asdf-zephyr [![Build](https://github.com/nsaunders/asdf-zephyr/workflows/Build/badge.svg)](https://github.com/nsaunders/asdf-zephyr/actions/workflows/build.yml) [![Lint](https://github.com/nsaunders/asdf-zephyr/workflows/Lint/badge.svg)](https://github.com/nsaunders/asdf-zephyr/actions/workflows/build.yml)

[zephyr](https://github.com/coot/zephyr) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities

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

# License

See [LICENSE](LICENSE) © [Nick Saunders](https://github.com/nsaunders/)
