<div align="center">

# asdf-zarf [![Build](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/build.yml/badge.svg)](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/build.yml) [![Lint](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/lint.yml/badge.svg)](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/lint.yml)


[zarf](https://github.com/defenseunicorns/zarf) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add zarf
# or
asdf plugin add zarf https://github.com/defenseunicorns/asdf-zarf.git
```

zarf:

```shell
# Show all installable versions
asdf list-all zarf

# Install specific version
asdf install zarf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zarf latest

# Now zarf commands are available
zarf version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/defenseunicorns/asdf-zarf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Defense Unicorns](https://github.com/defenseunicorns/)
