<div align="center">

# asdf-keyring-proxy [![Build](https://github.com/mrjk/asdf-keyring-proxy/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-keyring-proxy/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-keyring-proxy/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-keyring-proxy/actions/workflows/lint.yml)

[keyring-proxy](https://github.com/mrjk/keyring-proxy) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add keyring-proxy
# or
asdf plugin add keyring-proxy https://github.com/mrjk/asdf-keyring-proxy.git
```

keyring-proxy:

```shell
# Show all installable versions
asdf list-all keyring-proxy

# Install specific version
asdf install keyring-proxy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global keyring-proxy latest

# Now keyring-proxy commands are available
keyring-proxy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-keyring-proxy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
