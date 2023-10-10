<div align="center">

# asdf-git-xargs [![Build](https://github.com/defenseunicorns/asdf-git-xargs/actions/workflows/build.yml/badge.svg)](https://github.com/defenseunicorns/asdf-git-xargs/actions/workflows/build.yml) [![Lint](https://github.com/defenseunicorns/asdf-git-xargs/actions/workflows/lint.yml/badge.svg)](https://github.com/defenseunicorns/asdf-git-xargs/actions/workflows/lint.yml)


[git-xargs](https://github.com/gruntwork-io/git-xargs) plugin for the [asdf version manager](https://asdf-vm.com).

This unofficial ASDF plugin is not officially supported by the git-xargs team. Use at your own risk.

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- *NIX system (tested on Linux and macOS)
- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add git-xargs https://github.com/defenseunicorns/asdf-git-xargs.git
```

git-xargs:

```shell
# Show all installable versions
asdf list-all git-xargs

# Install specific version
asdf install git-xargs X.Y.Z

# Set a version globally (on your ~/.tool-versions file)
asdf global git-xargs X.Y.Z

# Now git-xargs commands are available
git-xargs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

[Thanks goes to these contributors](https://github.com/defenseunicorns/asdf-git-xargs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Defense Unicorns](https://github.com/defenseunicorns/)
