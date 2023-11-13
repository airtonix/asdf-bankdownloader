<div align="center">

# asdf-bankdownloader [![Build](https://github.com/airtonix/asdf-bankdownloader/actions/workflows/build.yml/badge.svg)](https://github.com/airtonix/asdf-bankdownloader/actions/workflows/build.yml) [![Lint](https://github.com/airtonix/asdf-bankdownloader/actions/workflows/lint.yml/badge.svg)](https://github.com/airtonix/asdf-bankdownloader/actions/workflows/lint.yml)

[bankdownloader](https://github.com/airtonix/bankdownloader) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-bankdownloader  ](#asdf-bankdownloader--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add bankdownloader
# or
asdf plugin add bankdownloader https://github.com/airtonix/asdf-bankdownloader.git
```

bankdownloader:

```shell
# Show all installable versions
asdf list-all bankdownloader

# Install specific version
asdf install bankdownloader latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bankdownloader latest

# Now bankdownloader commands are available
bankdownloader --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/airtonix/asdf-bankdownloader/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)
