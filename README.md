<div align="center">

# asdf-d2 [![Build](https://github.com/davidebriani/asdf-d2/actions/workflows/build.yml/badge.svg)](https://github.com/davidebriani/asdf-d2/actions/workflows/build.yml) [![Lint](https://github.com/davidebriani/asdf-d2/actions/workflows/lint.yml/badge.svg)](https://github.com/davidebriani/asdf-d2/actions/workflows/lint.yml)

[d2](https://d2lang.com/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add d2
# or
asdf plugin add d2 https://github.com/davidebriani/asdf-d2.git
```

d2:

```shell
# Show all installable versions
asdf list-all d2

# Install specific version
asdf install d2 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global d2 latest

# Now d2 commands are available
d2 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/davidebriani/asdf-d2/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Davide Briani](https://github.com/davidebriani/)
