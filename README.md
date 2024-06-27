<div align="center">

# asdf-chrome [![Build](https://github.com/weizhliu/asdf-chrome/actions/workflows/build.yml/badge.svg)](https://github.com/weizhliu/asdf-chrome/actions/workflows/build.yml) [![Lint](https://github.com/weizhliu/asdf-chrome/actions/workflows/lint.yml/badge.svg)](https://github.com/weizhliu/asdf-chrome/actions/workflows/lint.yml)


[chrome](https://chrome.chromium.org) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `zip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add chrome
# or
asdf plugin add chrome https://github.com/weizhliu/asdf-chrome.git
```

chrome:

```shell
# Show all installable versions
asdf list-all chrome

# Install specific version
asdf install chrome latest

# Set a version globally (on your ~/.tool-versions file)
asdf global chrome latest

# Now chrome commands are available
chrome --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/weizhliu/asdf-chrome/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matthew weizhliu](https://github.com/weizhliu/)
