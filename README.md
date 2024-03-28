<div align="center">

# asdf-redpanda-rpk [![Build](https://github.com/anthonyvallee/asdf-redpanda-rpk/actions/workflows/build.yml/badge.svg)](https://github.com/anthonyvallee/asdf-redpanda-rpk/actions/workflows/build.yml) [![Lint](https://github.com/anthonyvallee/asdf-redpanda-rpk/actions/workflows/lint.yml/badge.svg)](https://github.com/anthonyvallee/asdf-redpanda-rpk/actions/workflows/lint.yml)

[redpanda-rpk](https://github.com/anthonyvallee/asdf-redpanda-rpk) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add redpanda-rpk
# or
asdf plugin add redpanda-rpk https://github.com/anthonyvallee/asdf-redpanda-rpk.git
```

redpanda-rpk:

```shell
# Show all installable versions
asdf list-all redpanda-rpk

# Install specific version
asdf install redpanda-rpk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global redpanda-rpk latest

# Now redpanda-rpk commands are available
rpk --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/anthonyvallee/asdf-redpanda-rpk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Anthony Vallee](https://github.com/anthonyvallee/)
